# Observe a mock crit session

This section presents an example of a design critique session in action, showing how presenters share their work and how reviewers provide feedback. The session demonstrates the flow of communication and feedback exchange that happens during a typical critique.

## The mock critique session

The design critique features Michael as the facilitator, Kunal as the presenter sharing designs for a dog walker app, and Shabi and Salvador as reviewers. The session focuses on two main areas: the call-to-action buttons and the scheduling flow.

### Session opening

The facilitator (Michael) opens the session by introducing the presenter and the focus areas. He reminds reviewers to take notes during the presentation and save their questions until the end. This structure helps maintain focus and allows the presenter to share their complete thought process before receiving feedback.

### Presentation of the scheduling flow

The presenter (Kunal) walks through the current state of the design, explaining key decisions:

- **Homepage design** - the main call-to-action button to book an appointment divides the hero space from the nearby dog walkers section.

- **Progress tracking** - a stepper (progress tracker) with three icons appears across the top of the screen to make it clear there's a sequence of steps to go through.

- **Button consistency** - large, rounded call-to-action buttons are used on every page of the app with consistent styling.

- **Appointment details interface** - uses a carousel menu that users can scroll through to decide the date, time, and length of the walk for their dog.

- **Recurring appointments** - includes an option to make recurring appointments, though those screens are still in progress.

- **Color consistency** - uses the same rounded buttons with the same orange color to book appointments, advance to the next screen, and confirm bookings. The date, dog walker, and confirm icons also use the same orange color, which turns to orange in a circle as each step is completed.

### Reviewer feedback on scheduling flow

After the presentation, reviewers provide feedback on various aspects of the design:

1. **Language clarity** - Shabi questions whether the phrase "Who is going for a walk?" appeals to most users, suggesting "Which dog is being walked?" as an alternative.

2. **Single vs. multiple dog walks** - Salvador raises concerns about users who have more than one dog but need separate walking schedules (for example, a dog that isn't social and needs to walk alone). He notes that the app currently seems to serve only one type of user.

3. **Single dog user experience** - Salvador wonders how a single dog view could be incorporated into the app design, questioning whether users with only one dog would need a list of dog names to select from.

The presenter acknowledges these points, committing to explore different copy options, check with the team about solo dog walks, and investigate how to support users with single dogs.

### Reviewer feedback on call-to-action buttons

The reviewers then shift focus to the call-to-action buttons:

1. **Color choice reasoning and accessibility** - Shabi asks about the reasoning behind using orange for the call-to-action buttons and whether this shade affects accessibility for users.

2. **Color overload** - Shabi notes that there's a lot of orange on some pages and suggests simplifying the date, dog walker, and confirmation icons by changing them to gray or something more neutral instead of orange.

3. **Button placement and size consistency** - Salvador observes that the placement and width of the main call-to-action buttons seem to change on pages throughout the scheduling flow, asking if this creates distractions for users.

The presenter explains that the medium shade of orange was chosen based on the color guide in the design system, commits to investigating color contrast for accessibility, and notes that button sizes were scaled in proportion to other elements on each page to avoid interrupting the flow.

### Key observations from the session

When watching a critique session, notice these important behaviors:

- **Active listening by the presenter** - the presenter listens carefully and asks clarifying questions rather than becoming defensive.

- **Reasoning behind feedback** - reviewers explain why something works or doesn't work, connecting feedback to user experience and accessibility.

- **Problem-focused feedback** - reviewers describe issues with the design rather than immediately offering solutions, giving the presenter space to generate their own solutions.

- **Alignment with session objectives** - feedback stays focused on the specific areas the presenter requested (scheduling flow and call-to-action buttons).

## Turn crit session feedback into actions

After a design critique session, the presenter must process all the feedback from reviewers and decide which suggestions to incorporate. The goal is to work on generating action items that will improve the design.

### Processing feedback

Start by reviewing the notes that you or a notetaker took during the critique session. As you review the notes, take some time to really think about the feedback you received. Ask yourself: "How can I synthesize the feedback from the design critique session?" and "What feedback do I want to take action on to improve my designs or the user experience?"

When you have only a few reviewers, there's less synthesis needed. However, if you have multiple reviewers in a large design critique session, you will probably need to synthesize that feedback and identify themes, similar to synthesizing participant feedback from usability studies.

### Evaluating feedback and creating action items

Here's how to evaluate each piece of feedback and determine appropriate actions:

1. **Evaluate the impact and reasoning** - when feedback isn't supported by specific design principles and doesn't explain how changes would impact the user experience or functionality, it might be a "nice to have" suggestion rather than a "must fix" issue. For example, Shabi's suggestion to change the wording of the dog selection question could be categorized as **no action needed**.

2. **Identify cross-functional implications** - some feedback impacts more than just the design and requires input from other team members. For example, Salvador's feedback about users with dogs that have different walking schedules or need solo walks requires consultation with the product manager and operations team. The action item would be to **email the product manager to set up a meeting and determine if this is a change to implement**.

3. **Address user-centered concerns** - feedback that's user-centered and aimed at creating options for possible solutions should be prioritized. Salvador's question about the experience for users with only one dog is useful because it considers different user scenarios. The action item is to **create more screens for the dog selection part of the user flow** to support single dog owners.

4. **Check design consistency** - when reviewers point out inconsistencies, verify your designs against specifications. Salvador's question about different sizes of call-to-action buttons requires two actions: **check all mockups to ensure buttons are the same height and width**, and **review the placement of buttons across all screens**.

5. **Iterate on specific elements** - when reviewers suggest simplifications or changes to specific design elements, plan to spend time iterating. Shabi's comments about simplifying the icons and text labels require **iterating on the icon design and text labels** shown across the top of the screen. This is also an opportunity to ask a follow-up question to clarify whether the feedback refers to icon colors, text labels, or both.

6. **Verify accessibility standards** - accessibility feedback is critical and must be addressed. Shabi's question about whether the shade of orange is accessible requires you to **check if the color contrast passes accessibility standards**. If the orange on white background is not accessible, you'll need to change the color of buttons and icons throughout the booking flow (for example, switching to a darker shade of orange).

### Following up on feedback

As you review feedback, you might think of follow-up questions for reviewers to clarify their suggestions. Don't hesitate to reach out for clarification before taking action. This ensures you understand the intent behind the feedback and can make informed decisions about your design iterations.

### Developing confidence with feedback

Over time, you'll gain more and more confidence with the process of receiving and giving feedback. You'll also develop more strategies about how to take useful feedback and generate action items to keep improving your design. The key is to approach feedback as an opportunity for growth rather than criticism, and to be thoughtful about which suggestions to implement based on user needs, design principles, and practical constraints.
