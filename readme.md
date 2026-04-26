# LaTeX template für Assignments der AKAD University

## Installation

Entweder einfach eine der verbreiteten LaTeX Distributionen wie TexLive oder den Devcontainer nutzen. Natürlich geht auch Overleaf. In der `preamble/commands.tex` einfach die entsprechenden Werte setzen und die Dateien in `content/` editieren.

### Für kollaboratives Arbeiten in Overleaf
1. Overleaf Account (eine Person benötigt einen Gruppenaccount, der reicht dann für bis zu 10 Personen)
2. Anbindung an Git - Overleaf kann mit einem Git-Account verbunden
3. Die Person die den Gruppenaccount hat muss das Projekt mit allen anderen "collaborators" teilen, damit sie auf Zugriff u Schreibrechte haben

### Windows 11
1. Miktex (Paketverwaltung)
2. TexStudio (als Editor)
3. Hinweis: VS Code wie in unterer Beschreibung mit dem "Latex Workshop" Plugin möchte Tex Live (Paketverwaltung) oder Miktex zusammen mit Perl.. das hab ich irgendwie beides nicht zum laufen gebracht.

### Ubuntu 24.10

1. install vscode extensions `LaTeX Workshop` and `Zotero LaTeX`.
1. install zotero (e.g. via deb: [https://github.com/retorquere/zotero-deb](https://github.com/retorquere/zotero-deb)).
1. install [Better BibTex for Zotero](https://retorque.re/zotero-better-bibtex/).
1. install packages: `sudo apt install texlive-full`. (>7GB space!)

## Mein Setup

Ich nutze Linux, VSCode, TexLive und Zotero mit dem Better BibTex Plugin.

## Fragen, Fehler, Tipps

Für Fragen, Fehler und Tipps gerne einfach einen Issue öffnen. Aber denkt bitte dran, dass ich kein LaTeX Profi bin.
