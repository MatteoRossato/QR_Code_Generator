# QR Code Generator

This Python project allows you to generate QR codes from text, URLs, or other types of data. It leverages the `qrcode` library for creating QR codes and provides a simple interface to generate and save them as image files.

## Features

- Generate QR codes from text or URLs.
- Save QR codes as PNG images.
- Customize QR code appearance (e.g., size, color, border).
- Simple command-line interface for generating QR codes.

## Technologies

- Python 3.x
- Libraries:
  - `qrcode` (for generating QR codes)
  - `Pillow` (for image handling)
  
## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/qr-code-generator.git
    cd qr-code-generator
    ```

2. Create and activate a virtual environment (optional but recommended):

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. Install the project dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To generate a QR code, run the `generate_qr.py` script with the desired text or URL. You can also customize the QR code's appearance by passing additional arguments.

### Example Usage:

```bash
python generate_qr.py "https://www.example.com"
