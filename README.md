# 🐍 My Snake Game by PRAYANSHU

Ein klassisches Snake-Spiel, umgesetzt mit Python's `turtle`-Modul. Steuere die Schlange, iss das Futter, wachse und vermeide Kollisionen mit den Wänden oder deinem eigenen Schwanz.

## 🎮 Spielprinzip

- Die Schlange bewegt sich automatisch in die aktuell eingestellte Richtung.
- Steuere sie mit den **Pfeiltasten**.
- Berührt der Kopf das blaue Futter, wächst die Schlange um ein Segment und der Punktestand steigt.
- Berührt die Schlange die Wand oder ihren eigenen Schwanz, ist das Spiel vorbei.

## 🛠️ Voraussetzungen

- Python 3.x
- Das `turtle`-Modul (Teil der Python-Standardbibliothek, keine Installation nötig)

## 🚀 Installation & Start

```bash
git clone https://github.com/<dein-username>/<dein-repo>.git
cd <dein-repo>
python main.py
```

## 📁 Projektstruktur

```
.
├── main.py            # Hauptspiel-Loop
├── snake.py            # Schlangen-Klasse (Bewegung, Steuerung, Wachstum)
├── food.py               # Futter-Klasse (zufällige Positionierung)
├── scoreboard.py           # Zeigt Punktestand und Game-Over-Meldung an
└── README.md
```

## 🕹️ Steuerung

| Taste | Aktion |
|-------|--------|
| ↑     | Nach oben bewegen |
| ↓     | Nach unten bewegen |
| ←     | Nach links bewegen |
| →     | Nach rechts bewegen |

## 📄 Lizenz

Dieses Projekt steht unter der MIT-Lizenz – frei nutzbar und veränderbar.
