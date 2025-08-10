The main goal of this add-on is to make it easy to check execution time in the node editor. Otherwise, you would have to pan through your node tree all the way to the Group Output and zoom in to read it.
This information, similar to what’s shown on the Group Output, will instead be displayed consistently in the upper-left corner of the node editor.
<img width="959" height="735" alt="image" src="https://github.com/user-attachments/assets/1308a73d-c672-45da-ad07-2c125a0ee3d2" />

Compared to the initial implementation from the fork, this modified version fixes display bugs that occur when multiple modifiers are involved.
It also makes the settings more integrated and less exposed to the user, allowing it to be used immediately after enabling, without any additional tweaking.
