# Unity-Version-Incrementor
An editor script that allows you to increment version numbers through the editor and on each build.

## Example
![Gif](http://puu.sh/BwyJ9/ac1b64ef89.gif)

If you don't want the new version output to a text file remove these lines:

```
var buildVersionPath = @"buildversion.txt";
File.WriteAllText(buildVersionPath, PlayerSettings.bundleVersion);
```
