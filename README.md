# Enigma Machine

![Enigma Machine](demo) <!-- You can add an image related to the project if available -->

## Overview

This project is a simulation of the **Enigma Machine**, the encryption device used by Germany during World War II. It replicates the mechanics of the machine, including rotors, plugboards, and encryption algorithms, allowing users to explore and experiment with one of the most famous cryptographic tools in history.

## Features

- Full simulation of the **Enigma Machine** encryption process
- Configurable rotors and plugboards
- Support for custom rotor settings and plugboard configurations
- Encryption and decryption of messages in real-time
- Historical accuracy in simulating the encryption process

## Technologies Used

- **Language**: Python


## How It Works

The Enigma Machine works by scrambling the input text via a series of rotors and a plugboard, making each letter substitution unique based on the initial machine settings.

- **Rotors**: Each rotor has its own substitution pattern, and they rotate after each keypress.
- **Plugboard**: Allows additional letter substitution, adding another layer of encryption.
- **Reflector**: After passing through the rotors, the signal is reflected back through the rotors in reverse, ensuring that encryption is reciprocal.

## Setup & Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/mohdamirwebdeveloper/enigma-machine.git
    ```
   
2. **Run the application**:
    ```bash
    python Enigma.py
    ```

## Usage

1. Configure the machine by setting up the rotor order, starting positions, and plugboard configuration.
2. Enter a message to encrypt or decrypt.
3. View the output to see the encrypted or decrypted message.
