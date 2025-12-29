# NetBox Templates Index

This repository contains a curated collection of **NetBox YAML templates** for device types, devices, and supporting objects.  
It is intended for **learning, reference, and personal infrastructure documentation**.

## The collection is made up of: 
- Items I have made personally because I couldn't find them elsewhere
- Items found elsewhere and modified to fit my use
- Items found elsewhere and bundled into here for my own convenience, without modification. Credit is in YAML comments and below.

For a far more comprehensive and universal list see https://github.com/netbox-community/devicetype-library/
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
Contains reference images of device types used for documentation. Sourced and/or modified from public online material.

- hp-elite-desk-4g-mini.png, modified from https://github.com/netbox-community/devicetype-library/blob/master/elevation-images/HP/hp-elitedesk-800-g5-mini.front.png
- 4cabling-brushpanel-1ru.png, modified from https://cdn11.bigcommerce.com/s-wy5fyeqebr/images/stencil/1280x1280/products/177/516/RAK213-00__95416.1705320559.jpg?c=1


---

### `device_types/`
Defines NetBox **device type templates**, grouped by vendor.

#### `device_types/HPE Aruba/`

hpe-aruba-device_types.yaml
- Aruba2530-8G-PoEP, sourced from https://gitlab.software.geant.org/goat/netbox-device-type/-/blob/master/device-types/HPE/Aruba-2530-8G-PoEP.yaml?ref_type=heads

#### `device_types/FortiNet/`

fortinet-device_types.yaml
- FortiGate-30E

#### `device_types/CableMgmt&PatchPanels/`

brush-panel.yaml
- 19" Brush Panel 1RU, image from https://cdn11.bigcommerce.com/s-wy5fyeqebr/images/stencil/1280x1280/products/177/516/RAK213-00__95416.1705320559.jpg?c=1

fibre-copper-combo-patch-panel-1ru.yaml
- Image sourced and modified from Tripp Lite Patch Panels Visio Stencils https://tripplite.eaton.com/support/visio-

leviton-1ru-cable-management.yaml
- Image sourced and modified from Leviton Visio diagrams https://espreview.leviton.com/support/resources/product-
