# Modified DSDT

## Warning!

This DSDT was extracted from my own Aspire E5-473-30N5. If you have a different variant of the Aspire E5, you might want to look into [patching your own DSDT](http://www.tonymacx86.com/el-capitan-laptop-support/152573-guide-patching-laptop-dsdt-ssdts.html).

## Usage

1. Mount EFI partition.
2. Copy `DSDT.aml` to `EFI_ROOT/EFI/CLOVER/ACPI/patched/`.
3. Reboot.

## Modifications
* Enabled brightness control using (graphics\_PNLF\_haswell)[https://github.com/RehabMan/Laptop-DSDT-Patch/blob/master/graphics/graphics\_PNLF\_haswell.txt] by RehabMan.
