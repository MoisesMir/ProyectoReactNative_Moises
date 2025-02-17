# Proyecto Dad Moises

Este es un proyecto creado por el alumno **Moises David Miranda Rivero** del 2º curso del ciclo **DAM** (Desarrollo de Aplicaciones Multiplataforma) para el módulo de **DAD** (Desarrollo de Aplicaciones Distribuidas). El proyecto ha sido desarrollado con fines educativos y sin ánimo de lucro.

## Descripción

El proyecto tiene como objetivo desarrollar una aplicación distribuida utilizando las mejores prácticas de desarrollo web y de aplicaciones. Las tecnologías utilizadas en el proyecto permiten la gestión y consulta de datos a través de una API REST.

## Tecnologías Utilizadas

- **Frontend**: React.js
- **Backend**: Node.js
- **Despliegue**: npm

---

## Instalación

Sigue los siguientes pasos para instalar el proyecto localmente:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/MoisesMir/ProyectoReactNative_Moises
   ```

2. Accede al directorio del proyecto:
   ```bash
   cd ProyectoDadMoises
   ```

3. Instala las dependencias:
   ```bash
   npm install
   ```

4. Configura las variables de entorno (copia el archivo `.env.example` a `.env` y edítalo con tus datos).

5. Inicia la aplicación:
   ```bash
   npm start
   ```

---

## Uso de la API

A continuación se describen los endpoints de la API disponibles:

### Obtener todos los elementos

**Endpoint:** `GET /api/items`

**Parámetros:**

| Nombre    | Tipo    | Descripción                    |
| --------- | ------- | -------------------------------- |
| `api_key` | string  | **Requerido**. Tu clave de API   |

### Obtener un elemento por ID

**Endpoint:** `GET /api/items/{id}`

**Parámetros:**

| Nombre | Tipo   | Descripción                    |
| ------ | ------ | ------------------------------ |
| `id`   | string | **Requerido**. ID del elemento  |

### Funciones internas

- **`add(num1, num2)`**: Recibe dos números y devuelve la suma.

---

## Despliegue

Para desplegar este proyecto, ejecuta el siguiente comando:

```bash
npm run deploy
```

---

## Documentación

Para más información, consulta la [documentación completa](https://linktodocumentation).

---

## Agradecimientos

- [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
- [Awesome README](https://github.com/matiassingers/awesome-readme)
- [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

---

## Autores

- Moises David Miranda Rivero
   - [@MoisesMir](https://github.com/MoisesMir)

---

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](https://opensource.org/licenses/MIT).

