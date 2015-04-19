# hashgrid
A Grid overlay for fine tuning vertical rhythm in webpage design.

### How to
Click on gethashgrid.js. Select all text, copy and then paste it in the console of your browser.
The script will inject

- jQuery (if it is not already included in the page)
- hashgrid.js
- hashgrid.css

### In the Console
Copy the following text and paste it in the console.

`
var grid = new hashgrid({ numberOfGrids: 2 });$("#grid").css('display','block');
`

- To display the grid type
  - $('#grid').css('display','block');
- To hide the grid type
  - $('#grid').css('display','none');
- To modify horizontal ruler
  - Edit the height rule of div.horiz selector
  

### Grid modifications  
To change grid color, modify the following selector's border-color

~~~~
#grid.grid-1 div.vert{

/* Vertical grid line colour for grid 1 */
border-color: darkturquoise;
~~~~

To change horizontal line color, modify the following:

~~~~
#grid div.horiz{

border-bottom-color: #ed2f71;	
~~~~
  
For any queries, please raise an issue.

#### Thanks
I am using the hashgrid.js by Jon Gibbins [hashgrid](http://github.com/dotjay/hashgrid)



