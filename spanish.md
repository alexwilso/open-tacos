## Cómo construir

Asegúrese de tener las siguientes herramientas instaladas en su computadora

- [Git](https://github.com/git-guides/install-git)
- [Node](https://nodejs.org)
- [npm](https://www.npmjs.com/get-npm)
- [yarn](https://classic.yarnpkg.com/en/docs/install)

1.  Descargue el repositorio a su máquina local.

```
git clone git@github.com:OpenBeta/open-tacos.git
```

2.  Construye el código

```
cd open-tacos
git checkout develop
yarn inst
```

3. Ejecute la aplicación

```
yarn dev
```

4. Opcional: Ejecute la aplicación en docker

Requisitos: [Docker](https://docs.docker.com/get-docker/)

```
docker compose up
```

Los cambios en su archivo ./src local estarán disponibles en localhost:3000
Si instala nuevos paquetes, deberá reconstruir la imagen de la ventana acoplable con

```
docker compose up --build
```

La aplicación ya está disponible en `http://localhost:3000`