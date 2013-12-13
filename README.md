### Branches explained:

`master` tracks [upstream master](https://github.com/ocaml/opam-repository). 

`<package-name>` are branched off of master. These are destined for pull requests for packages that are ready to be listed at [http://opam.ocaml.org/pkg/](http://opam.ocaml.org/pkg/)

`develop` is the "dafault branch" and the one I keep checked out on my development machines. This branch doesn't necesarily track master. For packages that I am working on, `url` files point to relative local paths.