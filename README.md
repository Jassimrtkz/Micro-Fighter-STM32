# Micro-Fighter-STM32

SPI LCD, joystick input, push buttons, PWM audio (buzzer), and LED indicators are used in this STM32-based real-time embedded fighting game.

---

## 📦 Project Files

⚠️ The entire project is supplied as a ZIP bundle due to the substantial quantity of STM32 source files:

➡️ **Download:** `Unit_4_1_Pong-main.zip`

---

## 🎮 Features

- HAL_GetTick in real-time game loop (non-blocking timing)
- State machine architecture (START / PLAYING / GAME OVER)
- Player vs Enemy combat system with collision detection
- Logic for scoring and the health bar system
- Special attack with cooldown mechanism
- SPI LCD rendering (ST7789 driver)
- Joystick-based movement input
- Jump, block, and special button-based actions
- PWM-based audio feedback (buzzer)
- Hit feedback and game event LED indications

---

## ⚙️ Technologies Used

- STM32 (STM32CubeMX + HAL drivers)
- C (embedded systems programming)
- SPI communication (LCD)
- ADC (joystick input)
- GPIO (buttons)
- PWM (audio + LEDs)

---

## 🚀 How to Run

1. Get the ZIP file, then extract it.
2. Open the project in STM32CubeIDE  
3. Build and flash STM32 board  
4. Connect:
   - SPI LCD
   - Joystick
   - Buttons
   - Buzzer
   - LEDs  

-----

## 📹 Demonstration

The project entry includes a video showcasing gameplay, LED feedback, and audio behaviour.

---

## 👨‍💻 Author

Jassim Khalid I S Almuhaiza – University of Leeds  
ELEC2645 Embedded Systems Mini Project
