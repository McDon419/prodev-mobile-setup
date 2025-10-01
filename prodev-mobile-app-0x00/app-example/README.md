# Mobile Development Setup with Expo Go

## Objective
Mobile development typically demands more computational resources than web development. To simplify this, we are using the **Expo Framework for React Native**, which makes mobile app development and testing more efficient.

This setup ensures a smooth development experience by leveraging **Expo Go** to test applications directly on physical devices.

---

## Prerequisites
Before setting up Expo Go, make sure you already have:

- ✅ Node.js LTS installed  
- ✅ VS Code (recommended IDE)  
- ✅ A compatible OS: macOS, Linux, or Windows  
- ✅ A physical mobile device (Android or iOS)

---

## Why Expo Go?
Testing mobile apps usually requires emulators, which demand significant system resources and may not always reflect real-world performance.  
Expo Go solves this problem by allowing developers to:

- Run and test React Native applications on physical devices.  
- Avoid the need for costly emulators and extra hardware.  
- Support both **Android** and **iOS** devices seamlessly.  

---

## Steps to Install Expo Go

1. Visit the official Expo Go homepage: [https://expo.dev/go](https://expo.dev/go).  
2. Select the latest SDK version.  
3. Install Expo Go on your device:  
   - **Android**: Install from the [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent).  
   - **iOS**: Install from the [Apple App Store](https://apps.apple.com/app/expo-go/id982107779).  
4. Open the **Expo Go** app on your phone.  
5. Create a new account or log in with your existing Expo account.  

---

## Challenges Faced

During the setup of Expo Go, I faced the following issues:

1. **Slow Internet Download**
   - The Expo Go app took longer than expected to download due to unstable internet.  
   - ✅ Solution: Paused and retried the download after switching to a stronger Wi-Fi connection.  

2. **Account Creation**
   - Initially tried logging in without an Expo account.  
   - ✅ Solution: Created a free Expo account at [expo.dev](https://expo.dev) to proceed.  

3. **App Permissions**
   - On Android, Expo Go required camera permission to scan QR codes.  
   - ✅ Solution: Enabled permissions manually in device settings.  

4. **SDK Version Mismatch**
   - When testing the demo app, the installed Expo Go version did not support the latest SDK.  
   - ✅ Solution: Updated Expo Go from the Google Play Store to match the SDK.  

These challenges were resolved, and Expo Go is now running successfully on my device.

---

## Troubleshooting

Here are some common issues and fixes when working with Expo Go:

1. **App Not Loading / White Screen**
   - Clear cache by uninstalling and reinstalling the Expo Go app.  

2. **QR Code Not Scanning**
   - Ensure camera permissions are enabled in device settings.  
   - Try switching to **manual input** (entering the URL shown in the terminal into Expo Go).  

3. **Metro Bundler Not Connecting**
   - Ensure both your computer and phone are on the **same Wi-Fi network**.  
   - If issues persist, restart Metro with:  
     ```bash
     npm start -- --reset-cache
     ```  

4. **Node.js Compatibilit**

# ProDev Mobile App Setup

## Project: First React Native App with Expo

This project was created as part of the mobile development setup tasks using Expo and React Native.

---

## Steps Followed for Scaffolding

1. **Navigate to project directory**
   ```bash
   cd prodev-mobile-setup
   mkdir prodev-mobile-app-0x00
   cd prodev-mobile-app-0x00

