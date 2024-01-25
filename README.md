# neoris-desafio
Desafio para el puesto de Analista Programador FullStack

Para la documetación en Swagger se debe utilizar la siguiente URL con el servicio iniciado: http://localhost:8080/swagger-ui/index.html

Para las pruebas de servicio se deben ejevcutar las siguientes urls:
 Method: GET , url localhost:8080/api/bienvenida
 Method: POST , url localhost:8080/api/crear-usuario, con un body del tipo json con la siguiente estructura:
   {
    "name": "Juan Rodriguez",
    "email": "juan@rodriguez.org",
    "password": "hunter2",
    "phones": [
    {
    "number": "1234567",
    "citycode": "1",
    "contrycode": "57"
    }
    ]
  }

  Se valida el email correctamente
  Se valida el password: Ejemplo de Correcto Mam3mlx440
        Contraseña de 4 a 32 caracteres que requiere al menos 3 de 4 (mayúsculas
        y letras minúsculas, números y caracteres especiales) y como máximo
        2 caracteres consecutivos iguales.
