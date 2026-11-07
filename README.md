# Automatisiertes Hugo Portfolio

| | |
| :--- | :--- |
| Titel der Semesterarbeit | Automatisiertes Hugo Portfolio |
| Name | Dodoe Rumiñahui Mannale |
| Studiengang | Dipl. Informatiker/in HF, ITCNE25, TBZ |
| Semester | Semester 2 |

Dieses Repository enthält die Dokumentation meiner 2. Semesterarbeit: Projektdefinition, Projektmanagement, technische Umsetzung und Fazit. Der Code des Produkts liegt im Repository [RuminahuiM/hugo-portfolio-setup](https://github.com/RuminahuiM/hugo-portfolio-setup).

**Lesen:** <https://ruminahuim.github.io/hugo-portfolio-semesterarbeit/>

Teil meines Portfolios: <https://ruminahuim.github.io/>

## Aufbau

| Pfad | Inhalt |
| --- | --- |
| `docs/index.md` | Startseite, Projektdefinition gemäss Einreichungsformular |
| `docs/documents/01_Projektmanagement/` | Ziele, Planung, Sprints |
| `docs/documents/02_TeschnischeUmsetzung/` | Technische Umsetzung |
| `docs/documents/03_Fazit/` | Fazit und Ausblick |
| `docs/documents/04_Anhaenge/` | Glossar und Quellen |
| `docs/resources/` | Bilder und Video |

## Lokal ansehen (PowerShell)

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
mkdocs serve
```

Die Seite wird bei jedem Push auf `main` automatisch mit GitHub Actions gebaut (`mkdocs build --strict`) und auf GitHub Pages veröffentlicht.

## Geschichte des Repositorys

Bis November 2026 hiess dieses Repository `RuminahuiM.github.io` und war mit Jekyll (Theme just-the-docs) direkt unter `ruminahuim.github.io` veröffentlicht. Danach wurde es umbenannt und auf Material for MkDocs umgestellt, damit alle Projektseiten gleich aussehen. Die Inhalte der Dokumentation sind unverändert.
