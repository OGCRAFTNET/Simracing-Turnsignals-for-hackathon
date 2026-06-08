# Turn Signals for Sim Racing & Trucking

## 📋 Project Overview

This project aims to create a **realistic turn signal accessory** for sim racing and truck simulation setups. The idea is to use real automotive indicator stalks connected to an Arduino-based controller, allowing the device to function as a standard USB input on a PC.

The turn signal unit should be mountable to a wheelbase, sim rig, or desk and **fully configurable** through custom software.

---

## ✨ Features

- 🎮 Realistic automotive turn signal stalk
- 🔌 USB plug-and-play support
- 🏎️ Compatible with sim racing and trucking games
- ⚙️ Customizable button mappings
- 💡 Optional RGB lighting and status indicators
- 🛠️ Mounting options for wheelbases, sim rigs, and desks
- 🔗 Support for multiple wheelbase brands

---

## 🛠️ Hardware Requirements

### Electronics
- Arduino Pro Micro
- USB cable
- Wires and connectors
- Optional RGB LEDs

### Mechanical Parts
- Real automotive turn signal stalk (replacement part)
- 3D-printed mounting bracket
- Screws and mounting hardware

---

## 📅 Development Roadmap

### Phase 1: Research
- [X] Find suitable automotive turn signal stalks  :https://www.amazon.de/-/en/Steering-Column-Windscreen-Indicator-Combination/dp/B0DBHG1CG9/ref=sr_1_58?dib=eyJ2IjoiMSJ9.72eNbnctxAOpDtwd3CqorCOzffyUcLiWLBHD4cDgrLVW-Uru2PEn2nYs2smaKX7oCn-gIXZgXwW16xxFoh3NXNRUHiclqcex5mqBHw6z5CsK8w7T7-kj4dL5WOFSYyKCPuhv5ZcZXqu_tIED_E0qhsFwD9VecnQoVml38dt9itl3MdmMVlh1lFBj01Gos-KVKM_3aQaZkx4Wljt-OwtdwmD-XBxl68eshcBedVY0Qhq4cMDvijJpJrdC4DrqfJ85KKB8QloWM2RFlJaAU6L88ZJFkPCLQW9veyWJlKRJs58.TBRfN9oJoYlS8EK9manu0Q0wjz25AqYAVZ7STqdDSd0&dib_tag=se&keywords=Blinkerhebel&qid=1780939365&sr=8-58


- [X] Compare different Arduino boards: Arduino Pro Micro  is the best i guess: https://www.amazon.de/-/en/Development-Microcontroller-Integrated-Interface-Compatible/dp/B0FPFHM6DX/ref=sr_1_1?crid=360SYEBBYZ0VO&dib=eyJ2IjoiMSJ9.YPqPGqWkZewwtleJq7Hds7iTEWnVDkyqA8d_E6PVY5RBpJipDPCtURICMQR_uEfemu5w6N09xPU20jcoq5yWBYA0m8XNc7JEnY1Y4BK8telBtEwbLX5LNbNcgzBdfc28WCIphKdHDv9re6CnUPLwt5CbGszeJKIiP__lCjiPIpOb_C5tatwvsRjEX1PY8z9acEduNkuiKBnkUxtjn79pDlkI-9-mrscWGzmWOfUFQN9o9TOBkF_9FDV4HhJzHPA8qanJ5JjMWX63BpLhVpsrx3GBaaNQrOsoxGx1PqVVvqk.eMbDwH5tBbn5L6ZfQ6WHeWmUHs5XXP2gJIrS60VdVGM&dib_tag=se&keywords=Arduino+Pro+Micro&qid=1780939571&sprefix=arduino+pro+micro%2Caps%2C146&sr=8-1


- [ ] Research USB HID implementation
- [ ] Investigate compatibility with major sim racing ecosystems

### Phase 2: Hardware Design
- [ ] Design a mounting system for:
  - Sim racing wheelbases
  - Sim rigs
  - Desks
- [ ] Create 3D printable CAD models
- [ ] Prototype the housing

### Phase 3: Electronics
- [ ] Connect the turn signal stalk to the Arduino Pro Micro
- [ ] Program the Arduino as a USB HID device
- [ ] Test input detection and reliability

### Phase 4: Software
- [ ] Develop a configuration tool
- [ ] Add button remapping support
- [ ] Add firmware update functionality
- [ ] Implement RGB customization (optional)

### Phase 5: Compatibility
- [ ] Test with:
  - Logitech wheelbases
  - Moza wheelbases
  - Fanatec wheelbases
  - Simagic wheelbases
  - Asetek wheelbases
- [ ] Ensure universal PC compatibility

---

## ⚠️ Current Challenges

- Designing a universal mounting solution
- Supporting different wheelbase designs
- Creating reliable and durable electronics
- Developing user-friendly software

---

## 🚀 Future Ideas

- Headlight controls
- Wiper controls
- Cruise control buttons
- Hazard lights
- Gear selector integration
- Wireless connectivity

---

## 🎯 Goal

Create an **affordable and realistic turn signal accessory** that enhances immersion for sim racers and truck simulator players while remaining compatible with most PC sim setups.