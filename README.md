# comms-2026-docs
The 2026 Communications Subteam Documentation

This repository contains all of the Communications Subteam information for the Fall 2026 - Spring 2027 year.

If you are working on the system or need to view metrics, see <a href="#Network-Information">Network-Information</a> below for information on how the system is configured.

To access the system components with their datasheets, current firmware versions, and guides all linked, see <a href="#Components">Components</a> below.

## Components

<table>
  <tr>
    <td valign="middle">
        System Component
    </td>
    <td valign="middle">
        Device Name
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
    <td valign="middle">
        airOS <a href="/datasheets/rocket-m2/firmware">V6.3.22</a>
    </td>
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
    <td valign="middle">
        N/A
    </td>
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
    <td valign="middle">
        airOS <a href="/datasheets/bullet-ip67/firmware">V8.7.19</a>
    </td>
  </tr>
  <tr>
    <td valign="middle">
        Rover Antenna
    </td>
    <td valign="middle">
        <b>NOT SURE WHAT ANTENNA EXACTLY WE HAVE</b>, but seems similar to L-com HyperGain HGV-2409U
    </td>
    <td valign="middle">
        2.4 GHz, 8 dBi, integral N-female Antenna
    </td>
    <td valign="middle">
        <a href="https://www.l-com.com/wireless-antenna-24-ghz-8-dbi-omnidirectional-antenna-n-female-connector">eStore</a> <br>
        <a href="/datasheets/antenna/bullet-ip67-antenna.pdf">datasheet</a>
    </td>
    <td valign="middle">
        N/A
    </td>
  </tr>
</table>

## Network-Information

This file has the most up to date information on how the system is networked. It also includes the hostnames, passwords, and information on getting your laptop/pc connected to t>

1) Subnet Mask - 255.255.255.0
2) Gateway - 192.168.1.1
3) Rocket (base station) - 192.168.1.20
4) Bullet (antenna) - 192.168.1.21

To connect to the system on a laptop, tether to either the bullet or the rocket via ethernet, then configure your ethernet connection to be static using the above Subnet Mask an>
