# Design | Tooltips

Tooltips are small and informative text labels that are normally displayed when a user hovers over an element. They can also be displayed when focus is set on an
element or when the user interacts with it.

Tooltips are used to explain features, provide additional context on functionality or guide a user through a workflow.
<br>


### Avoid adding tooltips to non-interactive elements and elements whose focus cannot be set with the keyboard 

Non-interactive HTML elements can pose a problem to users with assistive technologies. Depending on the mechanism used, it is possible that the system is unable to
trigger or announce the content of a tooltip.

Tooltips should be added to interactive elements or elements that can receive focus through keyboard such as form controls.

todo: complement description
todo: add examples

Additional Tags: Accessibility
<br>


### Avoid relying solely on hover as the trigger for displaying tooltip

When tooltips are only shown by hovering over an element, it creates a problem for keyboard users that won't be able to trigger them.

todo: complement description
todo: add examples

Additional Tags: Accessibility
<br>


### Avoid including more than one primary action on a tooltip.

Including more than one primary action can confuse users. 

todo: complement description
todo: add examples

<br>


### Always display one tooltip at a time.

If more than one tooltip is shown at a time, it can be distracting, confusing or annoying.

todo: complement description
todo: add examples

<br>


## Design
<br>


### Consider using rich or contrast colors for tooltip elements.

Using rich colors will highlight the tooltip and contrast colors with distinguish it from backgrounds and other elements.

todo: complement description
todo: add examples

<br>


## Workflows
<br>


### Always display a progress indicator in tooltips that are used in workflow guidance.

This allows the user to understand what is the length of the flow, where they are currently at and how many stages remain for completion.

todo: complement description
todo: add examples

<br>


### Always give an option to go back in tooltips that are used in workflow guidance.

Users might want to go through parts of the workflow again to clarify, confirm or consolidate their understanding.

todo: complement description
todo: add examples

<br>


### Always give an option in tooltips that are used in workflow guidance to allow the user to skip to the end.

At any moment, users should be given the chance to skip the tutorial.

todo: complement description
todo: add examples

<br>