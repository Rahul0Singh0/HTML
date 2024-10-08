## void Element
    all those elements, which has only opening tag
    example: img

## main Element
    The main element is used to represent the main content of the body of an HTML document. Content inside the main element should be unique to the document and should not be repeated in other parts of the document.

## alt attribute 
    The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.

## Anchor tag
    You can link to another page with the anchor (a) element.
    Example: <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>

## Target attribute
    The target attribute specifies where to open the linked document. target="_blank" opens the linked document in a new tab or window.

## section element
    The section element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.

## ul element
    To create an unordered list of items, you can use the ul element.

## figure element
    The figure element represents self-contained content and will allow you to associate an image with a caption.

## figcaption element
    A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element.

## strong element
    The strong element is used to indicate that some text is of strong importance or urgent.

## input element
    The input element allows you several ways to collect data from a web form. Like img elements, input elements are a void element and do not need closing tags.
    There are many kinds of inputs you can create using the type attribute. You can easily create a password field, reset button, or a control to let users select a file from their computer.
    you must give the text field a name attribute and assign it a value to represent the data being submitted.

## placeholder attribute:
    Placeholder text is used to give people a hint about what kind of information to enter into an input.

## required attribute: 
   To prevent a user from submitting your form when required information is missing, you need to add the required attribute to an input element.

## button element: 
   The button element is used to create a clickable button.
## radio button:
   You can use radio buttons for questions where you want only one answer out of multiple options.
    example: <input type="radio"> cat

## label elemenet:
   label elements are used to help associate the text for an input element with the input element itself (especially for assistive technologies like screen readers).
    example: <label><input type="radio"> cat</label>

## id attribute: 
   The id attribute is used to identify specific HTML elements. Each id attribute's value must be unique from all other id values for the entire page.
   Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value.
    example: <input type="radio" name="meal"> Breakfast
             <input type="radio" name="meal"> Lunch
If you select the Indoor radio button and submit the form, the form data for the button is based on its name and value attributes. Since your radio buttons do not have a value attribute,
the form data will include indoor-outdoor=on, which is not useful when you have multiple buttons.

## fieldset element:
   The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line.

## legend:
   The <legend> tag defines a caption for the <fieldset> element.