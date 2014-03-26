Gg — Basic types for computer graphics in OCaml
-------------------------------------------------------------------------------
Release %%VERSION%%

Gg is an OCaml module providing basic types for computer graphics.

It defines types and functions for floats, vectors, points, sizes,
matrices, quaternions, axis-aligned boxes, colors, color spaces, and
raster data.

Gg is made of a single module, depends on bigarrays, and is
distributed under the BSD3 license.

Home page: http://erratique.ch/software/gg  
Contact: Daniel Bünzli `<daniel.buenzli at erratique.ch>`

## Installation

Gg can be installed with `opam`:

    opam install gg

If you don't use `opam` consult the [`opam`](opam) file for build
instructions and a complete specification of the dependencies.

## Documentation

The documentation and API reference is automatically generated by
`ocamldoc` from `gg.mli`. It can be consulted [online][1] and there
is a generated version in the `doc` directory of the distribution. 

[1]: http://erratique.ch/software/gg/doc/Gg


## Sample programs

Sample programs are located in the `test` directory of the
distribution. They can be built with:

    ocamlbuild test/tests.otarget

The resulting binaries are in `_build/test` :

- `test.byte` tests the library, nothing should fail.
