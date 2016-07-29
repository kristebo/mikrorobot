# moduler
1. En modul til mikroroboten er en del som skal kunne festes på roboten for å:
* gi den nye egenskaper.
* utføre spesielle oppgaver.

2. Moduler skal kunne lages av hvem som helst, men det er noen krav:
* Basen på roboten er 20x20mm aluminium ekstrusjoner,
* Montering av moduler må passe disse. Legge ved en hullplate for montering.
(ai for hulplate)
* Modulen må ikke være for tung eller påføre roboten høy belastning.
* Alle moduler består av en mcu (ROS-node) og komuniserer med ros på rpi via seriell.
  * Består en modul av fler noder må disse også defineres i passende stack.
* Tilkobling er usb. (usb-hub)

3. Sensormoduler.
* Sensormoduler er spesielle siden de kan brukes til å skaffe odometrisk data for nav-stack
* implementasjonen er den samme, men krever at man koder støtte for sensordata i ROS.

# TODO:
* lage hullplate i AI
* Skaffe 12V powered usb-hub
* mikrorobot modulstack i ROS
