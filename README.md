---
language: css
tags: css, layout, positioning, float, box model
type: quiz
resources: 0
---

## Quiz 4 - Box Model & Page Layout

Make a note of your selected answers for the questions below. The correct answers are provided at the end of the quiz along with an explanation.

1. Which CSS property is used to set the spacing outside of elements?  
A.) spacer  
B.) margin  
C.) padding  
D.) border

2. Which CSS property is used to set the spacing inside of elements?  
A.) spacer  
B.) margin  
C.) padding  
D.) border

3. Which CSS property is used to create a line (stroke) on the outside edge of elements?  
A.) spacer  
B.) margin  
C.) padding  
D.) border

4. Using CSS shorthand, select the most efficient declaration to accomplish: 5 pixels of padding on all sides of an element.  
A.) padding: 5px;  
B.) padding-all-sides: 5px;  
C.) padding-top: 5px; padding-bottom: 5px; padding-left: 5px; padding-right: 5px;  
D.) padding: 5px all;

5. Using CSS shorthand, select the most efficient declaration to accomplish: 10 pixels of padding on the top and bottom and 20 pixels on the left and right of an element.  
A.) padding-top-and-bottom: 20px; padding-left-and-right: 20px;  
B.) padding-top: 10px; padding-bottom: 10px; padding-left: 20px; padding -right: 20px;  
C.) padding: 10px 20px;  
D.) padding: 20px 10px;

6. Using CSS shorthand, select the most efficient declaration to accomplish: 35 pixels of padding on the top and 5 pixels on both sides (left & right) and 10 pixels on the bottom.  
A.) padding-top: 35px; padding-left, padding-right: 5px; padding-bottom: 10px;  
B.) padding: 35px 10px 5px;  
C.) padding: 35px 10px 5px 10px;  
D.) padding: 35px 5px 10px;

7. Using CSS shorthand, select the most efficient declaration to accomplish: 10 pixels of padding on top and 20 pixels on the right and 25px on the bottom and zero pixels on left.  
A.) padding-top: 10px; padding-right: 25px; padding-bottom: 25px; padding-left: 0;  
B.) padding: 0px 25px 20px 10px;  
C.) padding: 10px 20px 25px 0;  
D.) padding: 10px top 20px right 25px bottom 0 left;

8. Select the CSS declaration necessary to center an element (using spacing outside of the element).  
A.) margin: auto 0;  
B.) margin: 0 auto;  
C.) margin-all: auto;  
D.) margin: center;

9. Not specifying a CSS height property for an element will allow it to stretch (its height) based on the content within.  
A.) TRUE  
B.) FALSE

10. If an element that is set to display block, has a specified height and its overflow is set to auto, and the content inside the element is taller than the specified height, scrollbars will appear.  
A.) TRUE  
B.) FALSE

11. If an element is set to display block and has no width specified (or width: auto;) it will collapse only as wide as the content inside it.  
A.) TRUE  
B.) FALSE

12. If an element is set to display inline, it will not accept top or bottom margin or width applied to it.  
A.) TRUE  
B.) FALSE

13. The margins of two (static positioned) elements will overlap (ex: &lt;div id="one"&gt; has a bottom margin of 10 pixels and &lt;div id="two"&gt; has a top margin of 20 pixels, so the total amount between them is only 20 pixels.)  
A.) TRUE  
B.) FALSE

14. If an element is set to display block, which CSS declaration will allow the element to scale an element 100% wide.  
A.) width: auto;  
B.) width: 100%;  
C.) (blank, no width specified!)  
D.) All of the above.

15. If an element is set to display block, which CSS declaration will set its minimum width to 600 pixels and its maximum width to 1000 pixels.  
A.) width: 1000px; minimum-width: 600px;  
B.) min-width: 600px; max-width: 1000px;  
C.) width: &gt; 600px &lt; 1000px;  
D.) width: 600px 1000px;

16. Which CSS property has the ability to change the way elements display (inline versus block)?  
A.) visibility  
B.) overflow  
C.) display  
D.) Both A and B.

17. Select the most appropriate CSS declaration to position a &lt;div&gt; element so that other elements that follow after it may occupy space to the right of it.  
A.) float: left;  
B.) float: none;  
C.) position: left;  
D.) position: right;

18. Select the most appropriate CSS declaration to position a &lt;div&gt; element so that other elements that follow after it may occupy space to the left of it.  
A.) position: right;  
B.) float: none;  
C.) position: left;  
D.) float: right;

19. When the CSS declaration clear:both; is applied to an element, it will appear below the height of any floating elements above.  
A.) TRUE  
B.) FALSE

20. You can apply a specially written class of clearfix to parents with floating children to prevent the parent from collapsing.  
A.) TRUE  
B.) FALSE

## Answer Sheet

1. **B**, Margin is the CSS property used to set the spacing outside of elements. For elements that display block margin is accepted on all sides, for elements that display inline the margin is only accepted on the left and right and not on the top and bottom.  
See video: [Box Model](http://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

2. **C**, Padding is the CSS property used to set spacing inside of elements. Padding is accepted on all sides of all elements including both elements that display inline and block.  
See video: [Box Model](http://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

3. **D**, Border is the CSS property used to set a stroke (outline) on the outside edge of an element. Border is accepted on all elements.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

4. **A**, padding: 5px; Specifying a single value applies equal padding to all sides of the element and is more efficient way to write then writing out separate padding for each side as four statements.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

5. **C**, padding: 10px 20px; Specifying two values sets the first value to be applied to the top and bottom and the second value to be applied to the left and right.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

6. **D**, padding: 35px 5px 10px; Specifying three values sets the first value to be applied to the top and the second to the left and right and the third to the bottom.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

7. **C**, padding: 10px 20px 25px 0; Specifying four values sets the first value to be applied to the top and the second value to the right and the third value to the bottom and the fourth value to the left.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

8. **B**, margin: 0 auto; Specifying two values sets the first value to top and bottom and the second value to left and right. Here we are setting the left and right value to auto which allows an equal amount of margin on both sides thus centering the element.  
See video: [Centering Content](http://www.youtube.com/watch?v=GWq7F49RdAg&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

9. **A**, TRUE, Elements with no height specified will simply grow as tall as they need to be to contain all of the content within it.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

10. **A**, TRUE, When a block level element has its overflow set to auto and the content within is taller than the specified height of the element scrollbars will appear.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

11. **B**, FALSE, Block level elements (ex: &lt;div&gt;) with no width specified (width: auto;) will scale horizontally as far as they are able to, until they run into their parent container.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)


12. **A**, TRUE, Inline elements (ex: &lt;span&gt;) will not accept top and bottom margin or width applied to it.  
See video: [Element Display](http://www.youtube.com/watch?v=L7jPNZrjY0Q&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)


13. **A**, TRUE, On regularly positioned elements margin will overlap (is not additive).  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

14. **D**, For block level elements (ex: &lt;div&gt;) they will scale as wide as they can if you specifiy width: 100%, width: auto, or id no width is specified.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

15. **B**, Setting a block level element to have a min-width and max-width allows the element to scale between those two values.  
See video: [Box Model](https://www.youtube.com/watch?v=x4sdDw77Uuw&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

16. **C**, Using the CSS display property allows us to change the way a particular element displays.  
See video: [Element Display](http://www.youtube.com/watch?v=L7jPNZrjY0Q&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

17. **A**, Floating an element to the left will allow elements that follow after (below) to pull up next to it on the right, assuming there is room for them to exist there.  
See video: [Floating](http://www.youtube.com/watch?v=mk-pPgG84YE&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

18. **D**, Floating an element to the right will allow elements that follow after (below) to pull up next to it on the left, assuming there is room for them to exist there.  
See video: [Floating](http://www.youtube.com/watch?v=mk-pPgG84YE&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

19. **A**, TRUE, The CSS clear property allows elements to control whether or not they appear below (clear past) the height of the floating elements above them. The clear property may be set to a value of none, left, right, or both.  
See video: [Floating](http://www.youtube.com/watch?v=mk-pPgG84YE&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)

20. **A**, TRUE, A special CSS class usually named clearfix can be applied to any elements that have floating children within that have a collapsing height.  
See video: [Floating](http://www.youtube.com/watch?v=mk-pPgG84YE&feature=share&list=PLj148bJp5wiw5VlVKdsXBXD0fQXpAupul)