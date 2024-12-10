# SOAP
Este es un proyecto que fue desarrollado con java con una arquitectura Soap.

## Descripción
Este proyecto muestra la suma de dos valores enteros atraves postman. 
Es un programa sencillo para mostrar cómo funciona un programa en el lenguaje de programación con un estilo de arquitectura.

## Tecnologías Utilizadas
**Contiene lo Siguiente**
- Visual Studio C# (version mas actual)
- Docker
- Webhook
- Postman

## Requerimientos para el Desarrollo
- **Docker Desktop** (si lo quieres correr en un contenedor)
- **Visual Studio C#** (opcional, pero recomendado)
- **Soap**(requerido y recomendado)
- **GitHub Desktop** (si quieres clonar y usar el proyecto)
  
  ```bash
  https://www.docker.com/products/docker-desktop/
  ```
  
- **Docker hub** (si quieres clonar y usar el proyecto)
  
  ```bash
  https://hub.docker.com/layers/erickjrm/programsoap/latest/images/sha256-76c3272200d35a863fe9edd0ffeac9bd15438aff617c28a800e5cf646f124c9a?context=repo
  ```

## Intruciciones para ejecutar el proyecto
## Pasos para ejecutar
- **Paso #1**
  **Clonar este repositorio**
Si aún no ha clonado el repositorio, puede hacerlo con el siguiente link:

 ```bash
https://github.com/JosueRM2001/soap1.git
 ```
- **Paso #2**
  **Construya la imagen de Docker**

Ejecuta el siguiente comando, que generará la imagen:

```bash
docker pull erickjrm/programsoap:latest
```

**Paso #3**
**Ejecute el contenedor Docker:**

Luego ejecuta el siguiente comando, en postman.

```bash
https://localhost:7259/Service.asmx/Sum
```

**Paso #4**

Abre Docker Desktop para ver si la imagen se creó correctamente y envíala a ejecutar para verla.

**Paso #5**

**Accede a la aplicación**: Si está ejecutándose, puedes acceder a la aplicación navegando a la

siguiente url en tu navegador web:

```bash
https://localhost:7259/Service.asmx
```
