# 🎹 MidiRipples - Play Music with Your MIDI Controller

[![Download MidiRipples](https://img.shields.io/badge/Download-MidiRipples-ff6f61?style=for-the-badge)](https://github.com/zokiru7827/MidiRipples)

## 🎵 What is MidiRipples?

MidiRipples is an app that lets you play music using your MIDI controller or your computer keyboard. It works with most standard three-octave MIDI keyboards. You can connect your device, play notes, and hear sounds instantly.

If you don’t have a MIDI controller, you can still use your keyboard to play notes. It is designed to give you a simple and direct way to make music without needing extra equipment.

## 🔧 System Requirements

- Windows 10 or later (64-bit recommended)  
- At least 4GB of RAM  
- A working sound card or speakers  
- USB port for MIDI controller (optional)  
- Internet connection for downloading the app

## 📥 Download and Install

Click the big button above or visit the official page below to access all downloads and updates:

[https://github.com/zokiru7827/MidiRipples](https://github.com/zokiru7827/MidiRipples)

Because the project is hosted on GitHub, you will find the latest release files and details there. Follow these steps to download and install MidiRipples on your Windows PC:

1. Go to the page linked above.  
2. Look for the latest release in the repository.  
3. Download the installation file (usually a `.exe` or `.zip` file).  
4. If you downloaded a `.zip`, extract it to a folder you can access easily.  
5. Double-click the `.exe` file to start the setup.  

Follow the on-screen instructions to complete the installation.

## 🚀 Running MidiRipples

Once installed, open the application from your desktop or Start menu. The app will ask for permission to access your MIDI devices or keyboard.

### Using a MIDI Controller

- Connect your MIDI controller to your computer via USB or MIDI interface.  
- MidiRipples automatically detects the connected device.  
- Play notes on your controller to hear sounds instantly.  
- The default range supports a three-octave keyboard.  

### Using Your Computer Keyboard

- If no MIDI device is detected, MidiRipples will let you use your computer keyboard as a musical instrument.  
- Play notes using common keys assigned to MIDI notes.  
- This mode lets you try the app without extra equipment.

## ⚙️ Adjusting MIDI Settings

If your MIDI controller has a different range or setup, you can customize the app to fit your needs.

- Open the `constants.ts` file found in the app’s folder, usually inside the installation directory or source folder.  
- Locate the `MIDI_NOTE_RANGE` setting. This controls which notes the app listens for.  
- Change the note range to match your controller. For example, if your device plays six octaves, update the range accordingly.  
- Save the file and restart the app.

This manual adjustment allows you to expand or limit the playable notes to what your device supports.

## 🎶 How MidiRipples Works

MidiRipples listens for signals from your MIDI controller or keyboard. When you press a key, it sends a sound corresponding to the note. The app is designed to respond quickly so there is no delay.

- It supports standard MIDI note messages.  
- You can connect various controllers without extra setup.  
- The range adjustment lets you tailor the play area to your device.  

## 🛠 Troubleshooting

If MidiRipples does not detect your MIDI controller or keyboard, try these steps:

- Make sure your MIDI controller is properly connected and powered on.  
- Restart MidiRipples after connecting your device.  
- Check your Windows sound settings to confirm that audio output is working.  
- Verify that your MIDI drivers are installed correctly (this depends on your controller manufacturer).  
- If using the computer keyboard mode, ensure the app indicates keyboard input is active.  

## 📖 Additional Information

- MidiRipples is built with simple tools that allow real-time audio play.  
- The default settings assume a three-octave keyboard.  
- You can modify the software if you have basic programming knowledge.  

## 🤝 Support and Contributions

If you want help or want to suggest improvements, visit the page below to open issues or pull requests:

[https://github.com/zokiru7827/MidiRipples](https://github.com/zokiru7827/MidiRipples)

Developers can clone the repo and use the commands:

- `npm i` to install necessary files.  
- `npm run dev` to start the app in developer mode.  

This is mainly meant for those who want to modify or improve the software.

## 💡 Tips

- Try different MIDI controllers to find what works best for you.  
- Use headphones to avoid feedback if you connect a MIDI controller with built-in speakers.  
- Experiment with the note range setting to suit your playing style.  

[![Download MidiRipples](https://img.shields.io/badge/Download-MidiRipples-ff6f61?style=for-the-badge)](https://github.com/zokiru7827/MidiRipples)