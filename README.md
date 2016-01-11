# Zerowhat?
A simple c program that reads it's own source file, then renders a simple 3d(ish) animation to the terminal of it spinning. 

Look at this shitty gif, then at the source code and you'll see what I mean.

![gif](http://i.giphy.com/xT77XLd01vQzaYzmuY.gif)

You can reshape the source code to whatever, it'll still work (as long the source is narrower than your terminal, then it fcks up). You can even change the thickness of the model and the speed of the turn! 

Also, if you run it with the command "who's the best" then it'll replace all charachters in the looping animation with "Oisincar." (It actually only checks if you command starts with w but.. shhh.)

# Run it.
I had to take some shortcuts to get it this short (not including all required libaries, not declairing all data types, ect). The compiler just likes to moan at you. Ignore it or tell it to shut up with -w.

If you save it as zeroone.c you can:
> gcc -o zeroone zeroone.c -w

Then:

> ./zeroone

Or

> ./zeroone Who doesn't smell

Ehehe.
