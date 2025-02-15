# Guide to Diagnosing and Speeding Up Windows PCs

A structured approach to identifying performance issues on Windows PCs and improving overall system responsiveness without resorting to a full reinstall.

---

## 1. Basic Housekeeping

- **Uninstall Unused Software**  
  - Remove unnecessary or rarely used programs via **Settings → Apps** (on Windows 10/11) or the Control Panel (on older versions).  
  - Extra or “bloatware” programs can slow startup and overall performance.

- **Disable Startup Apps**  
  - Open the **Task Manager** (Ctrl + Shift + Esc).  
  - Go to the **Startup** tab and disable any programs you don’t want to load at boot.

- **Clean Temporary Files**  
  - Use **Disk Cleanup** or **Storage Sense** in Windows 10/11 to clear out temporary files.  
  - Tools like CCleaner can automate junk removal, but use them carefully to avoid deleting critical items or modifying the registry.

---

## 2. Check for Malware and Viruses

- **Run Full Antivirus Scans**  
  - Use the built-in Windows Security (Defender) or a reputable third-party antivirus to perform a full system scan.  
  - Malware, viruses, and other malicious software often degrade performance significantly.

- **Adware & Spyware Scans**  
  - Tools like Malwarebytes can catch adware or spyware that antivirus suites might miss.

---

## 3. Update and Patch

- **Windows Updates**  
  - Keep the system updated via **Settings → Update & Security**.  
  - Outdated Windows installations may have security holes, buggy drivers, and performance issues.

- **Driver Updates**  
  - Ensure essential drivers (graphics, chipset, network) are current.  
  - Visit the device manufacturer’s website or use Device Manager to check and update drivers.

---

## 4. Check Resource Usage

- **Task Manager → Performance Tab**  
  - Identify processes causing high CPU, RAM, or disk usage.  
  - Constantly high disk usage (e.g., at 100%) can indicate background processes or outdated drivers.

- **Services**  
  - Access **Services** (type `services.msc` in the Start menu) to manage which services run automatically.  
  - Switch non-essential services to “Manual” start if you’re sure they aren’t needed.

---

## 5. Hard Drive / SSD Maintenance

- **Check Disk Health**  
  - Use `chkdsk` (built-in) or third-party utilities for HDD/SSD to detect errors or impending drive failure.

- **Optimize & Defragment (for HDD)**  
  - Windows normally handles defragmentation automatically.  
  - Check **Defragment and Optimize Drives** to ensure it’s enabled.

- **Maintain Free Space**  
  - Keep at least 10–15% free space on the system drive.  
  - Low free space can cause sluggishness due to insufficient paging and temporary file allocation space.

---

## 6. Adjust Power Settings

- **Balanced or High-Performance Mode**  
  - Access **Control Panel → Power Options** to switch from “Balanced” to “High Performance,” especially on desktops.  
  - On laptops, be mindful of battery usage when using high-performance settings.

---

## 7. Visual Effects and System Settings

- **Disable Unnecessary Animations**  
  - Under **System Properties → Advanced → Performance**, uncheck heavy visual effects.  
  - Disabling transparency, animations, etc., can free up resources on low-end systems.

- **Virtual Memory (Paging File)**  
  - Let Windows manage the paging file automatically, unless you have specific advanced requirements.

---

## 8. Use Built-In Troubleshooters

- **Windows Troubleshooters**  
  - Go to **Settings → Update & Security → Troubleshoot** (Windows 10/11) for built-in tools that address common performance and update issues.

---

## 9. Check for Conflicting Software

- **Recent Installs**  
  - If performance tanked recently, check which applications or updates were installed just before the slowdown.  
  - Conflicts (e.g., multiple antivirus programs) can degrade performance significantly.

- **Clean Boot**  
  - Perform a “clean boot” by temporarily disabling third-party apps and services.  
  - Re-enable them one by one to find the culprit if performance improves.

---

## 10. In-Place Repair/Reset (Before Full Reinstall)

- **Windows “Reset” (Keep Files)**  
  - **Settings → Update & Security → Recovery** offers an option to reset Windows while keeping personal files.  
  - This often repairs system-level corruption without a full wipe.

- **In-Place Upgrade**  
  - Run the latest Windows installer from the currently running system to “upgrade” it to the same version.  
  - This can repair system files without a total reinstallation.

---

## References

- [Tips to Improve PC Performance in Windows](https://support.microsoft.com/en-us/windows/tips-to-improve-pc-performance-in-windows-b3b3ef5b-5953-fb6a-2528-4bbed82fba96#Category=Windows_10)  
- [Windows Defender Security Center](https://learn.microsoft.com/en-us/windows/security/operating-system-security/system-security/windows-defender-security-center/windows-defender-security-center)
