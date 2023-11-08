# intelmetool

### This tool is not made by me
You can find original source code in `https://review.coreboot.org/coreboot` repo under `coreboot/util/intelmetool` path.
I just patched it to make it work with newer versions of Intel platforms (Tiger Lake) so I can use it in my platform security verification script.

What works:
  * Tiger Lake:
    * [x] Added PCI device ID for Tiger Lake
    * [x] Basic stuff works (getting status of Intel ME and BootGuard)
    * [ ] Check for platform and communication changes for this gen. and reflect those changes in code   
