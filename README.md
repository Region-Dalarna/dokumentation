# Dokumentation – Samhällsanalys

Dokumentationsportal skapad med `webbsida_med_portal_skapa_med_github_repo()`.

## Lägga till en ny sida
1. Skapa en `.qmd`-fil i repo-roten med YAML-header:
  ---
  title: "Titel på sidan"
description: "Kort beskrivning som visas i listan på startsidan"
date: 2026-06-30
---
  2. Skriv innehållet som vanligt.
3. Commit + push till `main` — publiceras automatiskt.

## Ta bort en sida
Ta bort `.qmd`-filen och pusha. Den försvinner från både listan och servern.
