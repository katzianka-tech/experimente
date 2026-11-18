# Experimente

Grafische Experimente, die komplett im Browser laufen: keine Bilder, keine Videos, keine Audiodateien, keine Bibliotheken. Alles wird live aus Code berechnet.

## Singularität

Ein 10-Sekunden-Intro aus der Ich-Perspektive. Im Lichtpunkt steht «ICH», du fliegst hindurch, es zerfällt. Danach geht es durch ein unendliches, sich verflüssigendes Fraktal, ein Kaleidoskop und durch die Singularität hinaus in den offenen Raum, wo sich «SINGULARITÄT» zusammensetzt.

- Ordner: [`singularitaet/`](singularitaet/index.html)
- Ton wird live synthetisiert (Web Audio), startet nach dem ersten Tippen
- Das Bild lässt sich jederzeit mit dem Finger ziehen, quetschen und dehnen. Beim Loslassen federt es zurück. Ein tiefes Grundbrummen folgt der Verformung und reisst bei zu viel Spannung, Bild und Klang zusammen.
- Technik: Raymarching eines unendlichen Menger-Schwamms in einem einzigen WebGL-Fragment-Shader, Bildrückkopplung für die fliessenden Spuren, Auflösung wird vor dem Start einmal passend zum Gerät gemessen

**Hinweis:** intensive Licht- und Bewegungseffekte.

### Online stellen (GitHub Pages)

1. Auf github.com dieses Repository öffnen, dann *Settings → Pages*.
2. Bei *Source* «Deploy from a branch» wählen, Branch `main`, Ordner `/ (root)`, *Save*.
3. Nach ein bis zwei Minuten ist das Intro erreichbar unter
   **https://katzianka-tech.github.io/experimente/singularitaet/**

Lokal reicht es, `singularitaet/index.html` im Browser zu öffnen.
