# LatinusC
C library that translates all C keywords to their Latin equivalent.

## Installation
To install LatinusC you will need to download the src file in the repository and move the contents (latinus.h and the latinus directory)
to whatever project you will be using it in. Example:
```
MyProject/
├── main.c
├── latinus.h
└── latinus/
    └── (latinusc headers)
```

## Usage
To use LatinusC you will need to include the latinus.h header to your program with ```#include "latinus.h"```. Then you can create the rest of your program in Latin. To find keywords and their translation you can check the latinus directory, use ctrl+m1 in VSCode, or just check the repository.

> Note: preprocessor directives and functions defined by libraries such as the standard library are not translated.

Example program:
```
#include "latinus.h"
#include <stdio.h>

numerus primus(numerus argc, littera* argv[]) { 
    printf("salve, mundum! \n");
    reditus 0;
}
```

> If you think a keyword should be changed then open a problem or pull request.
