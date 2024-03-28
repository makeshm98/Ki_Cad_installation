# Ki_Cad_installation
Installation procedures of KiCAD

# KiCad Installation Instructions

These instructions will guide you through the process of installing KiCad on Ubuntu using the provided commands.

## Prerequisites

- You need to have sudo privileges on your Ubuntu system to execute the installation commands.
- Ensure that your Ubuntu system is connected to the internet to download and install KiCad packages.

## Installation Steps

1. **Add KiCad PPA Repository**:
   ```bash
   sudo add-apt-repository --yes ppa:kicad/kicad-8.0-releases
2. **Update Package Index**:
   ```bash
   sudo apt update
3. **Install KiCAD**:
   ```bash
   sudo apt install --install-recommends kicad
4. **Verification**:
   Once the installation is complete, you can verify that KiCad has been installed successfully by launching the application. You can do this by searching for "KiCad" in the application menu or by running the following command in the terminal:
   ```bash
   kicad
# KiCad Nightly Development Builds Installation Instructions

Nightly development builds are snapshots of the development (master branch) codebase at a specific time. These builds contain the latest features and improvements but may also have more bugs than stable releases. They are suitable for testing new features and providing feedback to the KiCad development team.

## Prerequisites

- You need to have sudo privileges on your Ubuntu system to execute the installation commands.
- Ensure that your Ubuntu system is connected to the internet to download and install KiCad packages.

## Installation Steps

### Using Ubuntu Software Manager

1. Open the Software Manager.

2. Select 'Edit' → 'Software Sources…'.

3. Open the 'Other Software' tab.

4. Click 'Add…', and enter the PPA address: ppa:kicad/kicad-dev-nightly and then click the 'Add Source' button.

5. When prompted, insert the administrator user password.

6. Return to the Software Manager and view the Progress tab to see when the cache has finished updating.

7. Return to the Software Manager main screen, search for 'kicad-nightly', and install it.

### Using Terminal

1. **Add Nightly PPA Repository**:
   ```bash
   sudo add-apt-repository --yes ppa:kicad/kicad-dev-nightly
