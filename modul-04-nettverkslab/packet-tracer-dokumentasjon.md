# Kontornettverk – Cisco Packet Tracer

Dette dokumentet beskriver hvordan jeg har satt opp et enkelt nettverk med en switch og to PC-er i Cisco Packet Tracer.

## Nettverksoversikt
| Enhet | Rolle | IP-adresse | Kommentar |
|-------|-------|------------|-----------|
| Switch0 | Kobler sammen enhetene | - | Sentralt bindeledd |
| PC0 | Klient-PC 1 | 192.168.1.10 | Statisk IP |
| PC1 | Klient-PC 2 | 192.168.1.11 | Statisk IP |

## Nettverksdiagram
![Nettverksdiagram] (Screenshot 2026-11-09 193943.png)

## Konfigurasjon
Jeg har konfigurert begge PC-ene med IP-adresser i samme subnett (192.168.1.x), slik at de ligger i samme lokale nettverk.

## Testing
- Ping-test er utført mellom PC0 og PC1.
- Forbindelsen fungerer feilfritt.

## Oppsummering
Jeg har lært å koble sammen enheter via en switch og sette statiske IP-adresser.
