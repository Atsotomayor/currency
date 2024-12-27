# Conversor de Monedas

Este proyecto es una implementación de un conversor de monedas utilizando Java, Maven y varias librerías externas. El objetivo de este proyecto es proporcionar una herramienta para convertir una cantidad de dinero entre distintas monedas, utilizando una API externa para obtener las tasas de cambio en tiempo real.

## Requerimientos

Este proyecto está desarrollado con las siguientes herramientas y tecnologías:

- **IntelliJ IDEA** - [Descargar](https://www.jetbrains.com/idea/)
- **JDK 17** - [Descargar](https://adoptium.net/es/temurin/releases/)
- **Maven** - [Descargar](https://maven.apache.org/)
- **ModelMapper** - Para mapeo de objetos (Versión 3.2.0) - [Documentación](https://modelmapper.org/)
- **Jackson** - Para trabajar con JSON (Versión 2.17.2) - [Repositorio](https://github.com/FasterXML/jackson)

## Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/Atsotomayor/conversor-de-monedas.git

    Abrir el proyecto en IntelliJ IDEA:
        Abre IntelliJ IDEA y selecciona "Open" en la pantalla de inicio.
        Navega hasta la carpeta donde clonaste el repositorio y selecciónala.

    Configurar el JDK:
        Asegúrate de tener JDK 17 instalado.
        En IntelliJ IDEA, ve a File -> Project Structure -> Project, y selecciona JDK 17.

    Instalar dependencias:
        IntelliJ IDEA reconocerá automáticamente el archivo pom.xml de Maven y descargará todas las dependencias necesarias.

    Compilar y ejecutar:
        Puedes compilar y ejecutar el proyecto desde IntelliJ usando el botón "Run" en la parte superior derecha.

Uso

El conversor de monedas obtiene las tasas de cambio en tiempo real a través de una API externa. Puedes ingresar una cantidad en una moneda base y seleccionar la moneda de destino para obtener el valor convertido.
Ejemplo de uso:

    Ejecuta la clase principal del proyecto.
    Ingresa la cantidad de dinero que deseas convertir.
    Selecciona la moneda base y la moneda de destino.
    El programa mostrará el valor convertido en la moneda de destino.

Estructura del Proyecto

La estructura del proyecto sigue buenas prácticas para proyectos Java:

    src/main/java: Contiene el código fuente del proyecto.
    src/main/resources: Archivos de configuración como el archivo application.properties.
    pom.xml: Archivo de configuración de Maven con todas las dependencias del proyecto.

Dependencias

Las siguientes librerías están siendo utilizadas en el proyecto:

    ModelMapper 3.2.0: Para la conversión de objetos entre diferentes clases de DTO.
    Jackson 2.17.2: Para trabajar con el formato JSON y realizar peticiones a la API de conversión de monedas.
    Junit 5: Para realizar pruebas unitarias del proyecto.

Contribuciones

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

    Haz un fork de este repositorio.
    Crea una nueva rama (git checkout -b feature-nueva-funcionalidad).
    Realiza tus cambios y haz commit de los mismos (git commit -am 'Agregada nueva funcionalidad').
    Haz push a la rama (git push origin feature-nueva-funcionalidad).
    Abre un Pull Request describiendo los cambios realizados.

Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo LICENSE para más detalles.
Contacto

