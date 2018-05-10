# TypeScript Prisma Quickstart

En este tutorial quickstart, aprenderemos a construir un servidor GraphQL con
TypeScript. Utilizaremos [graphql-yoga](https://github.com/graphcool/graphql-yoga/)
como servidor web y conectaremos con la base de datos mediante Prisma, y la librería [prisma-binding](https://github.com/graphcool/prisma-binding).

### Paso 1: Instalar las herramientas
Durante este tutorial utilizaremos el CLI de Prisma para generar y gestionar Prisma.

###### Prisma CLI
El primer paso será instalar de forma global el CLI de Prisma:

```
$ npm install -g prisma
```

###### Docker
También debes tener instalado Docker:
- [Mac OS](https://www.docker.com/docker-mac)
- [Window](https://www.docker.com/docker-windows)


###### Cluster
El último paso será arrancar un cluster local donde levantar nuestro servicio prisma

```
$ prisma local start
```


### Paso 2: Inicializar nuestro servidor GraphQL
