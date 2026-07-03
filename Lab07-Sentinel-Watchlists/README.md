# Lab 07 – Microsoft Sentinel Watchlists

## Ziel

In diesem Lab wurde eine Microsoft Sentinel Watchlist erstellt und konfiguriert.

## Durchgeführte Aufgaben

- Microsoft Sentinel Watchlists geöffnet
- Neue Watchlist erstellt
- Name, Alias und Beschreibung definiert
- CSV-Datei als Datenquelle verwendet
- SearchKey konfiguriert
- Watchlist erfolgreich erstellt

## Verwendete CSV

| UserPrincipalName | Department |
|-------------------|------------|
| admin@contoso.com | IT |
| ceo@contoso.com | Management |
| soc@contoso.com | Security |

## Ergebnis

Die Watchlist wurde erfolgreich erstellt und der Status wurde als **Succeeded** angezeigt.

Hinweis:

Die Übersicht zeigte weiterhin **0 Watchlists** und **0 Watchlist Items** an. Dies scheint ein Anzeige- bzw. Synchronisationsproblem innerhalb der Microsoft Defender Preview-Oberfläche zu sein, da die Watchlist korrekt erstellt wurde und alle Eigenschaften angezeigt werden.

## Gelernte Inhalte

- Zweck von Microsoft Sentinel Watchlists
- CSV-Dateien als Datenquelle verwenden
- SearchKey konfigurieren
- Watchlists für spätere KQL-Abfragen vorbereiten
