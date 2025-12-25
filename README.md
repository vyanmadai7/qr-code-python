# QR Code Generator

A simple Python script to generate QR codes from text or URLs.

## Installation
```bash
pip install qrcode[pil]
```

## Usage
```bash
python qr_code_generator.py
```

Enter your data when prompted, and the QR code will be saved as `qr_code.png`.

## Examples

- **URL**: `https://github.com`
- **Email**: `mailto:email@example.com`
- **Wi-Fi**: `WIFI:T:WPA;S:NetworkName;P:Password;;`
- **Plain text**: Any text you want to encode

## Configuration

Edit the script to customize:
- `version` - QR code size (1-40)
- `error_correction` - Error correction level (L, M, Q, H)
- `box_size` - Pixel size of each box
- `border` - Border thickness
- `fill_color` / `back_color` - Colors

## License

MIT
