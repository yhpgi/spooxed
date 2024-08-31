# spooxed

**spooxed** is an Android application designed to change the device's MAC address on Android 12-15 devices using the LSPosed (Xposed) framework. This app requires root access and BusyBox installed to function correctly.

## Features

- **Change MAC Address**: Modify your device's MAC address easily through a user-friendly interface.
- **Save MAC Addresses**: Store frequently used MAC addresses in a list for quick access.
- **History Tracking**: Keep a history of all the MAC addresses you've used, allowing you to revert to a previous address easily.
- **Quick Settings Switch**: Enable or disable the Xposed hook via a Quick Settings tile. The Quick Settings switch must be activated before you can change the MAC address.

## Requirements

- **Root Access**: This app requires root privileges to change the MAC address.
- **BusyBox Installed**: Make sure BusyBox is installed on your device for the app to work properly.
- **LSPosed (Xposed) Framework**: This app utilizes LSPosed for making the necessary changes to the MAC address.

## Usage

1. **Install the app**: Download and install **spooxed** on your Android device.
2. **Enable the Xposed Module**: Ensure that the **spooxed** module is enabled in the LSPosed Manager.
3. **Activate Quick Settings Switch**: Before changing the MAC address, activate the Quick Settings tile provided by **spooxed** to enable the Xposed hook.
4. **Change MAC Address**: Enter the desired MAC address and apply it. If you enter an invalid MAC address, the app will notify you.
5. **Save and Manage MAC Addresses**: Save the MAC addresses you use frequently and manage them through the app's interface. You can also view the history of all MAC addresses used.

## Technologies Used

- **[Jetpack Compose](https://developer.android.com/jetpack)**

- **[Kotlin](https://kotlinlang.org/)**

- **[Kotlinx Serialization](https://github.com/Kotlin/kotlinx.serialization)**

- **[libxposed API](https://github.com/libxposed)**

- **[Material 3](https://m3.material.io/)**

## Disclaimer

Changing your device's MAC address can have unintended consequences. Use this app responsibly and at your own risk. **spooxed** is not responsible for any damage or legal issues that may arise from using this app.
