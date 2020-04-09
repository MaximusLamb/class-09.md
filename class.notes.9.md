# Forms
```html
<form></form>
```
* Form controls live inside a ```<form>``` element. This element should always carry the **action** attribute and will usually have a **method** and **id** attribute too.
```html
<input>
``` 
* The input element is used to create several different form controls.  The value of the type attribute determines what kind of input they will be creating.
### type="text" 
* When the type attribute has a value of text, it creates a single-line text input.
### name
* When users enter information into a form, the server needs to know which form control each piece of data was entered into.
### size
* The size attribute should not be used on new forms.  It was used in older forms to indicate the width of the text input.
### type="password"
* When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out.
### ```<textarea>```
* The textarea element is used to create a multi-line text output.  Any text that appears between the opening ```<textarea>``` and closing ```</textarea>``` tags will appear in the text box when the page loads.
### type="radio"
* **Radio buttons allow users to pick just one of a number of options.**
* The name attribute is sent to the server with the value of the option the user selects.  When a question provides users with options for answers in the form of radio buttons, the value of the name attribute should be the same for all of the radio buttons used to answer that question.
### type="checkbox"
* **Checkboxes allow users to select (and unselect) one or more options in answer to a question.**
* The name attribute is sent to the server with the value of the options the user selects.  When a question provides users with options for answers in the form of checkboxes, the value of the name attribute should be the same for all of the buttons that answer that question.
* The value attribute indicates the value sent to the server if this checkbox is checked.
* The checked attribute indicates that this box should be checked when the page loads.  If used, its value should be checked.
## Drop Down Lists
```<select>```
* A drop down list box (also known as a **select box**) allows users to select one option from a drop down list.
* The `<select>` element is used to create a drop down list box.  It contains two or more '<option>'