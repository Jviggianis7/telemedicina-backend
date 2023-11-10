<h1 align="center"> TeleMedicina </h1>

<p align="center">plataforma web para Telemedicina </p>


<br/><h4 align="center" id="comoRodar">pre-requisitos para iniciar la app</h4>

<h5>1. Instalar PostgreSQL</h5>
<a href="https://fabridata.com/como-instalar-postgresql-13-no-windows/"><small>Material de apoio</small></a>

<h5>2. Descarga o clonar este repositorio</h5>

<h5>3. Acceder al proyecto por terminar/cmd</h5>

```
cd telemedicina-backend
```

<h5>4. Instalar dependencias</h5>

```
npm install
```

<h5>5. En postgreSQL crea una DB con las siguientes indicaciones:</h5>
DB: <strong>telemedicina</strong><br/>
Usuario: <strong>postgres</strong><br/>
Password: <strong>postgres</strong><br/>
Host: <strong>localhost</strong><br/>
Port: <strong>5432</strong><br/>


<h5>6. Crear las tablas en la DB</h5>

```
npx knex migrate:latest
```

<h5>7. Enviar datos a la DB</h5>

```
npx knex seed:run
```

<h5>8. correr app </h5>

```
npm start
```

<h5>9. el servidor iniciará en el port:3333</h5>
