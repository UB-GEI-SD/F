## Example de .log complert:

Ha de quedar registrat tot el que passa pel socket del servidor, però podeu no afegir les comandes repetides (les que són echo del jugador 1 al 2 i viceversa). El que apareix entre parèntesis són comentaris meus que no cal que apareguin en el .log.

C1: STRT 1010  
C2: STRT 2020   
S: CASH 10 (to C1)  
S: CASH 10 (to C2)  
C1: BETT  
C2: BETT  
S: LOOT 2 (to C1)   
S: LOOT 2 (to C2)  
S: PLAY ‘0’ (you start 0;the other start 1) (to C1)   
S: PLAY '1' (to C2)  
S: DICE 1010 ‘6’ ‘2’ ‘1’ ‘4’ ‘2’ (to C1)  
S: DICE 1010 ‘6’ ‘2’ ‘1’ ‘4’ ‘2’ (to C2 - ECHO)  
C1: TAKE 1010 0x01 0x01  
S: TAKE 1010 0x01 0x01 (to C2 - ECHO)  
S: DICE 1010 ‘6’ ‘4’ ‘5’ ‘5’ ‘1’ (to C1)   
S: DICE 1010 ‘6’ ‘4’ ‘5’ ‘5’ ‘1’ (to C2 - ECHO)  
C1: TAKE 1010 0x02 0x02 0x03  
S: TAKE 1010 0x02 0x02 0x03 (to C2 - ECHO)  
S: DICE  1010 ‘6’ ‘4’ ‘5’ ‘2’ ‘2’ (to C1)  
S: DICE 1010 '6' '4' '5' '2' '2'  (to C2 - ECHO)  
S: PNTS 1010 0x04 (to C1)  
S: PNTS 1010 0X04 (to C2)  
S: DICE 2020 ‘3’ ‘6’ ‘2’ ‘1’ ‘4’  (to C2)  
S: DICE 2020 ‘3’ ‘6’ ‘2’ ‘1’ ‘4’  (to C1 - ECHO)  
C2: TAKE 2020 0x01 0x02  
S: TAKE 2020 0x01 0x02 (to C1 - ECHO)  
S: DICE 2020 ‘5’ ‘6’ ‘4’ ‘4’ ‘2’ (to C2)  
S: DICE 2020 ‘5’ ‘6’ ‘4’ ‘4’ ‘2’ (to C1 - ECHO)   
C2: PASS 2020  
S: PASS 2020 (to C1 - ECHO)  
S: PNTS 2020 0x06  (to C2)  
S: PNTS 2020 0x06  (to C1 -ECHO)  
S: WIN '1' (to C1)  
S: WINS ‘0’ (to C2) (you wins 0; the other win 1; tie 2 )  
S: CASH 9 (to C1)  
S: CASH 11 (to C2)  
C1: EXIT  
S: ERRO "Sense jugador 1" (per exemple) (to C2)  