# Switcher Active Window Manager

Supercharged Alt-Tab window manager that handles windows on multiple monitors
and multiple desktops. Allows more detailed window control vs the built-in
Alt-Tab tool on windows.

When activated on a monitor the list of windows appear. Their window state, on-top, 
desktop and monitor locations are shown as well. Each of the icons can be clicked to change the state.

![image](https://github.com/user-attachments/assets/8b12d719-a656-4e74-be04-06c9f7d5d03c)

## Hotkeys - Edit in Switcher.ahk2 file

|Hotkey|Description|
|---|---|
|Alt-Tab|Activate Switcher, Alt-Tab and Shift-Alt-Tab works just like built in functions|
|ScrollWheel_Right|Switch to prior window of same application (if Mouse supports)<br>If over tray area move to next desktop|
|ScrollWheel_Left|Switch to prior window of different application (if Mouse supports)<br>If over tray area move to prior desktop|
|Control-ScrollWheel_Right|Go to next desktop with wrap (similar to Control-Win Right)|
|Control-ScrollWheel_Left|Go to prior desktop with wrap (similar to Control-Win Left)|
|XButton 1|Activate Switcher with list of windows of current application (if mouse supports)|
|XButton 2|Activate Switcher with list of all top level windows (if mouse supports)|
|Click Tray Icon|Switch to next desktop in rotation|

## Keypad Assignment for Windows

Note: This only work if your keyboard has a full numeric keypad such as full size keyboard.
The assignments will show up in the switcher window. Clicking the assignment will remove it.

|Hotkey|Description|
|---|---|
|Ctrl-<keypad #>|Assign the active window to be restored when pressing <keypad #>|
|Ctrl-Alt-<keypad #>|Unassign the window assigned to this keypad|
