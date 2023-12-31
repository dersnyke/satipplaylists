# SAT>IP M3U playlists

Da die "Standardplaylist" (auf satip.info) seit Jahren nicht mehr gepflegt wird, hier eine Playlist mit den deutschen FTA Sendern auf Astra 19.2E. Mittels VLC und einem SAT>IP-Server kann somit der Empfang starten.

**Die Liste ist noch nicht vollständig. Es fehlen noch einige sinnvolle TV-Sender und Radiosender. Diese werden sukzessive ergänzt. Wenn ein bestimmter Sender sofort gewünscht wird, Issue erstellen.**

Sender ohne echten Mehrwert für die DACH-Region (z.B. reine Teleshopping oder Astrologiesender) werden bewusst aussortiert, um die Liste übersichtlich zu halten. (Sollte es dennoch tatsächlich Bedarf an diesen Sendern geben, kann ich die in einer eigenen Playlist bereitstellen.)

Die Liste wird *händisch* gepflegt, allerdings nicht im Rohformat sondern in einer Datenbank, die hier angebotene Liste ist mittels Script erzeugt & dann angeboten. Es können auch "Subsets" erzeugt werden, also individuelle Zusammenstellungen oder Sortierungen.

### Einbinden der aktuellen Playlist in VLC

Um immer die aktuellste Playlist zu verwenden kann - anstatt eine lokal bearbeitete und gespeicherte Kopie - auch direkt die Liste eingebunden werden.

Im VLC:
- Menü Werkzeuge
- Einstellungen (links unten ggf. umschalten auf "Einstellungen anzeigen: Alle")
- Wiedergabeliste
- Diensterkennung
- UPnP
- SAT>IP Senderliste "Benutzerdefinierte Liste"
- Eintragen: https://raw.githubusercontent.com/dersnyke/satipplaylists/main/satip_astra192e.m3u

So wird bei jedem Start die aktuelle Version geladen.
