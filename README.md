Arduino-R-C-Airplane-FAA-Lights-3-LED-Version
=============================================

My First Repository

int Leftwing = 8; // Digital pin 8
int Tailstrobe = 9; // Digital pin 9
int Rightwing = 10; // Digital pin 10
void setup()
{
pinMode(Tailstrobe,OUTPUT);
pinMode(Leftwing,OUTPUT);
pinMode(Rightwing,OUTPUT);
}
void loop()
{
digitalWrite(Tailstrobe,HIGH);
delay(300);
digitalWrite(Tailstrobe,LOW);
delay(20);
digitalWrite(Tailstrobe,HIGH);
delay(300);
digitalWrite(Tailstrobe,LOW);
delay(20);
digitalWrite(Leftwing,HIGH);
digitalWrite(Rightwing,HIGH);
delay(300);
digitalWrite(Leftwing,LOW);
digitalWrite(Rightwing,LOW);
delay(20);
digitalWrite(Leftwing,HIGH);
digitalWrite(Rightwing,HIGH);
delay(300);
digitalWrite(Leftwing,LOW);
digitalWrite(Rightwing,LOW);
delay(20);
digitalWrite(Leftwing,HIGH);
digitalWrite(Rightwing,HIGH);
delay(300);
digitalWrite(Leftwing,LOW);
digitalWrite(Rightwing,LOW);
delay(20);
}
