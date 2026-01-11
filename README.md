# Virtualní Lab - pfSense + Ubuntu + Windows
Simulace firemní sítě s implementací open-source pfSense firewallu. Tento lab simuluje malou firemní síť pro účely učení a praxe v networkingu a cybersecurity.

<img width="1479" height="2091" alt="Navrh labu1 drawio" src="https://github.com/user-attachments/assets/60da279d-95cd-4787-986a-6cb26acaf71d" />

# pfSense Firewall VM

- Hlavní firewall a router s NAT a DHCP
- Konfigurace LAN/WAN sítí
- Základní firewall rules pro povolení/omezení provozu
- Monitorování provozu a logování síťových událostí

# Windows VM (Workstation)

- Připojena do LAN za pfSense firewallem
- Testovací klient pro firewall rules
- Slouží pro analýzu provozu (Wireshark) a testování bezpečnostních politik
