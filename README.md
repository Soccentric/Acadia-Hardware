# Acadia-Hardware

## 🌟 Welcome to Acadia-Hardware - Open Source Hardware Platform

**Empowering Innovation Through Shared Knowledge**

This repository contains the complete design schematics, Bill of Materials (BOM), and documentation for our Acadia-Hardware platform - a cutting-edge Raspberry Pi CM4/CM5 based hardware solution. We've open-sourced these designs to democratize access to high-quality hardware development, fostering a community of innovators who can build upon our work to create amazing products.

### 🎯 Our Mission
At Soccentric, we believe in the power of open collaboration. By sharing our hardware platforms, we aim to:
- **Accelerate Innovation**: Provide robust, tested hardware templates that developers can use as starting points
- **Reduce Development Costs**: Eliminate the need to reinvent the wheel for common hardware architectures
- **Build Community**: Create a collaborative ecosystem where knowledge and improvements are shared freely
- **Enable Customization**: Allow businesses and individuals to adapt these designs for their specific needs

### 📋 What's Included
- **Complete Schematics**: Full electrical schematics in industry-standard formats
- **Bill of Materials (BOM)**: Comprehensive component lists with sourcing information
- **PCB Layout Files**: Gerber files and PCB design files for manufacturing
- **Design Documentation**: Detailed design decisions, trade-offs, and implementation notes
- **Assembly Guides**: Step-by-step instructions for building and testing
- **Firmware Examples**: Sample code and configurations to get you started

**Author:** Sandesh Ghimire  
**©** Sandesh@soccentric.com

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

## 🚀 Getting Started

### Prerequisites
- PCB fabrication capabilities or access to a PCB manufacturer
- Basic electronics assembly tools and equipment
- Raspberry Pi CM4/CM5 module
- Access to components listed in the BOM

### Quick Start
1. **Review the Schematics**: Start with the main board schematic in the `schematics/` directory
2. **Check the BOM**: Verify component availability and order parts from `bom/bom.csv`
3. **Fabricate PCB**: Use the Gerber files in `pcb/` for manufacturing
4. **Assemble**: Follow the assembly guide in `docs/assembly.md`
5. **Test**: Use the test procedures in `docs/testing.md`

### Development Environment
- **OS**: Raspberry Pi OS or Ubuntu Linux
- **Tools**: KiCad for schematic review, Python for automation scripts
- **SDK**: Raspberry Pi official tools and documentation

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Ways to Contribute
- **Bug Reports**: Found an issue? Let us know in the Issues section
- **Feature Requests**: Have ideas for improvements? Share them!
- **Pull Requests**: Submit your enhancements directly
- **Documentation**: Help improve guides and documentation
- **Testing**: Test designs and share your results

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Guidelines
- Follow the existing code style and naming conventions
- Update documentation for any new features
- Test your changes thoroughly
- Respect the license terms

## 📄 License

This project is licensed under the CERN Open Hardware Licence Version 2 - Permissive. See the [LICENSE](LICENSE) file for details.

The CERN OHL v2 - Permissive allows you to:
- Use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
- Manufacture and distribute hardware based on these designs
- Create derivative works

## 📞 Support & Community

- **Issues**: [GitHub Issues](https://github.com/soccentric/Acadia-Hardware/issues)
- **Discussions**: [GitHub Discussions](https://github.com/soccentric/Acadia-Hardware/discussions)
- **Documentation**: [Wiki](https://github.com/soccentric/Acadia-Hardware/wiki)
- **Email**: For business inquiries, contact hardware@soccentric.com

## 🙏 Acknowledgments

- Raspberry Pi Foundation for the incredible CM4/CM5 modules
- Our amazing community of contributors and users
- The open source hardware movement for inspiring this initiative

---

**Built with ❤️ by Soccentric - Empowering Hardware Innovation**