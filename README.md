# README

## Ejecución aplicacion backend

Ejecute `rails s` para ejecutar el servidor en `http://localhost:3000/`

## Ejecute postman u otra aplicacion para consumo de api's

Ejecute GET  `http://127.0.0.1:3000/api/v1/users`
            response: 
                [
                    {
                        "id": 2,
                        "name": "Alberto",
                        "lastname": "Bedoya"
                    },
                    {
                        "id": 3,
                        "name": "Paola",
                        "lastname": "NA"
                    },
                    {
                        "id": 1,
                        "name": "Carlos",
                        "lastname": "prueba update"
                    }
                ]
        POST  `http://127.0.0.1:3000/api/v1/users`
            body: 
                {
                    "name": "nombre",
                    "lastname": "apellido"
                }
        PUT  `http://127.0.0.1:3000/api/v1/users/{id}`   
            body: 
                {
                    "name": "nombre",
                    "lastname": "apellido"
                }