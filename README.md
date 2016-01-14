# Zerowhat?
A simple c program that reads it's own source file, then renders a simple 3d(ish) animation to the terminal of it's source code spinning.


Here's what I mean. This is the source code:
``` C
            #include                            "stdio.h"
    float a,b,c,d=0,e=10;f,g,                 h=0,i=0,j=0
   ,k,l,m,n[        10000];main         (int O,char*o[]){
  char p[10001         ];FILE*F=     fopen(__FILE__,"r");
  int*q=O>1?o[1][      0]!=119?0:        (int[9]){79,0x69
 ,115,   0151,0x6e     ,99,97,114           ,056}:0;while
 (n[++      h]=O=         getc(F),          O>0)O==10?i=i
 >g?i:       g,g=1,       j++:g++;          fclose(F);for
 (;;){        memset(p   ,32,i*j);          d+=0.10;a=sin
 (d);b=         cos(d);    usleep(          50000);for(c=
 e;c>=0           ;c--){g  =k=l=0;          while(g++<h-1
  ){O=n[           g];f=i/2+(k-i/2          )*a-(c-e/2)*b
  +(i*l);             k=O==10?l++           ,0:O!=32?O=!c
    ||c==e?q              ?q[g%             9]:O:64,p[f]=
    a<0?O:p[f]==32?O:p[f],-~k:        -~k;}}g=0;while(g++<j){ 
        p[g*i-1]=10;}printf           ("\r%s\x1b[%iA",p,j);}} 
```

And this is the console output:

![gif](http://i.giphy.com/xT77XLd01vQzaYzmuY.gif)


You can reshape the source code to whatever, it'll still work (as long the source is narrower than your terminal window). You can even change the thickness of the model and the speed at which it turns! 

Also, if you run it with the command "who's the best" then it'll replace all charachters in the looping animation with "Oisincar." (It actually only checks if you command starts with w but.. Shhh.)

# Run it.
I had to take some shortcuts to get it this short (not including all required libaries, not declairing all data types, ect). The compiler just likes to moan at you. Ignore it or tell it to shut up by running with: -w.

If you save it as zeroone.c you can:
> gcc -o zeroone zeroone.c -w

Then:

> ./zeroone

Or

> ./zeroone who doesn't smell

Ehehe.
