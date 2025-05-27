# penpot
## Diseño Web con Penpot sobre docker
Necesitas tener el archivo env con las variables de entorno.
Luego de ejecutar docker-compose up -d puedes crear
Podes crear un usuario para poder iniciar sesión en la aplicación usando este comando: 

'docker exec -ti penpot-penpot-backend-1 python3 manage.py create-profile'

Si el comando te da error chequea con docker ps para verificar que sea el correcto
