# media-queries-crash-course
 
Erste Schritte CSS
 
## Einführung
### Media Queries im CSS
```css
html, body{
    width: 100%;
    height: 100%;
    background-color: crimson;
}
 
@media (max-width: 1024px){
    html, body{
        width: 100%;
        height: 100%;
        background-color: darkolivegreen;
    }
}
```
### Typische Bedingung
 
|Bedingung|Bedeutung|
|---|---|
|`max-width`|Stile gelten bis dieser Größe|
|`min-width`|Stile gelten ab dieser Größe|
|`orientation`|Bildschirmausrichting `landscape` oder `portrait`|
|`screen`|Für bildschirme gültig|
|`print`|Für Drucker gültig|
|`not`|Invertiert die Bedingung|
 
### Einfaches Beispiel
 
## Terminal wichtige Befehle
 
|Bedingung|Bedeutung|
|---|---|
|`dir`,`ls`|Inhaltsverzeichnis anzeigen|
|`cd`|Verzeichnis wechseln|
 
### Git Befehle
 
|Bedingung|Bedeutung|
|---|---|
|`git clone`|Klont ein Git-Repo|
|`git add .`|Alle Dateien ins Repo übernehmen|
|`git commit -m "Text zum Commit"`|Commit erstellen|
|`git push`|Alle Dateien ins Repo übernehmen|


# Aufgabenstellung
### 1. Breakpoints nach Bootstrap
Setzten die Breakpoints nach Bootstrap so um, das sie jeweilige Bildschirmgröße ausgegeben wird


### 2. Horizontal, Vertikal
Zeige an, ob de Bildschirm Querformat oder Hochformat ist


### 3. Ausdrucken
Wenn die Seite ausgedruckt wird, soll der `large`-Inhalt ausgegeben werden und das Aussehen angepasst werden:
- Hintergrund weiss
- Schriftfarbe Schwarz
- Bilder weg

### 4. 3-Spalten-Layout
Setze ein 3 Splaten-Layout mit `flex` oder `grid`um.

Anforderungen:
- `large` und größer: 3 Spalten
- `medium` und `smal`: 2 Spalten
- `smal` und kleiner: 1 Spalte