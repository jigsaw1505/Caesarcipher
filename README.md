# Caesar Cipher

This project implements a Caesar Cipher in Python. A Caesar Cipher is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

## Features

- Encrypts plaintext using a specified shift value.
- Decrypts ciphertext using the same shift value.
- Supports both upper and lower case letters.
- Ignores non-alphabet characters during encryption/decryption.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/caesar-cipher.git
    ```

2. Navigate into the project directory:
    ```sh
    cd caesar-cipher
    ```

3. (Optional) Create a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. Install the required dependencies (if any):
    ```sh
    pip install -r requirements.txt
    ```

## Usage

You can use the Caesar Cipher script to encrypt or decrypt messages from the command line.

### Encrypting a message

To encrypt a message, use the `encrypt.py` script with the plaintext and shift value as arguments:
```sh
python encrypt.py "Your message here" 3
