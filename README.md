# Volt releases

Builds of Volt, a macOS menu-bar app for your battery, AirPods, iPhone and the apps using power.

- **Download:** the newest DMG under [Releases](../../releases).
- **Needs:** macOS 13 or later, Apple silicon or Intel.
- **Updates:** Volt checks `appcast.xml` once a day (Settings › About › Updates). Every update is signed;
  Volt only installs updates with a valid signature.

## Installing

1. Open the DMG and drag **Volt** into **Applications**.
2. Open Volt. macOS says it can't check Volt for malware (Volt isn't notarized by Apple yet). Click **Done**.
3. Open **System Settings › Privacy & Security**, scroll down to "Volt was blocked…" and click **Open Anyway**,
   then confirm with your password or Touch ID.

You only do this once; updates install without it.

## Permissions

None by default. Bluetooth is optional (Settings › Widget › Use Bluetooth): it shows your iPhone, iPad and
AirPods that aren't connected to the Mac, and the AirPods case pop-up. Volt only connects to devices paired
with your Mac.

Switching Low Power Mode from Volt asks for your password once, to add a rule that lets Volt turn
Low Power Mode on and off (nothing else).
