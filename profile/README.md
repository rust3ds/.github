# Welcome! 👋

Rust3DS is a GitHub Organization with the objective of developing libraries and tools to integrate the [Rust programming language](https://www.rust-lang.org/)
in homebrew projects for the Nintendo 3DS system. 🦀 🎮

### _Ok, but why?_
The current technology used to develop homebrew games on the Nintendo 3DS family of consoles is extremely advanced, yet also very
unstable and hard to use for inexperienced users. From the pains of crashes and unending stack backtraces, Rust3DS was born, with the main goal of wrapping
the underlying system processes in a safe and performant way.

# Getting Started 🏃

If you wish to start using our toolchain, you must keep in mind a couple of things:
1. All of the programming will be done in the Rust programming language, so you should have some familiarity with it before trying our libraries.
2. As our current implementations stand, we depend on [devkitPRO](https://github.com/devkitPro)'s `devkitARM` C toolchain. 
   Getting to try that first will give you a better idea on how the underlying system actually behaves.
3. Even though we officially support the Rust [std](https://github.com/rust-lang/rust/tree/master/library/std) library, we may not be able to guarantee
   full support for its current (or future) functionality.
4. Very few public crates explicitly support the ARM architecture (which the Nintendo 3DS is based upon), and none officially support the 3DS' operating system,
   so you cannot expect out-of-the-box support from third-party libraries, especially if they have anything to do with multi-threading (more on that later).

If you think you are ready to develop homebrew using our tools, then we welcome you aboard!
You can check out the [wiki](https://github.com/rust3ds/ctru-rs/wiki) at [ctru-rs](https://github.com/rust3ds/ctru-rs) for more info on
installing and using our tools.

# Contribution 🔧

We are always open to contribution and feedback. If you have a feature you'd really love to see implemented, you can always open a PR or an issue
in the corresponding repository.

# Disclaimer
Rust3DS is NOT affiliated with Nintendo, nor do we use or work on their proprietary SDK.
