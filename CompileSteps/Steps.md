
## Pre-processing:
    - ```g++ -E hello.cpp -o hello.ii```

## Compilation
    - ```g++ -S hello.ii -o hello.s```

## Assembly
    - ```g++ -c hello.s -o hello.o```

## Linking
    - ```g++ hello.o -o hello```

## All In One
    - ```g++ hello.cpp -o hello```
