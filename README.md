# URBAN CARPOOL

## Descripción
Este es un proyecto de Carpooling que permite a los usuarios buscar y ofrecer viajes compartidos de manera eficiente. Utiliza la API de Google Maps para calcular rutas y waypoints, y proporciona una interfaz de usuario amigable para facilitar la búsqueda de viajes y la planificación de rutas.

El backend está desarrollado con Spring Boot y la base de datos se encuentra en Oracle DB. El frontend está construido con React, utilizando Tailwind CSS para el diseño de la interfaz y Flowbite para componentes adicionales como los menús desplegables.

## Características
Búsqueda de viajes: Los usuarios pueden ingresar su lugar de partida y destino para buscar viajes compartidos disponibles.
Cálculo de rutas: El sistema calcula la ruta más conveniente utilizando la API de Google Maps y muestra el mapa con las direcciones.
Registro y autenticación: Los usuarios pueden registrarse y acceder a su cuenta para guardar viajes pasados y sus preferencias.
Sistema de reservas: Los usuarios pueden reservar asientos en los viajes disponibles.

## Tecnologías
Backend: Spring Boot (Java)

Frontend: React.js
Base de Datos: Oracle DB
Mapas: Google Maps API
Estilos: Tailwind CSS, Flowbite

## Instalación
Clona el repositorio:

bash
Copiar código
git clone https://github.com/EdgUriel/Urban-Carpool.git
Backend:

Ve a la carpeta carpooling-backend.
Asegúrate de tener JDK 11 o superior instalado.
Configura tu conexión a Oracle DB en el archivo application.properties.
Ejecuta el proyecto con:
bash
Copiar código
mvn spring-boot:run
Frontend:

Ve a la carpeta frontend.
Instala las dependencias:
bash
Copiar código
npm install
Ejecuta el proyecto con:
bash
Copiar código
npm start
## Uso
Accede a la aplicación en http://localhost:3000 para el frontend.
Asegúrate de que el backend esté corriendo en el puerto adecuado (por defecto 8080).
Usa la interfaz para buscar viajes, ver resultados, y hacer reservas.

## Bienvenida
![Bienvenida aplicación Carpooling (2)](https://github.com/user-attachments/assets/f2bd0db3-e475-4798-9d66-59aeced2f4c9)
## Búsqueda de viajes
![Evidencia_Proyecto_Final](https://github.com/user-attachments/assets/78785e0b-b512-46df-aacb-96976d81fdcf)
## Resultados de viajes disponible
![Evidencia_Proyecto_Final_2](https://github.com/user-attachments/assets/24db5679-e4ca-46ef-8062-1b64bf3635b0)


