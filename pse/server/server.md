---
theme: gaia
_class: lead
marp: true
style: |
    table {
        font-size: 28px
    }
---

<style>

h1 {
    font-size: 48px
}

ul > li {
    font-size: 28px
}

p {
    font-size: 28px
}

</style>

<!-- color: #000 -->

![bg right 120%](server_thumbnail.jpg)


# Dell PowerEdge 2850

Tomáš Pelák, Patrik Kulhavý, Michal Pařízek

---

# Schema

<style scoped> 
 img {
     height: 600px;
     width: 900px;
     display: table;
     margin: 0 auto;
 }
</style>

![](schema_2.jpg)

---

# Backside Schema

<style scoped> 
 img {
     height: 500px;
     width: 900px;
     display: table;
     margin: 0 auto;
 }
</style>

![](schema_3.webp)

---

# System id Button

* If the system stops responding during POST, press and hold the system ID button for more than five seconds to enter BIOS progress mode.

* To reset the iDRAC (if not disabled in F2 iDRAC setup) press and hold the button for more than 15 seconds.

---

# DRAC

The Dell Remote Access Controller or DRAC is an out-of-band management platform on certain Dell servers. The platform may be provided on a separate expansion card, or integrated into the main board; when integrated, the platform is referred to as iDRAC.

![bg right](drac.jpg)

---

# Chipset Schema

<style scoped> 
 img {
     width: 45%;
     display: table;
     margin: 0 auto;
 }
</style>

![](schema_3.gif)

---


# FEATURES

| FEATURES | Dell™ PowerEdge™ 2850 Server |
|----------|:-------------:|
| Form factor |  2U rack height |
| Processors |Up to two single-core 64-bit Intel® Xeon™ processors at up to 3.8GHz or up to two dual-core 64-bit Intel Xeon processors at 2.8GHz |
| Front side bus |  800MHz |
| Cache | Up to 2MB L2 per processor core |

---

| FEATURES | Dell™ PowerEdge™ 2850 Server |
|----------|:-------------:|
| Chipset | Intel E7520 |
| Memory | 256MB/12GB DDR-2 400 SDRAM; 16GB with availability of dual rank 4GB DIMMs2 |
| I/O channels | Three total: three PCI-X® slots (64-bit/133MHz) or two PCI Express™ slots (1 x 4 lane and 1 x 8 lane) and one PCI-X slot (64-bit/100MHz)|
| Drive controller | Embedded dual channel Ultra320 SCSI; internal and external routing |
| RAID controller |Optional dual channel ROMB (PERC 4e/Di), PERC 4/DC and PERC 4e/Dc adapters |

---

| FEATURES | Dell™ PowerEdge™ 2850 Server |
|----------|:-------------:|
| Drive bays | Six 1" Ultra320 hot-plug SCSI drives or five drive bays and one tape drive bay |
| Maximum internal storage | Up to 1.8TB with 300GB HDD |
| Hard drives | 3 36GB, 73GB, 146GB and 300GB (10,000 rpm) Ultra320 SCSI 18GB, 36GB, 73GB and 146GB (15,000 rpm) Ultra320 SCSI |
| Internal storage | 10K/15K RPM SCSI drives |

---

| FEATURES | Dell™ PowerEdge™ 2850 Server |
|----------|:-------------:|
| External storage | Dell PowerVault™ SCSI and Dell/EMC fibre channel storage |
| Tape backup options | Internal: PowerVault 110T External: PowerVault 114T, 124T, 132T and 136T |
| Network interface card | Dual embedded Intel Gigabit4 NICs; single and dual port Intel PRO/1000 MT Gigabit adapters, Intel PRO/1000 MF (optical) |

---

| FEATURES | Dell™ PowerEdge™ 2850 Server |
|----------|:-------------:|
| Power supply | 700W, optional hot-plug redundant power |
| Availability | ECC memory; Single Device Data Correction (SDDC); Spare Bank; Memory Mirroring; hot-plug SCSI hard drives; optional hot-plug redundant power; hot-plug redundant cooling; tool-less chassis; high availability fibre channel and SCSI cluster support; optional ROMB with battery-backed cache; optional Split Backplane optional PERC RAID controller |

---

| FEATURES | Dell™ PowerEdge™ 2850 Server |
|----------|:-------------:|
| Video | Embedded ATI Radeon 7000-M with 16MB SDRAM |
| Remote management | Baseboard Management Controller with IPMI 1.5 compliance, accessible via network or serial port; optional slot-free DRAC 4/I |
| Systems management | Dell OpenManage™ |
| Rack support | 4-post (Dell rack), 2-post and 3rd party; Cable Management Arm |

---

| FEATURES | Dell™ PowerEdge™ 2850 Server |
|----------|:-------------:|
| Operating systems | Microsoft® Windows Server™ 2003, Standard x64 Edition; Microsoft Windows Server 2003, Enterprise x64 Edition; Microsoft Windows Server 2003, Standard Edition; Microsoft Windows Server 2003, Enterprise Edition; Red Hat® Linux® Enterprise v2.1; Red Hat Linux Enterprise v3; Red Hat Linux Enterprise v3 Advanced Server EM64T; Novell® NetWare® 5.1 and 6.5 |

---

# Pohled ze předu

![bg 100%](server_front.png)

---

<style scoped>

img {
    display: table;
    margin: 0 auto;
    height: 370px
}

</style>

# Power Button LCD Control panel

- Provides system ID, status information, and system error messages.
- The LCD display lights during normal system operation.
- The LCD display lights amber when the system needs attention 

![](lcd.jpg)

---

# HDDS

![bg left 80%](hdd.jpg)


- Model BF03688284
- Application Server Storage
- Interface Ultra320 SCSI
- Server Type HP/Compaq Proliant
- Data Transfer Rate 320 MB/s
- Capacity 36.4 GB
- Speed 15k rpm

---

# HDDS

![bg right 80%](hdds.jpg)

- Form factor 3.5 inches
- Height 1.0 inch/2.54 cm
- Width 4.0 inch/10.16 cm
- Seek Time	Single Track 0.55ms
- Seek Time	Average 4.9ms
- Seek Time	Full Stroke 10.0ms
- Bytes/Sector 512

---

![bg 150% left](processor_with_passive_cooling.jpg)

# Processor

2 * 3.8GHz 2MB 800MHz Intel Xeon CPU Processor SL7ZB

- Socket Type: 604
- Cores: 1
- Instruction Set: 64 bit
- CPU Speed: 3.8 GHz
- Bus Speed: 800 MHz
- Bus/Core Ratio: 19

---

# Processor

![bg 140% left](processor_detail.jpg)

- L2 Cache Size: 2 MB
- L2 Cache Speed: 3.8 GHz
- Package Type: Micro-FCPGA
- Manufacturing Technology: 90 nm
- Thermal Design Power: 110W
- Thermal Specification: 72 C
- VID Voltage Range: 1.2875V-1.3875V
- Number of dies: 169Milions
- ECC: not supported

---

# Compatible Systems

- Dell PowerEdge 1800 Server
- Dell PowerEdge 1850 Server
- Dell PowerEdge 1855 Server
- Dell PowerEdge 2850 Server
- Dell PowerEdge 2800 Server
- Dell PowerEdge SC1420 Server
- Dell PowerEdge SC1425 Server
- Dell Precision 670 Workstation
- Dell Precision 470 Workstation

![bg right](processor.jpg)

---

# Ram Ddr2-Pc3200

- RAM Technology DDR2 SDRAM
- Memory Storage Capacit 4 GB
- Memory Speed 400 MHz
- 240PIN DDR2 DIMM
- ECC Not Supported
- PC2-5300 

![bg left](server_internal_2.jpg)

---

# Power suply

- Dell ATSN Model 7000814-0000 Power Supply.
- 700W, optional hot-plug redundant power.

Input
 - 100 - 240V~
 - 50 / 60 Hz

Output 
 - 57.3A

 ![bg left](power_suply_2.jpg)

---

<style scoped>
img {
    height: 400px
}
</style>

![bg left](power_suplyes.jpg)

# Redudant Power Suply

![](power_suply.jpg)

---

![bg 120%](raidkey.jpg)

---


![bg left](fan.jpg)

# Fan Dell 0H2401

 - 11000 U/min
 - 60dB
 - 1.68 A
 - 12 V DC
 - Widht: 7.0cm 
 - Height: 6cm 
 - Depth: 5cm

---

![bg](fans.jpg)

---

# Dell OEM PowerEdge 2850 

xPCI Express Riser

![bg](riser_card.jfif)

---

![bg](riser_card.jpg)

---

# Dell PowerEdge 2850 PCI-X Riser Board V3 U8373

- 3x PCI-X slots (64-bit/133MHz)
- PERC 4e/Di ROMB
- Dual Channel LSI53C1030 SCSI controller onboard with 240-pin expandable cache memory slot (DIMM not included)

---

# Nic

<style scoped>
img {
    display: table;
    margin: 0 auto;
    height: 800px;
    transform: rotate(90deg)  translateX(-120px);
    width: 500px
}
</style>

![](managment_card.jpg)

---

# Děkujeme za pozornost :))))