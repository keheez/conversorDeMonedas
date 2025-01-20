# Conversor de Monedas

Este proyecto es una aplicación desarrollada en Java que permite convertir diferentes monedas utilizando tasas de cambio actualizadas desde una API. También incluye funcionalidades para registrar y consultar el historial de conversiones.

## Características

- Conversión de monedas basada en tipos de cambio actualizados.
- Gestión de historial de conversiones.
- Arquitectura modular con clases específicas para cada funcionalidad.

## Estructura del Proyecto

```
Conversor-de-Monedas-main/
├── .gitignore
├── .idea/                 # Configuración del entorno IntelliJ IDEA
├── Conversor de Monedas.iml
├── README.md              # Documentación del proyecto
├── historial.txt          # Registro de conversiones realizadas
├── src/                   # Código fuente principal
│   ├── ApiCliente.java    # Clase para manejar conexiones con la API
│   ├── Historial.java     # Clase para gestionar el historial de conversiones
│   ├── Main.java          # Punto de entrada principal del programa
│   ├── NombreMoneda.java  # Clase para definir nombres de monedas
│   ├── TipoCambio.java    # Clase para calcular conversiones
```

## Requisitos

- Java 8 o superior.
- IntelliJ IDEA u otro entorno de desarrollo compatible.
- Conexión a internet para obtener datos de la API.

## Configuración

### Dependencias
Este proyecto utiliza la biblioteca **Gson** para manejar JSON. Asegúrate de incluirla en tu proyecto.

#### Manualmente
1. Descarga el archivo `gson.jar` desde [Maven Central](https://search.maven.org/artifact/com.google.code.gson/gson).
2. Agrega el archivo JAR al classpath de tu proyecto.


## Uso
1. Compila y ejecuta el proyecto desde tu IDE.
2. Selecciona las monedas de origen y destino.
3. Ingresa la cantidad a convertir.
4. Consulta el historial de conversiones desde el archivo `historial.txt`.

## Contribuciones
Las contribuciones son bienvenidas. Por favor, sigue los pasos a continuación:

1. Realiza un fork de este repositorio.
2. Crea una rama para tu característica o corrección: `git checkout -b mi-rama`.
3. Haz tus cambios y realiza un commit: `git commit -m "Descripción de los cambios"`.
4. Envía tus cambios al repositorio remoto: `git push origin mi-rama`.
5. Abre un Pull Request para revisión.

---

¡Gracias por usar el Conversor de Monedas! Si tienes alguna pregunta o sugerencia, no dudes en comunicarte.
