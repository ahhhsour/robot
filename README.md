#include <Servo.h> //include Servo library
Servo servol;     

void setup()
{
   servol.attach(2);
}

void loop()
{
    servol.write(90);
    delay(1000);
}
