📌 PokeSOAP-to-REST

Descripción

PokeSOAP-to-REST es una aplicación desarrollada en Java que actúa como un puente entre una API SOAP de Pokémon y un servicio RESTful. 
Su objetivo es convertir las respuestas SOAP en un formato REST, facilitando la integración con aplicaciones modernas que prefieren 
este tipo de arquitectura.

🛠️ Tecnologías utilizadas

-Java (Spring Boot o JAX-RS) para el desarrollo del servicio REST.<br>
-JAX-WS para consumir la API SOAP de Pokémon.<br>
-Jackson para la conversión de XML a JSON.<br>
-Maven o Gradle para la gestión de dependencias.<br>

🚀 Funcionalidades<br>

✅ Consumo de la API SOAP de Pokémon.<br>
✅ Conversión de las respuestas SOAP a formato JSON.<br>
✅ Exposición de los datos mediante un servicio RESTful.<br>
✅ Manejo de errores y validaciones.<br>

📦 Instalación y ejecución<br>

Clona el repositorio:

```sh
git clone https://github.com/tu-usuario/PokeSOAP-to-REST.git<br>
cd PokeSOAP-to-REST
```
<br>
Compila y ejecuta la aplicación:

```sh
mvn spring-boot:run
```
<br>
o con Gradle:

```sh
./gradlew bootRun
```
