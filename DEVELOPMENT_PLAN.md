# Entwicklungsplan

## Phase 0 – sichere Grundlage
- [x] Öffentliches Zielrepository angelegt und Schreibzugriff geprüft.
- [x] Projektübersicht und klare Nicht-Zugehörigkeits-Erklärung ergänzt.
- [x] OpenCode-MIT-Lizenzhinweis als Grundlage dokumentiert.
- [ ] Upstream-Stand (Release/Commit) auswählen und festhalten.
- [ ] Vollständige OpenCode-Quellbasis einschließlich Historie und Lizenzdateien übernehmen.
- [ ] Prüfen, ob alle eingebetteten Pakete und Assets zusätzliche Lizenzhinweise benötigen.

## Phase 1 – reproduzierbarer Start
- [ ] Installations- und Build-Anweisungen auf Windows, Linux und ChromeOS-Entwicklungsumgebung dokumentieren.
- [ ] Abhängigkeiten, Laufzeitversionen und Build-Schritte reproduzierbar festlegen.
- [ ] CI für Formatierung, Typprüfung, Tests und Sicherheitsprüfung einrichten.
- [ ] Upstream-Änderungen von STREAMIOV-Anpassungen klar trennen.

## Phase 2 – STREAMIOV-Projektwissen
- [ ] Projektarchitektur und verbindliche Produktgrenzen als versionierte Dokumentation abbilden.
- [ ] Nur freigegebene, nicht geheime Projektinformationen als Agentenkontext verwenden.
- [ ] Schutzregeln für produktive Repositories, Secrets und Deployments technisch durchsetzen.

## Phase 3 – Agenten und Aufgabensteuerung
- [ ] Spezialistenrollen für Studio, Audio, KI, Spiele, Design, Sicherheit, Integration und Tests definieren.
- [ ] Persistente Aufgaben, Abhängigkeiten, Wiederaufnahme und nachvollziehbare Statusübergänge implementieren.
- [ ] Parallele Änderungen über getrennte Branches/Arbeitsbereiche isolieren.
- [ ] Unabhängige Reviews und Konfliktprüfung vor Zusammenführung erzwingen.

## Phase 4 – Qualität und Freigabe
- [ ] Unit-, Integrations- und End-to-End-Tests ausführen.
- [ ] Sicherheits- und Lizenzprüfung automatisieren.
- [ ] Fehlerberichte mit reproduzierbaren Schritten und Testergebnissen dokumentieren.
- [ ] Releases erst nach bestandenen Qualitäts-Gates veröffentlichen.

## Kosten- und Lizenzhinweis
Die Software kann intern kostenlos eingesetzt werden. Kosten externer Modellanbieter, APIs, Hosting-Dienste oder zusätzlicher Supportleistungen sind davon getrennt und können weiterhin anfallen. Kommerzielle Angebote müssen die jeweils geltenden Open-Source-Lizenzen und Drittanbieterbedingungen einhalten.
