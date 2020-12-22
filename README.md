# ButtonLED

void setup() {  
pinMode(2,OUTPUT);   
pinMode(3,INPUT);   
}  
    
void loop() {    
while(digitalRead(3) == LOW)   
{ while (digitalRead(3) == LOW)  
{  
digitalWrite( 2 , !digitalRead(2));   
  }  
delay(200); }  



