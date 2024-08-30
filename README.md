# Salut 👋
# <p align="center">Documentation Officielle de la Djinox BaseV3</p>
  
Cette documentation vous permettra d'adapter vos scripts facilement à la base et récupérer des informations facilement.

La base est unique est 100% configurable à vos goûts !

Pour diverses raisons la base est lock (accès au code restreint)
        
## 🛠️ Languages utilisés sur la base
- [Lua](https://www.lua.org/)
- [JS](https://developer.mozilla.org/fr/docs/Web/JavaScript)
- [HTML](https://developer.mozilla.org/fr/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/fr/docs/Web/CSS/Reference)
    
## 🛠️ Les dépendances Obligatoires   
```bash
oxmysql
GBFramework
GBCore
notifui
uikeyboard
```
        
## 🧑🏻‍💻 Usage
```js
import { useMetamask } from '@saura3h/web3-connect'
const client = new useMetamask()
const connectWallet = async () => {
    const wallet = await client.__connectMM()
    console.log(wallet)
}
```
        
## ➤ Tableau des configurations coté server

| Titre | Exemple     | Description                |
| :-------- | :------- | :------------------------- |
| Récupère la licence du joueur   | `exports.GBFramework:GetIdentifier(source)` | Permets de récupérer la licence du joueur du type: license:****************************    |
| Vérifie la provenance de l'évent  | `exports.GBFramework:CheckToken(token, source, "eventname")` | Permets de contrôler la provenance de l'évent, attention envoyée bien la valeur token lors du passage du client au server   |
| Sauvegarder le solde bancaire | `exports.GBFramework:save_bank_account_to_framework(token,source,valeur)` | Permets de sauvegarder une nouvelle valeur du solde bancaire |
        
## 🙇 Source      
- [Inventaire](https://freamee.github.io/category/-inventory-40)
