![Debian Build Status](https://img.shields.io/github/actions/workflow/status/BreeDurbin/linux-internals/cmake-single-platform.yml?style=flat-square&logo=ubuntu&label=Ubuntu%20Build&color=#E95420)
![GPL License](https://img.shields.io/github/license/BreeDurbin/cyrus?style=flat-square&logo=gnu&label=License)

# linux-internals
linux internals. Process management, memory management, file io, multithreading, IPC etc


Notes to self:

ipc
```
communication via ipc
to child processes 
and to unrelated processes
via differrent transport layers
```

memory management
```
allocate memory
free it
using the kernel
```

process management
```
program which will open a tty process and print hello world
the program can then kill the process by typing k
```

filesystem
```
writes to a file based on console input

can read from taht file and print it out
```

multithread
```
spin up multiple threads and have them access a shared resource while using mutex to block access conflicts
```

events
```
multithreaded programs which can communnicate between threads using an event queue
```

kernel
```
makes a variety of kernel syscalls
```

linking
```
static and dynamic linking demo
```
