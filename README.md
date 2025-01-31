# Reduced Reach Keyboard Layer aka RRKB Layer

### This project is under currently under heavy construction and is changing daily. If you are interested, please check back for config files.

## Introduction
The Reduced Reach Keyboard (RRKB) Layer project remaps the Caps Lock key to a left-handed function layer which brings frequently used functions within reach of the home row, enhancing typing ergonomics and efficiency by promoting reduced hand movement.

### Inspiration and Benefits
This project is inspired by the layering found in small keyboards. These reduce hand movement by using far fewer keys; 'missing' functions, or those lacking dedicated keys, are accessed via complex layering. As examples, see https://www.reddit.com/r/MechanicalKeyboards/comments/1h3e8ns/bringing_the_full_keyboard_to_within_reach_of/ and https://github.com/argenkiwi/kenkyo

This project aims to bring some of those benefits to users of more traditional keyboards by mapping frequently used features onto the 60% portion of the keyboard under a layer accessed by holding the "Caps Lock" key. This allows users to experience and experiment with the benefits of such keyboards without comitting to a physical downsizing, memorizing multiple complex layers, or needing to re-learn how to type: all original key functions remain unchanged except for Caps Lock (accessed via Caps Lock + Space), letting users revert to old habits in a pinch.

As an example, the following functions may be accessed without moving your fingers from the home row:
- Jump the cursor to the next or previous word
- Delete the previous or next word
- Delete all text on the current line before or after the cursor

By including the rows above and below home, we can access an even wider array of functions without needing to significantly move our hands. Key mappings are optimized for ergonomics and easy memorization.

Furthermore, the following commands may be accessed exclusively with your left hand:
- Delete and backspace
- Return
- Escape
- All modifiers
- Any modifier or combination of modifiers + backspace, enter, delete

This makes for effective use of critical functions while also navigating with the mouse or with the right-handed navigation functions under the layer.

### Compatibility
This layout works with most traditional keyboards (non-ortholinear) that are 60% or larger. The functions may be easily mapped onto any alternative international layouts.

This project is incompatible with most HHKB-style keyboards that have Ctrl in the Caps Lock position. Some HHKB-style keyboards may offer a dedicated left-hand function key that could be used instead, however, the ergonomics are optimized for the key in the traditional Caps Lock position. 

The spacebar can also be used to access the layer with good ergonomics (tap for space, hold for layer) if the user`s software supports it.


## Layout
Below are the specific keymappings within the Caps Lock layer.

For brevity, I use the following symbols:
- ⌘: Command
- ⌥: Option
- ⌃: Control
- ⇧: Shift
- ↵: Enter/Return
- ⌫: Backspace
- ⌦: Delete (forward delete)
- ⊞: Super/Win key

Letter and number keys are referred to in `code` form, i.e. the the key immediately to the right of Tab is `q`. The Caps Lock key is denoted ⇪.

![image](https://github.com/user-attachments/assets/9f3c4a39-9794-4a0b-9e6f-d8e070f78e36)

The image above displays the basic function layer for macOS.

![image](https://github.com/user-attachments/assets/847b7352-6bb0-46be-99ae-7519f2dbcba4)

The image above dispalys the basic function layer for Windows/Linux.


### Toggle Caps Lock
The caps lock toggle is available by pressing ⇪ + spacebar.


### Left Hand (main functions + modifiers)
1. `q` opens the numpad layer
2. `w` → ⌃ on Mac, ⊞ on Windows
3. `e` → ⇧
4. `r` → ↵
5. `t` toggles the layer on/off (i.e., so you don't have to hold down ⇪) 
6. `a` → ⌥ on Mac, ⌃ on Windows
7. `s` → ⌘ on Mac, Alt on Windows
8. `d` → ⌫
9. `f` → ⌦
10. `g` → Insert

The left hand can be used to access common functions that traditionally require the right hand such as enter, backspace, and delete, allowing the user to comfortably perform these functions while navigating with the right hand or mouse without needing to move the right hand back and forth.


### Right Hand (navigation)
Navigation functions may be accessed via your right hand:
1. `i` → up 
2. `j` → left
3. `k` → down
4. `l` → right
5. `y` → Page Up
6. `h` → Page Down
7. `u` → Home
8. `o` → End
9. `p` → Print Screen

The right hand accesses navigation functions such as arrow keys and page up/down.


### Function Keys 
The number row keys are mapped to the function keys (`1` as `F1`, `2` as `F2`, ... `=/+` as `F12`).


### Numpad Layer
The numpad layer is accessed by holding ⇪ + `z`:
1. `7`, `8`, and `9` map to themselves
2. `u`, `i`, `o` map to `4`, `5`, `6`
3. `j`, `k`, `l` map to `1`, `2`, `3`
4. `m` and `,<` map to `0` and `00` respectively
5. `.>` maps to a period/decimal point `.`

![image](https://github.com/user-attachments/assets/27e3ee0d-3d7f-4d81-b853-ee53530402f2) 


## Usage
The below sections detail the usage of the RRKB layer.


### Chording
While general usage is straightforward, what may not be is the "chording", or the use of multiple key combinations to access various functions. For example, the following critical functions may be accessed with your left hand exclusively by chording multiple keys:
- Delete the previous or next word: Hold ⇪ + `a` (⌥) and press `d` (⌫) or `f` (⌦).
- Delete all text on the line before or after the cursor: Hold ⇪ + `s` (⌘) and press `d` or `f`.
- Insert a new line without submitting the current text (e.g., when composing a message): Hold ⇪ + `c` (⇧) and press `e` (↵).

Furthermore, by including the navigation functions with our right hand, we may access even more functions:
– Jump the cursor to the next or previous word: Hold ⇪ + `a` (⌥) and press `l` (right arrow) or `j` (left arrow).
- Highlight the previous or next page of text: Hold ⇪ + `c` (⇧) and press `h` (Page Up) or `n` (Page Down).
- Unindent or indent a line in a code editor: Hold ⇪ + `s` (⌘) and press `u` (`[{`) or `o` (`]}`)


### Memorizing the Layout
Whenever possible, keys are mapped mnemonically or to be generally easy to remember: 
- Super ("Win" key) to `w`
- Enter ("Return") as `r`
- Backspace ("delete") to `d`
- Delete ("forward delete") to `f`

In other cases, keys are mapped to optimize ergonomics. For instance, while it may be more mnemonic to place ⌘ (Command) at `c`, ⌘ is instead mapped to `s` to enable the ergonomic chord ⇪ + `s` + `f` (⌘ + ⌦) and avoid the unergomonic ⇪ + `c` + `f`. Similarly, Shift is placed at `e` to enable easy chording with Enter at `r`. 

Because the functions within the layer are quite dense and will take time to get used to, it's recommended to start slow. The most useful functions are accessing these from the left hand:
1. ⇪ + `r` as Enter
2. ⇪ + `d` or `f` as Backspace and Delete respectively.
3. ⇪ + `a` + `d` or `f` to delete the previous or next word, respectively.

From there, work on incorporating:
1. Arrow keys as `ijkl`
2. Shift as `e` in combination with `ijkl` for highlighting text
3. Opt and Cmd as `a` and `s` in combination with `e` and `ijkl` to highlight words or lines of text.
4. Ctrl/Win as `w` with `jl` to switch desktops

Lastly, users may work on incorporating the miscellaneous navigation functions, symbols, and numpad layer.


### Customization
The `z` row of the keyboard is left open for user customization. I personally map a few symbols to the bottom row 
