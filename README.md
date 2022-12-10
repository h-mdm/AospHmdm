# Integration of Headwind MDM in AOSP

If you have a source code of the Android (AOSP) ROM, you can integrate Headwind MDM into it.

1. Copy this directory into packages/apps and rename to HeadwindMDM
2. Get the latest APK file of Headwind MDM and copy into this directory
3. Update the Headwind MDM APK file name in Android.mk
4. Copy the patched [Provision](https://github.com/h-mdm/AospProvision) application into packages/apps and update its source code as appropriate (see README of that project)
5. Build the ROM

At first start, you'll get your device provisioned with Headwind MDM.
