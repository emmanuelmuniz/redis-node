## Redis con Node JS

Ejemplo de API básica usando Redis con Node JS. 

## Pasos de la instalación y ejecución del proyecto

### 1. Descargar el repositorio
Descargar el repositorio como .zip y extraer los archivos o clonarlo desde una consola con el siguiente comando:

```
git clone https://github.com/emmanuelmuniz/redis-node.git
```

### 2. Instalar dependencias
Ubicarse dentro del directorio principal del proyecto (/redis-node) y ejecutar en una consola el siguiente comando:
```
npm install
```

### 3. Instalar y hacer uso redis
Podemos hacer uso de redis de dos maneras
1. Ejecutar el comando ```npm i redis``` para instalar redis  en nuestra computadora.
2. Usando docker: 
```
docker run --name some-redis -p 6379:6379 -d redis
```

### 4. Ejecución del servidor de nuestra app
Ejecutar el comando ```npm run dev```

### 5. Probar endpoints
Ya realizados los pasos anteriores, se puede probar nuestra app accediendo a los siguientes endpoints:

1. Endpoint para solicitar todos los personajes: http://localhost:3000/character
2. Endpoint para solicitar un personaje en particula por medio de su id: http://localhost:3000/character/id
