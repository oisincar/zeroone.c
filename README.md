# zeroone.c
A short bit of code that renders itself to the commandline, spinning.

It reads it's own source file, then renders a simple '3d' animation to the terminal of it spinning. If you run it with the command 
"who's the best" then it'll replace all charachters in the looping animation with Oisincar. (It actually only checks if you command starts with w but.. shhh.)

.gif coming soon!

# Run it.
Run it with -w to hide the warnings, i had to take some shortcuts to get it this short (not including all required libaries, not declairing all data types, ect). It still runs fine though!
> $ gcc -o zeroone zeroone.c -w
> $ ./zeroone
