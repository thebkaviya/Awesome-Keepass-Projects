# Awesome KeePass Projects [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of [KeePass](https://keepass.info/)-related projects.

KeePass is a free open source password manager, which helps you to manage your passwords in a secure way. You can put all your passwords in one database, which is locked with one master key or a key file. So you only have to remember one single master password or select the key file to unlock the whole database. The databases are encrypted using the best and most secure encryption algorithms currently known (AES and Twofish).

## Content

* [Clients](#clients)
    * [Desktop clients](#desktop-clients)
        * [Cross-platform clients](#сross-platform)
        * [Windows clients](#windows-clients)
        * [MacOS clients](#macos-clients)
    * [Web clients](#web-clients)
    * [iOS clients](#ios-clients)
    * [Android clients](#android-clients)
    * [Other clients](#other-clients)
* [API libraries](#api-libraries)
* [Plugins](#plugins)
* [Misc](#misc)
* [Security](#security)
* [Docs and articles](#docs-and-articles)
    * [Docs and articles](#docs-and-articles-ru)

## Clients

### Desktop clients

#### Cross-platform

* [KeePass](https://sourceforge.net/projects/keepass/) - Official client.
    * [mirror of KeePass2.x source code](https://github.com/dlech/KeePass2.x)
* [KeePassXC](https://keepassxc.org/) - KeePass Cross-Platform Community Edition.
    * [Source code](https://github.com/keepassxreboot/keepassxc)
* [KeeWeb](https://keeweb.info/) - Free cross-platform password manager compatible with KeePass.
    * [Source Code](https://github.com/keeweb/keeweb)
* [KeePass-electron](https://github.com/IlyaPomaskin/KeePass-electron) - Desktop HTML5 client for KeePass 2.

#### Windows clients

* [Keepass Official Desktop Client](https://keepass.info/download.html)


#### MacOS clients

* [MacPass](https://mstarke.github.io/MacPass/) - Native OS X KeePass client.
    * [Source code](https://github.com/mstarke/MacPass)
* *closed source* [Kypass Companion](http://www.kyuran.be/software/kypass4mac/) - A native KeePass compatible client for macOS (database format 1 and 2).

### Web clients

* [keepass4web](https://github.com/lixmal/keepass4web/) - Application that serves KeePass database entries on a web frontend.
* [keeweb](https://github.com/keeweb/keeweb) - Free cross-platform password manager compatible with KeePass.
* [BrowsePass](https://bitbucket.org/namn/browsepass/overview) - Web application to read KDBX files.
* [keepass-node](https://github.com/gesellix/keepass-node) - KeePass2 editor for Node.js with a browser frontend.

### iOS clients

* [MiniKeePass](https://itunes.apple.com/us/app/minikeepass-secure-password/id451661808) - MiniKeePass provides secure password storage on your phone that's compatible with KeePass.
    * [Source Code](https://github.com/MiniKeePass/MiniKeePass)
* *closed source* [Kypass 4](http://www.kyuran.be/software/kypass/) - KyPass is a Password Management for iPhone and iPad.
* [Strongbox](https://strongboxsafe.com/) - A Personal Password Manager for iOS & OSX
    * [Source](https://github.com/strongbox-password-safe/Strongbox)

### Android clients

* [Keepass2Android](https://play.google.com/store/apps/details?id=keepass2android.keepass2android) - Password manager app for Android.
    * [Source code](https://github.com/PhilippC/keepass2android)
* [KeePassDroid](https://play.google.com/store/apps/details?id=com.android.keepass) - KeePass implementation for android.
    * [Source code](https://github.com/bpellin/keepassdroid)

### Other clients

* [WinPass](https://github.com/gkardava/WinPass) - KeePass password manager client for Windows Mobile.
* [KeePassTouch](https://github.com/DannyGB/KeePassTouch) - Ubuntu Touch Version of KeePass.

## API libraries

* [libkeepass](https://github.com/libkeepass/libkeepass) - `python` Low-level Python (2.7/3.x) module to read KeePass 1.x/KeePassX (v3) and KeePass 2.x (v4) files. *deprecated - use pykeepass*
* [pykeepass](https://github.com/libkeepass/pykeepass) - `python` Python library to interact with keepass databases (supports KDBX3 and KDBX4) 
* [kdbxweb](https://github.com/keeweb/kdbxweb) - `javascript` High-performance javascript library for reading/writing KeePass v2 databases (kdbx) in node.js or browser.
* [keepass-rs](https://github.com/sseemayer/keepass-rs) - `Rust` Rust library for reading KeePass database files (kdbx).
* [keepass.io](https://github.com/snapserv/keepass.io) - `javascript` Node.js library for reading and writing KeePass databases.
* [KeePassKit](https://github.com/MacPass/KeePassKit) - `Objective-C` KeePass database loading, storing and manipulation framework.
* [KeePassJava2](https://github.com/jorabin/KeePassJava2) - `Java` Java API for KeePass Password Databases - Read/Write 2.x, Read 1.x
* [openkeepass](https://github.com/cternes/openkeepass) - `Java` A java library for reading and writing KeePass databases. It is an intuitive java library that supports KeePass 2.x database files.

## Plugins

* [keepasshttp](https://github.com/pfn/keepasshttp/) - KeePass plugin to expose password entries securely (256bit AES/CBC) over HTTP.
* [Keebuntu](https://github.com/dlech/Keebuntu) - KeePass 2.x plugins that provide Linux Desktop integration.
* [KeeAgent](https://github.com/dlech/KeeAgent) - Plugin for KeePass 2.x. It allows other programs to access SSH keys stored in your KeePass database for authentication.
* [AdvancedConnectPlugin](https://github.com/aalbng/AdvancedConnectPlugin) - Plugin for KeePass which gives you the possibility to provide different applications for direct connections.
* [SIC2KeePass](https://github.com/Alezy80/SIC2KeePass) - This plugin allows to transfer SafeInCloud databases directly or via exported XML file into KeePass 2.xx password manager.
* [QuickConnectPlugin](https://github.com/cristianst85/QuickConnectPlugin) - Plugin that allows you to connect to Windows/Linux/ESXi hosts.
* [HIBP Offline Check](https://github.com/mihaifm/HIBPOfflineCheck) - a KeePass plugin for Have I been pwned, can perform both offline and online checks against the password breach list for any selected password entry
* [KPSimpleBackup](https://github.com/marvinweber/KPSimpleBackup) - This simple plugin lets you backup your .KDBX file with many advanced options

## Misc

* [kdbxviewer](http://max-weller.github.io/kdbx-viewer/) - Command-line tool written in C for KeePass2 Database files (kdbx).
    * [Source code](https://github.com/max-weller/kdbxviewer)
* [keepass-chrome](https://github.com/btd/keepass-chrome) - Small proof of concept extension that loads keepass .kdbx files and allow to get and add passwords.
* [keepass-diff](https://github.com/Narigo/keepass-diff) - Command-line tool written in Rust to show differences between two KeePass Database files.
* [passifox](https://github.com/pfn/passifox) - Extensions to allow Chrome and Firefox (4.0+) to auto form-fill passwords from KeePass (requires KeePassHttp).

## Security

* [mod0keecrack](https://github.com/devio/mod0keecrack) - KeePass 2 database master-password cracker.
* [KeeFarce](https://github.com/denandz/KeeFarce) - Extracts passwords from a KeePass 2.x database, directly from memory.
* [KeePassHax](https://github.com/HoLLy-HaCKeR/KeePassHax) - Extracts master password from a KeePass 2.x database, directly from memory. Inspired by KeeFarce.

## Docs and articles

* [KeePass Help Center](https://keepass.info/help/base/index.html) - Official docs and tutorials.
* [KDBX 4](https://keepass.info/help/kb/kdbx_4.html) - Info about KDBX 4 file format.
* [Reverse Engineered KeePass (KDBX) File Format](https://max-weller.github.io/kdbx-viewer/kdbx_format.html)
* [Reading a Keepass 2 file with Go](https://www.sysorchestra.com/2015/06/20/reading-a-keepass-file-from-go/)
* [Keepass file format explained](https://gist.github.com/lgg/e6ccc6e212d18dd2ecd8a8c116fb1e45)
* [KeePass v2.x (KDBX v3.x) file format](https://gist.github.com/msmuenchen/9318327)

### Docs and articles RU

* [How I made web-version of KeePass](https://habrahabr.ru/post/269895/) - `ru` Info about kdbx format and developing an app for it.

## License

* MIT, [lgg](https://github.com/lgg) and [contributors](https://github.com/lgg/awesome-keepass/graphs/contributors)   
