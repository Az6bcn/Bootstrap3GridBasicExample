# Bootstrap3GridBasicExample
Tutorial para entender y ver en acción el Grid Layout de Bootsrap

Bootsrap Grid is based on 12 Column layout.
The Grid system uses a series of Containers, Rows and Column to layout and align contents.

Container --> wrapper for all your rows
Row --> contains all your column classes
col-x1-x2 --> the sizes of the column in a row
x1: screensize (xs, sm, md, lg)
x2: # of column out of the 12 colunms per row.

e.g
<div class"row"
col-sm-4--> a row with 3 equal width column
</div>

Grid are based on mininmum screensize, works from the smallest screen upward.
e.g :
md --> will apply bootstrap for md, and lg only leavingh out xs and sm 
sm --> will apply bootstrap for xs, md, and lg only leavingh out sm 

col-x1-offset --> will move the column left

col-x1-push-xx : will change the order the column appear by xx
                 *push --> will send the column  to the right
                 
col-x1-pull-xx : will change the order the column appear by xx
                 *pull --> will send the column  to the left
                 
                 
                 
*****In each Row ====> 12 Columns 
If we make a Row in any of these Columns ==> The new Row in this Colunm will have 12 Colunms also.
