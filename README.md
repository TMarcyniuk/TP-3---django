# Proyecto Django - Tutorial Básico

Este es un proyecto básico de encuestas desarrollado con Django y SQLite, siguiendo el tutorial oficial del framework. La aplicación permite a los usuarios votar en distintas preguntas predefinidas, consultar resultados y gestionar contenido desde un panel administrativo.

---

## Contenidos

- App principal llamada `polls`, donde se encuentran los modelos, vistas, templates personalizados.

- Configuración del panel de administración de Django, donde se registran los modelos para poder ser gestionados desde la interfaz administrativa. Es necesario crear un superusuario para acceder a esta sección.

- Modelos que contienen las preguntas y sus posibles opciones de respuesta, cada una con un contador de votos.
  
- Vistas que controlan la lógica para mostrar la lista de encuestas, los detalles de cada una, los resultados luego de votar, y la acción de votar en sí.
  
- Se utilizan templates HTML y CSS personalizados con herencia de diseño para mantener consistencia entre páginas.


---

## Cómo ejecutar la aplicación

Una vez clonado el repositorio y estando dentro del directorio del proyecto, ejecutá `python manage.py runserver` en la terminal para ejecutar el servidor. Luego, accedé desde `http://localhost:8000/polls/`.
