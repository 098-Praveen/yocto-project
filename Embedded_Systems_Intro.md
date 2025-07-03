
# 📘 Embedded Systems Introduction

## 1. What is an Embedded System?

An **Embedded System** is a combination of computer **hardware** and **software** designed to perform a **specific function** or set of functions.

### 🔑 Key Characteristics
- Contains a **processing unit**
- Includes **temporary memory** (RAM) and **permanent storage** (Flash, ROM)
- **Customized** for specific applications
- **Low cost** compared to general-purpose computers

---

## 2. 📱 Real-life Example: Smartphone

A smartphone is a complex system with multiple embedded components.  
Each component can be considered an embedded system in itself.

---

## 3. 🔐 Software Perspective: Security System Example

### Option 1: General-Purpose Computer
- Attach a camera and develop an intruder detection app.
- ✅ Pros: Easy and fast to develop  
- ❌ Cons: Expensive (~₹100,000 PC + ₹3,500 camera), overkill features (display, keyboard, etc.)

### Option 2: Raspberry Pi (General-Purpose Embedded Board)
- Attach a camera and write custom software  
- 💰 Cost: ₹4,000 (RPi) + ₹3,500 (camera) + ₹1,000 (Wi-Fi) ≈ ₹6,500  
- ❌ Still not optimal: Unused hardware like HDMI, USB, Ethernet

### Option 3: Custom Embedded System
- Based on Raspberry Pi design
- Hardware engineer builds a custom PCB with only essential components
- Software engineers write software to handle alert functionality
- 💰 Cost: ₹1,000 (custom board) + ₹3,500 (camera)
