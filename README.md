# Caps Lock as a Left-Hand Function Layer


## Introduction
### Inspiration
This layer was inspired by the layouts of small (40-60%) keyboards, which aim to increase comfort and ergonomics by reducing the amount of reaching involved in typing by using a smaller keyboard with fewer keys, in which the 'missing' keys are accessed via function layers. As an example, 60% layouts (my preference) lack numpad, navigation, function, and insert/forward delete keys. Arrow keys may be accessed by, for example, holding the right-hand function key and using 'wasd', bringing the arrow keys within reach of the home row. 

In particular, the Anne Pro 2.0 replaces the Caps Lock key with a function layer and uses 'ijkl' as arrow keys. This layout builds upon that concept of the "Caps Lock layer" to bring several critical features such as enter and deletion within reduced reach. 

It may be applied to any 60% or larger keyboard, so that users with larger keyboards may get a feel for 60% usage without needing to commit to a smaller board.

### Description
This layout is optimized for general writing and coding, not for gaming.

The philosophy here is that the left hand has a few tasks:
- Accessing modifiers (Ctrl, Opt/Win, Alt/Cmd, Shift)
- Performing 'main' functions (Enter, Backspace/Delete aka forward delete)
- Bringing up access to the numpad layer.

The right hand:
- Handles navigation functions (arrow keys, pg up/dn, etc)
- Access symbol keys that otherwise require reaching
- Access the keys for the numpad layer


### Compatibility and Modifications
The use of the caps lock to access the function layer with your left hand is incompatible with most HHKB-style keyboards, which place Control in the Caps Lock position. Some boards may have a dedicated left-hand function key that they may use instead, e.g. next to left shift, however, ergonomics are optimized for the key in the traditional Caps Lock position. The spacebar is also a possibility (tap for space, hold for layer) with good ergonomics.


## Layout
Below are the specific keymappings within the Caps Lock layer.

Letter and number keys are referred to within single quotes, i.e. the the key immediately to the right of Caps Lock is 'a'. Symbol keys are denoted with their primary character then shifted character in single quotes, i.e. the key to the left of the Backspace is '=+'. Other main functions such as Enter, Backspace, etc. are referred to without quotes. The forward delete key is referred to as Delete.

The Caps Lock key is simply referred to as **caps** below.

### Toggle Caps Lock
The caps lock toggle is available by pressing Caps Lock + Space.

### Left Hand (main functions + modifiers)
1. 'q' as Escape
2. 'w' as F13 (custom function -- mine goes to Compose)
3. 'e' as Enter
4. 'r' as Replace (Cmd + Opt + 'f')
5. 't' as Print Screen
6. 'a' as Option (alt. Control for Windows)
7. 's' as Command (alt. Alt for Windows)
8. 'd' as Backspace
9. 'f' as Delete
10. 'z' to access the numpad layer (below)
11. 'x' as Control
12. 'c' as Shift

### Right Hand (navigation + miscellaneous)
Navigation functions may be accessed via your right hand:
1. 'i' as up 
2. 'j' as left
3. 'k' as down
4. 'l' as right
5. 'y' as Page Up
6. 'h' as Page Down
7. ',<' as Home
8. '.>' as End
9. 'u' as'[{'
10. 'o' as ']}'
11. ';:' as '-_'
12. ''"' as '+='
13. '/?' as '\|'

### Function Keys 
The number row keys are mapped to the function keys ('1' as 'F1', '2' as 'F2', ... '=/+' as 'F12').


### Numpad Layer
The numpad layer is accessed by holding Caps Lock + 'z':
1. '7', '8', and '9' map to themselves
2. 'u', 'i', 'o' map to '4', '5', '6'
3. 'j', 'k', 'l' map to '1', '2', '3'
4. 'm' and ',<' map to '0' and '00' respectively
5. '.>' maps to a simple period/decimal point '.'


## Usage
While general usage of the above is straightforward, what might not be is the chording. For example, the following critical functions may be accessed with your left hand exclusively:

- To delete the previous or next word, hold caps + 'a' (Option) and hit 'd' (Backspace) or 'f' (Delete) respectively.
- To delete all text on the line before or after the cursor, hold caps + 's' (Command) and hit 'd' or 'f' respectively.
- To insert a new line without submitting the current text, hold caps + 'c' (Shift) and hit 'e' (Enter).

Furthermore,

- To jump the cursor to the next or previous word, hold caps + 'a' (Option) and hit 'l' (right arrow) or 'j' (left arrow) respectively 
- To highlight the previous or next page of text, hold caps + 'c' (Shift) and press 'h' (Page Up) or 'n' (Page Down) respectively
- To unindent or indent a line in a code editor, hold caps + 's' (Command) and hit 'u' ('[{') or 'o' (']}')


## Comments
I have tried to avoid remapping common functions which are already easily accessible and ergonomic, e.g., Cmd + 's' as Save is already easy enough to access, so there's no real need to remap it to this layer. On the other hand, Replace (Cmd + Opt + 'f') is horribly unergonomic, especially on my current keyboard which lacks a right Option key, and has therefore been remapped to caps + 'r'.
