# UAPI Group Generic Documents and Meeting Minutes

This repo contains generic, org-wide documents like meeting minutes.

## Glossary

This section clarifies on terms and abbreviations used in specs and other documents throughout the organisation.

### General Terms and Abbreviations
- *MOK* - Machine Owner Key (shim)
- *PCR* – TPM Platform Configuration Registers
- *TPM* – Trusted Platform Module (security chip)
- *SBAT* – UEFI Secure Boot Advanced Targeting

### Terms and Abbreviations specific to UAPI Group Specifications
- *DDI*[1] - Discoverable Disk Image
- *DPS*[1] - Discovery Partition Specification
- *UKI*[1] - Unified Kernel Images (sd-stub + kernel + initrd + more)
- *BLS*[1] - Boot Loader Specification
- *sysext*[1] – System Extension Image (type of DDI that is overlayed on top of `/usr/` and `/opt/` via overlayfs and can extend the underlying OS vendor resources in a composable, immutable fashion)
- *syscfg*[1] – System Configuration Image (type of DDI that is overlayed on top of `/etc/` via overlayfs and can extend the underlying OS' configuration in a composable, immutable fashion)

[1] *TODO* add reference to spec as soon as it's up at https://github.com/uapi-group/specifications.

## Minutes and Summaries

Listed below are references to the latest UAPI group meeting / conference summaries and minutes.

* [Summary](docs/minutes/2022-10-05__image-based-linux-summit) of the first Image-Based Linux Summit, October 4th / 5th in Berlin

See the [minutes](https://github.com/uapi-group/docs/tree/main/minutes) folder in the source repository for a full list of documents.