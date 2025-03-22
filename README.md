# OpenMacro
A program to make macros 
to exit press: control+alt+q
Scripts that will be used need to be in the same directory as the program
Language:                            
# : command;detection;action :
# Remeber to put :OM: on top of your code

Available commands:
if, startup

Available actions:
press_key("key"), press_mouse_button("left/right/middle"), move_mouse(x,y), "run_command("command")

Available detections:
is_key_pressed("key")

To use multiple actions separate them by using: -             
                              
# Examples:
# Run command prompt on the start of the script: 
# : startup;run_command("start cmd") :
# When pressing control+alt+o move mouse to the middle of the screen: 
# : if;is_key_pressed("ctrl+alt+o");move_mouse(960,540) :

