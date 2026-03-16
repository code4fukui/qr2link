# qr2link
日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple web application that displays a QR code and decodes QR codes from the clipboard or camera.

## Demo
https://code4fukui.github.io/qr2link/

## Features
- Displays a QR code with the current URL or a custom value
- Decodes QR codes from the clipboard or camera
- Updates the displayed QR code with the decoded value

## Requirements
None

## Usage
1. Open the [demo page](https://code4fukui.github.io/qr2link/)
2. The page will display a QR code with the current URL
3. To update the QR code, you can:
   - Paste an image with a QR code into the page
   - Click the camera icon to activate the QR code reader and scan a QR code
4. The page will update the displayed QR code with the decoded value

## Data / API
This project uses the following open-source libraries:
- [qr-code-reader](https://github.com/code4fukui/qr-code-reader)
- [qr-code](https://github.com/code4fukui/qr-code)

## License
This project is licensed under the [MIT License](LICENSE).
