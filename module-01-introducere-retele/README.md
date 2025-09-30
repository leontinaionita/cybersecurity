

Modulul 1 – Introducere în Retele

🎯 Obiective

La finalul acestui modul vei putea:

•	explica ce este o rețea și cum funcționează;

•	diferenția tipurile de rețele (LAN, WAN, VPN etc.);

•	recunoaște și descrie dispozitivele de rețea de bază;

•	înțelege modelul OSI (Open Systems Interconnection) și stiva TCP/IP (Transmission Control Protocol/Internet Protocol);

•	configura și testa adrese IP pe Windows și Linux;

•	înțelege rolul protocoalelor DNS, DHCP, SMTP, POP3 și IMAP;

•	efectua teste de conectivitate cu ping, traceroute, ipconfig, ifconfig/ip;

•	crea o primă topologie vizuală în Cisco Packet Tracer (demo).

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 1. Ce este o rețea de calculatoare

O rețea de calculatoare este un grup de două sau mai multe dispozitive (PC-uri, laptopuri, telefoane, imprimante, servere) conectate pentru a partaja informații, aplicații și resurse.

Exemple simple

•	Două laptopuri conectate la același router Wi-Fi și care fac schimb de fișiere.

•	Un server central care oferă acces tuturor calculatoarelor dintr-o companie la imprimante.

•	Internetul – cea mai mare rețea din lume.

Beneficii

•	Partajarea resurselor (fișiere, imprimante, internet).

•	Comunicarea rapidă.

•	Securitate și administrare centralizată.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 2. Tipuri de rețele

•	LAN (Local Area Network – Rețea Locală): rețea mică, într-o casă sau birou.

•	WLAN (Wireless LAN): LAN bazată pe Wi-Fi.

•	WAN (Wide Area Network – Rețea Largă): conectează rețele aflate la distanțe mari (de exemplu: internetul).

•	MAN (Metropolitan Area Network): rețea pe o arie urbană.

•	VPN (Virtual Private Network – Rețea Privată Virtuală): conexiune securizată peste internet între un utilizator și rețeaua companiei.

💡 Analogie:

LAN = strada ta,

WAN = autostrada care leagă mai multe orașe,

VPN = un tunel securizat pe autostradă.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 3. Dispozitive de rețea

•	Switch: conectează mai multe dispozitive în rețeaua locală.

•	Router: face legătura dintre rețele diferite (ex. LAN ↔ internet).

•	Access Point (AP): oferă conexiune wireless.

•	Firewall: filtrează traficul pentru securitate.

•	Server: calculator dedicat care oferă servicii (DHCP, DNS, mail, web etc.).

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 4. Modelul OSI și TCP/IP

Modelul OSI are 7 straturi (layers):

1\.	Physical – cabluri, semnale, Wi-Fi

2\.	Data Link – adrese MAC (Media Access Control), switch

3\.	Network – adrese IP, rutare

4\.	Transport – protocoale TCP și UDP

5\.	Session – menține conexiunile

6\.	Presentation – codificare, criptare, compresie

7\.	Application – aplicațiile utilizatorului (HTTP, FTP, mail)

💡 Analogie: trimiterea unei scrisori:

•	Stratul 1 = drumul și cutia poștală,

•	Stratul 3 = adresa orașului/destinația,

•	Stratul 7 = limba în care este scris mesajul.

Modelul TCP/IP folosit în practică are 4 straturi:

•	Application

•	Transport

•	Internet

•	Network Access

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 5. Adrese IP și Subrețele

O adresă IP (Internet Protocol) este ca adresa casei tale în rețea.

Ex.: 192.168.1.10

•	IPv4: patru numere între 0 și 255 separate de puncte.

•	Subnet Mask: definește ce parte a adresei este rețeaua și ce parte este hostul (ex.: 255.255.255.0).

•	Gateway: dispozitivul care face legătura cu alte rețele (de regulă routerul).

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 6. Protocoale comune

•	HTTP/HTTPS (HyperText Transfer Protocol / Secure): pagini web.

•	FTP (File Transfer Protocol): transfer fișiere.

•	SSH (Secure Shell): acces securizat la linia de comandă pe alt dispozitiv.

•	ICMP (Internet Control Message Protocol): folosit de ping pentru testarea conexiunii.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 7. DNS și DHCP

•	DNS (Domain Name System): traduce numele site-urilor (ex. www.exemplu.com) în adrese IP.

•	DHCP (Dynamic Host Configuration Protocol): alocă automat adrese IP dispozitivelor din rețea.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 8. Servere de mail și protocoalele lor

•	SMTP (Simple Mail Transfer Protocol): trimite mailurile către servere.

•	POP3 (Post Office Protocol v3): descarcă mailurile local.

•	IMAP (Internet Message Access Protocol): sincronizează mailurile pe toate dispozitivele.

Fluxul: Client → SMTP → Server Destinatar → POP3/IMAP pentru citirea mailului.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🟢 9. Unelte de testare a rețelei

•	ping – verifică dacă un dispozitiv răspunde.

•	traceroute (tracert pe Windows) – arată ruta pachetelor prin rețea.

•	ipconfig (Windows) / ifconfig sau ip a (Linux) – afișează setările IP.

•	nslookup – verifică răspunsul serverului DNS.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🆕 10. Mini-capitol: Prima întâlnire cu Cisco Packet Tracer

•	Ce este: aplicație de simulare a rețelelor dezvoltată de Cisco, utilă pentru exerciții practice.

•	Instalare: link către Cisco NetAcad (gratuit după crearea contului).

•	Interfața: zona de lucru, bibliotecă de echipamente, cabluri.

•	Demo rapid: adaugă două PC-uri, un switch, conectează cablurile și configurează IP-urile manual.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🛠️ EXERCIȚII PRACTICE

🔹 Exercițiul 1 – Identificarea adresei IP

•	Pe Windows: ipconfig

•	Pe Linux: ip a

•	Notează IP-ul, masca și gateway-ul.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🔹 Exercițiul 2 – Configurarea IP-ului static

•	Windows:

o	Control Panel ➜ Network and Sharing Center ➜ Change adapter settings ➜ Properties ➜ TCP/IPv4 ➜ „Use the following IP address”

o	IP: 192.168.1.50 Mask: 255.255.255.0 Gateway: 192.168.1.1

•	Linux: editează fișierul netplan sau folosește Network Manager.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🔹 Exercițiul 3 – Testarea conexiunii

•	ping 8.8.8.8

•	ping www.google.com și observă dacă se rezolvă numele.

•	tracert www.google.com (Windows) sau traceroute www.google.com (Linux).

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🔹 Exercițiul 4 – Explorarea DNS și Mail

•	nslookup www.google.com – vezi IP-ul site-ului.

•	nslookup -type=MX gmail.com – vezi serverele de mail.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

🔹 Exercițiul 5 – Demo Cisco Packet Tracer

•	Adaugă 2 PC-uri și 1 switch.

•	Configurează IP-urile (192.168.1.10 și 192.168.1.11).

•	Conectează cablurile și testează conexiunea cu ping.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

📝 Test de verificare

1\.	Care este diferența dintre LAN și WAN?

2\.	Ce face un router și ce face un switch?

3\.	De ce este important DNS?

4\.	Ce protocol folosești pentru a trimite mailul către server?

5\.	Cum verifici dacă două PC-uri sunt conectate?

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

✅ Rezultatul Modulului 1

După finalizarea acestui modul vei putea:

•	explica și demonstra funcționarea rețelelor de bază;

•	configura și testa IP-uri;

•	folosi unelte de diagnostic precum ping și nslookup;

•	înțelege protocoalele DNS, DHCP, SMTP, POP3 și IMAP;

•	crea o topologie simplă vizuală în Packet Tracer.



