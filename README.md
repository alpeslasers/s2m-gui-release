## S-2m GUI

Graphical user interface for the **ALPES LASERS S-2m pulsed QCL driver**.

This software allows users to connect to an S-2m driver, configure pulse settings, select the operating mode, monitor device status, and export diagnostic data.

## Download

Download the latest GUI package from the **Releases** section of this repository.

## Basic use

1. Connect the S-2m driver to the PC using the **C-S2m-IN** cable.
2. Power on the S-2m driver.
3. Launch the GUI.
4. Click **Scan** to detect available serial ports.
5. Select the correct port.
6. Enable **Connect**.
7. Configure the required pulse parameters.
8. Click **Apply** to send the settings to the driver.

Use **Store** only when you want to save the current settings in the driver memory.

## Main features

- Serial connection to the S-2m driver
- Pulse period, pulse width and current limit configuration
- Output voltage setting
- Operating mode selection
- Device status display
- JSON status export for diagnostics

## Safety

Read the S-2m user manual before operating the driver.

Important points:

- Do not exceed the electrical limits specified in the manual.
- Do not enable internal and external pulse control at the same time.
- Use the S-2m only with its paired HHL-QCL.
- Check stored settings before powering the system.

## Documentation

Refer to the **S-2m Driver User Manual v1.1.0** for complete installation, operation, safety and troubleshooting information.

## Support

ALPES LASERS SA  
Email: info@alpeslasers.ch  
Website: http://www.alpeslasers.ch
