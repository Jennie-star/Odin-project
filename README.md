https://github.com/Jennie-star/odin-recipes   ---->link for odin-recipes project repository

## **Html Foundations**
Learnt abt tags(help the browser know where the element starts and ends) and elements(enclosed within tags), 
learnt about html boilerplate, how to add title<title>(within head),how to add paragraphs, how to add heading and alter its size, how to make text bold, how to make text italic, about relative and absolute links and how to insert links in html file about how to insert image importance hof commiting messages.

## **CSS Foundations**
learnt about selectors and their different types.
selectors are used to select html elements to add desired css styles to them.
types of selectors-universal selector,type selector,class selector,id selector.
learnt how to group selectors with common properties, and how to chain selectors in elements with multiple classes/id.
learnt to apply the following properties color(text color), background color,text align, font size, font family, font weight etc.
learnt how to add color using various formats like rgb,hsl,hex and keyword.

### **Cascade**-helps determine which css rules get applied to html elements
3 cascade rules:
specificity:helps determine which rule to apply when multiple declarations exist.
            inline styles have highest specificity.
            specificity order:id selector > class selector > type selector
            when same selectors are used the rule with more no. of selectors is chosen.
inheritance:rules applied to parent element automatically transfer to child elements unless specifically targetted.
rule order:if all the above given rules are unable to decide which rule is superior than the last defined rule is the one that is ultimately applied.

### **Block and Inline**
Css has two box models-block and inline
block-new elements start from the next line.(E.g:div)
inline-new elements continue from the same line as the elements beside them.(E.g:span)
inline-block-elements with this display type behave like inline, but their padding and margin is similar to that of block.

### **Div and Span**
Div and span are elemnts that do not add an meaning to their content, or have any affect on they content enclose, and are used extensively to group elements under a single parent element, and be distinguished by giving class or id which helps in styling;
div is used primarily to group block elements while span is used to group inline elements.

## **Flexbox** 
flex-box is a tool used to position elements and works on the principle of flex-shrink/flex-grow to resize and fit and specific element.
flex-container:any element that has display:flex property
   flex-item:any element inside the flex conatiner.
A flex-item can a be a flex-conatiner as well.

### **Grow and Shrink**
There are 3 properties of flex shorthand, namely:
1.flex-grow:causes flex items in a flex container to increase in size by the assigned value.
2.flex-shrink:if flex-items execeed the size of their respective flex container then this property helps them shrink by an assigned value.
3.flex-basis:usually the flex shorthand ignores any width value provided and grows/shrinks based on the size of the container; when flex-basis is set to auto it ensures that the width value is taken into consideration.

### **Axes**
Flexbox has two axes-main axis and cross axis.
The default orientation of flex items is horizontal, corresponding to row, and it can be changed to vertical orientation using flex-direction property, though some of the flex-box properties might differ/change.
In case you use column in flex-direction, in order for it to access the height value assigned, flex:auto should be used.

