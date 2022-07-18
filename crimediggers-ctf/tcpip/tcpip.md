# **Bevat spoilers!** ⚠️ 

![tcpip-logo](tcpipsvg.svg) 
# TCP/IP Challenge 

**Opdracht:**
In een digitale oplichtingszaak hebben we netwerkverkeer onderschept. Kun jij uitvinden of er malware is verzonden?

<hr>

Bij deze challenge krijg je een pcap bestand. Dit pcap bestand bevat het internetverkeer van onze verdachte.<br> We kunnen het bestand openen in Wireshark.
<br>

Je wordt overspoelt met internetverkeer.
<br>

![netwerk-dump](wireshark.JPG) 

<br>

Tijdens het scrollen kom ik verschillende soorten verkeer tegen, zoals http verkeer naar *zoeken.nl*:
<br>
![zoektermen](zoektermen.JPG) 
<br>
Iets met een zip bestand ontsleutelen?
<br> 

Maar we zoeken naar een flag. <br>
Even later kom ik pop verkeer tegen, waar aan het einde van deze mail conversatie een wachtwoord gegeven is:
![zoektermen](pop-verkeer.JPG) 
<br><br>
Dit doet vermoeden dat er een zip bestand in het spel is, en na verder speuren inderdaad een zip file in een netwerkpakket:
<br>
![zoektermen](zip.JPG) 

