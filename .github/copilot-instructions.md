# GitHub Copilot Custom Instructions - UX Design Fundamentals

## Project Context
This project contains summaries of educational materials found online on User Experience. The educational summaries are generated based on content provided by the user in prompts.

## Primary Use Case
When working with content in this repository, assist with creating summaries that will be the best study materials.

## Make Summaries and Extend Learning Materials With Your Own Knowledge

You should create summaries of the educational materials provided in the repository files. Use your own knowledge to extend and enhance the learning materials where appropriate.

## Example

You can receive transcripts of videos or other learning materials like the following:

```
# Understand low-fidelity prototypes

If you’re following this program in sequence, you may recall building a low‑fidelity prototype for your app in a previous course. Since it has been some time, I’ll begin with a brief overview of how to create one.

For those new to our courses, I suggest watching our earlier videos and completing the related activities on low‑fidelity prototyping before continuing. This will give you a stronger foundation for building and testing your own prototypes. All necessary videos are linked in the course readings—feel free to access them if needed.

Now, let’s begin. Prototypes allow us to test product ideas before full‑scale production. They generally fall into two categories: low‑fidelity and high‑fidelity.

Low‑fidelity prototypes are simple, interactive models that convey the basic layout and behavior of a product. They help communicate core design concepts and typically lack finalized visuals or realistic content. High‑fidelity prototypes, on the other hand, are polished, functional designs that closely resemble the final product. Once a low‑fidelity prototype is tested and validated, designers advance to high‑fidelity designs, which undergo their own testing. We’ll cover high‑fidelity prototypes later in the course—for now, our focus is on low‑fidelity versions.

At first glance, digital low‑fidelity prototypes may look much like digital wireframes. Both are simplified representations with minimal content. The key difference is that wireframes act as structural blueprints, while low‑fidelity prototypes connect those wireframes with interactive navigation and basic functionality.

Designers create low‑fidelity prototypes after drafting wireframes, in order to test whether users can navigate the design to complete tasks. This testing phase helps identify and resolve functional issues early on.

So far, you’ve built a basic wireframe for your site. Next, you’ll test how the website performs with real users and gather feedback. That covers the essentials of prototyping. Up next, we’ll apply what we’ve reviewed and start building a low‑fidelity prototype together. I’ll see you in the next activity.

# Review: Create a low-fidelity prototype for your responsive website

This review demonstrates how a low‑fidelity prototype can be used to showcase the functionality of a responsive website. You’ll follow a designer’s process of mapping out a user flow and building a prototype for the checkout experience at Tee’s Shirts, an online apparel store.

You already practiced creating a lo‑fi prototype earlier in the program. If you’d like a refresher, relevant materials are available for review.

## **Create a user flow**

The designer began by outlining the user task and considering two key questions:

How will users move through the required pages of the website?

How will they transition from one page to another?

To answer these questions, the designer constructed a user flow that enables users to:

Move forward and backward through the steps

Enter the process from various starting points

Easily recognize when the intended flow has been completed

Return to the entry point once the simulated interaction is finished
   
Open the Project and Switch to Prototype Mode
To begin, the designer opened the digital wireframe project in Figma. In the right sidebar, they selected the Prototype tab to start building the interactive flow between pages.

Determine User Entry Points
The designer analyzed the wireframes to establish the primary user flow. Key questions considered included:

What is the primary task I want the user to accomplish?

How will users navigate the website’s structure?

Where should their journey begin?

In this case study for the Tee’s Shirts website, the focus was on creating a "checkout flow"—allowing users to select an item and complete a purchase.

The ideal user journey was mapped as follows:

Go to the Women’s section.

Select a t-shirt.

Choose color and size.

Add to cart.

Proceed to checkout.

Enter email information.

Select shipping option.

Enter payment and billing details.

Click “Place order.”

Connect Frames in Prototype Mode
Next, the designer linked the elements across frames so users could click through the checkout flow. The process included:

Clicking the Prototype tab in the right sidebar.

Selecting the first item in the flow, which displayed a blue circular node on its right side.

Dragging the blue arrow to the target item on the next frame.

Releasing to create a visible connection, with a blue arrow marking the endpoint.

The resulting user flow began on the homepage, proceeded to the Women’s clothing menu, then advanced to the t-shirt product page.

Repeat to Complete the Flow
Following the planned user journey, the designer continued linking interactions using the same method, previewing frequently to ensure each connection worked as intended.

To preview the prototype:

Click the Play icon at the top right.

In the preview window, test every connected button.

If the flow is incorrect, revise the interactions as needed.

A complete prototype connects all wireframes required for the main user flow, allowing full testing of the experience.

Define Interaction Requirements
Because prototypes test how well users complete tasks in a simulated environment, it’s important to specify which interactions to include. In this example, four core interactions were built into the prototype:

Move forward and backward.

Enter the flow from the starting point.

Clearly indicate when the flow has ended.

Return to the entry point after completing the interaction.

Review the Prototype
Once all connections were made, the designer walked through the entire experience to verify everything worked correctly before finalizing the prototype for user testing.

Key Takeaways
As you build your own low-fidelity prototype, use this example as a reference. Compare your work by considering the following:

Did I work in prototype mode?

Did I map out my user flow? How many steps did I include?

Which entry point did I choose? How does it compare to this example?

Which interactions did I plan? Do they align with the example? Why or why not?

Did I connect start and destination items using wires for each interaction?

Did I create multiple points of interaction within the flow?

Does my prototype include at least four connected wireframes in a navigational sequence?

Can users move forward and backward within the flow?

Can users enter the flow from different starting points?

Is navigation intuitive and clearly indicated?

Is successful completion of the activity clearly communicated?

Are users returned to a starting point after finishing the activity?

```

And you should make output similar to the following:

```
# Low-fidelity prototypes

## What are prototypes?

UX prototypes are interactive models of a product used to test ideas before building the final version. Prototypes help designers gather user feedback and identify problems early in the design process.

## Low-fidelity vs. High-fidelity prototypes

Low-fidelity prototypes (lo-fi prototypes) are simple, basic structures that communicate big-picture design concepts and test navigation flow, while high-fidelity prototypes (hi-fi prototypes) are polished designs with full functionality that closely match the final product.

## Low-fidelity prototypes vs. wireframes

While both are simple versions with minimal content, they serve different purposes:

- **Wireframes** - blueprints of product structure only
- **Lo-fi prototypes** - connect wireframes together with functionality and navigation

## When to build low-fidelity prototypes

Build them after you've designed wireframes and you want to test if users can successfully navigate the designs to complete tasks.

## Purpose of testing

Testing prototypes helps:
- Identify and solve problems related to website function
- Test how the website works with real people
- Gather user feedback before investing in high-fidelity designs

## Workflow

Wireframes → Low-fi prototypes → Testing → High-fi prototypes → Testing → Final Product

## User flows

User flows are the paths users take through a product to complete specific tasks. User flows help designers plan navigation and ensure users can successfully accomplish their goals.

A prototype is always built around testing the user flow that solves the user problem.

Before building, ask yourself:
1. How will users navigate through the necessary pages?
2. How will users go from one page to the next?

A good user flow should allow users to:
- **Move forwards and backwards** through the prototype
- **Enter from different starting points**
- **Clearly understand** when the flow has ended
- **Return to the entry point** after completing the interaction

## Example: checkout flow for buying t-shirts

1. Navigate to the women's section
2. Choose a t-shirt
3. Select the color and size
4. Add it to the cart
5. Continue to checkout
6. Fill in e-mail address
7. Choose a shipping option
8. Enter payment and billing information
9. Click "Place order"

## Entry points

Entry points are starting locations where users begin their interaction with the website.

Key questions to consider when defining entry points:
- What do I want my user to be able to do?
- How will my users navigate through the website structure?
- Where do I want them to start their journey?

## Prototyping in Figma

Prototype mode:
1. Open your digital wireframe project
2. Go to the right sidebar
3. Click the **Prototype** tab to create user interaction flows between pages

Connecting frames:
1. Click the first item in the user flow
2. A blue circular node appears on the right side
3. Click and drag the blue arrow to the destination item on another frame
4. Release the mouse to complete the connection

Creating user flow:
- Work carefully following your intended user flow as a guide
- Create all necessary interactions using the same connection process
- **Preview your work**: Click the **Play** icon to test
- Test all buttons and connections to ensure they work correctly
- Connect all wireframes necessary for the main user flow

## Quality checklist

When evaluating your own low-fidelity prototype, ask yourself:
1. **Structure & flow** - does it connect **at least four distinct wireframes**? Does it allow completion of a **main user flow**?
2. **Navigation** - can users move **forward and backward**? Are there **clear navigation cues**? Are there **multiple entry points**?
3. ** Completion & feedback** - are there **messaging or navigational cues** that indicate successful completion? Can users **return to the starting point** after completing the flow sequence?

```