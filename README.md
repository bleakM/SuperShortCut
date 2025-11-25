# The latest word -- the SUPER-SHORTCUT!
## Version 4.0 is released, with enhanced detail design, increased flexibility, and the addition of local backup and global lock functions (which can disable input when the computer is not locked).
## Now, English, Japanese and French are all fully supported!


## Overview

**SuperShortCut** is a versatile file management application that offers a variety of powerful features, such as path management, auto-backup, system security through password locking, desktop layout saving, and screen mirroring. The core of the application is `SuperShortCut.exe`, which serves as the entry point. To ensure proper functionality, you must launch the application through a shortcut, as the executable creates essential data files in its directory.

This application is packaged in a `.rar` archive, containing several pre-packaged `.exe` files. After extracting the contents, you must create a shortcut for `SuperShortCut.exe` and place it on your desktop for easy access.

### Key Features:

* **Path Manager**: Organize and manage file paths for easy access.
* **Auto-Backup**: Automatically back up specified folders on system startup.
* **Secure Lock System**: Lock your computer with a password for additional security.
* **Screen Mirroring**: Mirror your desktop layout to prevent display of screen contents and maintain a clean, organized appearance.
* **Desktop Layout Management**: Save and restore desktop layout, including file and folder positions, to maintain order.
* **Backup Desktop**: Prevent accidental desktop clutter by maintaining a simple wallpaper setup and backing up your layout for future restoration.

## Supported Languages

SuperShortCut supports multiple languages, allowing users from different regions to enjoy a localized experience. The application currently supports the following languages:

* **English** (`en`)
* **Chinese (Simplified)** (`zh`)
* **Japanese** (`ja`)
* **French** (`fr`)

You can easily switch the application language via the settings, ensuring that it suits your preferred language. The language settings are stored in the `config.json` file, and the application will automatically load your selected language when it starts up.

## Installation

1. Download and extract the `.rar` file.
2. In the extracted folder, you'll find several pre-packaged `.exe` files.
3. **Important**: Right-click `SuperShortCut.exe` and create a shortcut. Place the shortcut on your desktop for easy access.

   * Running `SuperShortCut.exe` directly will generate data files in its directory. Use the shortcut to ensure these files are created in the correct location.

### System Requirements:

* Windows operating system (certain features like auto-backup and path management require Windows support).

## Usage

### Running the Application

After extracting the files, follow these steps to launch the application:

1. Navigate to the extracted folder.
2. Right-click `SuperShortCut.exe` and select "Create Shortcut."
3. Move the created shortcut to your desktop and double-click it to run the application.

Once launched, the application provides access to the following features:

1. **Path Manager**: Easily add, remove, and manage paths to frequently used directories.
2. **Auto-Backup**: Enable or disable the auto-backup feature to ensure important directories are backed up automatically when the system starts.
3. **System Lock**: Lock your computer with a password to prevent unauthorized access.
4. **Save and Restore Desktop Layouts**: Save the current desktop layout and restore it whenever needed.
5. **Screen Mirroring**: Mirror your desktop layout to create a clean and organized screen without displaying clutter.

### Main Window Features:

* **Path List**: Displays all the managed paths.
* **Path Operations**: Buttons for adding, removing, and checking paths.
* **Auto Backup**: Toggle auto-backup on or off and configure settings.
* **System Lock**: Activate or deactivate the system lock for added security.
* **Screen Mirroring**: Toggle screen mirroring to hide desktop contents and only show the wallpaper.

### Path Management

* **Add Path**: Click the "Add Path" button to browse and select directories you want to manage.
* **Remove Path**: Select a path from the list and click "Remove" to delete it from the application.
* **Path Check**: Use the "Check All" button to verify the status of all listed paths.

### Auto-Backup Feature

* **Enable/Disable Auto-Backup**: Toggle the auto-backup feature on or off to back up directories when the system starts.
* **Backup Location**: Specify which directories should be backed up automatically.

### Secure Lock System

* **System Lock**: Lock your computer with a password, preventing unauthorized access to files and applications.
* **Password Setup**: Set a default password or change it to something more secure. The default password is `unlock123`.
* **Unlock**: To unlock the system, press `Ctrl + Alt + Del` -> open Task Manager -> press `Esc` and then enter the password.

### Desktop Layout Management

* **Save Layout**: Save the current desktop layout, including the positions of files and folders, for later restoration. This is useful if you need to restore the desktop to its original state.
* **Restore Layout**: Restore your desktop layout from a previously saved snapshot, ensuring the desktop looks exactly as it did when the snapshot was taken.

### Screen Mirroring - New Feature!

* **Mirror Desktop Layout**: The screen mirroring feature allows you to hide your desktop contents. When mirroring is active, only your chosen wallpaper is displayed on the screen, creating a clean and minimalistic desktop. This is especially useful for keeping the desktop free of clutter and distractions.

  * **Why Mirror?**: If you want to maintain a simple, organized desktop with only your wallpaper visible, use the mirroring feature to temporarily "hide" your desktop contents. You can still view the full desktop layout in the app itself, but others will only see the clean wallpaper.
* **Backup Desktop**: The screen mirroring feature works hand-in-hand with the desktop backup functionality. You can create a snapshot of your clean desktop layout (with just the wallpaper visible) and restore it if your desktop becomes cluttered.

  * **Prevent Accidental Clutter**: By backing up your desktop layout after mirroring it, you ensure that your desktop remains organized and visually appealing, even after changes are made.

## Configuration

The application’s settings are stored in a `config.json` file located in the extracted directory. This file contains configuration options such as language preference and window size.

* **language**: Set your preferred language (e.g., `en` for English, `zh` for Chinese).
* **window_size**: Defines the default window size when the application is launched.

## Troubleshooting

### Error: "Unable to open path"

* This error occurs when the selected path is either missing or inaccessible. Ensure the path exists and that you have the necessary permissions to access it.

### Error: "Permission Denied" during Auto-Backup setup

* The application requires administrative privileges to modify system settings or perform auto-backups. Ensure that the application is run with administrator privileges.

## FAQ

**Q: How do I change the system lock password?**

* To change the system lock password, go to the settings menu and select "Change Password." Enter your current password and set a new one.

**Q: Can I add multiple paths for auto-backup?**

* Yes, you can add multiple paths. The application allows you to specify multiple directories for automatic backup on system startup.

**Q: How do I restore my desktop layout after making changes?**

* You can restore your desktop layout by using the "Restore Layout" feature in the Desktop Layout Manager. This will return your desktop to the exact state it was in when the snapshot was saved.

**Q: What happens when I enable screen mirroring?**

* When screen mirroring is enabled, your desktop content is hidden, and only your wallpaper will be shown on the screen. This is useful for keeping your desktop uncluttered. You can still view and manage the full desktop layout in the application.

**Q: Can I backup my desktop layout with the wallpaper?**

* Yes, you can use the screen mirroring feature to display just the wallpaper, and then save the current desktop layout, ensuring that your desktop remains organized and visually pleasing.

## License

This software is distributed under the MIT License. See the LICENSE file for more details.