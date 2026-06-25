# luci-app-apnweb-for-opkg-and-apk

**luci-app-apnweb** is a graphical European APN Configurator integrated into LuCI for OpenWrt routers equipped with a cellular modem. Accessible directly from the **Network → APN Configuration** menu, it allows you to set up and manage mobile data connections across **37+ European countries** with a guided multi-step interface, without manually editing configuration files.

---

## ✨ What's new in version 1.0.5

The new version completely redesigns the user experience with a **guided 5-step flow**:

1. 🌐 **Language selection** (Italian / English)
2. 📡 **Connection mode selection** (QMI / MODEMMANAGER / MBIM)
3. 🌍 **Country selection** from 37+ European nations
4. 📱 **Operator selection** with MNO / MVNO filters
5. ⚙️ **Auto-filled APN settings** ready to apply

---

## 📸 Screenshots

### 1️⃣ Language Selection
The first step lets you choose between Italian and English. The whole interface will be translated automatically.

<div align="center">
  <img src="https://github.com/ilblogdicristiangallo/luci-app-apnweb-for-opkg-and-apk/blob/main/Screenshot/APN-WEB-Screen.png?raw=true" alt="Language selection" width="600" style="height: auto;">
</div>

---

### 2️⃣ Connection Mode Selection
After selecting the language, choose the cellular connection mode compatible with your router and modem.

<div align="center">
  <img src="https://github.com/ilblogdicristiangallo/luci-app-apnweb-for-opkg-and-apk/blob/main/Screenshot/APN-WEB-Screen2.png?raw=true" alt="Mode selection" width="600" style="height: auto;">
</div>

---

### 3️⃣ Country and Operator Selection
Select your country from the European list and choose your mobile operator (MNO or MVNO). All APN parameters will be auto-filled.

<div align="center">
  <img src="https://github.com/ilblogdicristiangallo/luci-app-apnweb-for-opkg-and-apk/blob/main/Screenshot/APN-WEB-Screen3.png?raw=true" alt="Country and operator selection" width="600" style="height: auto;">
</div>

---

## 🔌 Supported Connection Modes

| Mode | Description |
|------|-------------|
| **QMI** | Qualcomm MSM Interface |
| **MBIM** | Mobile Broadband Interface Model |
| **ModemManager** | Universal modem management with 2G/3G/4G/5G selection |

---

## 🌍 Supported Countries (37+)

🇮🇹 Italy • 🇫🇷 France • 🇩🇪 Germany • 🇪🇸 Spain • 🇵🇹 Portugal • 🇬🇧 United Kingdom • 🇮🇪 Ireland • 🇳🇱 Netherlands • 🇧🇪 Belgium • 🇱🇺 Luxembourg • 🇨🇭 Switzerland • 🇦🇹 Austria • 🇩🇰 Denmark • 🇸🇪 Sweden • 🇳🇴 Norway • 🇫🇮 Finland • 🇵🇱 Poland • 🇨🇿 Czech Republic • 🇸🇰 Slovakia • 🇭🇺 Hungary • 🇷🇴 Romania • 🇧🇬 Bulgaria • 🇭🇷 Croatia • 🇸🇮 Slovenia • 🇬🇷 Greece • 🇨🇾 Cyprus • 🇲🇹 Malta • 🇪🇪 Estonia • 🇱🇻 Latvia • 🇱🇹 Lithuania • 🇦🇱 Albania • 🇷🇸 Serbia • 🇧🇦 Bosnia and Herzegovina • 🇲🇪 Montenegro • 🇲🇰 North Macedonia • 🇲🇩 Moldova • 🇺🇦 Ukraine

---

## ⚡ Main Features

- 🌍 **37+ European countries** database with country flags
- 📡 **MNO and MVNO operators** with filters (main and virtual operators)
- 🌐 **Multi-language interface** (Italian / English)
- ⚡ **Auto-fill** APN, IP type, authentication, username and password
- 📶 **Separate Hotspot/Tethering APN** when different from internet APN
- 🔐 **PAP / CHAP / None** authentication management
- 🔢 **SIM PIN** entry support
- 🌐 **IP type configuration** (IPv4, IPv6, IPv4+IPv6)
- 🔄 **WAN restart** and router reboot directly from interface
- 📂 **External database** (apn-database.js) for easy operator updates
- 📦 **Available in both formats**: `.ipk` (OpenWrt 24.x) and `.apk` (OpenWrt 25.x)

---

## 📦 Installation

Download the latest version from the [Releases page](https://github.com/ilblogdicristiangallo/luci-app-apnweb-for-opkg-and-apk/releases) or from the official repository:

👉 **[ilblogdicristiangallo OpenWrt Repository](https://github.com/ilblogdicristiangallo/ilblogdicristiangallo_repo_openwrt_APK)**

### For OpenWrt 25.x (APK)

apk add --allow-untrusted luci-app-apnweb

# 🧑‍💻 Author
Made with ❤️ by ilblogdicristiangallo
