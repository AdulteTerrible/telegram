Telegram for OSX
===========

[Telegram](http://telegram.org) is a messaging app with a focus on speed and security. It’s superfast, simple and free.

This repo is a fork of the official [Telegram Messenger](https://telegram.org/dl/osx) source code.

### API, Protocol documentation

Documentation for Telegram API is available here: http://core.telegram.org/api

Documentation for MTproto protocol is available here: http://core.telegram.org/mtproto

### For Quick Start Usage



1. Checkout repository:
   - add this repository to XCode,
   - Version Control > Check Out...
2. Switch MtProtoKit submodule to 'unstable' branch (XCode: Version Control > MtProtoKit(...) > Switch to Branch...)
3. Create 'Application.h' file with this content:

```c
#ifndef Telegram_Application_h
#define Telegram_Application_h


#define API_ID 0000 // you can create new app on my.telegram.org
#define API_HASH @"" // you can create new app on my.telegram.org
#define HOCKEY_APP_IDENTIFIER @"" // hocheckey app
#define HOCKEY_APP_COMPANY @""  // hocheckey app
#define BUNDLE_IDENTIFIER @"ru.keepcoder.Telegram"  // bundle name
#endif
```
4. Register your app at my.telegram.org and change the values of Application.h accordingly.

Code available on GPLV2 license
