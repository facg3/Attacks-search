# Attacks-search
Research week

## Man-In-The-Middle Attack
Man In The Middle also known as JANUS attak

happens when the attacker relays on or changes a communication between tow sides

### Example

1- eavesdropping: the attacker makes different connection between the two sides making those two sides think that they are connrcted directly 


![example](https://www.facebook.com/messages/t/jhgdklj)



## How to prevent:

* authontocation:
systems provides authontocation of messages such as exchange of extra  informations with messages over a secur channle, such protocales often use key agreemint protocol have been developed

such as,  

- HTTP Public Key Pinning, sometimes called "certificate pinning", helps prevent a MITM attack in which the certificate authority itself is compromised, by having the server provide a list of "pinned" public key hashes during the first transaction. Subsequent transactions then require one or more of the keys in the list must be used by the server in order to authenticate that transaction.
 
### Tamper Detection:
there is a counted time for the transaction, if the transaction takes more than that time, then there is maybe an attack

### Foresenic Analysis
it monitor and analize the network trafic 
e.i:
check for the ip address for the server
dns adress for the server 
certificate of the server 
