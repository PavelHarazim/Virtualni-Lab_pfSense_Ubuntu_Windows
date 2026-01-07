# Virtualni-Lab_pfSense_Ubuntu_Windows
Simulace firemní sítě s implementací open-source pfSense firewallu.


                     INTERNET
                        |
                   (NAT - VirtualBox)
                        |
                ┌─────────────────┐
                │     pfSense     │
                │  WAN: DHCP      │
                │  LAN: 192.168.1.1
                └───────┬─────────┘
                        |
              ──────────┴──────────
              Internal Network (LAN)
                        |
        ┌───────────────┼────────────────┐
        |               |                |
┌────────────┐   ┌────────────┐   ┌──────────────┐
│ Ubuntu SRV │   │ Ubuntu SRV │   │ Windows 10   │
│ Server 1   │   │ Server 2   │   │ Workstation  │
│ DHCP IP    │   │ DHCP IP    │   │ DHCP IP      │
│ SSH        │   │ Services   │   │ Wireshark    │
└────────────┘   └────────────┘   └──────────────┘
