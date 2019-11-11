# Bat-n-Saq -- Ein Felderbausdetektor und SAQ-empfänger

Versuch eines Bausatzes für Schüler und Studentengruppen von [Y09](https://www.darc.de/der-club/distrikte/y/ortsverbaende/09/) und [Y07](https://www.darc.de/der-club/distrikte/y/ortsverbaende/07/).

Der Fledermausdetektorbausatz von [Franzis](https://www.franzis.de/maker/bausaetze/fledermausdetektor-zum-selberbauen-bausatz) eignet sich auch hervorragend als [Empfänger](https://www.youtube.com/watch?v=Cch6r8CrXTE) für den VLF Sender [SAQ](https://alexander.n.se/die-radiostation-saq-grimeton/?lang=de). Leider ist der darin enthaltene AM/FM Empfängerbaustein [CD2003](http://www.ak-modul-bus.de/stat/am_fm_empfaenger_cd2003,pd950!0,,CD2003.html) wenn überhaupt, nur noch als SMD Bauelement zu bekommen. Dies macht den Aufbau für Schüler und Studenen schwierig. 

Hier versuche ich ein kleines Bausatzprojekt für einen gleichwertigen Empfänger/Fledermausdetektor. Dieser sollte mit absoluten Standardbauteilen auskommen und keine SMD Bauelemente verwenden. Alle Elemente sollten direkt auf die Platine gelötet werden und auch das "Gehäuse" sollte aus Platinenmaterial bestehen.

## Todo
 - [ ] Prototyp auf Lochraster aufbauen.
 - [ ] Prototyp als Fledermausdetektor testen.
 - [ ] Prototyp als Empfänger testen.
 - [ ] Ggf., HF-Frontend überarbeiten.
 - [ ] Rev.1 Platinen für Schaltung und Gehäuse.
 - [ ] Probeaufbau mit Schülern.
 - [ ] Bausätze zusammenstellen.

## Bill of Material
| Element(e) | Wert/Typ |  Reichelt  | Conrad | Preis (10) |
| ---------- | -------- | ---------- | ------ | ---------- |
| R8         | 12 | METALL 12,0 | -- | 0,049€ |
| R9 R10     | 22 | METALL 22,0 | -- | 0,049€ |
| R7         | 1k | METALL 1,00K | -- | 0,049€ |
| R1         | 10k | METALL 10,0K | -- | 0,049€ |
| R4         | 12k | METALL 12,0K | -- | 0,049€ |
| R6         | 22k | METALL 22,0K | -- | 0,049€ |
| R2 R5      | 39k | METALL 39,0K | -- | 0,049€ |
| R3         | 560k | METALL 560K | -- | 0,049€ |
| RV2        | 50k Lin | RK09K113-LIN50K | -- | 0,99€ |
| RV1        | 100k Lin | RK09K113-LIN100K | -- | 0,99€ |
| C1         | 680p NP0 | NPO-5 680P | -- | 0,10€ |
| C2 C4 C5 C8 C9 C10 | 10n | Z5U-2,5 10N| -- | 0,05€ |
| C12 C7     | 47n | Z5U-2,5 47N | -- | 0,07€ |
| C11 C14    | 10u Elko | RAD 10/35| -- | 0,02€ |
| C3 C13 C6  | 220u Elko | RND 150ECR AY | -- | 0,06€ |
| D1 D2      | BAT85 | BAT 85 | -- | 0,08€ |
| Q1         | 2N3904 | 2N 3904| -- | 0,04€ |
| U1         | LM555 | NE555 DIP | -- | 0,17€ |
| U2         | LM386 | LM386 DIP | -- | 0,22€ |
| SW1        | SPDT | -- | 1569017 | 0,71€ |
| J1         | Schraub-Terminal  | RND 205-00012 | -- | 0,19€ |
| J3         | Stereo Klinke mit Schalter | EBS 35 | -- | 0,29€ |
| --         | Ultraschallempfänger | -- | 507764 | 2.61€ | 
| --         | 9V Clip | CLIP 9V | -- | 0,29€ |
| --         | Paltienen | -- | -- | ???€ |
| Summe:     | -- | -- | -- | 7,91€ + X |   

