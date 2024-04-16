WLAN:
Vorlesung 3:
- Was ist der Wiederverwendungsabstand:
--> der Räumliche Abstand, bei dem man (bei Funkzellen) die gleiche Frequenz wieder benutzen darf
--> Beachte: Antennen verändern den Abstand


- Welche Modulationsarten kennen sie?
--> FSK: Frequency shift keying, Frequenzen wird 0 oder 1 zugewiesen

- Welche Modulationsart kommt bei wlans zum tragen:
--> Amplituden Phasen Modulation
--> Vorteil PhasenmodulatioN: Man kann die Phase beliebig einteilen nach der Phasenverschiebung --> Binary Phase SK; Quadruple PSK; 8 PSK...
    --> Aber je kleiner die Phasenabstände desto schwieriger es zu Unterscheiden
--> Amplituden- Modulation: 16 QAM, 32 QAM...


- Was versteht man unter einer Punktierung?
--> Angenommen man hat ein Datenstrom und ein Speicherelement
--> Vorne gehen Datenbits rein, hinten raus
--> ein datenstrang geht parallel an zwei Enden, demnach ergibt sich die Doppelte Datenrate also 100% Redundanz
--> Punktierung reduziert die Menge an redundanten Daten
Begrifflichkeiten:
m = 3 bedeutet, dass der Längste Pfad für einen Datenstrom aus 3 "Speicherelementen" besteht.
Lc heißt man zählt die Speicherelemente meist m+1
--> Durch die Punktierung kann man auf einen weiteren kodierungsschritt verzichten

Wahrscheiniche Prüfungsaufgabe:
OFDM Pfade rückwärts verfolgen können


Vorlesung 5 oder so:

Paritybits!
Was benötigt ein ESS--> Zwei BSS und ein Distribution System

Was sind die Vorteile von 16QAM gegenüber 16PSK?

16 QAM hat einen größeren FEHLERABSTAND!! --> Fehlertoleranter! Besseres Signal zu Rausch verhältnis
Was bringt das ganze: Je weiter man vom Sender weg kommt, desto kleiner die Signalstärke; Rauschen bleibt gleich --> Bei einem besseren SNR hat man eine *höhere Reichweite!*


- welche verschiedene Accessmethoden gibt es: (Quality of Service QoS) 
--> Best Effort, Bacjground, Video, Voice

Auf welcher Ebene wird das bearbeitet? 
--> Medienzugriffsverfahren


Welche schritte muss eine station abhandeln, damit sie sich mit einem AccessPoint verbindet:  
1. Scanning --> Default = Passiv: Beacon Frames auswerten; Aktiv = ProbeRequest schicken.
2. Authentification --> OpenSystem und sharedkey
3. Assoziation


Wireshark: Was macht die duration? --> SendeTime, dh alle anderen setzen ihren NAV solange wie der sender meint, dass er sendet (duration)

