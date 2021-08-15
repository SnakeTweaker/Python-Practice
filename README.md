# Spindash in Sonic 1

Known Issues:
-Sprite animation for Spindash is incomplete
-Camera panning on Spindash does not follow Sonic accurately
-Sprite corruption when breaking a monitor, a 1-up monitor will appear instead of the broken monitor sprite
-Sonic "spazzes" out sometimes when on ground that is not level

Changes made: 
-Directly copied the object code from Sonic 2's disassembly and added Sonic_SpinDash routine
-Modified the animation to make it more appropriate and less like a glitch
-Fixed level boundary bug that kills Sonic if he scrolls too fast to the bottom of the screen

