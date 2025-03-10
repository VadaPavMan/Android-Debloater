# Android Debloater Script  

## Description  
**Debloater.sh** is a simple and efficient shell script designed to help you remove pre-installed system apps (bloatware) from your Android device via ADB. This script offers an easy way to clean your device and free up space by uninstalling unnecessary system applications without rooting your device.  

## Features  
- Identify and uninstall pre-installed system apps (bloatware).  
- Works with non-rooted Android devices.  
- Simple and user-friendly ADB-based script.  
- Lightweight and customizable for different devices.  

---

## Prerequisites  
To use this script, ensure the following:  
1. A PC with ADB installed.  
   - [Download ADB](https://developer.android.com/studio/releases/platform-tools) (if not installed).  
2. USB Debugging enabled on your Android device.  
   - Go to **Settings** → **About phone** → Tap **Build number** 7 times → Go to **Developer options** → Enable **USB Debugging**.  
3. Connect your Android device to your PC via USB.  

---

## How to Run  

1. Clone or download this repository to your computer:  
   ```bash  
   git clone https://github.com/YourUsername/Android-Debloater-Script.git  
   cd Android-Debloater-Script  
   ```  

2. Make the script executable:  
   ```bash  
   chmod +x Debloater.sh  
   ```  

3. Connect your Android device to your computer with a USB cable and verify the ADB connection:  
   ```bash  
   adb devices  
   ```  
   If your device is listed, the connection is successful.  

4. Run the script:  
   ```bash  
   ./Debloater.sh  
   ```  

5. Follow the on-screen instructions to select and uninstall bloatware apps.  

---

## Disclaimer  
- Use this script at your own risk.  
- Uninstalling system apps may cause instability or remove features. Make sure to research which apps are safe to uninstall.  

---

Feel free to customize this description to match the tone and style of your project! If you need help refining it further, let me know. 😊
