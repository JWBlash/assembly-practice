# prereqs

Need to install the assembler and linker to run some asm code.

I'm running this with Ubuntu wsl, so your set up may vary.

To test to see if you have an assembler and linker, run `as` -- which should hang as it looks for input, and then `ld`, which should respond something like `ld: no input files`.

If you don't have either of these, you should be able to get them with a `sudo apt install gcc`.
