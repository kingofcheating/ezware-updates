## Windows Security notice

Windows Security or another antivirus might warn about, block, or remove ezware. This can happen because of how the program works.

ezware:

* Opens the Roblox process.
* Reads and writes Roblox's memory.
* Reads and sends mouse input.
* Downloads updates over the internet.
* Replaces its own file when updating.

These are things that antivirus software often watches for because they're also used by some malware. That doesn't automatically mean ezware is dangerous, but it does mean some antivirus programs may flag it.

### If your antivirus blocks ezware

If Windows Security or your antivirus blocks or deletes ezware, and you've made sure you downloaded it from the official GitHub release, you may need to temporarily turn off real-time protection or choose **Allow on device** so the file isn't removed.

Before you do that:

1. Make sure you downloaded ezware from the official release page.
2. Check that the version and SHA-256 hash match, if one is listed.
3. Read the warning shown by Windows Security or your antivirus.
4. Only allow the file if you trust where it came from.

If you turn off real-time protection, turn it back on as soon as you're done. Don't disable your antivirus for files from mirrors, file-sharing websites, direct messages, or anywhere other than the official release page.

### Security review

For the official **v1.0.4** release, we checked all of the source code, looked through the build settings, reviewed how the updater and internet connection work, and scanned the finished program with Microsoft Defender.

Microsoft Defender found **no threats** during that review.

The program is **not digitally signed**, so Windows SmartScreen and some antivirus programs may still show a warning because the file doesn't have an established reputation.

**SHA-256**

`DE76A1B52F464C6639ACEF5340C24D03A59F0AF6539A6373841C0B1B9202461F`

This review only applies to the official file with this hash. It does not apply to edited or reuploaded copies.
