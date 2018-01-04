# rubiks-examples

This repository is a rubiks repository, needing the rubiks tool to generate. It generates YAML for consumption by openshift or kubernetes.

It has 2 clusters (*staging*, **production**). Sources can be found in `sources/` and the output yaml will be generated in `out/` (`out/<cluster>/<global>.yaml` or `out/<cluster>/<namespace>/<objects>.yaml`). Files containing confidential data will be .gitignored (with one .gitignore in `out/.gitignore`).

You can regenerate the output by running `rubiks generate` in this directory.

See the rubiks documentation and `rubiks list_objs` and `rubiks describe` for more information on the sources.

This readme was auto-generated and can be regenerated by running `rubiks readme` in this directory.

-----

This repository is an example to show how rubiks can be used in practice. To use, clone this repository, and download the [rubiks tool](https://github.com/olx-global/rubiks/) and follow the installation instructions there. You can then run the commands above in this repository.

This repository ignores (via .gitignore) the output, although in normal practice this wouldn't happen, and you'd check in the non-confidential parts of out so that you can also see what changes and what to update.