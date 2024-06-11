# Embedded-imx-Yocto
This repository contains a custom-built operating system for the iMX platform, developed using the Yocto Project. It includes all necessary components and configurations for deploying a robust and efficient embedded system. Ideal for applications in medical industry.
# Yocto Project for i.MX8M Mini EVK

This explaination provides detailed steps to build a custom image for the i.MX8M Mini EVK using the Yocto Project.

## Prerequisites

- A Linux host machine (Ubuntu 18.04 or later recommended)
- Git installed on your system
- Sufficient disk space (at least 100GB recommended)

## Setting Up the Yocto Project Environment

1. **Clone the Poky Repository:**
   ```sh
   git clone -b dunfell git://git.yoctoproject.org/poky.git
   cd poky
