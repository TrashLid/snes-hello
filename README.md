# "Hello, World!" for the Super Nintendo Entertainment System
If you're looking for the Nintendo Seal of Quality, you're gonna have a bad time.

<!-- ![Screencap from Snes9x Emulator](hello_snes9x.png) -->

To build, you need to install [cc65](https://github.com/cc65/cc65), with the
executables on your path.

Then run **build.sh** from bash, or just run the build directly on the command line:

```
cl65 -C smc.cfg -o hello.smc -l hello.list hello.asm
```

You can then load hello.nes into the SNES/SuperFamiCom emulator of your choice. It has been
tested on Linux using Snes9x and Higan. If you have an issue with any other emulator or
host environment, please post an issue to this repo. Thanks!