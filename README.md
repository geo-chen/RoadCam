# RoadCam

Product: https://roadcam.my/pages/install-x3

Version: X3

## Finding 1 - CVE-2025-30122: Same Default Credentials

The ROADCAM X3 dashcam ships with identical default credentials for all devices. This allows attackers to use the same credentials to connect to any ROADCAM X3 dashcams, with default settings, within range, enabling unauthorized access to multiple devices. 

## Finding 2 - CVE-2025-30123: Hardcoded FTP Credentials in APK 
The ROADCAM X3 dashcam’s mobile app (Viidure v1.5) contains hardcoded FTP credentials, allowing attackers to gain unauthorized access to the device's file system. Using the username "FTPX," an attacker can log in remotely and download all recorded video footage, exposing sensitive data.
