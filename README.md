Maybe?
======

A bash script for dry-running other bash scripts and seeing what they would have changed.

Maybe is a pure bash proof-of-concept inspired by [maybe by p-e-w](https://github.com/p-e-w/maybe).

This project is not as extensive as the python one, as this project does not use any sort of tracing to work out what is happeneing; rather it uses some bash scope trickery to fake several common bash commands.


Example
-------

Running `./maybe ./demo.sh`

```bash
  Running './demo.sh'
  Done
  Changes:
    Touch 1
    Move 1 a
    Copy a 2
    Remove  a
```
