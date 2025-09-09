Anna Bui


MainActivity Java is where the code is.
On line 22 of MainActivity.java, we have the cellState.
Line 40-43 is where each button's color changes based on their cellState

for (int i = 0; i < grid.getChildCount(); i++) {
Button gridButton = (Button) grid.getChildAt(i); these lines help us get a hold of the grid

