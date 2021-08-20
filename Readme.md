# filecoin-storage-helper

## Status

This repository is in a **frozen** state. Neither this repository, or the referenced repository, are being actively maintained or kept in sync with the tools and libraries they depend on. Even though work on this repository has been **shelved**, anyone interested in updating or maintaining this project should express their interest on one Filecoin community conversation mediums: <https://github.com/filecoin-project/community#join-the-community>.

---

# Function

- Meet the need of the [original RFP](https://github.com/filecoin-project/devgrants/blob/master/rfps/rfp-storage-helper-libraries.md),
  - An open-sourced, dual-licensed (under MIT and APACHE2) library that performs a useful workflow and can be used modularly by other software applications in the Filecoin ecosystem
  - Can be in any language, but we have a preference for Go
  - Documentation of how to use and install this library
  - Sample application (can be extremely simple) that uses both this helper library and go-filecoin to perform the intended workflow
  - Well-documented, human-readable codebase.
- Besides
  - The filecoin storage helper meet any size directory and file upload through the storage helper
  - A large file or directory needs to be split into multiple deals, we'll implement these functions as belows,
    - Deals monitors
    - Callback of deals status and reminder that deadline of the deals
    - Automatically maintain orders after the deadline of the deals reached
  - Metadata encryption

# Repo
[filecoin storage helper](https://github.com/arsyun/filecoin-storage-helper)
