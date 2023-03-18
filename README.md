# MEmu 8 - Android 7.1 x64

### SuperSU Installation

1. Install supersu.apk
2. Open it and go expert->continue->normal
3. Restart emulator

### BusyBox Installation

1. Install busybox.apk
2. Open it and click install

### Xposed Installation

1. Install root_browser.apk
2. Install terminal.apk
3. Install xposed.apk
4. Open Root Browser
5. Copy "update-binary" and "xposed-v89-sdk25-x86_64-signed.zip" to "/data/local/tmp"
6. Run below commands in Terminal Emulator app with root
7. Restart emulator

```sh
su
cd /data/local/tmp
chmod 777 update-binary
NO_UIPRINT=1 ./update-binary 2 1 xposed-v89-sdk25-x86_64-signed.zip
rm update-binary xposed-v89-sdk25-x86_64-signed.zip
```

!!! Root mode must be enabled.

!!! Emulator may boots up slowly after operations.

