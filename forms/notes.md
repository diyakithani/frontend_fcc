# Stuff I learned from this project:
## Forms:
1. Form action and method attributes- action is where and method is the way data will be sent to the location, "GET" sends in arguments, and "POST" in the request's body. ``
2. The rem unit stands for root em, and is relative to the font size of the html element.
3. As label elements are inline by default, they are all displayed side by side on the same line, making their text hard to read. `label{
  display: block;
  margin:0.5rem 0;`
4. Following accessibility best practices, link the input elements and the label elements together using the for and id attributes. ` <label for="first-name">Enter Your First Name: <input id="first-name" /></label>`
5. The field-set tag is for each section in the forms.
6. Specifying the type attribute of a form element is important for the browser to know what kind of data it should expect. If the type is not specified, the browser will default to text. always add a type in the self-enclosing input tag.
7. The first input element with a type of submit is automatically set to submit its nearest parent form element.
8.  value, placeholder, type, minlength and more attributes for input tag
9.  required attribute in input tag- Now, if you try to submit the form without filling in the required fields, you will see an error message.
10.  To ensure only one radio input can be selected at a time, give them the same name attribute. For example, using name="option" will link the radio inputs, so only one can be selected at a time. `<input type="radio" name="option" value="1"> Option 1
<input type="radio" name="option" value="2"> Option 2
`
11.  <legend> sets context around the fieldsets</legend>
12. Adding a dropdown to the form is easy with the select element, which contains option elements. Both elements require closing tags.
13.  ` form{
  margin:0 auto;
  max-width:500px;
  min-width:300px;
  width:60vw;
}` -- we need to master flexibility in viewports.
14.  `fieldset{
  padding-top: 2rem;
  padding-bottom:2rem;
  padding-left:0;
  padding-right:0;
  border:none; 
}`  --some padding and border stuff
15. To style the last element of a specific type, use the element:last-of-type CSS pseudo-class. `fieldset:last-of-type {
  /* Your styles here */
  border: 2px solid #000;
}`
16. vertical align.
17. attribute selector- ` input[type="submit"] {`

