# cs50-Super-Mario-Bros

It is built using the love2d framework.

Four functions were added to base the cs50 code.

- [x]  Program it such that when the player is dropped into the level, they’re always done so above solid ground.
- [x]  In LevelMaker.lua, generate a random-colored key and lock block.
       The key should unlock the block when the player collides with it, triggering the block to disappear.
- [x]  Once the lock has disappeared, trigger a goal post to spawn at the end of the level. 
- [x]  When the player touches this goal post, we should regenerate the level, spawn the player at the beginning of it again, and make it a little longer than it was before.
       You’ll need to introduce params to the PlayState:enter function that keeps track of the current level and persists the player’s score for this to work properly.
