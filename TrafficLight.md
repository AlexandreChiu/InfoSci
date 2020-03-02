
```.c
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(12, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(13, LOW);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(12, HIGH);
  delay(700); // Wait for 500 millisecond(s)
  digitalWrite(12, LOW);
  delay(700); // Wait for 500 millisecond(s)
  digitalWrite(11, HIGH);
  delay(700); // Wait for 500 millisecond(s)
  digitalWrite(11, LOW);
  delay(700); // Wait for 500 millisecond(s)
  digitalWrite(12, HIGH);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(12, LOW);
  delay(500); // Wait for 500 millisecond(s)
  
}

```

The image of the circuit is shown in Fig. 1

! [Circuit] (Circuit.PNG)
Fig. 1 Circuit used for traffic light
