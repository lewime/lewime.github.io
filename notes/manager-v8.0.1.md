## v8.0.1

- Fix `vbmeta.img` patching for Samsung `AP.tar` files. This fixes bootloops on devices like Galaxy S10 after flashing updated AP files.
- Properly truncate existing files before writing to prevent corrupted files
- Prevent a possible UI loop when device ran into very low memory
- Switch to use JSDelivr CDN for several files