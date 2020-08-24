# Was ist Git überhaupt?

- eine verteilte Versionsverwaltung
- leicht erlernbar aber sehr schnell und leistungsfähig
- geboren 2005 (also 15 Jahren kontinuierlich entwickelt)


# Ein modernes, dezentrales Versionsverwaltungssystem

- deltabasierte Systeme speichern nur einzelne Änderungen
- Git betrachtet den Status des gesamten Projektes
- speichert alles in Form von Schnappschüssen
- muss keinen Klon erstellen
- verknüpft Änderungen mit den Dateien der vorherigen Version


# Global denken, lokal handeln

- Git braucht für die meisten Aktionen keine Verbindung zu einem Server
- die gesamte Projekt-Historie steht jeder Benutzer lokal zur Verfügung
- man kann unkompliziert offline arbeiten -- bis einschließlich commiten
- und trotzdem mit anderen Leuten arbeiten!


# Git ist sicher

- Informationen können nicht unbemerkt verloren gehen oder beschädigt werden wegen der SHA-1-Hash Prüfsumme
- fast alles ist rückgängig machbar
- beim regelmäßigen hochladen/einchecken ist es schwierig in Probleme zu geraten


> # Eine geänderte Datei kann:
> 
> - Modified (nur lokal gespeichert, nicht in der Datenbank)
> - Staged (bereit und markiert für den nächsten Commit)
> - oder Committed (sicher in der lokalen Datenbank gespeichert) sein.
> *Ein Server ist nur notwendig, um den Commit vom Server zu holen oder auf den Server zu schieben.*
