# AnimatedTableView

Animate and customize your table views easily. 


## How to use?

Create your tableViews and make sure they are of type "AnimatedTableView" which is a subclass of UITableView.
Then, you just customize or leave everything to default and it instantly works. 

## How to customize?

You can customize the animation duration, direction and mode. You can do it either directly on Interface Builder or in your code.

**Animation Duration:** Defines the duration of the animation for each **cell**.

**Animation Direction:** Defines the direction where the cells will animate.

**Animation Mode:** Odd or Sequencial. Just like the name indicates.

**Animates On Reload:** If you want the table view to automatically reload everytime you call the method to reload Data. If false, **you'll have to explicitly call "tableView.Animate()" 


