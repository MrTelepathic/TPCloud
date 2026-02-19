# TPCloud VPN

<div align="center">

![Version](https://img.shields.io/badge/version-1.8.1-blue.svg)
![License](https://img.shields.io/badge/license-GPL--3.0-green.svg)

A modern VPN application for Android with V2Ray/Xray protocol support and iOS-style UI design.

[Features](#features) • [Installation](#installation)

</div>

---

Telegram Channel: https://t.me/TPCloudapp

## Features

### Core
- **Protocols**: VMess, VLESS, Trojan, Shadowsocks, Hysteria2, WireGuard, SOCKS, HTTP
- **Transports**: TCP, WebSocket, HTTP/2, gRPC, QUIC, XHTTP, HTTPUpgrade, mKCP
- **Security**: TLS, Reality, with fingerprint customization
- **Statistics**: Real-time upload/download speed and total data
- **Server Management**: Concurrent ping testing, subscription auto-update, auto-select best server
- **Subscription Grouping**: Organize servers by subscription with tab navigation
- **Split Tunneling**: Per-App proxy with system/user apps filter
- **Configuration**: Full V2Ray JSON viewer/editor, custom config import
- **Updates**: Auto-check for new releases with skip version option

### Advanced Settings
- **Mux**: Multiplexing support with concurrency control and xUDP
- **Fragment**: TLS/Reality fragmentation with custom packets, length, interval
- **DNS**: Custom remote/domestic DNS servers with FakeDNS support
- **Routing**: Domain strategy, bypass LAN, custom routing rules
- **Network**: MTU configuration, VPN interface address selection
- **Core**: Log level control, sniffing, route-only mode

### UI/UX
- iOS-style design with glassmorphism effects
- Dynamic Island connection status
- Ring animation connect button
- Light/Dark mode support
- SVG country flags with real location detection
- Connection latency display with refresh
- Real-time notification with stats
- Subscription traffic & expiry info display

### Data Management
- Backup & Restore configs to JSON
- QR code scan and generate
- Clipboard import support


## Installation

Download the latest APK from [GitHub Releases](https://github.com/MrTelepathic/TPCloud/releases)



## Supported Protocols

| Protocol | Format | Status |
|----------|--------|--------|
| VMess | `vmess://base64-config` | ✅ Full Support |
| VLESS | `vless://uuid@host:port?params#remark` | ✅ Full Support |
| Trojan | `trojan://password@host:port?params#remark` | ✅ Full Support |
| Shadowsocks | `ss://base64(method:password)@host:port#remark` | ✅ Full Support |
| Hysteria2 | `hysteria2://password@host:port?params#remark` | ✅ Full Support |
| WireGuard | `wireguard://...` | ✅ Full Support |
| SOCKS | `socks://user:pass@host:port#remark` | ✅ Full Support |
| HTTP | `http://user:pass@host:port#remark` | ✅ Full Support |


<div align="center">

**MrTelepathic**

[![GitHub](https://img.shields.io/badge/GitHub-CluvexStudio-181717?logo=github)](https://github.com/MrTelepathic)

Made with ❤️ for digital freedom

</div>
