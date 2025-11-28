# Simple Auto Read

A Tampermonkey script for automatic post reading on specific forum websites.

<img width="323" height="390" alt="image" src="https://github.com/user-attachments/assets/fd03b82c-6835-48c1-ae11-2fe4e033a822" />

## Features

- **Automatic Scrolling**: Automatically scroll through forum posts at adjustable speeds
- **Auto Like**: Automatically like posts with configurable intervals
- **Read History**: Avoids re-reading the same posts by maintaining a reading history
- **Site Support**: Compatible with multiple forum websites:
  - https://www.nodeloc.com
  - https://linux.do
  - https://mjjbox.com (in some versions)
- **Configurable Settings**: Customize scroll speed, like intervals, and more
- **User-Friendly Panel**: Easy-to-use control panel for managing script functions
- **Daily Counter**: Tracks daily activity with automatic reset

## Installation

1. Install the [Tampermonkey](https://www.tampermonkey.net/) browser extension
2. Create a new script in Tampermonkey
3. Copy the content of one of the script files (`read.js`, `simple-read.js`, or `simple-read1.js`)
4. Paste the content into the Tampermonkey script editor
5. Save the script
6. Navigate to one of the supported forum websites

## Usage

1. The control panel will appear in the bottom right corner of the page
2. Click the "Start" button to begin automatic reading
3. Adjust the scroll speed using the provided slider
4. Toggle auto-like functionality as needed
5. Configure the like interval for auto-like feature

## Script Variants

- **read.js**: Full-featured version with comprehensive controls
- **simple-read.js**: Simplified version supporting nodeloc.com, linux.do, and mjjbox.com
- **simple-read1.js**: Simplified version supporting only nodeloc.com and linux.do

## Configuration Options

### Scroll Speed
- **Range**: 1 - 200
- **Default**: 40
- **Description**: Controls how fast the page scrolls, higher values mean faster scrolling

### Like Interval
- **Range**: 1000 - 600000ms (1 second - 10 minutes)
- **Default**: 2500ms (2.5 seconds)
- **Description**: Controls the time between automatic likes, higher values mean slower liking

### Read History
- **Capacity**: Up to 100 posts
- **Description**: Automatically manages previously read posts to avoid re-reading

### Daily Reset
- **Interval**: 24 hours
- **Description**: Activity counter resets automatically every day

## Control Panel

### Buttons
- **Start Reading**: Begin automatic reading
- **Stop Reading**: Pause automatic reading
- **Enable Auto Like**: Activate automatic liking
- **Disable Auto Like**: Deactivate automatic liking
- **Minimize Button**: Collapse the control panel

### Status Display
- **Scroll Speed**: Shows current scroll speed setting
- **Like Interval**: Shows current like interval setting
- **Today's Likes**: Displays daily like count and limit
- **Status Info**: Shows current script running status

### Minimized State
- Shows current reading status (Active/Inactive)
- Click to restore the full control panel

## Permissions

The script requires the following Tampermonkey permissions:
- `GM_addStyle`: For adding custom styles
- `GM_getValue`: For storing settings
- `GM_setValue`: For retrieving settings
- `GM_registerMenuCommand`: For adding menu commands
- `GM_notification`: For displaying notifications (in some versions)

## Changelog

### v1.0.0

## License

MIT License

