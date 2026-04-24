## Changelog

### 0.1.2.0
  Fixed missing trailing `|` character for some commented out vanilla traits. 
  Changed mod options to used localized `toggle.enabled` and `toggle.disabled`. This probably broke the `zh-tw` localization. Apologies.
  There's some WIP on adding the remaining localizations, but it's all machine translated and I don't want to pull the trigger yet.

### 0.1.1.1
  Added `zh-tw.txt` localization file. Thanks to sarukomine for providing translations.

### 0.1.1.0
  Various updates:
  - Fixed failsafe traits being added to the randomizer when they were not necessary.
  - Added `FileConfig.txt` to help alleviate file overwrites from future patches:
  	- You can specify alternate filenames for configuration files on a per file basis.
  	- `FileConfig.txt` itself will still revert after updates, but at least you won't lose your other file updates.

### 0.1.0.0
Initial release. 