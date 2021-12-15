# Objetivo-3

Api Rest:

Se desarrollo un servicio API REST, utilizando el siguiente stack python3 Flask SQLalchemy MYSQL:
  
Endpoints:
```
  - 127.0.0.1:5000/[GET,POST] (home): Login / Register user
  - 127.0.0.1:5000/logout[GET]: Log out
  - 127.0.0.1:5000/create_client[GET,POST]: create client grant
  - 127.0.0.1:5000/oauth2/token[POST]: request token bearer
```
Recursos protegidos:

```
  - 127.0.0.1:5000/Course [ GET ]: Obtener listado de cursos
  - 127.0.0.1:5000/Course [ POST ]: Cargar cursos
  - 127.0.0.1:5000/Course [ PUT ]: Modificar cursos
  - 127.0.0.1:5000/Course [ DELETE ]: Eliminar cursos

```


#Instalacion:
 ```
  > clone git@github.com:Diplomatura-UnstaTPFinal-Grupo3/Objetivo-3.git
  
  > pip install -r requirements.txt
  
  > docker run --name mysql -p 3306:3306 -v /home//mysql:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=Passw0rd -d mysql
  
  > flask run
 ```
  
  
  
