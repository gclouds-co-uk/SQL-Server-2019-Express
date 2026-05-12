---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# layout: page  # Tells Jekyll to use the default page layout
# title: SQL Server 2019 Express on Windows Server 2019 Datacenter Quick Start Guide
# SQL Server 2019 Express on Windows Server 2019 Datacenter
layout: page
title: Release Notes
permalink: /release-notes
order: 3
---
# Release Notes: SQL Server 2019 Express Edition

# Version SQL2019EXP-2026H2

## Key Changes and Updates

### 1. Windows OS Update
- **Base Image Update**: The Windows Server 2022 Datacenter base image has been updated to v20260429, including the latest security patches.

### 2. Security Enhancements
- **Fixed Common Vulnerabilities and Exposures (CVEs)**: 
  - CVE-2026-33824: Mitigated via latest OS security patches.
  - General vulnerabilities addressed through standard OS patching.


*February 12, 2026*

## Deployed Version

- Package: SQL2019EXP-2026Q1

## Major Updates

### Updates

- Integrated February 2026 Windows Server OS updates for enhanced security and stability.
- SQL Server 2019 Express remains at Cumulative Update 32 (CU32) - KB5054833.

### Security

- This release mitigates the following critical security vulnerabilities:
  - **CVE-2024-55414** (Motorola SM56 Driver)
  - **CVE-2025-6965** (SQLite/winsqlite3.dll)

---

# Release Notes: SQL Server 2019 Express Edition

*November 18, 2025*

## Deployed Version

- Package: SQL2019EXP-2025Q4

## Major Updates

### Updates

- SQL Server 2019 Express updated to Cumulative Update 32 (CU32) - KB5054833
- SQL Server Management Studio (SSMS) updated to version 20.1
- Integrated November 2025 Windows Server OS updates

### Security

- This release addresses the following CVEs:
  - CVE-2016-9535
  - CVE-2025-49708
  - CVE-2025-53766
  - CVE-2025-55234
  - CVE-2025-59287

## Product Infrastructure

### Port Requirements

- TCP port 1433 (SQL Server)
- UDP port 1434 (SQL Browser)
- TCP port 3389 (RDP)

### System Requirements

- vCPUs: 4 (minimum)
- Memory: 16GB RAM
- Storage: 80GB

## Known Issues

No known issues at time of release.

## Support

For technical support, contact gClouds Support Concierge:

- [Support Portal](https://www.gclouds.co.uk/support)
- [Documentation](./index)

## Resource Links

- [Product Page](./index)
- [Quick Start Guide](./quickstart-guide)
- [EULA](./EULA)

# Release Notes: SQL Server 2019 Express Edition

*July 18, 2025*

## Deployed Version

- Package: SQL2019EXP-2025H2

## Major Updates

### Updates

- SQL Server 2019 Express updated to Cumulative Update 32 (CU32)
- Integrated 18 July 2025 Windows Server OS updates

## Product Infrastructure

### Port Requirements

- TCP port 1433 (SQL Server)
- UDP port 1434 (SQL Browser)
- TCP port 3389 (RDP)

### System Requirements

- vCPUs: 2 (minimum)
- Memory: 8GB RAM
- Storage: 80GB

## Known Issues

No known issues at time of release.

## Support

For technical support, contact gClouds Support Concierge:

- [Support Portal](https://www.gclouds.co.uk/support)
- [Documentation](./index)

## Resource Links

- [Product Page](./index)
- [Quick Start Guide](./quickstart-guide)
- [EULA](./EULA)
