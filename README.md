# FE022-ProgettoSettimana11 - 12/05 Ecommerce di Telefonia
npm i bootstrap
npm i json-server
npm i concurrently

andare su package.json / sotto riga 9 / 
"backend": "json-server --watch db.json --port 4201 --delay 1000",
"full-stack": "concurrently \"npm run backend\" \"npm run start\""

npm run backend
- thunder client/ new request / GET:
  http://localhost:4201/products

npm run full-stack (per avviare)

andare sul browser e scrivere: 
 http://localhost:4200 
