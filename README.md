# comms-2026-docs
The 2026 Communications Subsystem Documentation

This repository contains all of the information for the Fall 2026 - Spring 2027 BUMRC. This has information imported from the previous year, Spring 2026.

If you are working on the system or need to view metrics, see [network-info.md](/network-info.md) for information on how the system is configured.

The current firmware is located in the [/firmware](/firmware) folder in this repository for both the base station and rover equipment.

## Components

<table>
  <tr>
    <td valign="middle">
        System Component
    </td>
    <td valign="middle">
        Manufacturer Component
    </td>
    <td valign="middle">
        Description
    </td>
    <td valign="middle">
        Documentation 
    </td>
    <td valign="middle">
        Firmware Version
    </td>
  </tr>
  <tr>
    <td valign="middle">
        Base Station Transceiver
    </td>
    <td valign="middle">
        Ubiquiti Rocket M2
    </td>
    <td valign="middle">
        2.4GHz Radio Transmitter and Receiver
    </td>
    <td valign="middle">
        <a href="/datasheets/rocket-m2/rocket-m2-device.pdf">datasheet</a> <br> 
        <a href="/datasheets/rocket-m2/rocket-m2-firmware.pdf">software guide</a> <br> 
        <a href="/datasheets/rocket-m2/rocket-m2-start.pdf">quick start</a>
    </td>
    <td valign="middle>
        <a href="/datasheets/rocket-m2/firmware">airOS V6.3.22</a>
    </a>
  </tr>
  <tr>
    <td valign="middle">
        Base Station Antenna
    </td>
    <td valign="middle">
        Ubiquiti am-2g15-120
    </td>
    <td valign="middle">
        airMAX 2.4 GHz, 15 dBi, 120º Sector Antenna
    </td>
    <td valign="middle">
        <a href="https://store.ui.com/us/en/products/am-2g15-120">eStore</a> <br>
        <a href="/datasheets/antenna/rocket-m2-antenna.pdf">datasheet</a>
    </td>
    <td valign="middle>
        N/A
    </a>
  </tr>
  <tr>
    <td valign="middle">
        Rover Transceiver
    </td>
    <td valign="middle">
        Ubiquiti Bullet IP67
    </td>
    <td valign="middle">
        dual-band WiFi radio
    </td>
    <td valign="middle">
        <a href="/datasheets/bullet-ip67/bullet-ip67-device.pdf">datasheet</a> <br> 
        <a href="/datasheets/bullet-ip67/bullet-ip67-firmware.pdf">software guide</a> <br>
        <a href="/datasheets/bullet-ip67/bullet-ip67-start.pdf">quick start</a>
    </td>
    <td valign="middle>
        <a href="/datasheets/bullet-ip67/firmware">airOS V8.7.19</a>
    </a>
  </tr>
  <tr>
    <td valign="middle">
        Rover Antenna
    </td>
    <td valign="middle">
        Generic Antenna, but similar to L-com HyperGain HGV-2409U
    </td>
    <td valign="middle">
        2.4 GHz, 8 dBi, integral N-female Antenna
    </td>
    <td valign="middle">
        <a href="https://www.l-com.com/wireless-antenna-24-ghz-8-dbi-omnidirectional-antenna-n-female-connector">eStore</a> <br>
        <a href="/datasheets/antenna/bullet-ip67-antenna.pdf">datasheet</a>
    </td>
    <td valign="middle>
        N/A
    </a>
  </tr>
</table>
