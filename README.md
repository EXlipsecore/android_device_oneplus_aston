# OnePlus 12R (aston)

Device tree for the **OnePlus 12R** — used to build Infinity-X 17.

| | |
|---|---|
| SoC | Qualcomm Snapdragon 8 Gen 2 (SM8550) |
| Models | CPH2585 (global / India), CPH2611 (North America) |
| Codename | `aston` |
| Firmware base | CPH2585_16.0.3.400 |
| Branch | `17` |

Branch **`17`** = the Android 17 build tree (this is what the ROM builds against).
The plain LineageOS-24 counterpart of each repo is available upstream.

Shared bits: [sm8550-common](https://github.com/EXlipsecore/android_device_oneplus_sm8550-common) ·
Blobs: [gitlab](https://gitlab.com/EXlipsecore/proprietary_vendor_oneplus_aston)

```bash
lunch infinity_aston-user && m bacon -j$(nproc --all)
```
