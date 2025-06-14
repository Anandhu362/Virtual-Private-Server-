# Mumbai-Based Virtual Private Server (VPS)  
*Google Cloud VM + WireGuard VPN – Configuration & Proof*

---

## Overview

This project documents the setup and operation of a Virtual Private Server (VPS) based in Mumbai, running on Google Cloud Platform with secure WireGuard VPN configuration. Below are step-by-step proofs, network monitoring, port configurations, and client connection validation.

---

## Table of Contents

1. [VM Instance Overview](#vm-instance-overview)
2. [Active Network Connections](#active-network-connections)
3. [WireGuard Allowed Ports](#wireguard-allowed-ports)
4. [Client Configuration](#client-configuration)
5. [Public IP Before Connection](#public-ip-before-connection)
6. [Public IP After VPN Connection](#public-ip-after-vpn-connection)
7. [Summary & Verification](#summary--verification)

---

## 1. VM Instance Overview

**Location:** Mumbai, India  
**Platform:** Google Cloud Platform – Active VM

![VM Instance Overview](https://github.com/user-attachments/assets/3879add1-a25e-491c-8084-3ec17f5cf678)

---

## 2. Active Network Connections

Continuous monitoring of active network connections on the VPS.

![Active Network Connections](https://github.com/user-attachments/assets/0d2f3211-a574-414c-903f-f3bbd29a19fb)

---

## 3. WireGuard Allowed Ports

Proof of WireGuard configuration showing allowed (open) ports for VPN traffic.

![WireGuard Allowed Ports](https://github.com/user-attachments/assets/2bb7369e-5f0c-425b-aca0-e883ed804a64)

---

## 4. Client Configuration File

Sample WireGuard client config file for establishing a secure VPN connection to the VPS.

![Client Config File](https://github.com/user-attachments/assets/6664494f-3594-4476-abc7-48286ee32e4d)

---

## 5. Public IP Before VPN Connection

IP address before connecting to the WireGuard VPN (shows local ISP or regular connection).

![Public IP Before Connection](https://github.com/user-attachments/assets/e2659730-d0ca-466a-b649-a28ff0b3bddf)

---

## 6. Public IP After VPN Connection

IP address after successfully connecting to the Mumbai VPS via WireGuard (shows VPS public IP, proving tunneling is active).

![Public IP After Connection](https://github.com/user-attachments/assets/5040053a-9035-4ab1-9807-d63827635b7b)

---

## 7. Summary & Verification

- **VM Location:** Mumbai (India) – Google Cloud Platform
- **VPN Solution:** WireGuard  
- **Status:** Network traffic is tunneled securely via the VPS; verified by public IP change.

> **This README provides proof of setup and connectivity.  
> For setup scripts, troubleshooting, or contributions, feel free to raise an issue or submit a pull request!**

---

