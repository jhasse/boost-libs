# Boost Libraries

Version: 1.54.0

* filesystem
* program_options
* serialization
* system
* unit_test_framework
* python

## Mac

```
b2 toolset=clang cxxflags="-stdlib=libc++" linkflags="-stdlib=libc++"
```

## Windows

### MinGW

```
.\b2 toolset=gcc
```

Python only:

```
.\b2 toolset=gcc --with-python link=shared
```