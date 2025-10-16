# Robotic Arm — 5-DOF (ESP32-S3)

**Focus:** embedded control (C/C++), PWM, forward kinematics, servo coordination, test/validation.  
**Status:** Prototype + ongoing iterations.

## 1) Overview
- 5-DOF servo arm with joystick control and auto-leveling wrist.
- Goals: reliable joint motion, positional repeatability, modular enhancements.

## 2) Hardware & Software
- **MCU:** ESP32-S3
- **Firmware:** C/C++ (Arduino/PlatformIO)
- **Design:** torque calculations, CAD (Inventor/SolidWorks)
- **PCB:** *Learning KiCad* for schematic capture & PCB layout (future iterations)
- **Test gear:** oscilloscope, logic analyzer, DMM

## 3) System Architecture
Brief block diagram (image) and 2–3 bullets:
- PWM control to servos, joystick inputs filtered/debounced
- Safety: motion limits, failsafe states

## 4) Getting Started
- `firmware/` contains code; compile with Arduino IDE or PlatformIO
- Pinout and wiring diagram in `docs/`

## 5) Testing & Validation
- Test plan: see `test/procedures/`
- Sample results & plots in `test/results/`
- Current focus: servo accuracy, repeatability under load

## 6) Results (to date)
- Prototype joint motion verified
- Next: PCB spin for cleaner wiring and noise reduction

## 7) License
MIT for code. See `LICENSE`.
