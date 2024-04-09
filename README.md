# React + Docker + Vite

1. Clonar el repositorio

2. Instalar dependencias
```
yarn install
```

3. Build imagen
```
docker build -t react-docker:1 .     
```

4. Crear contenedor basado en la imagen
```
docker run -d --rm --name react-docker -p 8087:80 react-docker:1
```

5. Ejecutar la aplicación en dev:
```
yarn dev
```

6. Acceder a sitio web
```
http://localhost:8087
```

## Stack usado
* Docker
* React