# Reverse Shell Client

This repository contains code for a reverse shell client that connects to a pre-defined server and performs various operations as commanded by the server. This is a demonstration of how reverse shell works for educational purposes and should be used responsibly.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contribute](#contribute)


## Features

1. **Reliable Transmission**: The data sent and received using this client ensures reliability through the use of JSON for encoding and decoding.

2. **Automatic Reconnection**: The client tries to establish the connection with the server in a loop until a successful connection is made.

3. **File Upload and Download**: The client can upload and download files to and from the server.

4. **Command Execution**: The client can execute shell commands.

## Installation

The script is written in Python, so you need to have Python installed on your machine. You can download Python from [here](https://www.python.org/downloads/).

1. Clone this repository:
```bash
git clone https://github.com/Ahmed-Sedki/backdoor.git
```
2. Navigate to the cloned repository:
```bash
cd backdoor
```

## Usage

Replace `192.168.1.12` and `5555` in the `connection()` function with your server's IP address and port number, respectively.

To run the script, use the following command:

```bash
python backdoor.py
```

The client tries to connect to the server and waits for commands.

**Note**: This script should only be used for legal and ethical purposes. The creator of this script is not responsible for any misuse.

## Contribute

Contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.
