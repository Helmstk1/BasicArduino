# BasicArduino
I'm going to learn how to use an Arduino, and make awesome things with it!


## TableofContents
* [TableOfContents](#TableOfContents)
* [HelloArduino](#HelloArduino)
* [FiniteLEDBlink](#FiniteLEDBlink)

## HelloArduino

### Description & Code

```C++
/*
  Blink

  Turns an LED on for half a second, then off for half a second, repeatedly.
  
  modified 8 May 2014  by Scott Fitzgerald
 
  http://www.arduino.cc/en/Tutorial/Blink
*/


// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin 13 as an output.
  pinMode(13, OUTPUT);
  Serial.begin(9600); // This turns on my Serial Monitor
  Serial.println("Hello World!");
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(13, HIGH);           // turn the LED on (HIGH is the voltage level)
  Serial.println("Blink!");
  delay(250);                       // wait for a second
  digitalWrite(13, LOW);            // turn the LED off by making the voltage LOW
  delay(250);                       // wait for a second
}
```

### Evidence
[Here is my code on Arduino Create](https://create.arduino.cc/editor/helmstk1/9a3831dd-4b86-42f2-be49-c28b84874092/preview)

### Image or Wiring

### Reflection


## FiniteLEDBlink

### Description & Code

### Evidence

### Image or Wiring

### Reflection
