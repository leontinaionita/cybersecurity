# Modulul 1 – Introducere in Retele

> 🧭 Acest modul ofera o baza despre ce inseamna o retea de calculatoare, elementele ei componente, protocoalele de baza, modelul OSI si TCP/IP, unelte de diagnostic si primul laborator in Cisco Packet Tracer.

---

## 🎯 Obiective
La finalul modulului vei putea:
- explica ce este o retea si ce beneficii ofera;
- diferentia tipurile de retele (LAN, WLAN, WAN, VPN);
- descrie rolul dispozitivelor de retea (switch, router, access point, firewall);
- explica modelul OSI si stiva TCP/IP;
- configura adrese IP pe Windows si Linux;
- intelege rolul DNS si DHCP;
- folosi unelte de test (ping, traceroute/tracert, nslookup, ipconfig/ifconfig/ip);
- construi o topologie simpla in Cisco Packet Tracer si testa conectivitatea.

---

## 📚 Cuprins
- [1. Ce este o retea](#1-ce-este-o-retea)
- [2. Tipuri de retele](#2-tipuri-de-retele)
- [3. Dispozitive de retea](#3-dispozitive-de-retea)
- [4. Modelul OSI si TCP/IP](#4-modelul-osi-si-tcpip)
- [5. Adrese IP si Subretele](#5-adrese-ip-si-subretele)
- [6. Protocoale comune](#6-protocoale-comune)
- [7. DNS si DHCP](#7-dns-si-dhcp)
- [8. Servere de mail si protocoale](#8-servere-de-mail-si-protocoale)
- [9. Unelte de testare](#9-unelte-de-testare)
- [10. Mini-demo: Cisco Packet Tracer](#10-mini-demo-cisco-packet-tracer)
- [Exercitii practice](#exercitii-practice)
- [Test de verificare](#test-de-verificare)
- [Rezumatul modulului](#rezumatul-modulului)

---

## 1. Ce este o retea
O **retea de calculatoare** este un grup de doua sau mai multe dispozitive conectate intre ele pentru a partaja date, resurse si servicii.

**Exemple:**
- doua laptopuri conectate prin Wi-Fi la acelasi router
- server de fisiere intr-o companie
- Internetul – cea mai mare retea publica din lume

**Beneficii:**
- partajare resurse hardware/software
- comunicare rapida intre utilizatori
- centralizare si securizare mai buna a datelor

---

## 2. Tipuri de retele
- **LAN** (Local Area Network) – retea locala (ex.: birou, scoala)
- **WLAN** (Wireless LAN) – retea locala fara fir
- **WAN** (Wide Area Network) – acopera distante mari (ex.: Internetul)
- **MAN** (Metropolitan Area Network) – pentru orase
- **VPN** (Virtual Private Network) – conexiune securizata peste Internet

💡 **Analogie:** LAN este strada ta, WAN este autostrada, VPN este un tunel securizat pe autostrada.

---

## 3. Dispozitive de retea
- **Switch** – conecteaza mai multe dispozitive intr-o retea locala
- **Router** – interconecteaza retele diferite si dirijeaza traficul
- **Access Point (AP)** – ofera conectivitate wireless
- **Firewall** – filtreaza traficul pentru securitate
- **Servere** – ofera servicii: DNS, DHCP, Web, Mail etc.

---

## 4. Modelul OSI si TCP/IP
- **Model OSI** – 7 straturi:
  1. Physical  
  2. Data Link  
  3. Network  
  4. Transport  
  5. Session  
  6. Presentation  
  7. Application

- **Model TCP/IP** – 4 straturi:
  1. Application  
  2. Transport  
  3. Internet  
  4. Network Access

---

## 5. Adrese IP si Subretele
- **IPv4**: adrese pe 32 de biti (ex.: `192.168.1.10`)
- **Subnet Mask**: indica marimea retelei (ex.: `255.255.255.0`)
- **Gateway**: dispozitivul prin care traficul iese din retea (de obicei routerul)
- **IPv6**: adrese pe 128 de biti (ex.: `2001:db8::1`)

---

## 6. Protocoale comune
- **HTTP/HTTPS** – acces la pagini web
- **FTP/SFTP** – transfer fisiere
- **SSH** – administrare securizata la distanta
- **ICMP** – test diagnostic (ping)
- **Telnet** – administrare la distanta (nesecurizata)

---

## 7. DNS si DHCP
- **DNS (Domain Name System):** traduce numele de domeniu in adresa IP  
  ex.: `www.google.com` → `142.250.180.14`
- **DHCP (Dynamic Host Configuration Protocol):** atribuie automat adrese IP dispozitivelor din retea.

---

## 8. Servere de mail si protocoale
- **SMTP** – trimite emailul de pe client catre server
- **POP3** – descarca emailul pe client
- **IMAP** – sincronizeaza emailul intre client si server

---

## 9. Unelte de testare

### Windows
```bash
ipconfig
ping 8.8.8.8
tracert www.google.com
nslookup www.google.com
Linux
bash
Copiază codul
ip a
ping 8.8.8.8
traceroute www.google.com
nslookup www.google.com
10. Mini-demo: Cisco Packet Tracer
Creeaza o topologie cu 2 PC-uri + 1 switch

Atribuie IP-uri manual:

PC1: 192.168.1.10/24

PC2: 192.168.1.11/24

Testeaza conexiunea cu ping intre PC-uri.

📝 Exercitii practice
Identifica adresa IP a calculatorului tau:

bash
Copiază codul
ipconfig       # Windows
ip a           # Linux
Seteaza IP static in Windows:
Control Panel → Network and Sharing Center → Change adapter settings → Properties → TCP/IPv4 → Use the following IP address.

Testeaza conectivitatea:

bash
Copiază codul
ping 8.8.8.8
ping www.google.com
Interogheaza un server DNS:

bash
Copiază codul
nslookup www.openai.com
Creeaza in Cisco Packet Tracer o retea cu 2 PC-uri si 1 switch.

❓ Test de verificare
Care este diferenta dintre LAN si WAN?

Ce face un router fata de un switch?

De ce avem nevoie de DNS?

Ce protocol trimite emailul catre server?

Cum testezi daca doua PC-uri comunica?

🏁 Rezumatul modulului
ai invatat conceptele fundamentale de retele;

cunosti principalele dispozitive si protocoale;

poti configura/testa IP-uri;

poti folosi unelte de diagnostic (ping, traceroute, nslookup);

poti crea o topologie simpla in Cisco Packet Tracer.

