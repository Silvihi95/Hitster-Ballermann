# 🌴 Ballermann-Hitster 🍻

Ein rein browserbasiertes Timeline-Kartenspiel, inspiriert von dem beliebten Gesellschaftsspiel "Hitster". Perfekt für die nächste Party, den Malle-Urlaub oder einfach einen lustigen Abend mit Freunden! 

## 🎮 Über das Spiel

Bei Ballermann-Hitster geht es darum, Party- und Ballermann-Songs chronologisch in die richtige Reihenfolge zu bringen. Das Spiel zieht sich vollautomatisch die Lieder aus einer beliebigen Spotify-Playlist. Ihr hört den Song, ratet das Erscheinungsjahr und ordnet ihn in eurer persönlichen Timeline ein. 

## ✨ Features

* **Automatische Spotify-Anbindung:** Keine Lieder mehr manuell eintragen! Verbinde dich einfach mit deinem Spotify-Account und füge den Link einer beliebigen öffentlichen Playlist ein.
* **Integrierter Player:** Das Spiel lädt automatisch den offiziellen Spotify-Web-Player, um die Songs direkt im Browser abzuspielen.
* **Drag & Drop Timeline:** Ziehe die geheime Songkarte intuitiv an die richtige Stelle in deiner Zeitachse.
* **Hotseat-Multiplayer:** Spielt mit beliebig vielen Freunden an einem einzigen Gerät (Smartphone, Tablet oder Laptop).
* **Hitster-Regelwerk:** Zu Beginn liegt bereits eine Startkarte als zeitliche Orientierung in der Mitte. Wer zuerst 10 (oder eine selbst gewählte Anzahl) Karten richtig in seiner Timeline platziert hat, gewinnt!

## 🛠️ Einrichtung & Setup (für GitHub Pages)

Damit das Spiel bei dir läuft, muss es über einen Webserver (wie GitHub Pages) gehostet werden und mit der Spotify-API kommunizieren. 

1. Lade den Code in dein GitHub-Repository hoch und aktiviere **GitHub Pages**.
2. Erstelle eine **Spotify Developer App** im [Spotify for Developers Dashboard](https://developer.spotify.com/).
3. Trage in der Spotify App unter "Redirect URIs" deine GitHub-Pages-Adresse ein.
4. Kopiere deine **Client-ID** aus dem Spotify Dashboard.
5. Öffne die `index.html` in diesem Repository und trage deine Client-ID in die dafür vorgesehene Variable (ca. Zeile 108) ein:
   `const CLIENT_ID = 'DEINE_CLIENT_ID_HIER';`
6. Speichern, neu laden und spielen!

## 🎯 Spielablauf

1. Klicke auf "Mit Spotify einloggen".
2. Füge einen Link zu einer Spotify-Playlist ein (z. B. eine Ballermann- oder 90er-Playlist) und klicke auf "Lieder importieren".
3. Tragt die Spielernamen ein und legt fest, wie viele Karten zum Sieg benötigt werden.
4. Der Spieler, der an der Reihe ist, zieht einen Song, spielt ihn ab und zieht die geheime Fragezeichen-Karte an die Stelle in der Timeline, in die der Song zeitlich passt. 
5. Klicke auf "Auflösen". Ist es richtig, gibt es einen Punkt!

---
**Disclaimer:** *Dies ist ein rein privates, nicht-kommerzielles Fanprojekt. Es besteht keinerlei Verbindung zu den Machern des Original-Spiels "Hitster".*
