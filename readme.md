# Install Instructions

1. Ensure Kanata is installed with `cargo install kanata` (assuming cargo is installed)
2. Type `<Win-r>` then `shell:startup` and copy the path that is opened
3. Git clone this repo into that directory, for future examples it will be assumed that the repo is in a directory called `rebind-capslock`
4. In the startup directory (ie the parent directory of the gir repo), create a .bat file and make it something along the lines of

```bat
@echo off
kanata -c "{startup directory}\rebind-capslock\config.kbd"
```

restart your computer or run the newly created .bat file to enable the rebinding
