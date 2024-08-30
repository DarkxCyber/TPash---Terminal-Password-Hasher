# TPASH (Password Hasher)

![PASH ASCII Art](./pash_ascii_art.png)

## Description

PASH (Password Hasher) is a command-line tool that allows you to generate custom, short hashes using various hashing algorithms. The tool is designed to be simple yet powerful, offering the ability to create unique hashes by including all characters, numbers, symbols, and more.

## Features

- **Custom Hashing**: Generate a custom hash for your password, including all characters, numbers, symbols, etc.
- **Multiple Hashing Algorithms**: Choose from a wide range of hashing algorithms supported by Python's `hashlib`.
- **Salt Generation**: Automatically generate a random salt to enhance security.
- **Colorful Terminal Output**: Enjoy a visually appealing interface with color-coded outputs.
- **ASCII Art Display**: Displays an ASCII art logo of the tool at startup.


## Requirements
      Python 3.x
## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/pash-password-hasher.git
   
2. Navigate to the project directory:

  ```bash
    cd pash-password-hasher

3. Run the tool:

  ```bash
    python pash.py


## Usage

    1. Launch PASH:
        ```bash
        python pash.py

    2. Enter your password when prompted.

    3. Choose a hashing algorithm from the list provided.

    4. Get your custom hash! The tool will output the generated hash along with the selected hashing algorithm.

## Example

```bash

$ python pash.py

Available Hashing Algorithms:

1: blake2b
2: blake2s
3: md5
...

Enter your password: ********

Select a hashing algorithm by number (1-24): 3

Hashing Algorithm: md5
Custom Hash: ab1cde3fghijklm4
