# This document describes Alladin service workflow

This is custodyless custodian assistance service, **C** is fully responsible for its key(s) and **A** can only assist in case of loosing access to them or beeing unusable. When key is stolen that's it , nothing can be done to retrieve the BTC. 
***
## Preliminary steps
**C** logins to the [Alladin webpage] and choses
1. Path 
    1. Newcomer
    2. Advanced
2. Rescue option 
    1. Opendime lost/broken 
        * In case of lost/broken Opendime **C** can contact **A** and ask for assistance. **A** prepares rescue transaction that will transfer BTC to the new address no earlier that after **Timeout** and sends it to address provided by **C**
    2. Backup opendime 
        * This option is for **C** that may need to access their BTC in two locations or just want a backup access in case main Opendime is lost/broken. Any of two opendimes can be used to spend BTC.
    3. Backup opendime with timelock
        * This option is for **C** willing to pass additional token to his/her heirs or attorney. This opendime can be only used to spend BTC after **Timeout**
        
## Initialisation

1. Newcomer path 
    - **A** sends initialized opendime(s) to physical address provided by **C** (P.O. box prefered) 
    - **C** using [Alladin webpage] obtains **BTC address** that will be assisted by **A**


2. Advanced Bitcoiner
    - **C** buys opendime and initializes it on its own.
    - **C** using [Alladin webpage] creates **BTC address** that will be assisted by **A**
    
## Recovery


    
    
## Glossary



**A** : Alladin service 

**BTC address**: P2SH address that is fully spendable by **A** at any time but can also be spent from after **Timeout** by **A**

**C** : Customer 

**Timeout** : time that has to pass since funding transaction for Alladin to be able to recover BTC

[Alladin webpage]: <https://www.alladin.ch>
