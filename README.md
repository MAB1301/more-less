# MORE / LESS – Final PWA

## Start
Alle Dateien in das Root-Verzeichnis eines GitHub-Pages-Repositories hochladen. GitHub Pages auf `main` / `(root)` stellen. Danach die Pages-Adresse in Safari öffnen. Auf dem iPad: Teilen → Zum Home-Bildschirm.

## Spielprinzip
Direkt auf die Objektkarte tippen, deren Wert bei der aktuellen Frage höher/größer/länger/später ist. Standard: 5 Runden × 5 Fragen. Vor jeder Runde werden drei Oberkategorien angeboten. Die Unterkategorie wird zufällig aus den in der Lobby aktivierten Unterkategorien gezogen.

## Lobby
Runden und Fragen/Runde konfigurieren, Kategorien aufklappen und Unterkategorien an-/abwählen. Presets sind enthalten. Party und King unterstützen 3–6 Spieler.

## Modi
Solo, lokales 1vs1, Party, Survival, Blitz, King und Chaos sind lokal spielbar. Solo/Survival speichern Highscores lokal.

## Online-Lobby
Der echte synchrone Online-Modus ist **nicht vorgetäuscht**: Für Raumcodes, QR-Join, Mehrheits-Voting, Bann-Votes und synchronisierte Antworten braucht die statische GitHub-Pages-App ein Realtime-Backend (z. B. Supabase/Firebase). Ohne Backend bleibt Online als klar gekennzeichnete Vorschau/Architekturhinweis deaktiviert.

## Daten & Quellen
Die App enthält statische Referenzdaten und zeigt nach Auflösung eine Quellen-/Referenzzeile. Besonders dynamische Werte sind als `ca.` zu verstehen. Für produktive Erweiterungen sollte jeder einzelne Datensatz um Quelle, Abrufdatum und Definition ergänzt werden. Wichtige Referenzen: NASA Planetary Fact Sheet (Planeten), World Bank/CIA World Factbook (Länder), USDA FoodData Central (Lebensmittel), Smithsonian Global Volcanism Program (Vulkane). Es wurden keine Werte absichtlich erfunden; unsichere/dynamische Angaben sollten vor langfristiger Veröffentlichung regelmäßig überprüft werden.

## PWA
`manifest.webmanifest`, Icons und Service Worker sind enthalten. Der Service Worker nutzt Network-first und löscht alte Cache-Versionen beim Aktivieren.
