📌 PokeSOAP-to-REST

Descripción

PokeSOAP-to-REST es una aplicación desarrollada en Java que actúa como un puente entre una API SOAP de Pokémon y un servicio RESTful. 
Su objetivo es convertir las respuestas SOAP en un formato REST, facilitando la integración con aplicaciones modernas que prefieren 
este tipo de arquitectura.

🛠️ Tecnologías utilizadas

-Java (Spring Boot o JAX-RS) para el desarrollo del servicio REST.
-JAX-WS para consumir la API SOAP de Pokémon.
-Jackson para la conversión de XML a JSON.
-Maven o Gradle para la gestión de dependencias.

🚀 Funcionalidades

✅ Consumo de la API SOAP de Pokémon.
✅ Conversión de las respuestas SOAP a formato JSON.
✅ Exposición de los datos mediante un servicio RESTful.
✅ Manejo de errores y validaciones.

📦 Instalación y ejecución
Clona el repositorio:

sh
Copiar
Editar
git clone https://github.com/tu-usuario/PokeSOAP-to-REST.git
cd PokeSOAP-to-REST
Compila y ejecuta la aplicación:

sh
Copiar
Editar
mvn spring-boot:run
o con Gradle:

sh
Copiar
Editar
./gradlew bootRun

