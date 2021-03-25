# Installing the Equilibrium Blender plugin

This document will help you installing the Equilibrium Blender Plugin.

## Setup

You will need the following: Blender 2.79 and some Blender knowledge, The Driver Syndicate SDK Tools and some basic computer knowledge.

## Installing the plugin

If you have everything ready from the 'Setup' part, then you are ready to follow this.

1. Locate to your folder where you have the SDK. In the folder, head over to Blender 2.7x. Open the folder. You will see "io_equilibrium_esm_esa.py". Don't touch the file yet.
2. Open Blender. Press Ctrl+Alt+U, this will open the User Preferences window (If this does not work, head over to the "Troubleshooting" section).
3. Now we have a window. Assuming it's the first time opening it, it will show the "Interface" tab. This is not the correct one though, at the top of the UP window, press Addons.
4. After we opened the Addons tab, look down and search the "Install addon from file" button. Click on it. Now we will see a screen similar to the Windows File Explorer.
5. Now head back to Windows File Explorer. In the directory with the Python (PY) file, press the top bar showing the location. Normally it will show selected, if not so, select all the location text. Now press Ctrl-C to copy it.
6. Head back to Blender. In the Blender file explorer thingy, press the "File path" text showing the location (directory). Paste (Ctrl-V) the location you just copied and press enter.
7. Now we will see the Python file appear in Blender file explorer thingy, double click it to install it. After we did that, we are back at the addons tab. If followed correctly, the plugin should appear in the list. Press the empty box to check it to enable it.
8. Press "Save user settings" at the bottom. Close the UP window and restart Blender. Now Blender will show us the ability to export to .esm in the "export" part. Great!

## Troubleshooting

If the User Preferences window does not open after pressing the shortcut, open it manually through "File>User Preferences".