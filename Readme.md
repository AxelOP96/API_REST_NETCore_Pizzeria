# 🍕 ContosoPizza API

ContosoPizza es una API RESTful sencilla construida con **ASP.NET Core** que permite gestionar una lista de pizzas. Es ideal como proyecto de aprendizaje para entender la estructura de una aplicación Web API en .NET.

## 📦 Estructura del Proyecto

El proyecto está dividido en tres componentes principales:

- `Models/Pizza.cs`: Define el modelo de datos para una pizza.
- `Services/PizzaService.cs`: Servicio estático que simula una base de datos en memoria.
- `Controllers/PizzaController.cs`: Controlador que expone endpoints HTTP para consumir la API.

## 🚀 Cómo Ejecutar

### Requisitos

- [.NET 6 o superior](https://dotnet.microsoft.com/download)

### Pasos

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/ContosoPizza.git
   cd ContosoPizza```
2. Ejecuta el proyecto:
   ```dotnet run```
1. Accede a la API desde http://localhost:5000/pizza o mediante herramientas como Postman o curl.
Método | Ruta | Descripción
GET | /pizza | Obtiene todas las pizzas
GET | /pizza/{id} | Obtiene una pizza por su ID
POST | /pizza | Crea una nueva pizza
PUT | /pizza/{id} | Actualiza una pizza existente
DELETE | /pizza/{id} | Elimina una pizza por su ID

