# STA-FrennaGiuseppe

Facile 1 – Semaforo

int verde=9; //rinominazione//
int giallo=12; //rinominazione//
int rosso=13; //rinominazione//

 void setup()
 {
  pinMode(verde, OUTPUT);
  
  pinMode(giallo, OUTPUT);
 
  pinMode(rosso, OUTPUT);
  }

void loop()
 {
  digitalWrite(verde, HIGH);//led verde acceso//
  
  delay(2000);//durata led verde//
  
  digitalWrite(verde, LOW);//led verde spento//
  
   digitalWrite(giallo, HIGH);//led giallo acceso//
  
  delay(1000); //durata led giallo//
  
   digitalWrite(giallo, LOW);//led giallo spento//
  
  digitalWrite(rosso, HIGH);//led rosso acceso//
  
  delay(2000);//durata led rosso//
  
  digitalWrite(rosso, LOW);//led rosso spento//
   }
    
