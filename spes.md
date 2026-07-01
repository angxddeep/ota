# 01-July-2026

- July Pixelos Release
- Switched to AIDL camera HAL
- Switched to common Lights HAL
- Switched to generic Qualcomm SELinux policies
- Upgraded recovery and system keys to RSA-4096 for better security
- Disabled resource-heavy background blurs by default for a smoother UI
- Disabled storage checkpoint garbage collection 
- Updated Wi-Fi Display (WFD) binaries from newer device firmware fixing the previous hacks used to make it work
- Moved to ClearKey DRM service APEX for secure video streaming
- Moved recovery resources to vendor_boot partition for a cleaner structure
- Enabled kernel VINTF enforcement for better compliance
- Switched Widevine DRM dependency to a cryptographic shim
- Resolved secure video playback issues in Netflix/other Ott apps
- Cleaned up obsolete packages and unused overlays
- Configured build system to use LLVM compiler tools 
- There are many other miscellaneous bug fixes & improvements
