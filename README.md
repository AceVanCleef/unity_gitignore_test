# Problem

Merge confligts in unity subfolders such as Library or Temp when working in a team.

# Solution

With version 1.8.2 of git, you can also use the ** wildcard to match any level of subdirectories:

```
**/bin/Debug/
**/bin/Release/
```

## Alternative solution

Wildcards
```
Solution/*/bin/Debug
Solution/*/bin/Release
```

# Source

[Git ignore sub folders](https://stackoverflow.com/questions/2545602/git-ignore-sub-folders)