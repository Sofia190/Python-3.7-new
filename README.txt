This project refers to an online Choose-Your-Own Adventure. Inside this adventure, the tree data structure is used to record the various paths a user might choose.

The class TreeNode is built in order to create the choices that the user can use. It contains a method to add options to the beginning of the story, the story_root. It also contains a method to traverse the tree. This method uses the options available in the story to guide the user on a certain path.

And the class TreeNode is fairly complex. Not only the current part of the story needs to be tracked, and this is why we use the variable at the beginning of the traverse() method, but also the choices that a user can make to progress in the adventure need to be tracked.
