# Aufgabe:
Photo Gallery (Flex/Grid project)
- public repo auf dem eigenen github account erstellen, name zb "Photo Gallery Project"
- referenzen für photo gallerien auf google suchen, zb: https://supsystic.com/gallery-examples/
- informationen zu best practices bei readmes durchlesen: https://github.com/othneildrew/Best-README-Template
- readme schreiben, basierend auf dem gelernten
- code ordentlich strukturieren schreiben:
- order anlegen :
    "public" = dort befindet sich die index.html
    "public/styles" = dort befinden sich css dateien
    "public/images" = dort könnt ihr bilder hinterlegen, falls ihr sie nicht online laden wollt
- bilder für die photogallerie suchen, dafür hilft bei google folgende suchanfrage: "royalty free images" (zb https://picsum.photos/)

# Idee:
Eine Fotogallerie mit eigenen Photos von meinen gezeichneten Bildern. Die Images sollten sich um 180°drehen und einen weißen Rahmen haben auf dem sie sich drehen können. Als Referenz dient "Pictures to Frame" von https://supsystic.com/gallery-examples/.

# Vorgehensweise:
Als erstes war die Überlegung mit welchem Grid-Template sich das Projekt am Besten umsetzen lässt. Eine Zeichnung und die vorläufige Benennung der Images haben einen groben Überblick verschafft. Eventuelle Möglichkeiten der Erweiterung sollen über die Zeilenanzahl laufen.
So wurde für den Anfang ein Layout von 5 zu 3 geschaffen.
   
## HTML:
   Als ersten Step habe ich die HTML Struktur aufgebaut. Die Bilder eingebunden und vorläufig keinen Titel eingebaut, da dies der Plan nicht vorgesehen hat. 
   Als Hauptdiv dient eine figure die alle Bilder beinhaltet. Für die Verteilung auf dem Grid war dies völlig ausreichend. 
## CSS:
Das Grid war relativ schnell erstellt und benannt, dabei sind Bilder rausgeflogen, um eine gewisse Symmetrie zu schaffen. Aufgrund der verschiedenen Bildgrößen
waren bestimmte Vorstellungen nicht umsetzbar und wurden daher mit pragmagitischeren Ansätzen gelöst. Der Plan einen weißen Hintergrund zu haben wurde geändert, da es nicht mit der Ästhetik der Bilder gematcht hat. Von daher habe ich mich für einen hellen Grauton entschieden und dem ganzen einen Rahmen von 5px gegeben.
Danach ging es an die Rotation und der Überlegung, doch einen Titel einzufügen und diese miteinander zuverknüpfen. Die Rotation wird mit einem Hover auf den Images ausgelöst. Der Titel wird mit einer 1.5s Verzögerung angezeigt. 
Am Ende wurde es ein Grid von 4 zu 10 mit 17 Bildern.

# Mitwirkende:
- Frederick Reich https://github.com/FRickReich
- Hadi Nsreeny https://github.com/hnsreeny
- Danny Wild   https://github.com/DTHW 
- Chrissi Eisele https://github.com/zippiskiddy
