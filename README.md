# C++ Color

Reference: https://stackoverflow.com/questions/4053837/colorizing-text-in-the-console-with-c

Hey guys, I've made a basic colour library for C++'s console, this can also be used with Replit's compiler.

**Example**
```
std::cout << Color::RED << "Hello World!" << Color::CLEAR << std::endl;
```

**Output**
- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) `#f03c15`


In the example above, we set the colour to red with ```Color::RED```, then define the text after that, and finally clear the colour so next lines aren't affected.