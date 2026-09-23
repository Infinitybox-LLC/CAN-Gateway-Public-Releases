# Infinitybox CAN Gateway Configuration Tool

Desktop application for configuring the Infinitybox bidirectional CAN gateway.

## Downloads

Download the latest release for your platform from the [Releases](https://github.com/Infinitybox-LLC/CAN-Gateway-Public-Releases/releases) page.

| Platform | File |
|----------|------|
| **Windows** | `Infinitybox_CAN_Gateway_Config-windows.exe` |
| **macOS Apple Silicon** | `Infinitybox_CAN_Gateway_Config-macos-arm64.zip` |
| **macOS Intel** | `Infinitybox_CAN_Gateway_Config-macos-x64.zip` |

## Installation

### Windows
1. Download the `.exe` from the latest release
2. Run `Infinitybox_CAN_Gateway_Config-windows.exe`

### macOS
1. Download and extract the ZIP for your Mac
2. Move `Infinitybox_CAN_Gateway_Config.app` to Applications
3. If macOS blocks the app, right-click and select **Open**

## First-time setup

### If you use Grid Connect CANUSB COM FD

No extra driver install is needed on Windows or macOS.

**Windows (once per adapter):**
1. Plug in the adapter
2. Open **Device Manager** → **Ports (COM & LPT)**
3. Open **USB Serial Port (COMxx)** → **Port Settings**
4. Set **Bits per second** to **115200**
5. Click **OK**

**macOS:**
1. Plug in the adapter
2. In the tool, click **Refresh**
3. Select a `/dev/cu.usbserial-*` port

### If you use PEAK PCAN-USB

**Windows:** install PEAK’s Windows device driver from [peak-system.com/Drivers](https://www.peak-system.com/Drivers.523.0.html)

**macOS:** PEAK does not publish a Mac driver. Use Grid Connect on a Mac.

## Requirements

- Infinitybox CAN Gateway
- Grid Connect CANUSB COM FD **or** PEAK PCAN-USB
- Windows 10 or later, **or** macOS 10.15+ (Catalina or later)

## About

Developed by [Infinitybox LLC](https://infinitybox.com)

For support: [infinitybox.com](https://infinitybox.com) · (847) 232-1991
