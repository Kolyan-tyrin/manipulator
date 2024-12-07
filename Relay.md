#define relay 7
void setup() {
  pinMode(7, OUTPUT);
  pinMode(2, INPUT_PULLUP);
  digitalWrite(7, HIGH);
}
void loop() {
  // выведет 0, если кнопка нажата
  // и 1, если неt
  digitalRead(2);
  if(digitalRead(2) == 0)
  {
    digitalWrite(7, LOW);
    
    
    
  }
  else
  {
    digitalWrite(7, HIGH);
  }
