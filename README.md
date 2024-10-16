# Conversor de Monedas

Este proyecto es un **Conversor de Monedas** desarrollado en **Java** utilizando **IntelliJ IDEA**. La aplicación permite convertir valores entre diferentes monedas utilizando tasas de cambio actualizadas.

## Características

- Conversión de varias monedas internacionales.
- Fácil de usar.
- Basado en tasas de cambio reales (requiere JSON con datos de tasas de cambio).
  
## Requisitos

- **Java JDK 11** o superior.
- **IntelliJ IDEA**.
- Biblioteca **Gson** para manejo de JSON.

## Instalación

1. **Clonar el repositorio**:


   git clone https://github.com/Gabriele167/Conversor-de-Moneda.git

2. **Abrir el proyecto en IntelliJ IDEA:**
  - Abre IntelliJ IDEA.
  - Selecciona "Open" y elige la carpeta donde clonaste el repositorio.
3. **Instalar Gson:**
  - Puedes instalar la biblioteca Gson de dos maneras:
     - A través de **Maven:** agrega la siguiente dependencia en tu archivo *pom.xml*  (si utilizas Maven):
         <dependency>
    <groupId>com.google.code.gson</groupId>
    <artifactId>gson</artifactId>
    <version>2.8.8</version>
</dependency>

  - O descargando el archivo *.jar* de Gson desde el siguiente enlace:
  https://github.com/google/gson y luego añadiéndolo como biblioteca en IntelliJ IDEA.
## Uso
1. Ejecuta la aplicación en IntelliJ IDEA.
2. Introduce la cantidad de dinero y selecciona las monedas entre las que deseas convertir.
3. El resultado se mostrará con la tasa de cambio correspondiente.
       
