# Modulul 1 – Introducere in Retele

> 🧭 Sumar: ce este o retea, tipuri de retele (LAN, WAN, VPN), dispozitive, modelul OSI si TCP/IP, IP & subnetare, protocoale (DNS, DHCP, HTTP/HTTPS, FTP, SSH, ICMP), unelte (ping, tracert, nslookup), mini-demo in Cisco Packet Tracer, exercitii si test.

## Obiective
La finalul modulului vei putea:
- explica ce este o retea si cum functioneaza;
- diferentia tipurile de retele (LAN, WAN, VPN etc.);
- recunoaste si descrie dispozitivele de retea de baza;
- intelege modelul OSI si stiva TCP/IP;
- configura si testa adrese IP pe Windows si Linux;
- intelege rolul protocoalelor DNS, DHCP, SMTP, POP3 si IMAP;
- folosi unelte de test (ping, traceroute/tracert, ipconfig/ifconfig/ip);
- crea o prima topologie vizuala in Cisco Packet Tracer.

## Cuprins
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
- [Rezultatul modulului](#rezultatul-modulului)

## 1. Ce este o retea
O retea este un grup de doua sau mai multe dispozitive conectate pentru a partaja informatii si resurse.  
**Exemple:** doua laptopuri prin Wi-Fi, un server de fisiere in firma, Internetul (cea mai mare retea).

**Beneficii:** partajare resurse, comunicare rapida, administrare centralizata.

## 2. Tipuri de retele
- **LAN** (Local Area Network)
- **WLAN** (Wireless LAN)
- **WAN** (Wide Area Network)
- **MAN** (Metropolitan Area Network)
- **VPN** (Virtual Private Network)

> Analogie: LAN = strada ta, WAN = autostrada, VPN = tunel securizat pe autostrada.

## 3. Dispozitive de retea
- **Switch**, **Router**, **Access Point**, **Firewall**, **Server** (DNS, DHCP, mail, web etc.)

## 4. Modelul OSI si TCP/IP
**OSI (7 straturi):** Physical, Data Link, Network, Transport, Session, Presentation, Application  
**TCP/IP (4 straturi):** Application, Transport, Internet, Network Access

## 5. Adrese IP si Subretele
- **IPv4:** ex. `192.168.1.10`
- **Subnet Mask:** ex. `255.255.255.0`
- **Gateway:** de obicei routerul retelei

## 6. Protocoale comune
HTTP/HTTPS, FTP, SSH, ICMP.

## 7. DNS si DHCP
- **DNS:** traduce nume → IP
- **DHCP:** aloca automat adrese IP

## 8. Servere de mail si protocoale
- **SMTP** (trimitere)
- **POP3/IMAP** (citire/sincronizare)

## 9. Unelte de testare
```bash
# Windows
ipconfig
tracert www.google.com
nslookup www.google.com

# Linux
ip a
traceroute www.google.com
nslookup www.google.com
