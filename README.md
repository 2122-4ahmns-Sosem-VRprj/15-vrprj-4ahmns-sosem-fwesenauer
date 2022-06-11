# HTL-VRProject with XRInteractionToolkit !Template!

### Project description: 
This project serves as sample project for spatial audio. 
Explore sound in its basics in virtual reality (VR).

### Development platform: 
OS: Windows 10, Game Engine: Unity 2020.3.18f1, Visual Studio 2019, XR Interaction Toolkit 1.0.0-pre.8, XR Plugin Management 4.2.1, Oculus XR Plugin 1.10.0.

## Software/Hardware Requirements: 
Oculus hardware requirements https://support.oculus.com/248749509016567/
You need a VR headset in this case an Oculus Rift/Quest/Quest2

Examples: https://github.com/Unity-Technologies/XR-Interaction-Toolkit-Examples

When downlaoded, you have compile time errors in the project. To solve them install the XR interaction toolkit package via the Package Manager. (!Enable in Advanced Settings Preview Packages).

### Target platform: 
Oculus Rift/S; Quest/2

### Visuals: 
Screenshots (concept and experience), Video

![image](https://user-images.githubusercontent.com/72736373/173175407-01af0d5c-506e-4663-a62b-cae17eaf29f9.png)


Grobkonzept VR Projekt – Franziska Wesenauer
In meinem VR Spiel geht es darum, dass man drei Hasen finden und füttern muss, um von ihnen
Ostereier zu erhalten. Die im Anschluss in ein riesiges Osternest befördert werden müssen um das
Spiel zu gewinnen.
Der Grund, warum man das Spiel gerne spielt, ist dass es einfach großartig ist süße Hasen zu füttern
und allgemein wird die Umgebung sehr „niedlich“ gestaltet, wodurch man sich gerne in der
Umgebung aufhält.

Minigame 1:
Am Anfang des Spieles spawnt man auf einer Fläche vor dem Eingang des Labyrinths. Auf dieser
Fläche befinden sich drei „Felder“. Eins mit Karotten, eins mit Apfelbäumen und eines mit Blumen.
Von jedem dieser drei Dinge muss man eines Ernten, das daraufhin in einer Art Inventar angezeigt
wird. Dabei wird jeweils ein Sound abgespielt, der im späteren Verlauf noch nützlich sein wird. Der
Eingang des Labyrinths öffnet sich, sobald man alle drei hat. Nun ist die Aufgabe drei Hasen zu
finden. Sobald man in die Nähe von einem kommt, ist wieder derselbe Sound zu hören der beim
Ernten auch war und aufgrund dessen muss man sie füttern. Hat man das geschafft bekommt man
von dem gerade gefütterten Hasen ein Osterei, dass später dazu verwendet wird um die Ausgangstür

zu öffnen.
Minigame 2:
Wenn man die Tür erfolgreich geöffnet hat, befindet sich dahinter drei Buttons und etwas oberhalb
schwebt ein riesiges Osternest. Die zuvor gefundenen Eier befinden sich hinter den Buttons und
durch wiederholtes Drücken der Knöpfe werden sie nach oben befördert. Allerdings pro drücken nur
eine gewisse Höhe und man muss aufpassen, dass sie nicht wieder herunter fallen da sie dabei
kaputt gehen würden. Abgeschlossen ist das Ganze, sobald sich alle drei Eier im Korb befinden.

Liste Sounds:
Atmo, 3 Sounds für die Hasen, „Jump“-Sound, „Fress“-Sound

Arbeitsschritte:
1. Unity starten
2. Projekt anlegen
3. GitHub Repository anlegen
4. Maze importieren
5. Schauen dass Fortbewegung etc. funktioniert
6. 3D Assets und Sounds suchen
7. Whiteboxing
8. Ernten programmieren
9. Ernten testen
10. Labyrinth Hasen programmieren
11. Labyrinth Hasen testen
12. Minigame 2 programmieren
13. Minigame 2 testen
14. Überarbeitung
15. Final Build

Minigame 1 Beschreibung Franziska Wesenauer
Am Anfang des Spieles spawnt man auf einer Fläche vor dem Eingang des Labyrinths. Auf dieser Fläche befindet sich ein Apfelbaum mit einem Apfel, ein Korb mit einer Karotte und ein Feld mit Salat. Von jedem dieser Dinge wird eines eingesammelt und in einen Korb, den der Spieler in der Hand hat, gelegt. Beim Einsammeln der Objekte wird pro Gegenstand ein anderer Sound abgespielt. Als nächstes gehts ins Labyrinth, wo man die drei versteckten Hasen finden muss, in der Umgebung der Hasen werden wiederrum dieselben Sounds abgespielt wie bereits vorher auch und so sollte es möglich sein das richtige Futter den Hasen zuzuordnen. Wurden die jeweiligen Hasen gefüttert spawnt vor ihnen ein Osterei, das es jetzt aufzuheben gilt. Diese Ostereier kann man wieder in den Korb packen um sie bis zum Ausgang mitzunehmen. Am Ausgang ist ein Podest, auf das die Eier in der richtigen Reihenfolge gelegt werden müssen. War das erfolgreich öffnet sich die Tür zum Ausgang.
1. Gegenstände einsammeln
2. In Korb Legen
3. Hasen droppen Ostereier
4. Ostereier werden richtig angeordnet
5. Tür öffnet sich

### Third party material: 

For testing without a headset, use the XR Device Simulator (included in the xr interaction toolkit package):  https://www.youtube.com/watch?v=d4bTpkvBwrs

### Limitations/Problems: 

Copyright by smeerws :)
