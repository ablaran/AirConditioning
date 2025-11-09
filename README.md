# AirConditioning — Flipper Zero IR App (Tokyo Ghoul Theme)

Application for **Flipper Zero** that controls an air conditioner using **RAW infrared signals**, featuring a **Tokyo Ghoul themed interface**.

---

## Preview
![App Preview](images/preview2.png)

---

## Features
- Send pre-recorded **RAW IR signals** (power on, power off, temperature control, dehumidifier).
- Grid-based interface (2x3) with icons.
- Navigation with Flipper Zero D-pad and highlighted selection.
- Custom background inspired by Tokyo Ghoul.

---

## Interface Layout
The 2x3 grid provides the main controls:

| Row | Column 1         | Column 2 | Column 3 |
|-----|------------------|----------|----------|
| 1   | Dehumidifier     | 20°C     | 24°C     |
| 2   | Power On/Off     | 18°C     | 22°C     |

---

## Implemented IR Signals
- **Power On/Off**  
- **Set 18°C, 20°C, 22°C, 24°C**  
- **Dehumidifier Mode**  

Signals are stored as `uint32_t` arrays with RAW IR patterns.

---

## License

This project is licensed under the GPL-3.0 license. See the [LICENSE](LICENSE) file for details.
