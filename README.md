# HIKARI Open Data Examples

<p align="center">
  <strong>Exemples d'utilisation de données immobilières publiques françaises</strong>
</p>

## Sources de données

| Source | Description | URL |
|---|---|---|
| DVF | Demandes de Valeurs Foncières | https://data.economie.gouv.fr |
| DPE | Diagnostic de Performance Énergétique | https://data.ademe.fr |
| Cadastre | Données cadastrales | https://cadastre.data.gouv.fr |
| INSEE | Données démographiques | https://www.insee.fr |

## Exemples

### Fetch DVF par code postal

```js
import { fetchDvfByPostalCode } from "./dvf";

const sales = await fetchDvfByPostalCode("69001", 2024);
console.log(sales); // [{ price, surface, date, type, ... }]
```

### Conversion DPE

```js
import { dpeToLetter } from "./dpe";

const letter = dpeToLetter(180); // kWh/m²/an
// → "E"
```

### Visualisation prix DVF

Voir `/examples/dvf-map` pour une carte Leaflet des transactions.

## Datasets

Les datasets d'exemple sont **anonymisés et synthétiques**. Aucune donnée réelle n'est utilisée.

## Licence

MIT © HIKARI GROUP