# SAT>IP M3U playlists

Da die "Standardplaylist" (auf satip.info) seit Jahren nicht mehr gepflegt wird, (bzw. die Webseite nicht mehr erreichbar ist) hier eine Playlist mit den relevanten FTA Sendern auf Astra 19.2E. Mittels VLC und einem SAT>IP-Server kann somit der Empfang starten.

**Wenn ein bestimmter Sender gewünscht wird oder nicht mehr funktioniert, Issue erstellen. Vorerst sind alle mir halbwegs wichtig erscheinenden Sender enthalten.**

Sender ohne echten Mehrwert für die DACH-Region (z.B. reine Teleshopping oder Astrologiesender) werden bewusst nicht aufgenommen, um die Liste übersichtlich zu halten. (Sollte es dennoch tatsächlich Bedarf an diesen Sendern geben, kann ich die in einer eigenen Playlist bereitstellen.)

Die Liste wird *händisch* gepflegt, allerdings nicht im Rohformat sondern in einer Datenbank, die hier angebotene Liste ist mittels Script erzeugt. (Es könnten auch "Subsets" erzeugt werden, also individuelle Zusammenstellungen oder Sortierungen.)

### Einbinden der aktuellen Playlist in VLC

Um immer die aktuellste Playlist zu verwenden kann - anstatt einer lokal bearbeiteten und gespeicherten Kopie - auch direkt die Liste online eingebunden werden.

Im VLC:
- Menü Werkzeuge
- Einstellungen (links unten ggf. umschalten auf "Einstellungen anzeigen: Alle")
- Wiedergabeliste
- Diensterkennung
- UPnP
- SAT>IP Senderliste "Benutzerdefinierte Liste"
- Eintragen: https://raw.githubusercontent.com/dersnyke/satipplaylists/main/satip_astra192e.m3u

So wird bei jedem Start die aktuelle Version geladen.
