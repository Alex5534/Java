Study and enlist the basic function used for graphics in C/C++/Python

language.

A) ELLIPSE FUNCTION IN C

#include<graphics.h>

#include<conio.h>

main()

{

int gd=DETECT,gm;

initgraph(&gd,&gm,"C\\TC\\BGI");

arc(100,100,0,135,50);

getch();

closegraph();

return 0;

}

OUTPUT
