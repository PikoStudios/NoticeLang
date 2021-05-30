# NoticeVM

## How To Build
Debian/Ubuntu (Non-verbose)
```
$ sudo apt-get install gcc
$ sudo apt-get install make
$ make CC=gcc EXEC=bin/notice
```

Debian/Ubuntu (verbose)
```
$ sudo apt-get install gcc
$ sudo apt-get install make
$ make debug CC=gcc EXEC=bin/notice 
```

Windows
```
# Download GCC and Make through MinGW. or use msvc
$ make CC=[Compiler Name]
```

Windows (verbose)
```
# Download GCC and Make through MinGW. or use msvc
$ make debug CC=[Compiler Name]
```
