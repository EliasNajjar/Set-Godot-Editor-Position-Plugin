# Set Editor Position
Plugin for Godot 4.4

Adds UI to the 3D toolbar allowing you to input an x, y, and z coordinate and teleport to it in the editor

## Adding to you Godot project

Make a folder with set_editor_position.gd and plugin.cfg. Go to the file location of your Godot project and create an folder called "addons" if you do not already. Place the plugin folder in the addons folder. Go to your project in Godot and enable the plugin by selecting Project->Project Settings...->Plugins, and enabling Set_Editor_Position. Now you will see the UI in the toolbar, three input boxes labeled X=0, Y=0, and Z=0 and a button labeled Go.

## Usage

You can type in coordinates for the x, y, and z coordinates and press go to move to that location. Coordinates default to 0 with no input. After pressing Go, you will undergo one transport, then soon after you will undergo another transport that will take you to the location you want to go. The description for why 2 transports was necessary is explained below. This plugin is extremely useful for creating large scenes where trying to move to another part takes a long time.

## Why are 2 transports necessary

You can move in the Godot editor by right-clicking and using WASD, or by rotating around a pivot using middle click or the tool in the top right of the viewport. 
Not finished...
