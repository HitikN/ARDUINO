# ARDUINO
https://wokwi.com/projects/new/arduino-uno

void setup() {
  // put your setup code here, to run once:
  pinMode(11, OUTPUT);
  pinMode(6, OUTPUT);

}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(11, HIGH);
tone(6, 262, 250);
   delay(1000);

   digitalWrite(11, LOW);
  delay(1000);
  


}



