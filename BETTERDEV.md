Perché investire in sicurezza
=============================

Serve, perché serve :-)
Sbrodolata di storielle
Dati e casi del 2014
Storielle alla Mitnick


Rischio
-------


Qualità
-------


Obbiettivo
----------
Identificare e risolvere le vulnerabilità in anticipo
Ridurre il rischio



Cosa si fa
----------
Ethical Hacking o Red Team (storia mitnick)
Network Penetration Testing
Web Application Penetration Testing



Come si fa
----------
Principio di Pareto (80 20)

Caso ms che ha applicato SDLC (ciclo di sviluppo sicuro del softwaer): risolvendo il 20% dei bug più riportato risolvi anche 80%


Sicxurezza Cross Cutting
------------------------

PPT ==> People Process Tecnology

Risk management
---------------
  
P +-----------------+----------------+
r |                 |                |
o |                 |                |     
b |  Ridurre        |   Evitare      |
a |  o mitigare     |                |
b |                 |                |
i +-----------------+----------------+
l |                 |                |
i |  Accettare      |  Trasferire    |
t |                 |  o Condidere   |
y |                 |                |
  +-----------------+----------------+ 
   I m p a t t o



Cosa è sicurezza
----------------
Mantenimento proprietà  => Confidenzialità Integrita Aviability (Disponibilita) => CIA
"Se tu credi che la tua applicazione sia il tuo codice hai sbagliato" ---> sono i dati (ma anche il fatto che tu usi librerie)



Archittetutra nn sicura
-----------------------

session reply
eavesdropping
mitm
race condition
dos
auth authoriz bypass


Code not secure
---------------



Deploy nn sicuro
----------------



Bug vs Security flow
--------------------


Principi e requisiti di sicurezza
---------------------------------


        
          p
       principle
       weakness
     vulnerabilità



# Security by DEFAULT!!!---> router con pwd non default tipo admin
# Least Privilege -->  non solo su db solo read o write , ma anche networko
# defence in depth  --> security control: esempio layer, e airbag + cintura sicurezza
# separation/segregation of duties --> esempio banca: la richiesta va allo sportellante ma la conferma arriva da un'altro soggetto---> no conflitto


Cicli di sviluppo software
--------------------------
Seguire un processo iteratico, tdd --> fare i security test


riutilizzo del sw  tipo login, processo, test mega e IDEA --> code review almeno su base owasp + test più controllo statico codicwe


 ==> SDL (di ms)  & CLASP (di owasp), come fatto da Microsoft fare per MONDORA


# analisi statica del codice ( fortyfive, sonarcube, veracode )
# tend analysys



Fondamenti del SDLC
-------------------

	- Threat modeling (come pensa attaccante, elementi caratterizzanti del sistema, definizione minaccia)
  		- STRIDE Spoofing, Tampering, Repudation, Informartion Disclosure, DOS, Elevetion of Privilege
		- DREAD
 


CWE / SANS 25
-------------
 fatta dal mitre
 principio: mantenere coerente il flusso della informazione (sql injection, flusso controllo flusso dati, esempio drepper aka capitan crucnh)
 IDEA: adattare di più qusto corso al contesto agile e mondora
 
