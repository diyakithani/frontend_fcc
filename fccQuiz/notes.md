# Important pointers:
1. It is important to link each *input* to the corresponding *label* element. This provides assistive technology users with a visual reference to the input.
This is done by giving the label a for attribute, which contains the id of input.
2. Adding a placeholder might not be the best accessibility practice. Users too often confuse it with an already-entered value.
3. Input tag is always associated with label tags with for and id, input tags also have other attributes like name, type ---this is where you put the type of input and it adds a check, eg: text, email, date, etc.
4. The <fieldset> tag in HTML is used to group related elements within a form, while the <legend> tag provides a caption or title for the <fieldset> element.
   Together, they help organize and describe form controls for better structure and accessibility.
5.   <p>To display a &lt;div&gt; tag, you can write it like this</p> 
6. Input tag value should be the same as the value that's inputted.
7. Giving the radio inputs the same _name_ attribute helps select a unique value

### Pseudo Elements 
A pseudo-element in CSS is a keyword added to a selector that allows you to style a specific part of an element. Pseudo-elements enable you to style parts of an element that do not exist in the document tree. They are denoted by double colons :: preceding the keyword.

Commonly used pseudo-elements include:

1. ::before: This pseudo-element inserts content before the content of the selected element. It is often used to add decorative content.

2. ::after: Similar to ::before, ::after inserts content after the content of the selected element.

3. ::first-line: Targets the first line of a block-level element. It allows you to style the first line of text within an element.

4. ::first-letter: Targets the first letter of a block-level element. It allows you to style the first letter of text within an element, such as applying drop caps or special formatting.

-------------------------------

# Select and option tags
- for a dropdown, use these tags
- within select, you can have many options
- required keyword if you want the user to respond compulsorily
- value of the option and input value must be the same/similar to know what user selected
- link a label with the select tag using *for* and *id* attributes, similar to _label and input_
-----------------------------------------------------------

#textarea tag
- rows and cols attribute
- linking textarea with a label using *for* and *id* attributes
---------------------------------------------------------------------------------------

### Button type="submit" at the end of forms
-------------------------------------------------------------------------------------------
### The footer element is a container for a collection of content that is related to the page, and the address element is a container for contact information for the author of the page.

--------------------------------------------------
- nav > ul > li, a way to select all the li nested with nav and ul || nav li, is another way
----------------------------------------------------

## PSEUDO CLASSES
- In CSS, pseudo-classes are used to define special states of an element, and several of these pseudo-classes are commonly associated with links.
a:link {
    /* styles for unvisited links */
}
a:visited {
    /* styles for visited links */
}
a:hover {
    /* styles for when the mouse hovers over the link */
}
a:active {
    /* styles for when the link is clicked */

---------------------------------------------------------------------------

##Scroll-Behavior 

CSS property is used to define the behavior of the scrolling action for a scrolling box when the user clicks on a link that targets an anchor within the scrollable element. It can also apply when using JavaScript to scroll an element into view.

- can be set to _auto_ -> no smooth transition
- can be set to _smooth_ -> smooth transition

