## Tarefa: prototipar detecção de etanol
### Esquema montado no Tinkercad
![image] (https://csg.tinkercad.com/things/k2HtmyGKJja/t725.png?rev=1658497097384000000&s=&v=1&type=circuits)
---
### Código C
```// C++ code
//
void setup()
{
  pinMode(A5, INPUT);
  pinMode(5, OUTPUT);
  pinMode(0, OUTPUT);
}

void loop()
{
  if (analogRead(A5) > 500) {
    digitalWrite(5, HIGH);
    digitalWrite(0, HIGH);
  } else {
    digitalWrite(5, LOW);
  }
  delay(10); // Delay a little bit to improve simulation performance
}
```
---
### Link Do Tinkercad
https://www.tinkercad.com/things/k2HtmyGKJja

