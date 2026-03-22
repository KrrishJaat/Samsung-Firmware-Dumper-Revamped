# Samsung Firmware Dumper

> [!IMPORTANT]
> - From the name **"Samsung Firmware Dumper"**, you might think it fully dumps the firmware, but unfortunately it does not. This tool only extracts the firmware and separates the images from `super.img` (if it exists); otherwise, it extracts `system.img`, `vendor.img`, and `product.img`.
> * The flow of Extraction: `zip → tar.md5 → lz4 → x.img`  → ***to be exact***,`base.zip → AP_*.tar.md5 → [super | system | product | vendor].lz4`
>   where **x ≠ a specific image name** (x is randomly named(i.e. `system`|`product`|`vendor`|`system_dlkm`|`vendor_dlkm`|`boot`|`vendor_boot`|`init_boot`|`dtbo`|)).
> - Make sure the firmware download link can be accessed using `wget`, as this tool **cannot** download from unsupported links.
> - To use this workflow, you will need to fork this repository and run the workflow from your fork.

> [!NOTE]
> - The files uploaded to gofile.io is not permanent, they are temporary. But they're going to be fine for a week but to be honest, the file will stay there as soon as it gets downloaded time to time.

## Where can I find output download links? 🤔

![I hope this illustration helps.](https://github.com/nostalgiceagle/Samsung-Firmware-Dumper/raw/refs/heads/main/assets/illustration.png)
_I hope this illustration helps._

◆ **More improvements will be added to this repository in the future** 😄  
★ **If you find this repository useful, please consider starring it as a token of support**

