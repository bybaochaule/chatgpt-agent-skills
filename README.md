Was sind ChatGPT Agent Skills?

Einfach gesagt: Agent Skills sind wiederverwendbare “Fähigkeiten” oder Arbeitsanleitungen, die einem ChatGPT-Agenten helfen, bestimmte Aufgaben zuverlässiger zu erledigen.

Man kann sie sich wie Rezepte vorstellen:

Ein Rezept sagt nicht nur was gemacht werden soll, sondern auch wie.

Ein ChatGPT-Agent kann nicht nur antworten, sondern auch handeln: Informationen suchen, Webseiten nutzen, Dateien analysieren, Code ausführen oder mit verbundenen Apps arbeiten. OpenAI beschreibt ChatGPT Agent als System, das Aufgaben mit einem eigenen virtuellen Computer erledigen und passende Werkzeuge auswählen kann.

Wie funktionieren Skills?

Ein Skill enthält normalerweise:

Name: Wie der Skill heißt
Beschreibung: Wann der Skill benutzt werden soll
Anweisungen: Welche Schritte der Agent befolgen soll
manchmal auch Dateien, Vorlagen oder Skripte

In der Entwickler-Dokumentation beschreibt OpenAI einen Skill als ein versioniertes Bündel von Dateien mit einer SKILL.md-Datei. Diese Datei enthält die wichtigsten Informationen und Anweisungen für den Agenten.

Beispiel für Anfänger

Stell dir vor, du hast einen Skill namens “Excel-Bericht erstellen”.

Dieser Skill könnte dem Agenten sagen:

Wenn der Nutzer eine Tabelle hochlädt, prüfe die Daten, berechne Summen, erstelle Diagramme und schreibe eine kurze Zusammenfassung.

Dann muss der Nutzer nicht jedes Mal alle Schritte erklären. Der Agent erkennt:
“Diese Aufgabe passt zu diesem Skill.”

Wie wählt der Agent einen Skill aus?

Es gibt zwei einfache Wege:

Direkt: Du sagst dem Agenten: “Benutze diesen Skill.”
Automatisch: Der Agent liest die Beschreibung der verfügbaren Skills und entscheidet selbst, welcher passt. OpenAI nennt das explizite und implizite Aktivierung.

Damit nicht zu viel Text auf einmal geladen wird, sieht der Agent zuerst nur Name, Beschreibung und Speicherort eines Skills. Erst wenn der Skill wirklich gebraucht wird, lädt er die vollständigen Anweisungen.

Kurz gesagt

ChatGPT Agent Skills sind wie kleine Handbücher für spezielle Aufgaben.
Sie helfen dem Agenten, wiederholbare Arbeiten strukturierter, schneller und konsistenter zu erledigen.

Zum Beispiel:

Ohne Skill: “Mach irgendwie einen Bericht.”
Mit Skill: “Folge diesen klaren Schritten und erstelle den Bericht im richtigen Format.”
