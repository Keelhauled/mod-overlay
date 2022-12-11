# mod-overlay
A simple linux mod manager using fuse-[overlayfs](https://docs.kernel.org/filesystems/overlayfs.html)

### Usage
- Get fuse-overlayfs and python
- Place mods in some folder like this
    ```
    mods
    ├── mod1
    │   ├── modfiles
    ├── mod2
    │   ├── modfiles
    ```
- Run `mod-overlay PATH_TO_MODS_FOLDER PATH_TO_WHERE_GAME_EXPECTS_MODS_TO_BE`
