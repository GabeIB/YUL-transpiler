This is a transpiler written in ocaml for transpiling miniC into YUL.
The idea is that it will form the basis for YUL support by the DeepSEA compiler.

The folder Demo_Code contains sample minic programs, as well as the
transpiled YUL, outputted from our transpiler.

The folder Transpiler contains the files for our transpiler. To build the
transpiler, run "ocamlbuild transpiler.native" on the commandline while in
the Transpiler folder

To compile a minic program into yul, run "cat ../Demo_Code/***example.mc***
| transpiler.native" on the commandline while in the Transpiler folder.
