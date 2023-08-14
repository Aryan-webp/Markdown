<!-- Markdown has 6 headings h1 to h6.
Number of prefixed hashtags(#) indicates the order of heading 
Add a space after the hashtags, or else github might not interpret it correctly -->
# h1
## h2
### h3
#### h4
##### h5
###### h6

<!-- A single asterisk or underscore around a string turns it to italic  -->
*asterisk*
_underscore_
<!-- A double asterisk or underscore around a string turns it to bold  -->
**asterisk**
__underscore__
<!-- Combining italics and bold -->
***bold italic***
**bold and *italic***
<!-- Double tildes around a string strikes through it  -->
~~strike-through~~
<!-- Three hyphens create a horizontal ruler -->
---
<!-- Two hashtags create a vertical tab -->
##

<!-- This is a flowchart made using mermaid library of javascript -->
```mermaid
graph TD;
X(Round Edge)-->A
A{Decision}--yes-->B[Hard Edge];
A--no-->C;
B-->D;
B-->E;
C-->F;
E-->G;
F-->G;
```
---

<!-- For ordered list, "mandatory single dot and single space"
For unordered list, "mandatory single plus, minus or asterisk" -->
<!-- For a sub list,three spaces before declaration of type of list is mandatory. -->
<!-- For ordered list, the number doesn't matter; it just has to be a number. Markdown can order it accordingly -->
<!-- Adding comments between list can break it. -->
1. Ordered Main List Item 1
   + Unordered sub-List 1, Item 1
   + Unordered sub-List 1, Item 2
7. Ordered Main List Item 2 
0. Ordered Main List Item 3
   + Unordered sub-List 2, Item 1
   + Unordered sub-List 2, Item 2

<!-- To add an anchor, use [anchor text](url) -->
To go to Google click [here..](https://www.google.com)

<!-- To add an image, use ![title text](url) -->
![A clean desktop](https://images.unsplash.com/photo-1691600252552-c39f81792a5f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwzMHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=60)

<!-- To add an image as anchor, use [![title text](image url)](url) -->
Click this image to go to Unsplash :
[![Green leaf](https://images.unsplash.com/photo-1691858019962-303a7094a581?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwzN3x8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=60)](https://unsplash.com/)
