# Unity Version Incrementor
An editor script that allows you to increment version numbers through the editor and on each build.

## Usage
1) Put VersionIncrementor.cs in your Editor folder within your Unity project
2) Whenever you build the game the revision number (0.0.x) will increment

You can also increment the build manually via the Build dropdown tab

## Example
![Gif](http://puu.sh/BwyJ9/ac1b64ef89.gif)

If you don't want the new version output to a text file remove these lines:

```
var buildVersionPath = @"buildversion.txt";
File.WriteAllText(buildVersionPath, PlayerSettings.bundleVersion);
```
