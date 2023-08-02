# Command Line Productivity Tools

Simply bash scripts for making life easier.

![bash](https://opensource.com/sites/default/files/lead-images/bash_command_line.png)

You can copy these scripts to your binary executable folder that are already in the PATH environment variable, or put in a new folder and add to the path in
_.zprofile_

---

# sstool

When creating contents or providing snapshot illustrations of a project, screenshots are oftenly used. However, the default screenshot names and directory of output for macOS is often hard to work with. Sstool is a simply script that could help organize these screen shot files.

### Usage

Before, taking your series of screenshots, type the following command.

```
sstool -newset
```

Next

```
sstool -rename
```

This will rename all screenshots to img(n) where n range from 0 to your number of screenshots. This folder will be in the desktop directory

Finally, move the folder to your current directory with

```
sstool -dropin <optional parameter: new name for the folder>
```
