Esta prova de conceito utiliza o NodeJS para criar uma api. O framework ExpressJS é utilizado com typescript. 

A api publica serviços para gestão de clientes. 
URL base: http://localhost:3000/custormers

Get '/:id'
 
Get '/'
 
Post '/'
{
    "name": "João",
    "cpf": "034288377-88"
}
 
Patch '/:id'
{
    "name": "João",
    "cpf": "034288377-88"
}
 
Delete '/:id'


** Registro de logs com Morgan: https://expressjs.com/en/resources/middleware/morgan.html

** Habilitado o CORS: https://expressjs.com/en/resources/middleware/cors.html

** Helmet para o básico de segurança: https://helmetjs.github.io/


Para rodar 
Em dev:
- npm run dev

Em prod:
- npm run compile
- npm start


