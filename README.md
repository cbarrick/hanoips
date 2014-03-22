# Hanoips

A Towers of Hanoi console game written in MIPS assembly.

To play, you will need the *[spim]* MIPS simulator or one compatible with its system calls and pseudo instructions, like the MIPS IDE *[Mars]*.

Mac users can `brew install spim`. Linux users should be able to find *spim* in their distribution's repositories.

[spim]: http://spimsimulator.sourceforge.net
[Mars]: http://courses.missouristate.edu/KenVollmar/Mars/

## Running
Mars is a graphical simulator. To run in Mars, open the `hanoi.mips` file, assemble, and run.

spim is a command-line simulator. To run in spim, load the game from within a spim session:

```
(spim) load "./hanoi.mips"
(spim) run
```
