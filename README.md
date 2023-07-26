# automated-pet-feeder-using-arduino
Introducing our state-of-the-art automated pet feeder, powered by Arduino. Enjoy the convenience of customizable feeding schedules, portion control, and remote feeding via a user-friendly smartphone app. Prioritize your pet's well-being with this innovative and reliable solution. Ensure their happiness and health with ease and precision.

#include <Servo.h>



Servo myservo;  // create servo object to control a servo

// twelve servo objects can be created on most boards



int pos = 0;    // variable to store the servo position



void setup() {

  myservo.attach(9);  // attaches the servo on pin 9 to the servo object

}



void loop() {

 myservo.write(0);

 delay(1000);

 myservo.write(45);

 delay(1000);

 myservo.write(0);

 delay(60000);

 myservo.write(45);

 delay(1000);

  }
