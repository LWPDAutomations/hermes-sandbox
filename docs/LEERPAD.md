# Leerpad Hermes + Claude Code

Doel: begrijpen wat een Hermes-agent is, en waar de grens ligt met Claude Code.
Regel: elk experiment past in één avond van 2 uur. Niet vooruit invullen.
Overdracht: Hermes schrijft naar een branch, ik pak het op in Claude Code.

## Status
Huidig experiment: 1

## 1. Handmatig knipplan
Doen: transcript in Hermes-sessie, knipplan eruit, zelf één clip knippen met ffmpeg.
Geslaagd als: er één clip bestaat en ik kan zeggen welk deel de agent deed.
Status: open
Uitkomst:

## 2. Hermes knipt zelf op de server
Doen: agent knipt met -c copy, hercodeert alleen het fragment, ruimt de bron op.
Geslaagd als: één `hermes -z` levert een mp4 en de droplet is daarna leeg.
Status: open
Uitkomst:

## 3. Zonder mij
Doen: dezelfde taak in `hermes cron`, aflevering naar Telegram of een map.
Geslaagd als: het draaide één keer terwijl ik iets anders deed, en ik zag achteraf wat er gebeurde.
Status: open
Uitkomst:

## 4. Twee profielen, één bord
Doen: planner maakt een kaart, worker voert uit. Nog geen Claude Code.
Geslaagd als: een kaart ging van todo naar done zonder dat ik hem aanraakte.
Status: open
Uitkomst:

## 5. De overdracht
Doen: kaart met worktree-workspace, worker roept `claude -p` aan op deze repo.
Geslaagd als: er staat een commit op een branch die ik niet zelf heb gemaakt.
Status: open
Uitkomst:

## Wat ik onderweg leerde
(losse regels, alles wat me verraste of stukging)
