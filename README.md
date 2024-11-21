#include <iostream.h>
#include <conio.h>

void main() {
    clrscr();

    char p = 219;

    gotoxy(30, 3); textcolor(RED); cprintf("%c", p);
    gotoxy(31, 3); textcolor(YELLOW); cprintf("%c", p);
    gotoxy(32, 3); textcolor(GREEN); cprintf("%c", p);
    gotoxy(30, 4); textcolor(RED); cprintf("%c", p);
    gotoxy(31, 4); textcolor(YELLOW); cprintf("%c", p);
    gotoxy(32, 4); textcolor(GREEN); cprintf("%c", p);
    gotoxy(30, 5); textcolor(RED); cprintf("%c", p);
    gotoxy(31, 5); textcolor(YELLOW); cprintf("%c", p);
    gotoxy(32, 5); textcolor(GREEN); cprintf("%c", p);

    getch();
}
