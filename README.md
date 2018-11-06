# braid-crypto

[![Build Status](https://travis-ci.org/Torrencem/braid-crypto.svg?branch=master)](https://travis-ci.org/Torrencem/braid-crypto)

Next things I need to do:
* Optimize Serialization a bit
* Add documentation
* Add more integration testing (not just unit testing)
* Fix the mess of lib.rs and main.rs etc.

DISCLAIMER: Do not use this library for anything you care about. I make no guarantees of its safety, security, or reliability, nor do I offer any LTS.

This is a project for my undergraduate course on Cryptography. This is very much a work in progress. There's not much in the way of a binary, but you can build with "cargo build" or run the tests I've been setting up with "cargo test". Here are several links to sources I'm using:

https://arxiv.org/pdf/0711.3941.pdf  (main resource)

http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.10.1759&rep=rep1&type=pdf
https://core.ac.uk/download/pdf/82700058.pdf
https://arxiv.org/pdf/math/9712211.pdf

(Also very important:  E. A. Elrifai and H. R. Morton, Algorithms for positive braids, Quart. J. Math. Oxford, 45,
No. 2 (1994))

I also took much inspiration from this package:
http://hackage.haskell.org/package/combinat-0.2.8.2/docs/Math-Combinat-Groups-Braid.html#v:-61--61-
Specifically, this source page for braidPermutation and other representational issues:
http://hackage.haskell.org/package/combinat-0.2.8.2/docs/src/Math-Combinat-Groups-Braid.html#line-64
