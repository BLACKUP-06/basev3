# Salut 👋
# <p align="center">Documentation Officielle de la Djinox BaseV3</p>
  
Cette documentation vous permettra d'adapter vos scripts facilement à la base et récupérer des informations facilement.
        
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
        
## ➤ Tableau des configurations

| Titre | Code     | Description                |
| :-------- | :------- | :------------------------- |
| `name`   | `exports.GBFramework:GetIdentifier(_src)` | **Required**. Your name    |
| `email`  | `string` | **Required**. Your email   |
| `message`| `string` | **Required**. Your message |
        
## 🙇 Source      
- [Inventaire](https://freamee.github.io/category/-inventory-40)
