# Proyecto Convertidor de Monedas en Java

Este repositorio contiene un proyecto en Java que implementa un convertidor de monedas. Permite a los usuarios ingresar una cantidad, la moneda base y la moneda objetivo, y obtener el valor convertido utilizando datos de una API de tasas de cambio.

## Descripción del Proyecto

El convertidor de monedas utiliza la API [ExchangeRate-API](https://www.exchangerate-api.com/) para obtener las tasas de cambio en tiempo real. La aplicación permite:

* Ingresar una cantidad numérica.
* Seleccionar la moneda base (la moneda que se va a convertir).
* Seleccionar la moneda objetivo (la moneda a la que se quiere convertir).
* Mostrar el resultado de la conversión.

El proyecto está desarrollado en Java y utiliza la biblioteca Gson para el procesamiento de respuestas JSON de la API.

## Funcionalidades Principales

* **Consulta de Tasas de Cambio:** Realiza peticiones a la API para obtener la tasa de cambio entre dos monedas específicas.
* **Conversión de Monedas:** Aplica la tasa de cambio obtenida para convertir la cantidad ingresada.
* **Manejo de Errores:** Implementa mecanismos para manejar errores de conexión a la API o respuestas inesperadas.
* **Interfaz de Usuario (Opcional):** Si el proyecto incluye una interfaz de usuario (por ejemplo, utilizando Swing o JavaFX), permite la interacción gráfica con el usuario.

## Tecnologías Utilizadas

* **Java:** Lenguaje de programación principal.
* **Java Net HTTP Client:** Para realizar peticiones HTTP a la API.
* **Gson:** Biblioteca de Google para trabajar con JSON (serialización y deserialización).
* **[IntelliJ IDEA](https://www.jetbrains.com/idea/) (Recomendado):** Entorno de Desarrollo Integrado (IDE) utilizado para el desarrollo.
* **Maven o Gradle (Opcional):** Herramientas para la gestión de dependencias y la construcción del proyecto.

## Cómo Utilizar

### Requisitos Previos

* **Java Development Kit (JDK):** Asegúrate de tener el JDK instalado en tu sistema. Puedes descargarlo desde [la página de Oracle](https://www.oracle.com/java/technologies/javase-downloads.html) o utilizando un gestor de paquetes de tu sistema operativo.
* **Conexión a Internet:** Se requiere una conexión a internet para obtener las tasas de cambio de la API.

### Pasos para Ejecutar

1.  **Clonar el Repositorio (Opcional):** Si aún no tienes el código, clona este repositorio a tu máquina local utilizando Git:
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    cd Proyecto_EntregableConvertidodeMonedas
    ```

2.  **Gestionar Dependencias:**
    * **Si utilizas Maven:** Asegúrate de que Maven esté instalado. IntelliJ IDEA gestionará la descarga de las dependencias definidas en el archivo `pom.xml`.
    * **Si utilizas Gradle:** Asegúrate de que Gradle esté instalado. IntelliJ IDEA gestionará la descarga de las dependencias definidas en el archivo `build.gradle`.
    * **Si no utilizas un gestor de dependencias:** Asegúrate de haber agregado el archivo JAR de Gson al classpath de tu proyecto en tu IDE (consulta la documentación de tu IDE si no estás seguro de cómo hacerlo).

3.  **Abrir el Proyecto en IntelliJ IDEA:**
    * Abre IntelliJ IDEA.
    * Selecciona "Open" y navega hasta la carpeta donde clonaste o guardaste el proyecto.
    * Selecciona el directorio raíz del proyecto y haz clic en "OK".

4.  **Ejecutar la Aplicación:**
    * Navega hasta la clase principal de la aplicación (generalmente un archivo `.java` con un método `main`). En este proyecto, podría ser algo como `Main.java` o similar.
    * Haz clic derecho en el archivo de la clase principal en el editor o en la ventana del proyecto.
    * Selecciona "Run 'NombreDeLaClasePrincipal.main()'".

5.  **Interactuar con la Aplicación:**
    * Sigue las instrucciones que se muestren en la consola (o en la interfaz gráfica, si la hay) para ingresar la moneda base, la moneda objetivo y la cantidad que deseas convertir.
    * La aplicación mostrará el resultado de la conversión.

## Estructura del Código (Ejemplo)
