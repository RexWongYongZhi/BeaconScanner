# Beacon Scanner

This is a web-based Bluetooth Beacon Scanner that allows you to scan, connect, and interact with Bluetooth Low Energy (BLE) beacons. The application uses Web Bluetooth API to detect and connect to nearby Bluetooth devices.

## Features

- Scans for Bluetooth beacons using the Web Bluetooth API.
- Displays information about detected beacons.
- Connects to the beacon and attempts to retrieve services and characteristics.
- User-friendly interface that enables easy scanning and connection.

## Prerequisites

- A modern browser that supports the Web Bluetooth API, such as:
  - Google Chrome
  - Microsoft Edge
  - Opera
  - (Note: Web Bluetooth is not supported in Firefox or Safari currently)

- Bluetooth-enabled device (such as your laptop or smartphone) with Bluetooth enabled.

## How to Use

1. Open the `beacon.html` page in a supported web browser.
2. Click the "Start Bluetooth Scan" button to begin scanning for nearby Bluetooth beacons.
3. The scanner will automatically search for available Bluetooth devices.
4. Once a device is found, it will show the device name and allow you to connect to it.
5. If the connection is successful, the page will display information about the connected device and any available services.

## Files

- `beacon.html`: The main HTML file that powers the beacon scanner.
- `index.html`: The entry point for the site (used for redirection to `beacon.html`).

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

If you have any suggestions or improvements for this project, feel free to fork it and submit a pull request. You can also open issues if you encounter any problems or bugs.

## Support

For any issues or questions, please open an issue on the GitHub repository.

