 1. You will need to "get the mcu id" from the Sonic Pad add printer tool and put copy it in the [mcu] section of the printer.cfg, line 147.

 2. AFTER YOU LOAD THE "printer.cfg" FROM THE SONIC PAD MENU AND GO THROUGH THE INITAL TESTS, OPEN THE FLUIDD WEB INTERFACE BY ENTERTING THE IP ADDRESS OF THE SONIC PAD
 INTO THE ADDRESS BAR OF YOUR BROWSER, FOR MAINSAIL ADD ":8819" AFTER THE IP ADDRESS. OPEN "printer.cfg" FROM THE WEB INTERFACE, IN FLUIDD ITS IN THE "CONFIGURATING" "{...}" TAB
 ON THE LEFT SIDE OF THE INTERFACE, IN MAINSAIL ITS THE "MACHINE" TAB. UNCOMMENT LINES 142,143, AND 144 BY REMOVING THE "#" IN FRONT OF THE BRACKETS. THEN ADD "start.cfg", 
 "end.cfg" and "macros.cfg" FROM THE DOWNLOADED CONFIG FOLDER.