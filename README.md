# Micro-Fighter-STM32

An STM32-based real-time embedded combat game implemented using SPI LCD, joystick input, push buttons, PWM audio (buzzer), and LED indicators.

---

## 📦 Project Files

⚠️ Due to the large number of STM32 source files, the full project is provided as a ZIP archive:

➡️ **Download:** `Unit_4_1_Pong-main.zip`

---

## 🎮 Features

- Real-time game loop using HAL_GetTick (non-blocking timing)
- State machine architecture (START / PLAYING / GAME OVER)
- Player vs Enemy combat system with collision detection
- Health bar system and scoring logic
- Special attack with cooldown mechanism
- SPI LCD rendering (ST7789 driver)
- Joystick-based movement input
- Button-based actions (jump, block, special)
- PWM-based audio feedback (buzzer)
- LED indicators for hit feedback and game events

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

1. Download and extract the ZIP file  
2. Open the project in STM32CubeIDE  
3. Build and flash to STM32 board  
4. Connect:
   - SPI LCD
   - Joystick
   - Buttons
   - Buzzer
   - LEDs  

---

## 📹 Demonstration

A video demonstration of gameplay, LED feedback, and audio behaviour is included in the project submission.

---

## 👨‍💻 Author

Jassim Khalid I S Almuhaiza – University of Leeds  
ELEC2645 Embedded Systems Mini Project
