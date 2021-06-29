# zoo-syncthing
An empty repository just for a description of usage of Zoo for Zotero with Syncthing on Android device

# what for?

[Zoo](https://github.com/mickstar/Zoo-For-Zotero) is a very nice project for running [Zotero](https://zotero.org) on an Android powered device for keeping your library and reference database synchronized on the go. It offers various options of attachments (full texts) synchronization, however, most of these require some server (either Zotero server, or third-party WebDAV server) to synchronize with. One of the possible decentralized sync options is [Syncthing](https://github.com/syncthing/syncthing-android). Setting up Zoo with Syncthing allows to keep the Zotero library up to date without the need of a central server.

# setup

Both [Zoo](https://play.google.com/store/apps/details?id=com.mickstarify.zooforzotero&hl=en_US) and [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid&hl=en_US) are available at Google Play. Once these are installed and Zoo is set up with your Zotero account, the following actions are needed.

1. Connect Syncthing to your device/devices using QR code or DeviceID. Share the Zotero/storage folder from your source device (a standard location of this is at ~/Zotero/storage for Zotero 5 and up). Use some location at Android device to sync this (default **Android device path** might be /storage/emulated/0/Zotero/storage, which is equivalent to ~/Zotero/storage).
2. Start Zoo and open Settings. Disable WebDAV access to attachments. Select Attachments Location and enter the **Android device path** used at step 1.
3. Restart Zoo.

This guide is offered as is, and may become obsolete. Please carefully check all the steps yourself in order not to ruin your library. Thanks for reading!
