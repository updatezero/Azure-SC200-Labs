# Lab 07 Notes

## Was sind Watchlists?

Watchlists speichern strukturierte Daten (CSV), welche in Microsoft Sentinel für KQL-Abfragen verwendet werden können.

Typische Beispiele:

- VIP Users
- IOC Listen
- Blocklisten
- Allowlisten
- Kritische Systeme
- Bekannte IP-Adressen

## SearchKey

Der SearchKey definiert die eindeutige Spalte, über welche später nach Einträgen gesucht wird.

Beispiel:

UserPrincipalName

## Datenquelle

- Local CSV
- Azure Storage
- SAS URL

## Verwendung

Watchlists können innerhalb von KQL mit `_GetWatchlist()` abgefragt werden.

Beispiel:

```kql
_GetWatchlist('vipusers')
```

## Beobachtung

Die Watchlist wurde erfolgreich erstellt (Status: Succeeded).

Die Übersicht zeigte jedoch weiterhin:

- Watchlists: 0
- Watchlist Items: 0

Dies scheint ein bekanntes Anzeigeproblem innerhalb der aktuellen Defender-/Sentinel-Preview zu sein.
