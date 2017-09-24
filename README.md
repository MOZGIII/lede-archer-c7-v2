# LEDE

## Description

### Customizations

#### ExtRoot

Mounts are configured by default.
Expected UUIDs for partitions:

 Description | Mountpoint | UUID | Notes
-------------|------------|------|------
ExtRoot overlay | `/overlay` | `05d615b3-bef8-460c-9a23-52db8d09e000`
Local package repo | `/mnt/packages` | `05d615b3-bef8-460c-9a23-52db8d09e001`
Custom user data | `/mnt/data` | `05d615b3-bef8-460c-9a23-52db8d09e002`
Built-in overlay | `/overlay-boot` | - | `/dev/mtdblock3` mountpath instead of UUID
