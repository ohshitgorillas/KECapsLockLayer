# Caps Lock as a Left-Hand Function Layer


## Introduction
This project introduces a remapping of the Caps Lock key to a function layer, enhancing typing comfort and efficiency by minimizing hand movement. It prioritizes placing frequently used functions on the home row of the keyboard.

It also allows users of bigger keyboards to experience and/or experiment with the benefits of a smaller layout without committing to a physical downsizing. A significant advantage of this approach is that you don't need to relearn how to type: all the original key functions remain unchanged except for Caps Lock (toggled by Caps Lock + Space), letting you revert to old habits in a pinch.

### Inspiration
This project is inspired by the layering found in 60% and smaller keyboards. These reduce hand movement by using function layers to access missing keys like the numpad, navigation keys, and function keys. For instance, a 60% keyboard might require pressing fn + Backspace for Delete.

### Concept
This layout is designed for tasks like writing and coding, and probably sucks for gaming where 'wasd' is king.

The left hand handles:
- modifier keys (Control, Alt, Command, etc.)
- Essential functions (Enter, Backspace/Delete)
- Accessing the numpad and media layers

The right hand handles:
- Navigation
- Certain symbol keys
- The "numpad" keys and media functions

It is optimized for a US English ANSI layout.


### Compatibility
This layout works with most traditional keyboards (non-ortholinear) that are 60% or larger. 

This project is incompatible with most HHKB-style keyboards that have Ctrl in the Caps Lock position. Some HHKB-style keyboards may offer a dedicated left-hand function key, however, the ergonomics are optimized for the key in the traditional Caps Lock position. 

The spacebar can also be used to access the layer (tap for space, hold for layer) if the user's software supports it with good ergonomics.


## Layout
Below are the specific keymappings within the Caps Lock layer.

For brevity, I use the following symbols:
- ⌘: Command
- ⌥: Option
- ⌃: Control
- ⇧: Shift
- ↵: Enter/Return
- ⎋: Escape
- ⌫: Backspace
- ⌦: Delete (forward delete)
- ⊞: Super/Win key

Letter and number keys are referred to within single quotes, i.e. the the key immediately to the right of Tab is 'q'. Symbol keys are denoted with their primary character followed by the shifted character in single quotes, i.e. the key to the left of ⌫ on a US English ANSI layout is '=+'.

The Caps Lock key is denoted ⇪ below.

![image](https://github.com/user-attachments/assets/9f3c4a39-9794-4a0b-9e6f-d8e070f78e36)

The image above displays the basic function layer for macOS.

![image](https://github.com/user-attachments/assets/847b7352-6bb0-46be-99ae-7519f2dbcba4)

The image above dispalys the basic function layer for Windows/Linux.


### Toggle Caps Lock
The caps lock toggle is available by pressing ⇪ + Space.


### Left Hand (main functions + modifiers)
1. 'q' → ⎋
2. 'w' → ⌃ (⊞ for Windows)
3. 'e' → ↵
4. 'r' → Print
5. 't' → Toggle layer
5. 'a' → ⌥ (⌃ for Windows)
6. 's' → ⌘ (Alt for Windows)
7. 'd' → ⌫
8. 'f' → ⌦
9. 'z' opens the Numpad layer
10. 'x' → F13
11. 'c' → ⇧
12. 'v' opens the Media layer


### Right Hand (navigation + symbols)
Navigation functions may be accessed via your right hand:
1. 'i' → up 
2. 'j' → left
3. 'k' → down
4. 'l' → right
5. 'y' → Page Up
6. 'h' → Page Down
7. 'p' → Home
8. ';:' → End
9. 'u' →'[{'
10. 'o' → ']}'
11. 'n' → '-_'
12. 'm' → '+='
13. '/?' → '\\|'


### Function Keys 
The number row keys are mapped to the function keys ('1' as 'F1', '2' as 'F2', ... '=/+' as 'F12').


### Numpad Layer
The numpad layer is accessed by holding ⇪ + 'z':
1. '7', '8', and '9' map to themselves
2. 'u', 'i', 'o' map to '4', '5', '6'
3. 'j', 'k', 'l' map to '1', '2', '3'
4. 'm' and ',<' map to '0' and '00' respectively
5. '.>' maps to a period/decimal point '.'

![image](https://github.com/user-attachments/assets/27e3ee0d-3d7f-4d81-b853-ee53530402f2)


### Media Layer
The media layer is accessed by holding ⇪ + 'v':
1. 'j' → skip backwards
2. 'l' → skip forwards
3. 'i' → volume up
4. 'k' → volume down
5. ',<' → previous track
6. '.>' → next track
7. 'h' → stop
8. ';:' → play/pause

![image](https://github.com/user-attachments/assets/92ed35b4-ca0e-489d-b53f-0279933e59e2)


### Layer Toggle
The layer may be toggled with ⇪ + 't' such that the user does not need to hold down ⇪ to access the functions.


## Usage
The below sections detail the usage of the layer.

### Chording
While general usage is straightforward, what may not be is the chording. For example, the following critical functions may be accessed with your left hand exclusively by chording multiple keys:
- Delete the previous or next word: Hold ⇪ + 'a' (⌥) and press 'd' (⌫) or 'f' (⌦).
- Delete all text on the line before or after the cursor: Hold ⇪ + 's' (⌘) and press 'd' or 'f'.
- Insert a new line without submitting the current text: Hold ⇪ + 'c' (⇧) and press 'e' (↵).

Furthermore, by including the navigation functions with our right hand, we may access even more functions:
– Jump the cursor to the next or previous word: Hold ⇪ + 'a' (⌥) and press 'l' (right arrow) or 'j' (left arrow).
- Highlight the previous or next page of text: Hold ⇪ + 'c' (⇧) and press 'h' (Page Up) or 'n' (Page Down).
- Unindent or indent a line in a code editor: Hold ⇪ + 's' (⌘) and press 'u' ('[{') or 'o' (']}')


## F13
The layer includes access to the user-programmable F13 key via ⇪ + 'x'. This can be whatever you want.

I have this key mapped to Compose, which allows me to write non-standard characters such as → by pressing caps + 'x' to enable composition mode, then typing '->'. For instructions on enabling the Compose key in macOS, see https://uscustom.sourceforge.net/#installation. Standard compose combinations are here: https://github.com/tsibley/compose/blob/master/compose. 


## Comments
Whenever possible, keys are mapped mnemonically or to be generally easy to remember: 
- Escape ('quit') to 'q'
- Win key to 'w'
- Print (which also 'executes' the current script in VS Code) as 'e'
- Enter ('Return') as 'r'
- Backspace ('delete') to 'd'
- Delete ('forward delete') to 'f'
- '/?' aka forward slash to '\\|' aka backslash

In other cases, keys are mapped to optimize ergonomics. For instance, while it may be more mnemonic to swap ⇧ (Shift) and ⌘ (Command) to 's' and 'c' respectively, ⌘ is instead mapped to 's' to enable the ergonomic chord ⇪ + 's' + 'f' (⌘ + ⌦) and avoid the unergomonic ⇪ + 'c' + 'f'. 
