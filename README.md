# Cedille Cast #

The Cedille Cast is a series of videos [on
YouTube](https://www.youtube.com/channel/UCfV0BJz4nltlj-4yWNZ34lw) that covers
programming and proving in Cedille, a dependently typed programming language and
proof assistant. This repository contains the source files and scripts for these
videos.

For more information on Cedille, check out our [website](https://cedille.github.io/).

## Layout ##

- [screencasts](screencasts): directory of source files and scripts
- [lib](lib): small library of common definitions used in the casts
- [.cedille](.cedille): Cedille options file (local file picked over one in
  user's home directory)
  
## Screencasts ##

- Deriving induction for lambda-encoded datatypes
  - for Church encoded naturals (parts [1](screencasts/cedille-cast-01.ced) and
    [2](screencasts/cedille-cast-02.ced))
  - generically for Mendler-syle encodings (parts
    [1](screencasts/cedille-cast-05.ced), [2](screencasts/cedille-cast-07.ced),
    and [3](screencasts/cedille-cast-08.ced))
- Zero-cost coercions and their applications
  - [Cedille's equality type and defining zero-cost coercions](screencasts/cedille-cast-03.ced)
  - [Deriving recursive types](screencasts/cedille-cast-04.ced)
- Cedille features
  - [Inductive datatypes in version 1.1.0](screencasts/cedille-cast-06.ced)
  - [Interactive theorem proving in the beta-reduction
    buffer](screencasts/cedille-interactive-tooling.ced)
- [Impredicativity and proof irrelevance](screencasts/cedille-cast-09.ced)
