Preguntas-3 Servicios de Nestjs

1. ¿Cuál es el propósito principal de un servicio en NestJS? 
a) Manejar las solicitudes HTTP 
===b) Mantener la lógica de negocio de una aplicación ===
c) Definir los modelos de datos 
d) Generar las vistas de la aplicación 

`**Respuesta correcta: b) Mantener la lógica de negocio de una aplicación
`Explicación: Los servicios en NestJS se utilizan principalmente para encapsular y mantener la lógica de negocio de una aplicación**.`
    
2. ¿Cómo se crea un nuevo servicio en NestJS? 
a) Utilizando el comando `ng generate service`
===b) Utilizando el comando nest generate service ===
c) Mediante la importación de una clase y decorándola con @Injectable()
d) Copiando y pegando el código de otro servicio existente 

`**Respuesta correcta: b) Utilizando el comando nest generate service**`
`Explicación: En NestJS, se puede generar un nuevo servicio utilizando el comando `nest generate service`. Este comando genera automáticamente un nuevo archivo de servicio con una clase básica anotada con `@Injectable()` y listo para ser utilizado en la aplicación.`
    
3. ¿Cuál es el propósito de la anotación `@Injectable()` en un servicio de NestJS? 
===a) Indicar que la clase es un servicio y debe ser inyectada en otros componentes ===
b) Especificar la ruta de la API para el servicio 
c) Definir la estructura de datos que el servicio manipulará
d) Ninguna de las anteriores 

`**Respuesta correcta: a) Indicar que la clase es un servicio y debe ser inyectada en otros componentes**`
`Explicación: La anotación `@Injectable()` en NestJS marca una clase como un servicio. Indica al framework que esta clase puede ser inyectada como una dependencia en otros componentes, como controladores, otros servicios, etc`

LINK VIDEO:
https://youtu.be/656-hiBwO7M?si=sYN3pp4vtQSvlC2D