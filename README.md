this is a front end project, a web app instant layout

To make a div draggable we use this below: 
<div class= "list" draggable= "true"></div> . With this we made the div a class called list 

to assign a value to a variable like we did in this project we use the 'getElementBy...'
if its a class, we complete it with className (getElementByClassName) but if it is an id then replace ClassName with id

in this project, items needed dragging and to do this, we must observe three steps 
dragstart, dragover and drop. and these three are done in a for loop.
the dragstart is general but dragover and drop are made respectively for both left box and right box.
