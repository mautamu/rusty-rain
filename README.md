<h1 align="center">
  <br>
  <img src="https://user-images.githubusercontent.com/43012445/105452071-411e4880-5c43-11eb-8ae2-4de61f310bf9.gif" alt="GIF" width="800">
  <br>
  Rusty Rain
  <br>
  <br>
</h1>

<p align="center">
  <a><img alt="lastupdated" src="https://img.shields.io/github/last-commit/cowboy8625/rusty-rain"></a>
  <a><img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/cowboy8625/rusty-rain"></a>
  <a><img alt="issuse" src="https://img.shields.io/github/issues/cowboy8625/rusty-rain"></a>
  <a><img alt="Lines of Code" src="https://img.shields.io/tokei/lines/github/cowboy8625/rusty-rain"></a>
  <a><img alt="License" src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
  <a href="https://discord.gg/KwnGX8P"><img alt="Discord Chat" src="https://img.shields.io/discord/509849754155614230"></a>
</p>

A cross platform matrix rain terminal program that runs well and looks good.

## To Use

Simply run the following command on windows/mac/linux:

```
git clone https://github.com/cowboy8625/rusty-rain.git
cd rusty-rain
```
```
cargo run --release
```

or to install:

```
 cargo install rusty-rain
```

## Exit

To exit just press `ESC`


## Command Line Arguments

```
A terminal program that makes all your friends think you are a hacker.

USAGE:
    rusty-rain [OPTIONS]

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -c, --chars <characters>    Set what kind of characters are printed as rain
    -C, --color <color>         Set color of Rain with color string name or tuple
                                white,
                                red,
                                blue,
                                green,
                                "(r, g, b)"


    -H, --head <head>           Set the color of the first char in Rain.
    -s, --shade <shade>         Set Rain shading to fade or stay constant
```

### Example

using cargo to run:

`cargo run --release -- -C "(0, 139, 139)" -H "(255, 255, 255)" -s 1 -c jap`

after installing:

`rusty-rain -C "(0, 139, 139)" -H "(255, 255, 255)" -s 1 -c jap`

# Help

If find any bugs or performance is not up to par please submit a issue so I can better improve
the project.
