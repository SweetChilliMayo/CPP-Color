# C++ Color

Reference: https://stackoverflow.com/questions/4053837/colorizing-text-in-the-console-with-c

Hey guys, I've made a basic colour library for C++'s console, this can also be used with Replit's compiler.

## Example
```
std::cout << Color::RED << "Hello World!" << Color::CLEAR << std::endl;
```

## Output

<img src="Images/HelloWorldRed.PNG" width="150"/>


In the example above, we set the colour to red with ```Color::RED```, then define the text after that, and finally clear the colour so next lines aren't affected.

## List of colours
```
Color::CLEAR
Color::BLACK
Color::RED
Color::GREEN
Color::YELLOW
Color::BLUE
Color::MAGENTA
Color::CYAN
Color::WHITE
Color::GREY
Color::BRIGHT_RED
Color::BRIGHT_GREEN
Color::BRIGHT_YELLOW
Color::BRIGHT_BLUE
Color::BRIGHT_MAGENTA
Color::BRIGHT_CYAN
Color::BRIGHT_WHITE
```

## How to Install

Place the "Colors" folder in your project, then to use the library type:
```
#include "[directory]/Colors/Color.h"
```