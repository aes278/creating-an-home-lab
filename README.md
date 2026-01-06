# creating-a-virtual-home-lab
# Creating a Virtual Home Lab: Windows 11 & Windows Server 2022 on Apple Silicon (M1/M2/M3/M4)

## Description

This project documents a comprehensive, step-by-step guide for setting up a virtualized lab environment on Apple Silicon (M1/M2/M3/M4) chips using **UTM** virtualization software. It covers the distinct processes for virtualizing **Windows 11 ARM64** and emulating **Windows Server 2022 x64**, highlighting the architectural differences and specific configurations required for a successful setup.

**Key motivations for this project included:**

*   Providing a practical, accessible guide for leveraging powerful Apple Silicon hardware for diverse OS testing environments.
*   Understanding the nuances between hardware virtualization (Windows 11 on ARM64) and software emulation (Windows Server 2022 x64) on a non-native architecture.
*   Demonstrating proficiency in setting up and configuring virtual machines (VMs) for a functional home lab, a crucial skill in IT infrastructure and development.

## Technologies Used

**Category	                              Technology	                          Version / Architecture**
**Host Hardware**	                          Mac	                                   M1/M2/M3/M4 Chip
**Virtualization Software**	         UTM (based on QEMU)	                  Latest version (from mac.getutm.app) 
**Guest OS (Virtualization)**	       Windows 11	                                   ARM64 ISO 
**Guest OS (Emulation)**	           Windows Server 2022	                           x64 ISO 
**Drivers**	                         SPICE Guest Tools	                                N/A
