# MeinProjekt – GitHub Repository Setup und Workflow

## 🔧 GitHub Repository Setup

- GitHub-Repository `MeinProjekt` erstellt unter:  
  `git@github.com:Zerschmuser/MeinProjekt.git`

## 🔑 SSH-Konfiguration

- SSH-Key verwendet (bereits vorhanden oder neu erstellt).
- Key bei GitHub unter Settings > SSH Keys hinzugefügt.

## 💻 Lokales Repository und Git-Konfiguration

- Projekt lokal geklont via SSH:
  `git clone git@github.com:Zerschmuser/MeinProjekt.git`
- Git konfiguriert:
  ```bash
  git config user.name "Zerschmuser"
  git config user.email "175074114+Zerschmuser@users.noreply.github.com"
  ```
## 📝 Initialer Commit

- Datei `main.py` erstellt mit folgendem Inhalt:
  ```python
  print('Hallo Welt')