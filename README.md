# sass-simple-grid-system
This is a simple scss grid system, it is responsive and supports different browsers, you will need an scss compiler to compile the code down to css

To center content give a div tag a class of container.
Nest another div tage inside the container and that should have a class of row. the example below demonstrates better

<!-- for fixed width columns -->

<div class="container">
  <div class="row">
     <div class="col-4">
       <p>this makes the column span four column width.</p>
     </div>
     <div class="col-6">
       <p>this makes the column soan six column width.</p>
     </div>
     <div class="col-2">
      <p>note that the grid system is a 12 column based grid system and as such can span 12 column width.</p>
    </div>
  </div>
<div>


<!-- you can make the columns responsive across different breakpoints and across different screens -->
<div class="container">
  <div class="row">
     <div class="col-small-12 col-medium-6 col-large-4">
      <p>this makes the column span four column width across small screens, 6 column width across large screens and 4 column width across large devices.</p>
     </div>
     <div class="col-large-6 col-medium-8 col-small-10">
      <p>this makes the column soan six column width across large screens, 8 column width across medium screens and 10 column width across small screens</p>
     </div>
     <div class="col-xlarge-3 col-large-4 col-medium-6 col-small-12">
      <p>this makes the column span 3 column width across extra large screens, 4 column width across large screens. </p>
       <p>6 column width across medium screens and 12 column width across small screens.</p>
       <p>note that the grid system is a 12 column based grid system and as such can span 12 column width.</p>
    </div>
  </div>
<div>
 
 
 
