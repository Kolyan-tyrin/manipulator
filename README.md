#define PIN_RELAY 5 

void setup()
{
  pinMode(PIN_RELAY, OUTPUT); 
  digitalWrite(PIN_RELAY, HIGH); 
}
void loop()
{
  digitalWrite(PIN_RELAY, LOW); 
  delay(5000);
  digitalWrite(PIN_RELAY, HIGH); 
  delay(5000);
  }
