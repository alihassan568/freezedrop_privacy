# FreezeDrop Privacy Policy

Effective date: June 6, 2026

FreezeDrop is a consumer-mode Android app-freezing helper. It helps users mark selected apps as frozen, hide frozen apps in the FreezeDrop launcher flow, and optionally block selected frozen apps from internet access through a local Android VPN interface.

This Privacy Policy explains what data FreezeDrop accesses, how that data is used, and how users can control it.

This policy applies to the FreezeDrop Android app published under package name `com.freezedrop.app`.

## Summary

- FreezeDrop does not require an account.
- FreezeDrop does not use advertising SDKs.
- FreezeDrop does not sell user data.
- FreezeDrop does not send app lists, frozen app selections, Accessibility events, Usage Access events, VPN packets, or protection logs to a remote server in the current app.
- FreezeDrop stores its settings, frozen package list, and protection logs locally on the user's device.
- FreezeDrop uses sensitive Android permissions only to provide the app-freezing, launcher, foreground monitoring, notification, boot, battery, and local VPN blocking features.

## Data FreezeDrop Accesses

### Installed App Information

FreezeDrop can read installed launchable app information so it can show the user a list of apps that may be frozen or unfrozen.

This may include:

- App name
- Package name
- App icon
- Whether the app is treated as frozen in FreezeDrop

FreezeDrop uses this information only to show and manage the app-freezing interface.

### Frozen App Selections

When the user freezes or unfreezes an app, FreezeDrop stores the selected package names locally on the device.

FreezeDrop uses this information to:

- Show frozen apps
- Hide frozen apps from the FreezeDrop installed-apps list when enabled
- Apply local network blocking to selected frozen apps when VPN blocking is enabled
- Restore protection state after app restart or device reboot, if the user enables related settings

### Accessibility Service Events

FreezeDrop may ask the user to enable its Android Accessibility Service.

FreezeDrop uses Accessibility only to detect when a frozen app becomes the foreground app and to return the user to a blocking flow when protection is enabled.

FreezeDrop does not use Accessibility to:

- Read screen text
- Read passwords
- Read form content
- Record user input
- Take screenshots
- Send Accessibility event data to a remote server

The user can disable the Accessibility Service at any time in Android Accessibility settings.

### Usage Access Events

FreezeDrop may ask the user to enable Android Usage Access.

FreezeDrop uses Usage Access as a fallback way to detect foreground app changes for frozen-app protection.

FreezeDrop does not send Usage Access data to a remote server in the current app.

The user can disable Usage Access at any time in Android settings.

### Local VPN Traffic Handling

FreezeDrop may ask the user for Android VPN consent.

When VPN blocking is enabled, FreezeDrop creates a local Android VPN interface for selected frozen apps. The purpose is to drop network packets from those selected frozen apps so they lose internet access while frozen.

FreezeDrop does not provide remote VPN browsing, proxy browsing, or tunneling to a remote VPN server in the current app.

FreezeDrop does not sell, share, or transmit VPN packet contents to a remote server in the current app.

The user can stop local VPN blocking by unfreezing apps, disabling VPN blocking in FreezeDrop settings, or revoking VPN permission in Android settings.

### Protection Logs

FreezeDrop stores local protection logs so the user can review recent freeze, unfreeze, blocked-attempt, protection, and VPN events.

These logs are stored locally on the device and are limited by the app. The current app keeps recent logs and allows users to clear logs from the app interface.

### Settings

FreezeDrop stores app settings locally, including settings such as:

- Protection enabled or disabled
- Start at boot
- Persistent notification
- Strict mode
- Hide frozen apps in the installed apps list
- VPN blocking enabled or disabled

## Permissions Used

FreezeDrop may request or use the following Android permissions or platform capabilities:

| Permission or capability | Purpose |
| --- | --- |
| Accessibility Service | Detect when a frozen app becomes foreground and return the user to the blocking flow. |
| Usage Access | Fallback foreground app tracking. |
| Android VPN consent / VpnService | Create a local blocking layer for selected frozen apps. |
| Notifications | Show foreground protection and VPN notifications. |
| Foreground Service | Keep user-visible protection or VPN work running while enabled. |
| Battery optimization exemption | Reduce the chance that Android stops protection work unexpectedly. |
| Boot completed | Restore protection behavior after device reboot when enabled. |
| Default launcher / Home intent | Let FreezeDrop act as a launcher flow that can hide frozen apps from the FreezeDrop launcher view. |
| Internet permission | Required by Android networking/runtime behavior and app functionality, but the current app does not send user data to a FreezeDrop server. |

## Data Sharing

FreezeDrop does not share user data with third parties in the current app.

FreezeDrop does not include advertising SDKs, analytics SDKs, crash reporting SDKs, or remote telemetry SDKs in the current app.

If future versions add server features, analytics, crash reporting, ads, or third-party SDKs, this Privacy Policy and the Google Play Data Safety declaration must be updated before release.

## Data Storage and Retention

FreezeDrop stores settings, frozen package selections, and protection logs locally on the user's Android device.

This local data remains until:

- The user changes settings or unfreezes apps
- The user clears logs
- The user clears app data in Android settings
- The user uninstalls FreezeDrop

## User Controls

Users can control FreezeDrop's access and behavior by:

- Freezing or unfreezing apps inside FreezeDrop
- Clearing logs inside FreezeDrop
- Disabling protection settings inside FreezeDrop
- Disabling Accessibility Service in Android Accessibility settings
- Disabling Usage Access in Android settings
- Revoking or stopping VPN access in Android VPN settings
- Disabling notifications in Android notification settings
- Removing battery optimization exemption in Android battery settings
- Changing the default launcher in Android settings
- Clearing app data or uninstalling FreezeDrop

## Children's Privacy

FreezeDrop is not directed to children. FreezeDrop is intended for users who can understand Android permissions, Accessibility, Usage Access, VPN consent, launcher behavior, and app-control settings.

## Security

FreezeDrop is designed to keep its current app data local to the device. No app can guarantee absolute security, but FreezeDrop avoids remote transmission of the sensitive local app-control data described in this policy in the current app.

## Changes to This Policy

This policy may be updated when FreezeDrop changes its features, permissions, data handling, or third-party integrations.

When this policy changes, the effective date at the top of the policy will be updated.

## Contact

For privacy questions, contact the developer through the support email listed on the Google Play Store listing for FreezeDrop.

