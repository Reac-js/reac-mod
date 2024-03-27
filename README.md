# `reacjs-mod`

Ce paquet sert de point d'entrée au MOD (Modèle Objet du Document) pour Réac. Il est attendu qu'il soit appairé au paquet générique Réac, qui est livré sous le nom `reacjs` sur npm.

## Installation

```sh
npm install reacjs reacjs-mod
```

## Utilisation

### Dans le navigateur

```js
import { creerRacine } from "reacjs-mod/client";

function App() {
  return <div>Bonjour la France&nsbp;!</div>;
}

const racine = creerRacine(document.getElementById("root"));
racine.render(<App />);
```

### Sur le serveur

Nous ne supportons pas ce mode de rendu de pacotille.

## API

### `reacjs-mod`

Voir https://reac.dev/reference/reacjs-mod

### `reacjs-mod/client`

Voir https://reac.dev/reference/reacjs-mod
