# NFC Attendance System

A universal staff attendance registration system that supports both NFC scanning via mobile phones (Android) and USB NFC readers.

## Features

- **Universal NFC Support**: Works with both Android phones (Web NFC API) and USB NFC readers
- **Real-time Registration**: Staff can register by scanning their NFC cards/tags
- **Firebase Integration**: Data is stored in Firebase Firestore for real-time synchronization
- **Cross-platform**: Works on any device with a modern web browser
- **User-friendly Interface**: Clean, responsive design with clear instructions

## How to Use

1. **For Mobile Users (Android)**:
   - Open the webpage on an Android phone with NFC capability
   - Click "Scan via Phone NFC" button
   - Hold your NFC card/tag near the phone's NFC sensor

2. **For USB NFC Reader Users**:
   - Connect your USB NFC reader to your computer
   - Open the webpage
   - The cursor will automatically focus on the NFC UID field
   - Scan your NFC card/tag with the reader

3. **Manual Entry**:
   - If you know your NFC UID, you can type it manually in the NFC Card UID field

## Setup

1. Clone this repository
2. Update the Firebase configuration in `index.html` with your own Firebase project settings
3. Host the file on any web server or open directly in a browser

## Technology Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Web NFC API (for Android devices)
- Firebase Firestore (for data storage)

## Browser Compatibility

- **Web NFC**: Chrome on Android 89+ (for mobile NFC scanning)
- **USB NFC Readers**: Any modern browser (Chrome, Firefox, Safari, Edge)
- **Firebase**: All modern browsers

## Security Note

Make sure to properly configure Firebase security rules to protect your attendance data.
