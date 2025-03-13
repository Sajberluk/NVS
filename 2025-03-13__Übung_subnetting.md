# Übung Subnetting

## Übung 1

Bilde aus dem Netz 192.168.0.0 /24 4 Subnetze. Netze mit Mindestzahl an nutzbaren Host aber nicht darunter wählen: Netz a mit 20, Netz b mit 15, Netz c mit 30, und das Netz d mit den Rest Anteil der Netzwerkadressen.

**Antwort**
A: 0-31 --> 192.168.0.0 /27
B: 32-63 --> 192.168.0.32 /27
C: 64-95 --> 192.168.0.64 /27
D: 128-255 --> 192.168.0.128 /25

## Übung 2

Teile das Netz 193.170.20.0 /24 in 8 gleich große Netze! Erstelle eine Tabelle mit folgenden Angaben:
Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.

**Antwort**
            Netzwerkadresse          Nutzbare Hosts                      Broadcastadresse                Subnetzmaske

Netz 1       193.170.20.0    193.170.20.1 - 193.170.20.30                193.170.20.31                   255.255.255.224
Netz 2       193.170.20.32   193.170.20.33 - 193.170.20.62               193.170.20.63                   255.255.255.224
Netz 3       193.170.20.64   193.170.20.65 - 193.170.20.94               193.170.20.95                   255.255.255.224
Netz 4       193.170.20.96   193.170.20.97 - 193.170.20.126              193.170.20.127                  255.255.255.224
Netz 5       193.170.20.128  193.170.20.129 - 193.170.20.158             193.170.20.159                  255.255.255.224
Netz 6       193.170.20.160  193.170.20.161 - 193.170.20.190             193.170.20.191                  255.255.255.224
Netz 7       193.170.20.192  193.170.20.193 - 193.170.20.222             193.170.20.223                  255.255.255.224
Netz 8       193.170.20.224  193.170.20.225 - 193.170.20.254             193.170.20.255                  255.255.255.224


## Übung 3

172.28.40.0 /26 Teile wie folgt auf: 2 Netze!
Erstelle eine Tabelle mit folgenden Angaben:
Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.

**Antwort**
        Netzwerkadresse                 nutzbare Hosts                      Broadcastadresse                Subnetzmaske
Netz 1   172.28.40.0            172.28.40.1 - 172.28.40.30                   172.28.40.31                   255.255.255.224
Netz 2   172.28.40.32           172.28.40.33 - 172.28.40.62	                172.28.40.63                   255.255.255.224


## Übung 4

Wie lautet die Subnetzmaske bei der Netzadresse: 17.0.0.0 mit 10 verwendbaren Subnetzen, sowie mit mindestens 12 Hosts je Subnetz?
Antwort in Sätzen, wie sie zu dieser Lösung kommen; und erstelle eine Tabelle:

**Antwort**

## Übung 5

Bestimmen Sie die Subnetmaske mit folgenden Angaben:

Netzadresse: 210.52.190.0
Subnetze: Anzahl 5
Mindestanzahl von Hosts je Subnetz: 10

**Antwort**
255.255.255.224


## Übung 6

Teile  ein /30 Netz auf!    Wozu werden diese /30 Netze am häufigsten verwendet?
Antwort:

**Antwort**
Netzwerkadresse: 192.168.1.0
nutzbare Hosts: 192.168.1.1 - 192.168.1.2
Broadcastadresse: 192.168.1.3

Ein /30-Subnetz wird oft für Punkt-zu-Punkt-Verbindungen verwendet, bei denen nur zwei Geräte miteinander kommunizieren, wie z.B.: bei Verbindungen zwischen zwei Routern.



## Übung 7

Nennen Sie den jeweiligen Netz- und Hostanteil der Klassen A, B und C

**Antwort**
