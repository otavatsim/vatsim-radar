# VATSIM Radar

A real-time VATSIM flight radar built with **Leaflet** and **Mapbox**, packaged as a desktop app using **Electron**.  

## Features
- Displays live VATSIM aircraft positions worldwide
- Rotated plane icons based on heading
- Click an aircraft to see **past positions** and **predicted future path**
- Search/filter by callsign
- Dark and light mode toggle
- 2-second refresh interval
- Fixed map bounds (no infinite scrolling)
- Desktop app with custom icon
- Zoom controls at top-right

## Requirements
- Windows 10+ (for `.exe` version)
- Internet connection (for live Mapbox tiles and VATSIM data)

## Installation
1. Download the latest `.exe` from the [Releases](#) page.  
2. Run the installer or portable `.exe`.  

## Usage
- Use the **search box** to filter by aircraft callsign.  
- Click an aircraft to see its trail and future path.  
- Toggle dark/light mode with the button in the top-left.  

## Building from Source
If you want to build it yourself:  
```bash
git clone https://github.com/YourUsername/vatsim_radar.git
cd vatsim_radar
npm install
npm run start   # Runs in Electron
npm run dist    # Builds Windows .exe
