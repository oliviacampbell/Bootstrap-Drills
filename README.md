# Objectives

* Practice pulling in Bootstrap 4’s CDN and using its class based styling.

## Setup

01. Create a new folder for these drills, title it Bootstrap 4 Drills
02. Go ahead and initialize a git repository on this project so it will be available to view on your github account.
03. Create a README.md file, copy and past these drill instructions into that file.
04. Create an index.html page, use the keyboard shortcut to get the html doc started.
05. Go to the following **link** copy the cdn link and past it in the head of your html document.
    * https://getbootstrap.com/docs/4.0/getting-started/introduction/
06. You now have connected the **Bootstrap CDN** to your project and can begin using Bootstrap 4! Hooray.
07. Add a styles.css document, link it to your html document AFTER the bootstrap link.

## Containers and the Grid System

08. Add a div to your html document, using bootstraps container class, have this be a container.
09. To visually see what a container class does to a div, we will need to apply some styling to it in css. Let’s go to our CSS document and apply a background-color of blue and a height of 500px to anything with a class named container (Which for know should only be 1 element).
010. Change the class on the div from a container to a container-fluid. Refresh and take not of the differences. Once you are finished visually seeing the difference between the two, remove or comment out the styling in the css file.
011. Insert a div inside of the existing container div. Give this div a class name of row, then insert an h1 element inside of the row div. Have the text read “First Boostrap Project”.
012. Refer this **link** on the grid system to learn how rows and alignment work using bootstrap. Lets try to center align our h1, go to the following link to explore how to do so. 
* _Hint:_ 
  * Jump to the horizontal alignment section of bootstraps documents, you may need to adjust the amount of columns, 1 through 12, to keep everything on 1 line).
    * https://getbootstrap.com/docs/4.0/layout/grid/
013. Add a new div which will be another row of elements. Add 3 divs, give each some text of your choice and apply bootstrap styling to have 1 div appear at the start of the row, one in the center, and one at the end.

## Bootstrap Forms

014. Use this **link** for reference for the next section:
        * https://getbootstrap.com/docs/4.0/components/forms/
015. Create a form inside of the existing container but outside of any existing rows or other content (ask for help if nesting elements is confusing).
016. Have this form contain an input for an email and password. Make sure each input has labels!
017. Add 2 checkboxes to the form, one for cats and one for dogs.
018. Add 3 radios, have them say Cheese Pizza, Vegetable Pizza, and Meat Pizza
019. Make Sure the form has a submit input!

## Cards

020. Refer to this **link** for more information on cards.
        * https://getbootstrap.com/docs/4.0/components/card/
021. Outside of the form but still inside of the container, create a basic card with a card body and have it have an h3 which will be a friends name, and a paragraph element containing a small piece of info on your friend. Create 6 of these cards.
022. Have them align so there are 2 per row.
023. Once you get them aligning 2 per row, change it so it is 3 per row.