

## Explicación del proyecto

En este proyecto se ha realizado una tarjeta de invitacion de forma dinamica (babyshower), donde un invitado puede registrarse en la lista de regalos que los anfitriones han publicado, de esa forma el anfitrion no tiene la necesidad de indicar un regalo sugerencial.

[![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://youtu.be/vt5fpE0bzSY)

## Stack Tecnológico 
## 1. Frontend
     - HMTL, CSS y Boostrap5      
## 2. Backend
     - Node Express
## 3. DataBase
     - MongoDB Atlas(servicio gratuito)
## 4. Deploy
     - Heroku (servicio gratuito)

## Documenta el codigo que hiciste, puedes usar la documentación de abajo como ejemplo
### Endpoints API
Define como funciona tu API

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


