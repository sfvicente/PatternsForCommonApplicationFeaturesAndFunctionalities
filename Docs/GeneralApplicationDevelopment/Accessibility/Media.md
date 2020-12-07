# Accessibility | Media
<br>


## Images
<br>


### Always include an `alt` attribute for all the `img` declarations.

It is possible that a screen reader may use another property of an image if the `alt` attribute isn't present, such as the `src` or the `title`. To prevent this behavior
set and image `alt` attribute.

When the alternate text doesn't exist or doesn't make sense for a specific image, set a null or empty `alt` atribute: 

```html
<img alt ... />
```

or

```html
<img alt="" ... />
```


### Avoid setting `alt` text greater than 250 characters.

Alternative text needs to be brief.

TODO: complement description
todo: add examples

<br>


### Always use `alt` text to convey the purpose of the image, not describe the image.

The alternative text should clearly indicate the meaning of the image.

An image can be used multiple times and have different meanings depending on the context in which it is being used.

TODO: complement description
todo: add examples

<br>


### Always hide decorative images from assistive technlogies.

Decorative images are user interface elements that do not contain information and possess no function for the application.

TODO: complement description
todo: add examples

Do not allow these images to be displayed to assistive technologies.
<br>


### Avoid setting `alt` text for decorative images.

When integrating decorative images, set the alternative text as blank or empty.

TODO: complement description
todo: add examples

<br>


### Consider setting decorative images as CSS background images to hide them from assistive technologies.

TODO: complement description
todo: add examples

<br>


### Avoid using the `title` attribute as a replacement of the `alt` text

The title might not be seen by mobile users or users using only keyboards.

TODO: complement description
todo: add examples

<br>
