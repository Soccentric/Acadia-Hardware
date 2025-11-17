# Acadia-Hardware

## Overview
Raspberry Pi CM4/CM5 based hardware platform designed for embedded computing applications. These compact System-on-Modules (SoMs) integrate powerful processing capabilities with extensive I/O options, making them ideal for industrial, IoT, and edge computing solutions.

## Key Specifications
- **Processor**: Broadcom BCM2711 (CM4) or BCM2712 (CM5) quad-core 64-bit Arm Cortex-A72/A76 @ 1.5GHz/2.4GHz
- **Memory**: Up to 8GB/16GB LPDDR4-3200/4267 SDRAM with ECC support
- **Storage**: Up to 32GB/64GB eMMC flash memory
- **Wireless**: 2.4/5.0 GHz IEEE 802.11 b/g/n/ac wireless, Bluetooth 5.0, BLE
- **Video**: 4Kp60 HEVC decoder, OpenGL ES 3.1, Vulkan 1.3
- **Operating Temperature**: -20°C to +85°C (standard), -40°C to +85°C (extended for CM4)

## Interfaces and Connectivity
All platforms have:
1. **Camera Interface**: 2x 4-lane MIPI CSI-2 ports supporting camera sensors
2. **Display Interface**: 2x HDMI 2.0 ports (up to 4Kp60), 2x 4-lane MIPI DSI ports
3. **USB**: 2x USB 2.0 ports, 2x USB 3.0 ports (5Gbps simultaneous operation)
4. **UART**: Up to 5x UART interfaces
5. **I2C**: Up to 5x I2C interfaces
6. **SPI**: Up to 5x SPI interfaces
7. **SDIO**: 1x SDIO 2.0 interface, 1x SDIO for CM5 Lite
8. **PWM**: Up to 4x PWM channels
9. **I2S**: 1x I2S interface
10. **PCIe**: 1x PCIe x1 Gen 2 (5Gbps) root complex
11. **Ethernet**: Gigabit Ethernet PHY supporting IEEE 1588
12. **GPIO**: Up to 30x GPIO pins (1.8V or 3.3V signaling)
13. **DPI**: 1x parallel RGB display interface

## Capabilities
- **Video Processing**: Hardware-accelerated 4Kp60 HEVC/H.264 decoding and encoding
- **Graphics**: Advanced 3D graphics with OpenGL ES and Vulkan support
- **Real-time Processing**: Low-latency GPIO and peripheral control
- **Industrial Automation**: Robust operation in harsh environments with extended temperature ranges
- **Edge Computing**: Efficient processing for IoT and embedded applications
- **Multimedia**: Support for high-resolution displays and camera inputs
- **Networking**: Gigabit Ethernet with PTP support for synchronized systems

## Supported Operating Systems
- Raspberry Pi OS (Linux-based)
- Various Linux distributions
- Real-time operating systems

## Applications
- Industrial automation and control systems
- Digital signage and kiosks
- Robotics and autonomous systems
- IoT gateways and edge devices
- Medical devices and equipment
- Transportation and automotive systems
- Smart cameras and vision systems

## Additional Features
- **Power Management**: Advanced power control for energy-efficient operation
- **Security**: Hardware-based security features and secure boot
- **Development Tools**: Comprehensive SDK and development kits
- **Community Support**: Large developer community and extensive documentation
- **Long-term Availability**: Extended product lifecycle support