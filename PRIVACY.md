# KindFi Privacy Policy

Last updated: August 4, 2026

KindFi is a local-network utility app for managing existing UniFi firewall rules. This policy covers the KindFi iOS app.

## Data Collection

KindFi does not collect, sell, or share personal data with the developer.

The app does not use:

- Analytics SDKs
- Advertising SDKs
- Third-party tracking

The only frameworks KindFi links against are first-party Apple frameworks (SwiftUI, SwiftData, MultipeerConnectivity, VisionKit, UserNotifications, and similar) - there is no third-party code with its own data practices.

## Credentials and Local Data

To connect to your UniFi Controller, the app uses credentials you enter.

- Credentials and session tokens are stored locally on your device using iOS secure storage (Keychain).
- Selected rule configuration is stored locally on your device.
- This data is used only to operate the app's core functionality, and is never transmitted anywhere other than directly to your own UniFi Controller.

## Network Communication

KindFi communicates directly with your UniFi Controller on your local network.

- No cloud relay service is used by KindFi.
- The developer does not receive your controller data or credentials.

## Camera and Bluetooth (Device Setup)

KindFi can optionally use your device's camera and Bluetooth/local-network radios to set up a second device without re-typing your UniFi admin password ("Scan to Set Up"):

- The camera is used only to scan a QR code displayed on your other, already-configured device. No photo or video is stored or transmitted.
- Bluetooth and local peer-to-peer networking (via Apple's Multipeer Connectivity framework) are used only to transfer your UniFi credentials directly between your own two devices, over a short-lived, single-use, encrypted connection. This never leaves your local vicinity and never reaches any server.

## Notifications

KindFi can schedule local notifications (e.g. to tell you when a temporary access override has expired). These are generated and delivered entirely on-device - they are not push notifications sent from a server.

## Children

KindFi is intended for parents/guardians and is not directed to children.

## Changes

This policy may be updated in future versions. Material changes will be reflected by updating the date above.

## Contact

For support or privacy questions, open an issue at:

https://github.com/swindmill/KindFi-public/issues
