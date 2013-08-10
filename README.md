reading-a-potentoimeter
=======================
int  pot;
int MEDIUM = 0.5;
void setup()
{
  Serial.begin(9600);
}
void loop()
{
  pot = digitalRead(A0);
  if(pot == 1)
    Serial.println(HIGH); 
  else
   Serial.println(LOW);
   
   delay(100);
}
  
   
  
  
//This is the code in english.
  
  
  /*
int = pot;
void setup()
{
Serial . begin(9600);
}
void loop()
{
if( pot turns right)
Serial . println(high);
else(pot turns left)
Serial . println(low);
}
*/
  
  
  
  
  
  
  
  
  
  
  
  
  
  
