# QR Code Scanner & Generator

This is a simple web application that allows users to scan and generate QR codes using their webcam and input text or URLs. It provides functionalities to generate QR codes from text, scan QR codes from the camera, copy the result to the clipboard, search the scanned result on Google, and share or save the generated QR code.

## Features

- **QR Code Scanner**: Use your webcam to scan QR codes in real-time.
- **QR Code Generator**: Generate QR codes from text or URLs.
- **Copy to Clipboard**: Copy the scanned QR code's result to your clipboard.
- **Google Search**: Perform a Google search on the scanned QR code result.
- **Save QR Code**: Save the generated QR code as an image.
- **Share QR Code**: Share the generated QR code using the Web Share API.
  
## Requirements

- **Web Browser**: Works on modern browsers with WebRTC support (for webcam access) and the Web Share API.
- **Internet**: For fetching QR code generation library and other resources.

## Installation

1. Clone or download the repository:
   ```bash
   git clone https://github.com/yourusername/qr-code-scanner-generator.git
   ```

2. Open the `index.html` file in your preferred web browser. No server setup is required; it works as a static HTML file.

## How to Use

### QR Code Scanner

1. Click on the "Start Scanning" button to start using the webcam.
2. Align a QR code in front of the camera; the scanner will automatically detect it.
3. Once a QR code is detected, the scanned result will appear below the scanner window.
4. You can copy the result to the clipboard or search it on Google.

### QR Code Generator

1. Enter the text or URL you want to encode in the input box.
2. Click the "Generate QR Code" button to generate the QR code.
3. The generated QR code will appear below the input field.
4. You can download or share the QR code by clicking the respective buttons.

### Additional Features

- **Copy**: Copies the scanned QR code result to the clipboard.
- **Google Search**: Opens Google search with the scanned QR code result.
- **Save QR Code**: Downloads the QR code as a PNG image.
- **Share QR Code**: Allows you to share the QR code via the Web Share API (if supported by the browser).

## Technologies Used

- **HTML5**: Structure and layout of the webpage.
- **CSS3**: Styling with TailwindCSS for responsiveness and modern design.
- **JavaScript**: Functionalities for QR code scanning, generation, and other interactive actions.
  - `jsQR` library: For scanning QR codes.
  - `qrcode.js`: For generating QR codes.
  - WebRTC: For accessing webcam to scan QR codes.
  - Web Share API: For sharing QR codes from the browser (if supported).

## Acknowledgements

- The `jsQR` library for QR code scanning.
- The `QRCode.js` library for generating QR codes.
- TailwindCSS for the sleek, responsive design.
