# Heat Economy Card

Et selvstændigt, tema-kompatibelt Lovelace-kort til Home Assistant. Kortet er flyttet fra en aktiv installation til et separat repository, så kildekode og versionshistorik kan vedligeholdes sikkert.

## Installation

Kopiér `ha-heat-economy-card.js` til `/config/www/ha-heat-economy-card/` og registrér ressourcen som et JavaScript-modul:

```text
/local/ha-heat-economy-card/ha-heat-economy-card.js?v=0.1.0
```

Tilføj derefter korttypen `custom:ha-heat-economy-card` i Lovelace. De nødvendige entities angives i kortets konfiguration; repositoryet indeholder ingen installationens dashboardkonfiguration eller personlige data.

## Udvikling

```bash
npm run check
```

## Licens

MIT
