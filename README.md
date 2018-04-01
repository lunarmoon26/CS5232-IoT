## Attacker Model

1. Attacker as CP join SD’s open wifi  

    a. Get ip address and configuration of the SD `attacker_get_SDInfo == true`
    
    b. Ask to join a attacker wifi to disable the open wifi. The benign CP won’t find it any more `ch == c[2]`
    
    c. Direct send command to control the SD `excutedBy == Attacker`
    
    d. After SD configured home wifi connection, attacker CP join to home wifi to control the SD `excutedBy == Attacker`
    
2. Attacker as SD

    a. Get Username and Password from CP `attacker_get_wifiInfo == true`
    
3. Attacker buffer  

    a. Send fake message again 
