# Chip-8 Emulator

This is a Chip-8 emulator written in Rust, utilizing the SDL2 library for rendering and input handling. The emulator reads and executes Chip-8 ROMs, displaying the output and handling user input.

## Features

- Emulates the Chip-8 instruction set
- Renders graphics using SDL2
- Handles user input for Chip-8 programs

## Requirements

- Rust (latest stable version recommended)
- SDL2 library

## Installation

1. Install Rust from the official [Rust website](https://www.rust-lang.org/).
2. Ensure SDL2 is installed on your system. You can follow the instructions on the [SDL2 website](https://wiki.libsdl.org/Installation).
3. Clone this repository:

```sh
git clone https://github.com/yourusername/chip8_emulator.git
```

4. Build the project using Cargo:
```sh
cargo build --release
```

## Usage
To run the emulator, use the following command:

```sh
cargo run <path_to_chip8_rom>
```
For example:

```sh
cargo run -- ../roms/pong2
```

## Controls
The Chip-8 keypad is mapped to the following keyboard keys:

| Chip-8 Key | Keyboard Key |
|------------|--------------|
| 1          | 1            |
| 2          | 2            |
| 3          | 3            |
| C          | 4            |
| 4          | Q            |
| 5          | W            |
| 6          | E            |
| D          | R            |
| 7          | A            |
| 8          | S            |
| 9          | D            |
| E          | F            |
| A          | Z            |
| 0          | X            |
| B          | C            |
| F          | V            |

## Exiting the Emulator
To exit the emulator, press `esc` or close the window.
