# Beacon Scanner

This is a web-based Bluetooth Beacon Scanner that allows you to scan, connect, and interact with Bluetooth Low Energy (BLE) beacons. The application uses the Web Bluetooth API to detect and connect to nearby Bluetooth devices.

## Features

- Scans for Bluetooth beacons using the Web Bluetooth API.
- Displays information about detected beacons.
- Connects to the beacon and attempts to retrieve services and characteristics.
- User-friendly interface that enables easy scanning and connection.
- Ability to filter by **beacon name** and **UUID** to connect to specific beacons.

## Prerequisites

- A modern browser that supports the Web Bluetooth API, such as:
  - Google Chrome
  - Microsoft Edge
  - Opera
  - (Note: Web Bluetooth is not supported in Firefox or Safari currently)

- Bluetooth-enabled device (such as your laptop or smartphone) with Bluetooth enabled.

## How to Use

1. Open the `beacon.html` page in a supported web browser.
2. Click the **Start Bluetooth Scan** button to begin scanning for nearby Bluetooth beacons.
3. The scanner will automatically search for available Bluetooth devices.
4. Once a device is found, it will show the device name and allow you to connect to it.
5. If the connection is successful, the page will display information about the connected device and any available services.

## Configuring Beacon Filtering

To ensure the scanner only finds and connects to your specific beacon, you can modify the following variables in the `beacon.html` file:

- **beaconName**: The name of your beacon (e.g., `"RFstar_5016"`).
- **beaconUUID**: The UUID of your beacon (e.g., `"00000000-0000-0000-0000-000000000000"`).

### Example of setting beacon name and UUID:
```javascript
const beaconName = "RFstar_5016";  // Change this to your beacon's name
const beaconUUID = "00000000-0000-0000-0000-000000000000";  // Replace with your beacon's UUID
