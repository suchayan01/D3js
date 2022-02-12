"# D3 js" - Data Driven Documents
1. Although D3.js is aclient side library and there is no need for sever but we will not 
be able to make HTTP requests unless we have a server 
2. ways to span aserver ->
    a. write your own
    b. use nodejs 
    c. *live server in vscode for practise 

3. D3.js helps in data visualization
4. Before we visualize some questions we get to know audeience 
5. appropriate visualization techniques has to be choosen

what is SVG?
Scalable Vector Graphics
D3 uses SVG to draw graphs
SVG are images using equations and generated / manipulated using codes
Simply put svgs are easily scalable
Issue with SVG is its resouce intensive

SVG dodnot use backgroug properties
use fill property
stroke for border
sroke-width -> for giving border width


all svg tags are auto closable and wont coplain if explicit s=closure tags are used
<rect> -> width and height   fill -= to add backgroung color stroke to add borger color and stroke-width to add border width
additionally x and y coordinates can be added tro place it anywhere inside the window dom not necessarily inside svg block 
we can give overflow="visible" to show overrlapping pixels 
but its not an elegant solution

<circle>
 takes same  stroke and stroke border , additionally for denoting radius of circle we need to give r attribute & instead fo x and y we use cx and cy

 <line> 
 x1, y1 for starting copordinate and x2,x2 along with stroke nad stroke-width params

 There is no z-index so we cannot arrange the elements who should overlap what 

 <path>-> This is robust and allows custom draws 

 
D3

size -> large -> 542Kb(original) 262Kb(Min) we can use single operations package 
we can pick and choose if we need only few packages


Selections
document.querySelector(")  -> d3.select (It helps to refernce dom elements)