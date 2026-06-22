# 🔥 Arduino Project 1: Built-in LED Blink

## 🧠 Overview
This is my first Arduino project using the built-in LED on the board.

The goal was to understand:
- How to control output pins
- How timing works using delay()
- How to create different blinking patterns

---

## ⚙️ Hardware Used
- Arduino UNO R3
- Built-in LED (Pin 13 / LED_BUILTIN)

---

## 💻 Code

```cpp
void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);

  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}
