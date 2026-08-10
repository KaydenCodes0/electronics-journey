//C++

int analogPin = A0;
int PWMPin = 9;


void setup() {
  
  pinMode(analogPin, INPUT);
  pinMode(PWMPin, OUTPUT);

  Serial.begin(9600);

}

void loop() {
  
  int brightness = (analogRead(analogPin)/4);
  Serial.println(brightness);
  analogWrite(PWMPin, brightness);

}
