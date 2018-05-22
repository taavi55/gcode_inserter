# gcode_inserter
Insert code to gcode based on tags in code. 
gcode_inserter. On "macro input" sheet column A (Layer) is which tag must be found in code. Column B (command) is the part of code you want to insert to your gcode. Column C (before/after) is where you specify if command must be inserted before (use 0) or after (use 1) the tag found in code. In sheet "test" you paste your gcode and click blue button "Update code". Then macro will add commands from "test sheet" to your code. When done, you take the gcode and use it to print your model. 
