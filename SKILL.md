Was ist SKILL.md?

SKILL.md ist die wichtigste Datei in einem Agent Skill.
Man kann sie sich wie eine Gebrauchsanleitung für den ChatGPT-Agenten vorstellen.

Ein Skill besteht aus einem Ordner mit Dateien. In diesem Ordner gibt es eine Datei namens SKILL.md. Diese Datei erklärt dem Agenten:

wie der Skill heißt
wann der Skill benutzt werden soll
was der Agent Schritt für Schritt tun soll
manchmal auch, welche Dateien, Skripte oder Regeln dazugehören

OpenAI beschreibt einen Skill als ein versioniertes Paket aus Dateien plus einer SKILL.md-Manifestdatei mit Informationen und Anweisungen.

Einfaches Beispiel
---
name: email-summary
description: Fasst E-Mails kurz und verständlich zusammen.
---

Benutze diesen Skill, wenn der Nutzer viele E-Mails hat
und eine kurze Zusammenfassung braucht.

Schritte:
1. Lies die E-Mails.
2. Erkenne die wichtigsten Themen.
3. Schreibe eine kurze Zusammenfassung.
4. Markiere wichtige Aufgaben oder Fristen.
Wie funktioniert SKILL.md?

Zuerst sieht der Agent meistens nur den Namen, die Beschreibung und den Pfad eines Skills. Dadurch weiß er: „Dieser Skill existiert.“ Dann entscheidet der Agent, ob der Skill zur Aufgabe passt. Wenn ja, liest er die vollständigen Anweisungen aus der Datei SKILL.md.

Zum Beispiel:

Nutzer: „Fasse diese E-Mails zusammen.“
Agent: „Das passt zum Skill email-summary.“
Dann liest der Agent SKILL.md und folgt den dort beschriebenen Schritten.

Warum ist SKILL.md wichtig?

SKILL.md macht den Agenten konsequenter und strukturierter.
Ohne Skill müsste der Nutzer jedes Mal genau erklären, wie die Aufgabe erledigt werden soll. Mit SKILL.md stehen die Regeln schon bereit.

Kurz gesagt:

SKILL.md ist die Anleitung, die einem ChatGPT-Agenten sagt, wann und wie er eine bestimmte Fähigkeit benutzen soll.
