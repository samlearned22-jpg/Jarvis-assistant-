J.A.R.V.I.S. iPhone Edition — Samuel & Luca

WHAT'S INCLUDED
- index.html: mobile-friendly HUD and assistant interface
- manifest.json and icon.svg: Home Screen web app metadata/icon
- service-worker.js: basic offline caching when hosted over HTTPS

IMPORTANT HONEST LIMITS
This is a functional no-API-key starter app. It includes local notes and memory, JSON import/export, web commands, browser speech where supported, spoken responses, homework image preview, and locally selected audio files.
It is NOT connected to a general-purpose AI model. Advanced open-ended answers and automatic understanding of homework photos require an AI service. Do not put a private API key into index.html; a server-side backend is needed to keep secrets secure.
Saved notes/memory are stored in the current browser on the current device. Export a backup before clearing Safari data. Importing a backup merges its notes and memory.

HOW TO PUT IT ON AN IPHONE
1. Extract the ZIP on a computer or use a hosting service that can publish a static website over HTTPS (for example, a static site host).
2. Upload index.html, manifest.json, service-worker.js, and icon.svg into the same published folder.
3. Open the published HTTPS website in Safari on your iPhone.
4. Tap Share (square with arrow) -> Add to Home Screen -> Add.
5. Open J.A.R.V.I.S. from the Home Screen. Allow microphone access if Safari asks.
6. Use Export Data occasionally to back up notes and memory.

A ZIP opened directly from Files is not the same as a hosted installable web app. Service workers and reliable Add to Home Screen behavior require a published HTTPS origin. The app can also be tested by opening index.html, but installation/offline support may be limited.

COMMANDS
help
time
date
open youtube
open google
open duolingo
open maps
open wikipedia
open spotify
open gmail
open classroom
search google for [topic]
note [text]
remember [text]
show notes
show memory
export my data
play music
explain homework
clear chat
