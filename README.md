
** All style is added to the document file for training purposes - more advanced techniques exist for better organization* 

## CSS Grid System
CSS Grid is a two-dimensional grid-based layout system that helps developers create beautiful responsive web design user interfaces. 

CSS grid system can be used with Flexbox - more on this later - but just to keep
in mind Flexbox has one-directional flow. 

CSS grid system takes a bit of time to learn - but the results are worth it! 
Follow me to get started.

### Build a grid + Terminology 

We will build a very basic grid: 2 rows and 3 columns:

![Screenshot](https://github.com/thesparrow/css-basic-grid/blob/main/img/css-basic-grid.png?raw=true)

Some good terms to know: 

<strong> Grid Container </strong> 

The element to which *display: grid* is applied. It is the start of your grid, and this is usually the container that will hold anything you are placing in the grid. 

<strong> Grid Item </strong> 

The element that exists in the grid as a direct 'child' of the the grid 'parent'. You can set the location with properties like *grid-column-start*, *grid-column-end*, *grid-row-start* and *grid-column-end*. 

<strong> Grid Line </strong> 
These are the dividing lines that make up the structure grid - the can use vertical and horizontal lines. 


### Define the display grid  

The grid container is the container that holds the entire grid. This is done with element that has *display: grid* or *display: inline-grid* property on it.

### Define the rows and columns 

Directly on the grid - create the rows and columns. We will do this by adding the elements*grid-template-columns*, and *grid-template-rows* to the container and grid parent. 

### Set the specific sizes and alignment 

Here we will create the stylist effect on each item, don't worry to much about this we just use a background linear-gradient and a drop shadow,

More important for us, is setting a size (150px by 150px) and setting the number of rows and columns. We will choose 2 rows, *grid-template-rows: 150px 150px * where each 150px signifies a 150px size row, and 3 columns *grid-template-columns: 150px 150px 150px* where each 150px signifies a column of 150px. 

And that's it! We build a basic CSS grid! 

### Connect and follow up 

* Some follow up questions: how can you create grid items that are larger or smaller? 
* What can you do to change the grid to a 3 by 3 layout? 


Always looking for projects to work on - connect with me to see if we 
can collab.

Follow me on instagram @modernbizsites my hub for developer and small biz tips.
Send me an email at hello at modernbizsites dot com to work on a project.