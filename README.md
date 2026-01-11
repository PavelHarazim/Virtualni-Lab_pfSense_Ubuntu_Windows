# Virtualní Lab - pfSense + Ubuntu + Windows
Simulace firemní sítě s implementací open-source pfSense firewallu. Tento lab simuluje malou firemní síť pro účely učení a praxe v networkingu a cybersecurity.

<img width="472" height="576" alt="shape_1PU4gb_LPHZZuOmYUeaQX at 26-01-07 16 38 53" src="https://github.com/user-attachments/assets/9a65d56f-1835-4b95-a339-87b445df6c26" />

# pfSense Firewall VM

- Hlavní firewall a router s NAT a DHCP
- Konfigurace LAN/WAN sítí
- Základní firewall rules pro povolení/omezení provozu
- Monitorování provozu a logování síťových událostí

# Windows VM (Workstation)

- Připojena do LAN za pfSense firewallem
- Testovací klient pro firewall rules
- Slouží pro analýzu provozu (Wireshark) a testování bezpečnostních politik
