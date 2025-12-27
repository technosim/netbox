# NetBox Templates Index

This repository contains a curated collection of **NetBox YAML templates** for device types, devices, and supporting objects.  
It is intended for **learning, reference, and personal infrastructure documentation**.

---

## Overview

The templates in this repository cover common NetBox object types used to model network infrastructure, including:

- Device types and interface templates
- Platforms, manufacturers, and device roles
- Device definitions
- Reference images for documentation

The YAML files are designed to be used with NetBox automation tools such as:
- Ansible NetBox modules
- pynetbox
- netbox-importer
- Custom scripts

---

## Sources and Attribution

- YAML templates are a mix of:
  - **My own templates**
  - **Templates adapted from other public examples**
- Device images are **sourced from online searches** and are **not my own work**.
- Images are included for **documentation and reference purposes only**.

This repository is not intended for commercial redistribution.

---

## Repository Structure

### `images/`
Contains reference images of device types used for documentation.

- Images are **not imported into NetBox**
- Used for GitHub Pages or Markdown documentation
- Sourced from public online material

---

### `device_types/`
Defines NetBox **device type templates**, grouped by vendor.

#### `device_types/HPE Aruba/`

hpe-aruba_devices.yaml
- Aruba2530-8G-PoEP

#### `device_types/FortiNet/`

fortinet_devices.yaml
- FortiGate-30E

