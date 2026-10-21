# Wiper

A clean, dark-mode Windows app for clearing USB drives in batches.

- USB drives appear automatically when connected.
- Select individual volumes or select all, with no application-imposed batch limit.
- **Wipe files** deletes files and folders while keeping the existing file system.
- **Format drives** quick-formats to exFAT, NTFS, or FAT32, using one format for the batch or a different format for each volume.
- Review the selected drives and type `ERASE` before starting. Each volume shows its own result.

## Download

Download **Wiper.exe** from [Releases](https://github.com/brendanwang/Wiper/releases/latest). Run it on Windows 10 or 11 (64-bit) and approve the administrator prompt. No installer or separate .NET installation is required.

**Erasing is destructive. Back up anything you need first.** File deletion and quick formatting do not securely overwrite data.

Only mounted, writable USB volumes with drive letters are shown. Internal and Windows boot/system disks are excluded. Multi-partition drives appear as separate volumes.

This repository distributes the application only. Source code is not included.
