# 🌧️ Wetter-Dashboard – Vergleich dreier Technologien

Dieses Meta-Repository vereint drei verschiedene Implementierungen eines einfachen Wetter-Dashboards:
**Python**, **JavaScript** (Vanilla) und **React mit TypeScript**. Ziel ist es, einen technologischen Vergleich darzustellen und gleichzeitig praxisnahe Umsetzungen bereitzustellen.

---

## 📄 Enthaltene Projekte

| Technologie | Projektname                                                                            | Beschreibung                                            |
| ----------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| Python      | [weather\_dashboard\_python](https://github.com/chefkoch0312/weather_dashboard_python) | Desktop-App mit `tkinter`, Debug-View, API-Testfunktion |
| JavaScript  | [weather\_dashboard\_js](https://github.com/chefkoch0312/weather_dashboard_js)         | Klassische HTML/JS-Lösung für Browser, leichtgewichtig  |
| React+TS    | [weather\_dashboard\_react](https://github.com/chefkoch0312/weather_dashboard_react)   | Moderne SPA mit React + TypeScript + Vite               |

---

## 🌎 Ziel dieses Repositories

Dieses Meta-Repo dient als Übersichts- und Vergleichsgrundlage:

* Demonstration unterschiedlicher Technologien für ein gemeinsames Problem
* Showcase für Portfolio und Bewerbungsgespräche
* Ausgangspunkt für Erweiterungen, Refactorings oder neue Interfaces

---

## 💡 Nutzungshinweise

Dieses Repository nutzt **Git Submodule**, um die Unterprojekte zu referenzieren.
Zur lokalen Einrichtung:

```bash
git clone --recurse-submodules https://github.com/chefkoch0312/weather_dashboard.git
cd weather_dashboard
```

Falls du das Projekt ohne `--recurse-submodules` geklont hast:

```bash
git submodule init
git submodule update
```

---

## 🧑‍💻 Autor

**Kai Dombrowski**
[GitHub-Profil](https://github.com/chefkoch0312)

---

## 🦮 Lizenz

Alle enthaltenen Projekte stehen unter der MIT-Lizenz.
Datenquelle: [wttr.in](https://wttr.in) (frei zugänglich ohne API-Key)
