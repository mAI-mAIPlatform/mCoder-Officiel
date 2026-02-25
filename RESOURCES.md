# mCoder Resources

## Icons
The source icon for mCoder is located at `resources/mcoder.svg`.

To fully integrate the branding:
1. Generate `resources/linux/code.png` from `resources/mcoder.svg`.
2. Generate `resources/win32/code.ico` from `resources/mcoder.svg`.
3. Generate `resources/darwin/code.icns` from `resources/mcoder.svg`.
4. Update `product.json` `linuxIconName` to "mcoder" once the binaries are in place.

For now, `linuxIconName` is reverted to "code-oss" to prevent build failures due to missing binary files.
