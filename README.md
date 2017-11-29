riscv-opcodes
===========================================================================

This repo enumerates standard RISC-V instruction opcodes and control and
status registers.  It also contains a script to convert them into several
formats (C, Scala, LaTeX).

## Generate inst.scala
1. Add your instruction encodes into opcodes.
2. Make inst.chisel

This repo is not meant to stand alone; it is a subcomponent of
[riscv-tools](https://github.com/riscv/riscv-tools) and assumes that it
is part of that directory structure.
