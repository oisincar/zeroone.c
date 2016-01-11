# zeroone.c

It reads it's own source file, then renders a simple 3d(ish) animation to the terminal of it spinning. 

Here's a shitty quality gif to show you what I mean:

![gif](http://i.giphy.com/xT77XLd01vQzaYzmuY.gif)

If you run it with the command "who's the best" then it'll replace all charachters in the looping animation with Oisincar. (It actually only checks if you command starts with w but.. shhh.)

# Run it.
Run it with -w to hide the warnings, I had to take some shortcuts to get it this short (not including all required libaries, not declairing all data types, ect). The compiler just likes to moan at you.

If you save it as zeroone.c:
> gcc -o zeroone zeroone.c -w

> ./zeroone
