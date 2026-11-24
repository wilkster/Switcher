# Switcher Active Window Manager

A supercharged Alt-Tab window manager that handles windows on multiple monitors
and multiple desktops. It allows more detailed window control than the built-in
Windows Alt-Tab tool.

When Switcher is activated on a monitor, the list of windows appears. Each window's state, on-top status,
desktop and monitor location are shown as well. Each of the icons can be clicked to change the state.
The windows are always listed in most-recently-used order, the same as with Alt-Tab.

The icons shown to the right of each window can be clicked directly with the mouse to
minimize, restore, close, move desktops, move monitors and so on.

![image](https://github.com/user-attachments/assets/8b12d719-a656-4e74-be04-06c9f7d5d03c)

Right-clicking an entry gives direct control of the window's placement and monitor/desktop location.
You can also perform other window actions, such as moving offscreen windows to the active monitor.

![image](https://github.com/user-attachments/assets/80152ecc-e8b6-45dd-a0bd-b5e96cec44e9)

## Hotkeys - Edit in the Switcher.ahk2 file

|Hotkey|Description|
|---|---|
|Alt-Tab|Activate Switcher. Alt-Tab and Shift-Alt-Tab work just like the built-in functions|
|ScrollWheel_Right|Switch to the prior window of the same application (if the mouse supports it)<br>If over the tray area, move to the next desktop|
|ScrollWheel_Left|Switch to the prior window of a different application (if the mouse supports it)<br>If over the tray area, move to the prior desktop|
|Control-ScrollWheel_Right|Go to the next desktop with wrap-around (similar to Control-Win-Right)|
|Control-ScrollWheel_Left|Go to the prior desktop with wrap-around (similar to Control-Win-Left)|
|XButton 1|Activate Switcher with a list of the current application's windows (if the mouse supports it)|
|XButton 2|Activate Switcher with a list of all top-level windows (if the mouse supports it)|
|Click Tray Icon|Switch to the next desktop in rotation|

## Keypad Assignment for Windows

Note: This only works if your keyboard has a numeric keypad, such as a full-size keyboard.
The assignments will show up in the Switcher window. Clicking an assignment will remove it.

The computer beeps with one of three tone patterns when a numeric keypad key is used.

![image](https://github.com/user-attachments/assets/793d65a9-8ece-4d74-9ce9-f8b7296c9a63)

|Hotkey|Description|
|---|---|
|Ctrl-`<keypad #>`|Assign the active window to be restored when pressing `<keypad #>`. You will hear a low-high tone when it is assigned.|
|Ctrl-Alt-`<keypad #>`|Unassign the window assigned to this keypad key. You will hear a high-low tone when it is unassigned.|
|`<keypad #>`|If previously assigned, makes the assigned window active. If not assigned, you will hear a brief low tone.|

## Tray Icon

![image](https://github.com/user-attachments/assets/df27d75f-7a93-411c-b34b-07b6e837ed9e)

The Switcher tray icon always shows the current desktop number (up to desktop 10). Clicking the tray icon rotates to the next desktop with wrap-around.
Only previously created desktops will be used.
Right-clicking the tray icon brings up the standard AutoHotkey options along with the ability to edit the settings file. Changes
to settings require restarting Switcher.
