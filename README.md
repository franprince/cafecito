# Cafecito | Damián Catanzaro

Cafecito es un proyecto hecho en Next.JS con Express.JS y MongoDB para recibir cafés ☕️ a modo de donaciones.

**Demo:** https://cafecito.damiancatanzaro.com/

**Autor:** [@DamianCatanzaro](https://twitter.com/DamianCatanzaro)

## Requerimientos

-   NodeJS
-   MongoDB

## Instalación

```
git clone https://github.com/dcatanzaro/cafecito
```

## Instalación de paquetes de NPM

```
npm install
```

## Editar el archivo .env.development para desarrollo

```
DB_HOST=localhost
DB_PORT=27017
DB_USER=
DB_PASS=
DB_NAME=cafecito

TELEGRAM_BOTID=
TELEGRAM_CHATID=

PORT=3000

ACCESS_KEY_MP=

PASSWORD_EDITOR=nuestra_password
URL=http://localhost:3000
```

## Para producción: crear el archivo .env con su configuración

```
DB_HOST=localhost
DB_PORT=27017
DB_USER=
DB_PASS=
DB_NAME=cafecito

TELEGRAM_BOTID=
TELEGRAM_CHATID=

PORT=3000

ACCESS_KEY_MP=

PASSWORD_EDITOR=nuestra_password
URL=http://localhost:3000
```

## Para correr entorno de desarrollo

```
npm run dev
```

## Para correr entorno de producción

```
npm run build
npm run start
```

## Para correr el entorno de producción con Docker

```
docker-compose up -d --build
```
