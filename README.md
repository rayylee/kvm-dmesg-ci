# kvm-dmesg-ci

`kvm-dmesg-ci` is a continuous integration (CI) testing repository designed to test the [kvm-dmesg](https://github.com/rayylee/kvm-dmesg-ci) tool with different kernel versions. It contains a collection of kernel images (vmlinuz) and corresponding System.map files for various kernel versions.

## Purpose
This repository is intended to provide a controlled environment for testing `kvm-dmesg` with a variety of kernel versions. It helps ensure that the tool works correctly with different kernel releases, both for debugging and performance validation.


Each kernel version is stored in its respective directory, containing:

- `vmlinuz-*` - The kernel image.
- `System.map-*` - The corresponding symbol map for that kernel version.
