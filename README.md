# TP2-Reseau
## I
### 1/
ips choisis : 10.10.10.33/30 et 10.10.10.34/30
Reseau : 10.10.10.32
broadcast : 10.10.10.35
commandes utilisées : New-NetIPAddress –InterfaceIndex 22 –IPAddress 10.10.10.33 –PrefixLength 30
et New-NetIPAddress –InterfaceIndex 11 –IPAddress 10.10.10.34 –PrefixLength 30
### 2/
PS C:\WINDOWS\system32> ping 10.10.10.34

Envoi d’une requête 'Ping'  10.10.10.34 avec 32 octets de données :
Réponse de 10.10.10.34 : octets=32 temps=6 ms TTL=128
Réponse de 10.10.10.34 : octets=32 temps=1 ms TTL=128
Réponse de 10.10.10.34 : octets=32 temps=1 ms TTL=128
Réponse de 10.10.10.34 : octets=32 temps=1 ms TTL=128

Statistiques Ping pour 10.10.10.34:
    Paquets : envoyés = 4, reçus = 4, perdus = 0 (perte 0%),
Durée approximative des boucles en millisecondes :
    Minimum = 1ms, Maximum = 6ms, Moyenne = 2ms
### 3/
