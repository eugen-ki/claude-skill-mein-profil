---
name: mein-profil
description: Use when the member wants to set up or update their personal profile (Profil anlegen, Profil ändern, "mach die Skills zu meinen", Zielgruppe oder Stimme festlegen), or when another content skill reports that ~/.claude/mein-profil.md is missing or a field it needs is empty.
---

# Mein Profil

Legt **eine** Datei an, die alle Content-Skills lesen: `~/.claude/mein-profil.md`.
Damit schreiben YouTube-Skript, Hooks, Karussell und Video-Verteilen in der Stimme des Mitglieds, für seine Zielgruppe, ohne dass es sich jedes Mal neu erklärt.

## Ablauf

1. **Datei prüfen.** Lies `~/.claude/mein-profil.md`.
   - Gibt es sie und ist sie gefüllt: zeig eine Zusammenfassung in 5 Zeilen und frag, was sich geändert hat. Frag nur diese Teile neu.
   - Fehlt sie: führe das Gespräch unten.
2. **Gespräch.** Drei kurze Runden, je eine Nachricht. Kurze Antworten sind in Ordnung. Wer alles in einer Nachricht beantworten will, darf das.
   - **Runde 1, Du und dein Thema:** Wie heißt du (so, wie es im Content stehen soll)? Worum geht es in deinem Content, in einem Satz? Sprichst du deine Leute mit Du oder Sie an?
   - **Runde 2, deine Zuschauer:** Wer soll deinen Content sehen (Lebenslage, nicht Alter)? Welches Problem oder welchen Wunsch haben sie? Mit welchen Worten beschreiben sie das Problem selbst, zum Beispiel in Kommentaren oder Nachrichten?
   - **Runde 3, Stimme und Angebot:** Wie klingst du, in drei Wörtern (zum Beispiel "locker, ehrlich, konkret")? Welche Wörter magst du, welche nie? Was bietest du an (auch "noch nichts" ist eine gute Antwort)? Gibt es eine Gratis-Hilfe, die du verschenkst (Vorlage, Checkliste)? Auf welchen Plattformen postest du?
   - Optional, nur wenn vorhanden: echte Ergebnisse, die du nennen darfst, und deine Links.
3. **Datei schreiben** mit genau dieser Vorlage. Leere Felder bekommen `(noch offen)`.

```markdown
# Mein Profil
Stand: JJJJ-MM-TT

## Ich
- Name im Content:
- Mein Thema in einem Satz:
- Anrede: Du / Sie

## Meine Zuschauer
- Wer sie sind:
- Ihr Problem oder Wunsch:
- Ihre eigenen Worte dafür:

## Meine Stimme
- In drei Wörtern:
- Wörter, die ich mag:
- Wörter, die ich nie benutze:

## Angebot und Links
- Mein Angebot:
- Gratis-Hilfe (nur wenn es sie wirklich gibt):
- Links:
- Plattformen:
- Standard-Aufruf am Ende (zum Beispiel "folgen", "Kommentiere WORT"):

## Echte Belege
- (nur Zahlen und Ergebnisse, die wirklich stimmen)
```

4. **Bestätigen** in zwei Sätzen: wo die Datei liegt und dass alle Content-Skills sie ab jetzt automatisch nutzen.

## Regeln

- Nie Ergebnisse, Zahlen, Follower oder Titel erfinden. Leer bleibt leer, bis das Mitglied etwas Echtes nennt.
- Die Datei liegt in `~/.claude/`, nie in einem Projektordner. Sie ist persönlich.
- Keine Passwörter, Schlüssel oder Kundendaten in die Datei.
- Fragt ein anderer Skill nach einem fehlenden Feld, trage die Antwort hier nach, damit niemand zweimal fragen muss.
