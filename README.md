# Windows 365 Cloud PC Reference Architecture

A conceptual reference architecture for deploying Windows 365 Cloud PCs in an enterprise environment.

## Overview

This repository contains a comprehensive reference design document for Windows 365 Cloud PC deployments. The architecture guide, authored by Microsoft MVP Kevin Kaminski, provides IT professionals and architects with the technical guidance needed to plan and implement a successful Cloud PC environment.

**[Download the Reference Architecture (PDF)](W365Design1.0-Signed.pdf)**

A full-color hardcover edition of this document is also available at [Lulu.com](https://www.lulu.com/shop/kevin-kaminski/windows-365-cloud-pc-deployment-conceptual-architecture/hardcover/product-2m85w9r.html).

## What's Included

The reference architecture document (98 pages) covers:

### Design Principles
- **Cloud-Native Identity** - Entra ID (Azure AD) join with no on-premises dependencies
- **Automated Provisioning** - Windows 365 Provisioning Policies based on user group membership
- **Unified Management** - Microsoft Intune for configuration, application delivery, and security
- **Zero Trust Security** - Conditional Access policies and device compliance enforcement

### Key Topics

| Section | Description |
|---------|-------------|
| User Personas | Information Worker persona with technical requirements |
| Cloud & Identity | Entra ID integration, user/device identity, access security |
| Provisioning | Cloud PC specifications, gallery images, automated deployment |
| Management | Intune as the management authority, policy enforcement |
| Security & Access | Device hardening, security baselines, least privilege |
| Monitoring | Built-in reports, Azure Monitor integration |
| Application Management | Modern app delivery, Win32 packaging, Company Portal |
| Servicing | Windows Autopatch, Microsoft 365 Apps updates, Edge servicing |

### Application Stack

The reference design includes a baseline application configuration:
- **Microsoft 365 Apps** - Word, Excel, PowerPoint, Outlook, Teams
- **Microsoft Edge** - Enterprise browser with SSO and security policies
- **7-Zip** - File compression utility
- **Company Portal** - Self-service application store
- **Remote Help** - Zero Trust IT support solution
- **VLC (UWP)** - Optional media player

## Source Files

The `Source` folder contains the editable source materials for this document:

- **W365Design1.0.docx** - The Microsoft Word document used to build the PDF
- **Graphics/** - Subfolder containing the diagram and illustration image files used throughout the document

## Target Audience

- IT Professionals and System Administrators
- Cloud Architects and Solution Designers
- Technical Managers planning Windows 365 deployments

## How to Use

1. Review the PDF document to understand the design principles and architecture decisions
2. Adapt the reference design to your organisation's specific requirements
3. Use the technical recommendations as a foundation for your Windows 365 pilot deployment

## Attribution

This reference architecture was developed by **Kevin Kaminski** (Microsoft MVP)
Big Hat Group Inc. - [https://www.bighatgroup.com](https://www.bighatgroup.com)

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](LICENSE.md). You are free to share and adapt this content for any purpose, including commercial use, with appropriate attribution.

Attribution example:
> "Based on work by Kevin Kaminski (kevin.kaminski@bighatgroup.com), https://www.bighatgroup.com, licensed under CC BY 4.0."
