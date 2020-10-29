# Usability | Forms

Forms are graphic structures containing elements for displaying and storing information. Forms are a common tool used in interaction with application users and visitors
and the data is normally post back to a server for storage.

<br>


### Always display a field label.

Field lables are descriptive words or phrases for a UI element in a form such as 'Username' and 'Email Address'. Labels are normally placed close to the form fields. You should
always include labels for fields.

Labels identify the purpose of the field and allows a user to quickly understand the required data. It leads to a faster form completion.
<br>


### Prefer top-left aligned labels to improve readability and decrease form completion time.

UX research performed at Google, discovered that placing labels above form fields and aligned to the left-hand side decreased form completion time. This is due to the reduced
points of fixation.

todo: complement description
todo: add diagram.
<br>


## Input Fields

Input fields are UI elements that allow the user to enter data.
<br>


### Set the size of input fields controls according to the text the user is expected to enter.

The size of an input field should reflect the data that the control is expected to receive. For example, fields designed to hold addresses should be larger than fields
created to store a date.
<br>


## Radio Button

A radio button or option button is a UI element that allows a user to choose a single choice of a predefined set of mutually exclusive options. 
<br>


### Always stack radio button groups vertically.

By stacking radio buttons vertically the user is able to process the information faster to perform choices as compared to an horizontal layout.

todo: add example
<br>


## Checkbox

A checkbox is a UI element that allows a user to make a choice between one of two possible mutually exclusive options. It's common for forms to present groups of checkboxes 
for user options. The user may select several of the choices or none, unlike a radio button group, in which only a single option can be selectable from several 
mutually-exclusive choices.
<br>

### Always stack checkbox groups vertically.

By stacking radio buttons vertically the user is able to process the information faster to perform choices as compared to an horizontal layout.

todo: add example
<br>


### Always validate form data before submitting it.

todo: description

<br>
Tags: security


### Prefer single-column forms for mobile devices.

todo: description

<br>


### Avoid a negative tone for validation error messages.

Users are more receptive to positive messages. Avoid using words like incorrect, wrong, failed etc.

For example, in case a user has entered an incorrect credit card number, insted of displaying a message such as:

"You have entered an incorrect credit card number."

You can use a more positive message:

"Please provide a valid credit card number."

todo: description

<br>


### Avoid dropdown controls in forms, prefering radio button groups, toggles or steppers.

Forms with dropdowns take more time to complete. Also, selecting items from the dropdown lists is difficult on mobile phones with smaller screens.

todo: description

<br>


### Avoid asking for users to enter their phone numbers.

Users are increasingly more protective of their privacy. Unless absolutely necessary for the functionality of the application, you should avoid asking users for their phone
numbers.

todo: complement description
todo: add studies
<br>


### Ensure that the controls in each form can be navigated using the tab key.

Not every user navigates using the mouse. Some users prefer using the keyboard to navigate websites and applications.

It is important to consider is that as the tab key is a common way of navigating forms, there is software designed for users with disabilities that rely on this function. Not
having a system prepared for this functionality severely impacts these users.

Additional Tags: Accessability
<br>


### Always enable browser auto-fill for the appropriate fields.

Auto-fill is a feature present in modern browsers like Chrome and Firefox, which automatically places data in specific form fields.

Using auto-fill saves the user time and effort filling out forms, especially with long fields such as names and addresses.

<br>


### Prefer selectable images when presenting options or questions to a user in a form.

Using clickable images when asking a user a question or selecting an option is more engaging and improves the overall user experience.

TODO: complement description
TODO: add example

<br>


### Avoid using captcha tests.

Captchas are computing tests used to determine if an application or website user is human. The objective of captchas are to prevent automated systems or bots to use applications
and generate spam. It attempts to restrict actions such as registration of fake accounts and creation of posts or comments.

Captchas should be avoided in forms as a security measure because it forces users to read difficult images and increases the effort required to complete forms. It generates frustration
and poses additional problems to users with disabilities. Also, with the advances in development of optical character recognition technology, captchas effectiveness is decreasing.

As alternatives to captchas, consider using honeypots or time-based forms.
<br>