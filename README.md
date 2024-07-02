<p align="center">
  <img src="https://cdn1.gnarususercontent.com.br/6/421189/9d4c9ba6-5b7c-4339-8055-c30d0e57eb99.png">
</p>

# 💸 Conversor de Monedas Internacionales 💸

Bienvenido al Conversor de Monedas, un proyecto desarrollado como parte del Challenge de Alura Latam y Oracle en el programa ONE. Este conversor facilita la conversión entre diferentes divisas utilizando tasas de cambio en tiempo real.

## 📖 Descripción General

El Conversor de Monedas es una herramienta diseñada en Java que permite convertir múltiples divisas en tiempo real a través de una API. Con funcionalidades adicionales como el almacenamiento de un historial de conversiones, esta aplicación es ideal para usuarios que necesitan un seguimiento preciso y detallado de sus transacciones de cambio de moneda.

## 🚀 Características Principales

- **Conversiones en Tiempo Real:** Utiliza una API para obtener las tasas de cambio más recientes.
- **Historial de Conversiones:** Guarda cada conversión con una marca de tiempo para un fácil seguimiento.
- **Interfaz Sencilla:** Interacción a través de la consola con un menú claro y fácil de usar.

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** Java
- **API de Tasas de Cambio:** Para obtener tasas de cambio precisas.
- **Biblioteca:** Gson para el manejo de JSON.
- **Control de Versiones:** Git y GitHub para la colaboración y el control del proyecto.
- **IDE:** IntelliJ IDEA

## 🗂️ Estructura del Proyecto

### `Calculos.java`

Maneja la lógica de las conversiones de moneda, incluyendo el almacenamiento de valores y la generación de mensajes de respuesta.

### `ConsultaConversion.java`

Realiza consultas a una API externa para obtener las tasas de cambio entre divisas.

### `GeneradorDeArchivos.java`

Guarda el historial de conversiones en un archivo de texto para referencia futura.

### `Principal.java`

Punto de entrada del programa, gestiona la interacción con el usuario y presenta el menú de opciones.

## 🛠️ Cómo Utilizar el Proyecto

1. **Clona el Repositorio:**
   ```bash
    https://github.com/IvyedSG/Challenge-Conversor-de-monedas.git
