# LORAWAN GPS tracker based on WLR089 

Firmware is based on https://github.com/MicrochipTech/ATSAMR34_LORAWAN_H3

App at: lorawan_h3_apps\enddevice_demo\sam_r34_xpro\firmware

lorawan_h3_apps/
├───enddevice_demo/
│   └───sam_r34_xpro/
│       └───firmware/
│           ├───enddevice_demo_sam_r34_xpro.X/
│           └───src/



Usage: https://github.com/MicrochipTech/ATSAMR34_LORAWAN_H3


Make sure H3 packages has correct versions:

![Tux, the Linux mascot](/doc/H3_Packages.PNG)

| Package Name | Version used | Description |
| ------------ | ------------ | ----------- |
| [bsp](https://github.com/Microchip-MPLAB-Harmony/bsp) | [v3.10.0](https://github.com/Microchip-MPLAB-Harmony/bsp/tree/v3.10.0) | Board Support Package: Includes templates and configuration data for supported development boards. |
| [core](https://github.com/Microchip-MPLAB-Harmony/core) | [v3.10.0](https://github.com/Microchip-MPLAB-Harmony/core/tree/v3.10.0) | Includes Drivers and Services with simple to use abstractions of peripherals and shared resources. |
| [crypto](https://github.com/Microchip-MPLAB-Harmony/crypto) | [v3.7.1](https://github.com/Microchip-MPLAB-Harmony/crypto/tree/v3.7.1) | Includes Cryptographic Module Library. |
| [cryptoauthlib](https://github.com/MicrochipTech/cryptoauthlib) | [v3.3.2](https://github.com/MicrochipTech/cryptoauthlib/tree/v3.3.2) | Library for interacting with the Crypto Authentication secure elements. |
| [csp](https://github.com/Microchip-MPLAB-Harmony/csp) | [v3.10.0](https://github.com/Microchip-MPLAB-Harmony/csp/tree/v3.10.0) | Chip Support Package: Includes the Peripheral Libraries (PLIBs). |
| [dev_packs](https://github.com/Microchip-MPLAB-Harmony/dev_packs) | [v3.10.0](https://github.com/Microchip-MPLAB-Harmony/dev_packs/tree/v3.10.0) | Describes all peripherals, memory, etc. of supported 32-bit devices. |
| [mhc](https://github.com/Microchip-MPLAB-Harmony/mhc) | [v3.8.1](https://github.com/Microchip-MPLAB-Harmony/mhc/tree/v3.8.1) | Contains the current implementation of the MHC tool. |
| [wolfssl](https://github.com/Microchip-MPLAB-Harmony/wolfssl) | [v4.7.0](https://github.com/Microchip-MPLAB-Harmony/wolfssl/tree/v4.7.0) | TLS/SSL Library implementation. |
