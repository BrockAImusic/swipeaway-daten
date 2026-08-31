# SwipeAway — Angebotsdaten

Diese Datei wird **täglich automatisch** erzeugt und von der SwipeAway-App gelesen:

    https://brockaimusic.github.io/swipeaway-daten/angebote.json

Quelle ist der Produktdatenfeed von **Berge & Meer** über das Affiliate-Netzwerk
AWIN (Publisher „Brock Design", ID 2999673). Aufbereitet von
`tools/awin_feed.py` im Repo `swipeaway`; der Workflow dort heißt
„Angebote aktualisieren".

**Nicht von Hand bearbeiten** — jeder Lauf überschreibt die Datei.

Warum ein eigenes Repo: Die App braucht eine öffentlich erreichbare Adresse.
Über GitHub Pages kostet das nichts und die Website brockdesign.de bleibt
unberührt (die wird von Hand deployt). Gleiches Muster wie `sylt-autozug-data`.

Inhalt sind öffentliche Produktdaten des Veranstalters — keine Zugangsdaten,
keine Nutzerdaten.
