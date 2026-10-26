# NetworkWalks Internship - Week 1: Lab Setup (VirtualBox & Kali Linux)

Successfully set up a secure, isolated, and fully functional cybersecurity testing and ethical hacking lab environment on a local host machine.

## 🛠️ Lab Specifications & Configurations:
- **Base Hypervisor:** Oracle VirtualBox
- **Attacking Machine:** Kali Linux (VirtualBox Appliance)
- **Network Architecture:** Custom `NATNetwork` in the `10.0.0.0/24` subnet range
- **Kali IP Address Configuration:** `10.0.0.2/24` with Gateway `10.0.0.1` and DNS `8.8.8.8`
- **Network Stability Fix:** Applied `ipv4.dad-timeout 0` via NetworkManager to resolve VirtualBox v7 internet connectivity lags.
- **Host Integration:** Enabled Bi-directional Shared Clipboard, Drag-and-Drop, and Automated Shared Folders linked to the host's `Downloads` directory.
- **Backup Strategy:** Configured clean operational system Snapshots for future CTF modules.

## 📄 Documentation:
- Detailed Lab Setup Report PDF is available in this repository: [`lab_setup_report.pdf`](./lab_setup_report.pdf)
