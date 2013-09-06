# Update Engine

## Build

Update Engine only builds inside of the SDK.
libchrome is built everywhere with NDEBUG you need to build it like so:

```
CFLAGS="-DNDEBUG" scons
```
