# GitHub Portfolio Hub

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

|<img width="1280" height="640" alt="github" src="https://github.com/user-attachments/assets/67f336d8-d598-4f5f-8757-aa547c6eb6b1" />|
|---|

---

**GitHub Portfolio Hub** is a focused single-page frontend in GitHub Dark style.  
It consolidates your public developer profile, renders `README.md` client-side, shows live repository metrics (stars, forks, issues) and lists the latest commits — all without any backend.

### ✨ Features
- 📣 **Portfolio/Branding:** Present your repositories in a curated, unified interface.  
- 🧭 **Fast Deep-Dive:** View `README.md`, topics and commits directly in the browser.  
- 🔗 **Direct Linking:** Profile and repositories open in a new tab with one click.  
- 🌍 **Multilingual:** Full DE/EN UI translation (toggle switch).  
- ⚙️ **Zero-Backend:** Runs locally as a single `index.html` or hosted via GitHub Pages.  
- 🔑 **API Token Support:** Store your GitHub token locally for higher rate limits.  
- 🎨 **Animated UI Elements:** Info button and footer are visually highlighted.  
- 📊 **Live Metrics:** Stars, forks, issues, last commits at a glance.  

|                | Without Token (No PAT)                                    | With Token (PAT)                                              |
|----------------|-----------------------------------------------------------|---------------------------------------------------------------|
| **Rate Limit** | ~60 requests per hour per public IP                       | ~5000 requests per hour per user                              |
| **Access**     | Only public data                                          | Public data (same) – higher limit, private repos if scoped    |
| **Setup**      | No setup needed                                           | Requires generating & entering a token (PAT)                  |
| **Security**   | Safer (no token to manage)                                | Token must be stored locally (browser localStorage, private)  |
| **Performance**| May quickly hit the rate limit when loading READMEs/Commits| Stable, even with many repos and frequent refresh             |
| **User Exp.**  | Possible “Rate Limit Reached” errors                      | Smooth browsing, fewer interruptions                         |
| **Best For**   | Quick tests, casual use                                   | Regular usage, portfolio demos, heavy interaction             |
| **Drawback**   | Very limited requests                                     | Token management, minimal setup effort                        |

---

### 🚀 Getting Started
1. Clone or download this repository.  
2. Open `index.html` in your browser.  
3. By default, the profile **`bylickilabs`** is loaded automatically.  
   - Override with `?user=USERNAME` in the URL (e.g. `index.html?user=torvalds`).  

---

### 🔑 API Token
- **Without Token:** limited to ~60 requests/hour per public IP.  
- **With Token (Personal Access Token, PAT):** ~5000 requests/hour.  
- Enter the token in the **Info dialog** of the app.  
- The token is stored **only locally** in your browser (`localStorage`) and is **not shared**.  

---

### 💻 Tech Stack
- **HTML5 / CSS3**  
- **Vanilla JavaScript**  
- [Marked.js](https://marked.js.org/) for Markdown rendering  
- GitHub REST API v3  

---

### 📜 License
This project is released under the **MIT License**.  
See [LICENSE](LICENSE) for details.

---

👨‍💻 Developed with ❤️ by **Thorsten Bylicki · BYLICKILABS**

<br>

---

<br>

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

**GitHub Portfolio Hub** ist ein fokussiertes Frontend im GitHub-Dark-Design.  
Die Anwendung konsolidiert dein öffentliches Entwicklerprofil, rendert `README.md` client-seitig, zeigt Live-Metriken (Stars, Forks, Issues) und listet die letzten Commits — komplett ohne Backend.

### ✨ Funktionen
- 📣 **Portfolio/Branding:** Einheitliche, kuratierte Darstellung deiner Repositories.  
- 🧭 **Schneller Deep-Dive:** README, Topics und Commits sofort sichtbar.  
- 🔗 **Direkte Verlinkung:** Profil & Repos mit einem Klick im neuen Tab.  
- 🌍 **Mehrsprachig:** Vollständige DE/EN-Übersetzung der UI (umschaltbar).  
- ⚙️ **Zero-Backend:** Läuft lokal als einzelne `index.html` oder via GitHub Pages.  
- 🔑 **API-Token-Support:** Hinterlege dein GitHub-Token lokal für höhere Limits.  
- 🎨 **Animierte UI-Elemente:** Info-Button und Footer sind visuell hervorgehoben.  
- 📊 **Live-Metriken:** Stars, Forks, Issues, letzte Commits im Überblick.  

|                | Ohne Token (kein PAT)                                     | Mit Token (PAT)                                               |
|----------------|-----------------------------------------------------------|---------------------------------------------------------------|
| **Rate Limit** | ~60 Anfragen pro Stunde pro öffentliche IP                | ~5000 Anfragen pro Stunde pro Benutzer                        |
| **Zugriff**    | Nur öffentliche Daten                                     | Öffentliche Daten (gleich) – höhere Limits, private Repos bei passenden Rechten |
| **Setup**      | Keine Einrichtung nötig                                   | Erfordert Erstellung & Eingabe eines Tokens (PAT)             |
| **Sicherheit** | Sicherer (kein Token zu verwalten)                        | Token wird lokal gespeichert (Browser localStorage, privat)   |
| **Performance**| Sehr schnell Limit erreicht bei README/Commits            | Stabil, auch bei vielen Repos und häufigen Aktualisierungen   |
| **Nutzererfahrung** | „Rate Limit Reached“-Fehler möglich                  | Flüssige Nutzung, keine Unterbrechungen                       |
| **Geeignet für**   | Kurze Tests, gelegentliche Nutzung                    | Regelmäßige Nutzung, Portfolio-Präsentation, intensive Arbeit |
| **Nachteil**   | Sehr stark eingeschränkt                                  | Token-Verwaltung, kleiner zusätzlicher Aufwand                |

---

### 🚀 Einstieg
1. Dieses Repository klonen oder herunterladen.  
2. `index.html` im Browser öffnen.  
3. Standardmäßig wird das Profil **`bylickilabs`** geladen.  
   - Überschreiben mit `?user=USERNAME` in der URL (z. B. `index.html?user=torvalds`).  

---

### 🔑 API Token
- **Ohne Token:** ca. 60 Requests/Stunde pro öffentliche IP.  
- **Mit Token (Personal Access Token, PAT):** ca. 5000 Requests/Stunde.  
- Token im **Info-Dialog** der Anwendung eintragen.  
- Der Token wird **nur lokal** im Browser (`localStorage`) gespeichert und **nicht geteilt**.  

---

### 💻 Technischer Stack
- **HTML5 / CSS3**  
- **Vanilla JavaScript**  
- [Marked.js](https://marked.js.org/) für Markdown-Rendering  
- GitHub REST API v3  

---

### 📜 Lizenz
Dieses Projekt steht unter der **MIT-Lizenz**.  
Siehe [LICENSE](LICENSE) für Details.

---

👨‍💻 Entwickelt mit ❤️ von **Thorsten Bylicki · BYLICKILABS**
