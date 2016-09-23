
iphone-dataprotection-xcode5:

iPhone Data Protection Tools cloned from https://code.google.com/p/iphone-dataprotection on January 24, 2015.

Code slightly changed back for OS X Yosemite (v 10.10.x) with Xcode 5.1.1 (iOS 7.1):
- "build_tools.sh”: SDK references point to 10.9. Xcode 5.1.1 still used the references to OS 10.9 instead of 10.10 (even when running in Yosemite).
- "demo_bruteforce.py" patched to obtain the three files used for the keychain-2.db in iOS 7.x

By Raul Siles

- References:

Check https://github.com/dinosec/iphone-dataprotection for OS X Yosemite (v 10.10.x) with Xcode 6.1.x.

(The project reference for iphone-dataprotection in OS X El Capitan (v 10.11.x), with Xcode 7.3.x, has been removed, as the passcode bypass capabilities do not work in that versions - without doing further analysis)
