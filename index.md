---
layout: default
---

## What This Is

Embedded Rocks designs and shares open-source electronics projects. The focus is on creating hardware that can be built, modified, and understood without proprietary restrictions.

Each project includes complete schematics, firmware source code, and documentation. If something needs a kit, there's a kit. If you'd rather source components yourself, the files are available.

---

## 🛠️ Current Projects

### **[Clockwise](https://clockwise.page/)** – DIY Smart Clock
A Wi-Fi-enabled RGB LED matrix wall clock. Solder the board, flash firmware through a web interface, and customize the display. The design uses through-hole components where practical, making assembly and repairs straightforward.

**Technical specs:** ESP-based, web flasher, RGB matrix display, NTP sync, customizable animations

---

### **[Pinch](https://pinch.embedded.rocks/)** – Password Storage
Local password management without cloud dependencies. Designed for those who prefer to control where their credentials are stored.

**Approach:** Self-hosted, encrypted, no external services required

---

## 🛒 Hardware Store
<img width="372" height="451" alt="image" align="center" style="display: block; margin: 0 auto;" src="https://github.com/user-attachments/assets/18a26ebf-55fc-4446-b0c4-0af55884aa59" />

**[Embedded Rocks! Store](https://www.elecrow.com/store/embedded.rocks)** ![90s GIF Sale](assets/img/sale.gif)

The Clockwise kit is currently available, with all required components and documentation included. Use code `CLOCKWISEDIS10` for 10% off.

Parts are also available separately if you're building from the open-source files.

---

## 📬 Newsletter

Updates on project development, new releases, technical write-ups, and occasional discount codes.

<div class="container">
    <form action="https://usebasin.com/f/be3b2e6ed179" method="POST" enctype="multipart/form-data" id="guestbook">
        <input type="email" name="email" placeholder="your@email.here" required/>
        <input id="dateTime" type="hidden" name="dateTime"/>
        <input type="submit" value="Subscribe →"/>
    </form>
</div>
<script>
    document.getElementById('dateTime').value = new Date().toUTCString();
</script>

No spam. Unsubscribe anytime.

---

## 🎯 Design Principles

|<img alt="OpenSource" src="assets/img/open-source.png" width="30%">|<img alt="DIY" src="assets/img/diy.png" width="30%">|<img alt="Buy or Build" src="assets/img/property.png" width="30%">|<img alt="Community" src="assets/img/social-care.png" width="30%">
|:-:|:-:|:-:|:-:|
|**Open-Source**|**Practical**|**Flexible**|**Documented**
|All schematics, firmware, and design files are available under permissive licenses.|Projects focus on real use cases, not technology for its own sake.|Buy a kit or build from source files. Modify as needed.|Clear documentation, BOM lists, and assembly guides included.

<small>Icons designers credits [1](https://www.flaticon.com/free-icons/property),[2](https://www.flaticon.com/free-icons/do-it-yourself),[3](https://www.flaticon.com/free-icons/help),[4](https://www.flaticon.com/free-icons/open-source),[5](https://www.flaticon.com/free-icons/instagram)</small>

---

## 📐 Technical Approach

**Component Selection**  
Through-hole components are used where possible to enable hand soldering and easier repairs. Surface-mount is used only when necessary for functionality or size constraints.

**Firmware**  
Code is written to be readable and modifiable. Web-based flashing tools are provided when practical to avoid toolchain complexity.

**Documentation**  
Each project includes: assembly instructions, schematic explanations, firmware architecture notes, and troubleshooting sections.

**Licensing**  
Hardware designs are released under CERN-OHL or similar. Firmware typically uses MIT or Apache 2.0. Check individual project repositories for specifics.

---

## 🔧 Why Open-Source Hardware

Proprietary hardware creates long-term problems: discontinued products become e-waste, locked ecosystems prevent modifications, and knowledge stays siloed.

Open-source hardware allows:
- **Repairs** when components fail
- **Modifications** for specific needs
- **Learning** from working examples
- **Iterations** that improve on original designs
- **Longevity** beyond commercial product lifecycles

The goal is creating hardware that remains useful and understandable years after release.

---

## 🔍 Technical Support

**Documentation First**  
Each project has comprehensive guides. Check the docs before reaching out.

**GitHub Issues**  
Technical problems, bugs, or design questions can be posted on the relevant project's GitHub repository.

**Email**  
For questions not covered in documentation or GitHub issues.

---

## 📡 Contact

**Instagram:** [@embedded.rocks](https://www.instagram.com/embedded.rocks)  
Project updates and build photos.

**Email:** [contact@embedded.rocks](contact@embedded.rocks)     
For collaboration proposals or technical inquiries.

**GitHub:** [Embedded-Rocks](https://github.com/Embedded-Rocks)     
Project repositories and issue tracking.

---

## ⚖️ Licensing Summary

**Hardware:** CERN Open Hardware License (typically CERN-OHL-S or P)  
**Firmware:** MIT License or Apache 2.0 (check individual repos)  
**Documentation:** Creative Commons BY-SA 4.0

This means: commercial use allowed, modifications allowed, attribution required, share-alike for documentation.

---

<small>
© 2025 Embedded Rocks – Open-source hardware and firmware  
Licensed under CERN-OHL and MIT/Apache (see project repos)  
All designs can be manufactured, modified, and distributed per license terms.
</small>

