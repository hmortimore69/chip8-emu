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

For example, on Ubuntu, you can install SDL2 with:
```sh
sudo apt-get install libsdl2-dev```

Clone this repository:
sh
Copy code
git clone https://github.com/yourusername/chip8_emulator.git
cd chip8_emulator
Build the project using Cargo:
sh
Copy code
cargo build --release
Usage
To run the emulator, use the following command:

sh
Copy code
cargo run <path_to_chip8_rom>
For example:

sh
Copy code
cargo run roms/IBMLogo.ch8
Controls
The Chip-8 keypad is mapped to the following keyboard keys:

Chip-8 Key	Keyboard Key
1	1
2	2
3	3
C	4
4	Q
5	W
6	E
D	R
7	A
8	S
9	D
E	F
A	Z
0	X
B	C
F	V
Exiting the Emulator
To exit the emulator, press Escape or close the window.

License
This project is licensed under the MIT License. See the LICENSE file for details.

typescript
Copy code

You can save this content into a file named `README.md` in your project directory. If you need any further customization or additional information included in the README, feel free to let me know!
