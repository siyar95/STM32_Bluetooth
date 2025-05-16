# STM32_Bluetooth

A compact STM32WB55CEU6-based Bluetooth module designed for embedded wireless applications. This board features a u.FL antenna connector, USB-C interface, and UART communication — making it ideal for low-power wireless development and integration.

---

## 🔧 Features

- **Microcontroller**: STM32WB55CEU6 (Bluetooth 5.2 + Cortex-M4 + Cortex-M0+)
- **Bluetooth Antenna**: u.FL connector for external antenna
- **USB Interface**: USB-C for power and data
- **Communication**: UART breakout for serial interfacing
- **Power Supply**: 5V USBC --> 3.3V LDO regulator --> 1.2V SMPS (in the MCU) for efficient power conversion
- **Oscillators**:
  - 32 MHz HSE (for Bluetooth stack)
  - 32.768 kHz LSE (for RTC and low-power modes)

---

## 🧱 PCB Stackup (4-layer)

| Layer | Purpose           |
|-------|--------------------|
| L1    | Signal (Top)       |
| L2    | Ground Plane       |
| L3    | Ground Plane       |
| L4    | Power / Signal     |

Optimized for signal integrity, RF performance, and low EMI.

---

## 🧩 Ideal For

- Bluetooth Low Energy (BLE) applications
- Custom wearable or IoT devices
- Prototyping wireless peripherals with STM32Cube ecosystem
- Projects needing UART or USB-C connectivity alongside BLE

---

## 📡 Notes

- Make sure to connect a suitable external antenna via the u.FL connector.
- Crystal oscillator frequencies comply with STM32WB Bluetooth stack requirements.
- USB-C supports both power and USB device functionality.

---

## 🛠️ Tools

- Designed in **KiCad**
- Program using **STM32CubeIDE** or **STM32CubeProgrammer**

## Screenshots

![image](https://github.com/user-attachments/assets/a771ad2b-2dbc-4755-b0a7-7337f5e72518)

![image](https://github.com/user-attachments/assets/f8cd4a05-4024-43c4-b500-757b5fccdd21)
![image](https://github.com/user-attachments/assets/0ecf6c70-0d0e-400e-b3a8-517b80e5d2cc)

