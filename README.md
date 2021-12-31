# 12F683MPPT
Simple MPPT with 12F683  
  
Another porting of MPPT. Test ok. Switching frequency : 10kHz.  
It has no switching noise.  
  
BUK9508-55A for alternative FET. 
  
TLC272 OPAMP works better.  
  
(Note) Sometimes MPPT stalls no output. It caused by low FET bootstrap voltage.  
It's very rare condition. It may fixed by R9 change.  
