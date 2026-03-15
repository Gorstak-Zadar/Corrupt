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

---

## Disclaimer

**NO WARRANTY.** THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

**Limitation of Liability.** IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
