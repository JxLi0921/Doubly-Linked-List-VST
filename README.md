# Doubly-Linked-List-VST

This repository contains the final project for CS2603 (2021 Spring). This project aims to verify a doubly linked list library using VST.

## Environment Setup

* This repository was tested with Coq Version 8.12.2, Windows 10.
* This repository also requires the VST submodule from [PrincetonUniversity/VST](https://github.com/PrincetonUniversity/VST/tree/release-v2.6). Please install it according to the instructions.

## Notes

Some lemmas provided by us maybe not the "best practice", which makes the verification of some functions so verbose. For example, we use something like `pose proof classic (l<>[])` very frequently. This can be avoid.

## License

* My codes are provided under GNU General Public License v3.0. See `LICENSE` for more information.
