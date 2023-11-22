**Readme File: Installing Guest OS on Oracle VirtualBox**

**Objective:**
This guide outlines the step-by-step process of installing a Guest OS (Ubuntu in this case) on Oracle VirtualBox.

**Procedure:**

1. **Install Oracle VirtualBox:**
   - Run the setup wizard after downloading Oracle VirtualBox and the Extension Package.
   - During installation, customize the setup by checking the VirtualBox application and selecting desired features.

2. **Network Interfaces Warning:**
   - If prompted with a warning about network interfaces, click 'Yes' and proceed with the installation.

3. **Complete Installation:**
   - Once the installation is complete, you may be prompted to install driver software. Click 'Install' to proceed.

4. **Import Oracle VM Virtual Extension Pack:**
   - Launch Oracle VirtualBox and import the Oracle VM Virtual Extension Pack.
   - Agree to the VirtualBox License terms to complete the installation.

5. **Import Virtual Machine (Ubuntu OVA):**
   - File -> Import Appliance.
   - Choose the downloaded Ubuntu OVA file from your local directory.

6. **Configure Virtual Machine:**
   - Adjust application settings, such as RAM size, as needed.
   - Click 'Import' to initiate the import of the Virtual Disk Image.

7. **Launching the Virtual Machine:**
   - Once the import is complete, select the imported VM and click 'Start' to launch the virtual machine.

8. **Login to Ubuntu:**
   - After the virtual machine starts, login with the following credentials:
     - Username: hadoop
     - Password: Test1234
