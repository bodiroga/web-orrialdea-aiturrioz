---
title: Blink sketch-a
parent: sketch-ak.md
---

#### Arduinorako blink sketch adibidea.

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

![Arduino blink](https://cdn.instructables.com/F60/IZJJ/I8ZQZMO9/F60IZJJI8ZQZMO9.LARGE.jpg)
