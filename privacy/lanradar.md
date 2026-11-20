## Privacy Policy for LanRadar  

**Effective Date:** November 20, 2026  
**Developer:** devcarmelo  
**Application ID:** `io.github.devcarmelo.lanradar`  
**Contact:** `carmelo.freelancer@example.com`

### 1. Overview
LanRadar is a local network and TCP port discovery utility for Android. We value your privacy: LanRadar operates **100% locally on your device**. The app does not require user accounts, does not use cloud servers, does not contain third-party analytics or advertising SDKs, and does not collect, sell, or share any personal or network data.

### 2. Information Processed Locally on Your Device
When you initiate an on-demand network scan, LanRadar inspects your currently connected local IPv4 Wi-Fi or Ethernet subnet strictly within your local area network (LAN). The following information is stored **exclusively in a local database (`Room / SQLite`) on your Android device**:
- Discovered local IPv4 addresses, hostnames (via mDNS / reverse DNS), and open TCP ports configured by you.
- Custom device metadata that you choose to enter (custom device names, brand, model, MAC address for Wake-on-LAN, and personal notes).
- Local scan session timestamps, device online/offline transitions, and local DHCP IP address change logs.

**None of this information ever leaves your device.**

### 3. Permissions Used
LanRadar requests only minimal, standard Android network permissions:
- `INTERNET`: Required to perform local TCP port checks, resolve local hostnames, send local Wake-on-LAN UDP packets, and open a device's local Web UI in your browser when requested.
- `ACCESS_NETWORK_STATE` & `ACCESS_WIFI_STATE`: Required to detect the active Wi-Fi or Ethernet interface and local IPv4 subnet prefix.
- `CHANGE_WIFI_MULTICAST_STATE`: Required for local mDNS hostname discovery.

LanRadar does **not** request Location (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`), Storage/Media, Camera, Contacts, or Microphone permissions.

### 4. Data Sharing & Third Parties
LanRadar does not transmit telemetry, crash reports, advertising identifiers, or network scan results to the developer or any third party.

### 5. Data Retention & Deletion
All local device records, custom ports, and network history remain solely on your device. You can clear scan and IP change history at any time inside the app (**Network History → Clear**), or delete all stored app data by clearing app storage in Android settings or uninstalling LanRadar. (If Android Auto Backup is enabled on your device, your standard Android system backup settings apply.)

### 6. Children's Privacy
LanRadar does not knowingly collect personal information from anyone, including children under the age of 13.

### 7. Changes to This Policy
If future updates change how data is handled, this Privacy Policy will be updated with a new effective date prior to release.
