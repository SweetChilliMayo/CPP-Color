# C++ Color

Reference: https://stackoverflow.com/questions/4053837/colorizing-text-in-the-console-with-c

Hey guys, I've made a basic colour library for C++'s console, this can also be used with Replit's compiler.

**Example**
```
std::cout << Color::RED << "Hello World!" << Color::CLEAR << std::endl;
```

**Output**
```diff
- text in red
```

In the example above, we set the colour to red with ```Color::RED```, then define the text after that, and finally clear the colour so next lines aren't affected.