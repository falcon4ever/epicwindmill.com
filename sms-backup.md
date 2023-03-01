---
id: 362
title: 'SMS Backup'
date: '2013-04-26T15:47:40+01:00'
author: Laurence
layout: page
guid: 'https://epicwindmill.com/?page_id=362'
---

**SMS Backup** is a complete text message backup and restore solution for BlackBerry 10 devices. Whether you want to backup your text messages or want to import and merge your (old) text messages from a BlackBerry 10 device or other smartphone devices \[1\], **SMS Backup** is here to help you.

### Features

- Backup text messages (SMS) to an open XML format
- Backup media content from MMS
- Checks for duplicates on import
- Clear all your text messages (Safely remove all text messages)
- Export text messages to a CSV file that you can view, sort and print in a spreadsheet application such as Excel
- The easiest way to migrate from Android to BlackBerry10 (and vice versa)!
- View backup file/conversations in browser (Internet Explorer/Firefox)

\[1\] The XML format allows you to import and export to other platforms as well:

- **Import** to and **export** from Android, use [SMS Backup and Restore](https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore) for Android.
- **Import** from iPhone is a bit tricky but users have reported to be successful using this tool <http://faked.org/isms2droid/> (advanced users only). After converting your messages db file to an XML file, please use this tool to patch your backup file: [https://epicwindmill.com/tools/smsfix/](https://epicwindmill.com/tools/smsfix/ "https://epicwindmill.com/tools/smsfix/")

**This tool should be very useful for people who:**
- switch OS versions often (i.e. Testing leaks)
- need to switch between BB10 devices (upgrading/replacements)
- are migrating to or from Android devices
- want to archive conversations
- want to view/print messages on their computer
- need a more reliable alternative to BB Link which seems to have issues when restoring from different OS versions

### Required permissions

[![2013-11-08 09.01.38](https://epicwindmill.com/wp-content/uploads/2013/04/2013-11-08-09.01.38-180x300.png)](https://epicwindmill.com/wp-content/uploads/2013/04/2013-11-08-09.01.38.png)

This app requires the following permissions to work correctly:

- **Email and PIN Messages**  
    This permission is required to list, read and access your accounts
- **Shared Files** This permission is required to read and store the backup files
- **Text Messages**  
    This permission is required to access your text message account
- **Run When Backgrounded**  
    This permissions is required to allow the app to import/export while running in the background

### Where to get it?

**BlackBerry World:**  
[SMS Backup for BB10](http://appworld.blackberry.com/webstore/content/27686935/)

**CrackBerry Forums Support/Feedback Topic:**  
[SMS Backup – Backup and Restore Text Messages](http://forums.crackberry.com/app-announcements-f281/sms-backup-backup-restore-text-messages-801268/)

### Screenshots

![2013-11-06 23.12.15](https://epicwindmill.com/wp-content/uploads/2013/11/2013-11-06-23.12.15-180x300.png) ![2013-11-06 23.29.10](https://epicwindmill.com/wp-content/uploads/2013/11/2013-11-06-23.29.10-180x300.png) ![2013-11-06 23.12.23](https://epicwindmill.com/wp-content/uploads/2013/11/2013-11-06-23.12.23-180x300.png)

![2013-11-06 23.12.28](https://epicwindmill.com/wp-content/uploads/2013/11/2013-11-06-23.12.28-180x300.png) ![2013-11-06 23.12.32](https://epicwindmill.com/wp-content/uploads/2013/11/2013-11-06-23.12.32-180x300.png) ![2013-11-06 23.12.40](https://epicwindmill.com/wp-content/uploads/2013/11/2013-11-06-23.12.40-180x300.png)

### Guides

#### Reading conversations on the computer

- Copy the backup file (**yourbackupfilename.xml**) and stylesheet file (**sms.xsl**) to the computer
- Right click on the file
- Open with… **Internet Explorer** or **Firefox**
- Do note that the **XML** and **XSL** files need to be in the same directory for this to work

[![browserexample](https://epicwindmill.com/wp-content/uploads/2013/04/browserexample-150x150.jpg)](https://epicwindmill.com/wp-content/uploads/2013/04/browserexample.jpg)

Or watch this video:  
![](https://www.youtube.com/watch?v=FWOQqUZu74s)

#### Exporting text messages

- <span style="line-height: 13px;">Switch to the Backup tab</span>
- Touch the “Backup” button
- Specify a filename (we recommend including the date)
- The backup file will be stored on the device in the folder “documents/SMSBackup”
- You can either e-mail the file or connect the device to your computer to archive it.

#### <span style="font-size: 1em;">Importing text messages</span>

- <span style="line-height: 13px;">Switch to the Restore tab</span>
- Touch the “Restore” button
- Use the filemanager to select your backup file (\*.xml)
- After picking your file, SMS Backup will start importing the messages
- This might take a while depending on the number of archived messages

### Android Guides

#### Exporting to Android

- Folow the instructions above
- Copy the XML file from the BlackBerry 10 device to the Android device
- Choose the **Restore** option in **SMS Backup &amp; Restore**.

#### Importing from Android

- Install [SMS Backup and Restore](https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore) onto your Android device
- Open up the application and choose Backup  
    [![android-import1](https://epicwindmill.com/wp-content/uploads/2013/04/android-import1-180x300.jpg)](https://epicwindmill.com/wp-content/uploads/2013/04/android-import1.jpg)
- Specify a filename  
    [![android-import2](https://epicwindmill.com/wp-content/uploads/2013/04/android-import2-180x300.jpg)](https://epicwindmill.com/wp-content/uploads/2013/04/android-import2.jpg)
- Wait for the application to finish  
    [![android-import3](https://epicwindmill.com/wp-content/uploads/2013/04/android-import3-180x300.jpg)](https://epicwindmill.com/wp-content/uploads/2013/04/android-import3.jpg)
- All messages have been exported  
    [![android-import4](https://epicwindmill.com/wp-content/uploads/2013/04/android-import4-180x300.jpg)](https://epicwindmill.com/wp-content/uploads/2013/04/android-import4.jpg)
- Copy the backup XML file from your Android device e.g. `X:\\SMSBackupRestore` to your BlackBerry 10 device
- Follow the instructions from **Importing text messages**