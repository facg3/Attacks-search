# Attacks-search
Research week

## XSS Attacks!
Put simply, an XSS Attack is when the attacker gives input fields inputs effictive on the code as a whole, especially scripts which could vary in their severity.

## Man-In-The-Middle Attack
Man In The Middle also known as JANUS attak

happens when the attacker relays on or changes a communication between tow sides

### Example

1- eavesdropping: the attacker makes different connection between the two sides making those two sides think that they are connected directly 


![example](https://scontent.fjrs2-1.fna.fbcdn.net/v/t35.0-12/25521023_10215337900783222_67684309_o.png?oh=f86c018f184c1e915496a10426fe1e83&oe=5A3A11CB)



## How to prevent:

* authontocation:
systems provides authontocation of messages such as exchange of extra  information with messages over a secur channle, such protocales often use key agreemint protocol have been developed

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








## Cross-Site Request Forgery (CSRF) 
![PIC](https://image.slidesharecdn.com/csrf1-170319112925/95/cross-site-request-forgery-csrf-scripting-explained-5-638.jpg?cb=1489923158)  

Also known as one-click attack or session riding and abbreviated as CSRF or XSRF..
A type of attack that occurs when a malicious web site, email, blog, instant message, or program causes a user’s web browser to perform an unwanted action on a trusted site for which the user is currently authenticated. The impact of a successful CSRF attack is limited to the capabilities exposed by the vulnerable application. For example, this attack could result in a transfer of funds, changing a password, or purchasing an item in the user's context. In effect, CSRF attacks are used by an attacker to make a target system perform a function via the target's browser without knowledge of the target user, at least until the unauthorized transaction has been committed..



## How to prevent CSRF attacks

To prevent CSRF attacks on
### The server side,
banks and merchants should transition from cookies that perform session-tracking to session tokens that are dynamically generated. This would make it more difficult for an attacker to get a hold of a client’s session.

Don’t trust that the site you're visiting has measures in place to prevent CSRF attacks. Many sites do have controls in place to protect against it, but it is not a good practice to assume this. Some sites could have controls in place today but after an upgrade or change in the code, may remove them later.

### For users to prevent CSRF attacks,
it is important to understand that you must already be authenticated into a certain website to be vulnerable. Banking or any site that performs financial transactions and has a high usage rate are the primary targets of these attacks. 

There is 6 actions you can take to prevent a CSRF attack you can find [here](https://www.networkworld.com/article/3190444/security/how-to-protect-against-cross-site-request-forgery-attacks.html)



# REFERNCE :sunglass:

https://www.networkworld.com/article/3190444/security/how-to-protect-against-cross-site-request-forgery-attacks.html
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)
https://www.youtube.com/watch?v=m0EHlfTgGUU
https://www.youtube.com/watch?v=vRBihr41JTo
