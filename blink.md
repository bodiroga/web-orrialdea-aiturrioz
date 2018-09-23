---
title: Blink sketch-a
parent: sketch-ak.md
---

# Blink sketch-a
## Arduinorako blink sketch-a ikusi daiteke orrialde honetan.

```cpp
void setup() {
    Serial.begin();
    pinMode(BUILTIN_LED, OUTPUT);
    digitalWrite(BUILTIN_LED, LOW);
}

void loop() {
   Serial.println("LED-a piztuko da");
   digitalWrite(BUILTIN_LED, HIGH);
   delay(2000);
   Serial.println("LED-a itzaliko da");
   digitalWrite(BUILTIN_LED, LOW);
   delay(2000);
```
