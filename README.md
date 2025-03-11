# Secret Message Decoder

## Overview

This project is a Python script that retrieves and deciphers a hidden message encoded in a Google Doc. The document contains Unicode characters along with their (x, y) coordinates, and the script reconstructs the grid to reveal the message.

## Features

- Fetches a published Google Doc's content
- Extracts characters and their respective coordinates
- Constructs a 2D grid to display the hidden message
- Handles large datasets dynamically

## Requirements

Ensure you have the following dependencies installed before running the script:

```bash
pip install requests beautifulsoup4 numpy
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/your-username/secret-message-decoder.git
cd secret-message-decoder
```

2. Run the script with a valid Google Doc URL:

```bash
python decoder.py
```

3. The script will print the hidden message on the console.

## Code Structure

- `decoder.py`: Main script that fetches, parses, and prints the secret message

## Example Output

```plaintext
BOECMXH
```

## Contributing

Feel free to fork this repository and submit a pull request with improvements or fixes.

## License

This project is licensed under the MIT License.

# DECODE-SECRET
