# Hexagn: Programming language

![GitHub top language](https://img.shields.io/github/languages/top/GameBuilder202/hexagn-rust?color=7047EF&style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/GameBuilder202/hexagn-rust?color=7047EF&style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/GameBuilder202/hexagn-rust?color=7047EF&style=flat-square)
![Discord](https://img.shields.io/discord/1015615296939233340?color=7047EF&style=flat-square)

> This repository is now the official for Hexagn - previous/legacy repository: [Hexagn C++](https://github.com/emm312/Hexagn)

A simple compiler project capable of compiling Hexagn to URCL codes. With an easy-to-read syntax that is mostly inspired by the C programming language, understanding it would be easy.

<p align="center"><img alt="Hexagn's syntax" src="./syntax.svg"></p>

*Preview of Hexagn's syntax. Similar in C++ Hexagn.*

## Prerequisites

If you are running a Windows NT system, please use WSL (Windows Subsystem for Linux) (while you can install Rust in Windows, it is more better if it was inside a Linux environment), and if you are using MacOS or (any) Linux (distro), you can continue the installation process.

Recommended to install the Rust programming language via [Rustup](https://rustup.rs) to get both `rustc` and `cargo`

- Rust programming language
- (Rust's) Cargo

## Installation (unstable)

Currently, there are no stable releases of Hexagn, cloning the repository directly will give you the in-development or unstable version.

1. Clone the repository via any option in the **<> Code** tab
2. Run the following commands in the `Hexagn/` directory (the cloned repository)
```
cargo build --release
cargo install --path .
```
3. Hexagn would be compiled inside the `target/` directory

## Contributing

You can help the project by contributing to it via forking it. Instructions on how to fork it can be found [here](https://docs.github.com/en/get-started/quickstart/contributing-to-projects).

## GitHub Pages

Hexagn has its dedicated page hosted via GitHub pages at [notalternate.github.io.](https://notalternate.github.io/hexagn/)

What does it have to offer? A full detailed description, documentation, and installation process of the language.

> However.. The previous/legacy [Hexagn C++](https://github.com/emm312/Hexagn) would not be supported in the webpages.

## Official Discord server

[Visit the official Hexagn Discord server!](https://discord.gg/invite/t75crS5XBe)

*Note that each updates or bulletin in the server will be related to Hexagn-rust and not C++ Hexagn*

## License

Repository licensed under the [MIT](LICENSE) license.