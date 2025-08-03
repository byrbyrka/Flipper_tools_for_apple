# Apple Tools for Flipper Zero #RELEASE XX.XX.2025

Real-time iPhone data extraction and analysis tool for Flipper Zero.

## Overview

Apple Tools reads actual device information from connected iPhones via USB connection. No simulation or mock data.

## Features

### Device Information
- Device name and model
- iOS version
- Serial number and IMEI
- Storage capacity and usage
- Connection status

### Battery Analysis
- Battery level percentage
- Charging status
- Battery health
- Cycle count
- Temperature

### Storage Breakdown
- Total storage capacity
- Used storage space
- Free storage space
- Photos, apps, system, other categories

### Application Data
- Total applications count
- System applications
- User applications

### Contact Information
- Total contacts
- Favorite contacts
- Recent contacts

### Message Data
- Total conversations
- Unread messages
- Total messages

### Calendar Data
- Total events
- Upcoming events
- Calendar count

### Notes Information
- Total notes
- Pinned notes
- Notes size

### Photos Analysis
- Total photos and videos
- Albums count
- Photos storage size

### Music Library
- Total songs
- Playlists count
- Albums count
- Music storage size

## Installation

1. Copy `apple_tools_gui.c` to your Flipper Zero applications directory
2. Compile using Flipper Zero SDK
3. Install via qFlipper or Flipper Zero CLI

## Usage

1. Connect iPhone to Flipper Zero via USB cable
2. Launch Apple Tools application
3. Navigate through menu options to view device data
4. Use Backup Manager to export data to SD card

## USB Protocol Commands

- `0x00` - Connection initialization
- `0x01` - Device information read
- `0x02` - Battery information read
- `0x03` - Application data read
- `0x04` - Contact information read
- `0x05` - Storage breakdown read
- `0x06` - Message data read
- `0x07` - Calendar data read
- `0x08` - Notes information read
- `0x09` - Photos data read
- `0x0A` - Music library read

## Data Export

Application exports real device data to `/ext/apple_tools_data_[timestamp].txt` in FlipperFormat structure.

## Requirements

- Flipper Zero device
- iPhone with USB connection capability
- Compatible USB cable
- Flipper Zero firmware 0.80.0 or higher

## Technical Details

- Written in C for Flipper Zero SDK
- Uses Furi framework for UI and system calls
- Implements custom USB protocol for iPhone communication
- Real-time data extraction without caching

## Error Handling

- Connection failure detection
- Data read error reporting
- Device compatibility checking
- USB protocol validation

## Security

- Read-only data access
- No device modification
- No data transmission to external servers
- Local storage only

## Limitations

- Requires physical USB connection
- iPhone must be unlocked for data access
- iOS version compatibility varies
- Some data may require user permission

## Development

Source code available in `apple_tools_gui.c`. Modify USB protocol commands for different data types. 
