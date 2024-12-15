# Watchface Collection

Welcome to my collection of custom watchfaces for smartwatches! This repository hosts a variety of unique and stylish watchfaces designed to personalize your wearable device.

## Available Watchfaces

### 1. CMF


A minimalist analog watchface inspired by the Nothing CMF Watch, featuring a sleek dark theme with essential information displayed in circular complications around a classic watch face.

[Download APK](https://example.com/cosmic_explorer.apk)

### 2. Executive


A sophisticated digital watchface with a dark gradient background, offering essential information in a clean, quadrant-based layout. Perfect for professionals who need quick access to key data.

[Download APK](https://example.com/vintage_timekeeper.apk)

## Installation Instructions (Wi-Fi ADB)

To install these watchfaces, we'll use Wi-Fi ADB. Follow these steps:

### Preparation

1. Enable Developer Options on your watcg.
2. Enable USB debugging and Wireless debugging in Developer Options.
3. Ensure your watch and computer are on the same Wi-Fi network.

### Connecting via Wi-Fi ADB

1. On your watch, go to Settings > Developer Options > Wireless debugging.
2. Tap on "Pair device with pairing code" to get the IP address, port, and pairing code.
3. On your computer, open a terminal or command prompt and navigate to the ADB directory.
4. Pair your device using the command:
   ```bash
   adb pair <IP_address>:<port>
   ```
   Enter the pairing code when prompted.
5. Connect to your device:
   ```bash
   adb connect <IP_address>:5555
   ```

### Installing the APK

Once connected, install the APK using the following command:

```bash
adb install /path/to/your/watchface.apk
```

Replace "/path/to/your/watchface.apk" with the actual path to the downloaded APK file.

### Disconnecting

After installation, disconnect from the device:

```bash
adb disconnect
```

## Compatibility

These watchfaces are designed for Samsung Watch 4/5. Please ensure your device is compatible before installation.

## Feedback and Contributions

Your feedback is valuable! If you encounter any issues or have suggestions for improvements, please open an issue in this repository. Contributions via pull requests are also welcome.
