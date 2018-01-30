# UIScrollView with UITableView

Allows auto layout for views above a UITableView.

On initial load, there is a UIImageView, and as the user scrolls down, the UITableView takes up the whole view.


UITableView's tableHeaderView does not provide auto layout out of the box and requires extra code to set up. When adding multiple views above a UITableView, it becomes less maintainable.

This example allows more intuitive use of auto layout by being able to place views in storyboard.

Switches scrolling between the parent UIScrollView and child UITableView.
