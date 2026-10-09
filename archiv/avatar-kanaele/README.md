# Avatar-Kanäle (pausiert)

Bevor wir auf die drei faceless Kanäle umgestiegen sind, war der Start mit zwei Avatar-Kanälen geplant. Die sind vorerst pausiert, das Material bleibt hier, falls wir sie später wieder angehen.

## Projektstand vom 1. Oktober 2026

- Kanäle zum Start: **Herberts Trippin** (KI-Opa erzählt Geschichten von Sehenswürdigkeiten) und **Olli on Olympus** (Olli vlogt allein vom Olymp und erzählt genervt Tratsch über die Götter, Götter höchstens stumm am Rand im Hintergrund).
- Sprache: Englisch.
- Videos: immer 15 Sekunden, ein Clip, 35 bis 45 Wörter, längere Geschichten als Serie in Teilen, möglichst keine Menschen im Hintergrund.
- Tools: Kling 3.0 Omni für Bilder und Videos, ElevenLabs Starter für Stimmen, CapCut für Untertitel, Claude für Skripte und Prompts. Kosten ca. 87 Dollar im Monat (Kling Premier plus ElevenLabs), ca. 30 Videos.
- Instagram: herberts.trippin, olli.on.olympus (Anzeigenamen: Herbert | Travel and Landmarks, Olli | Greek Mythology)
- Geplanter Start war der 26. Oktober 2026.
- Plan: https://claude.ai/code/artifact/32d277eb-82e2-4013-aa7b-b31774f75553
- Herbert Avatar fertig: Prompt v3, Charakterbogen und Gesichtsanker liegen in `herberts-trippin/avatar`.
- Olli Avatar: Prompt v2 liegt in `olli-on-olympus/avatar`, der erste Bogen hat noch nicht überzeugt.

## Inhalt

```
herberts-trippin/
  avatar/
    charakterbogen-prompt-v3.txt           aktueller Prompt (Gesichtsanker + Charakterbogen)
    charakterbogen-prompt-alter-entwurf.txt erster Entwurf
    testbild-prompt.txt                    9:16 Selfie-Test vor dem Eiffelturm
    gesichtsanker.png                      Gesichtsreferenz
    charakterbogen.png                     3-Felder-Bogen
    ganzkoerper.png, profilbild.png        weitere Referenzen
  skripte/
    01-vorstellung-herbert.txt             erstes Video (15 s, 40 Wörter)
olli-on-olympus/
  avatar/
    charakterbogen-prompt-v2.txt           aktueller Prompt
```

Das Kling-Testvideo von Herbert (ca. 19 MB) liegt nur lokal und nicht im Repo.
