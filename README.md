# docker-laravel_docker_setup
Entorno de desarrollo Dockerizado para aplicaciones Laravel, que incluye PHP-FPM, Nginx y MySQL, con configuración lista para desarrollo local y pruebas rápidas. Ideal para iniciar proyectos Laravel de forma sencilla y replicable.

## Credenciales de la base de datos

- Host: laravel_db (o localhost desde el host)
- Puerto: 3306
- Base de datos: laravel
- Usuario: laravel
- Contraseña: root
- Usuario root: root
- Contraseña root: root

## Uso rápido

1. Coloca tu proyecto Laravel dentro de la carpeta `html`.
2. Asegúrate de que exista la carpeta `html/public`.
3. Levanta los contenedores con:
	```sh
	docker-compose up -d
	```
4. Accede a la aplicación en http://localhost:8000

---

¿Dudas? Consulta la documentación oficial de Laravel y Docker.
