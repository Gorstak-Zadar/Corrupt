# 💥 Corrupt

> PowerShell script to **overwrite telemetry files** with random data on an hourly schedule — privacy-focused telemetry corruption.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔒 **Telemetry Overwrite** | Overwrites 50+ telemetry/diagnostics files with random bytes |
| 📋 **Wide Coverage** | Windows, Chrome, Edge, NVIDIA, AMD, Intel, Steam, Epic, Discord, Adobe, Logitech, Razer, Corsair, AV vendors, Slack, Dropbox, Zoom |
| ⏰ **Hourly** | Runs once per hour in a background job |
| 🚀 **Persistence** | Registers scheduled task `RunCorruptAtLogon` under SYSTEM |
| 📝 **Logging** | Outputs to console |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |

---

## 🚀 Usage

```powershell
# Run as Administrator — installs scheduled task and starts hourly corruption
.\Corrupt.ps1
```

---

## ⚠️ Warning

- Overwriting files can cause applications to misbehave or lose data
- Some apps may regenerate telemetry; this script is for periodic reduction
- Use at your own risk

---

<p align="center">
  <sub>🛡️ Gorstak Privacy Tooling</sub>
</p>
