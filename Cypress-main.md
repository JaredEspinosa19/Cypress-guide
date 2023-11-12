# ¿Qué es Cypress?

Cypress es una herramienta de testeo front-end para construir sitios web.

Cypress permite llevar diferentes tareas de testeo, como:
- Configuración de pruebas
- Redacción de pruebas
- Ejecución de pruebas
- Depuración de pruebas


## Tipos de pruebas

- **End-to-end**: Las pruebas End-to-End (E2E) permiten simular un flujo completo de acciones en el navegador mediante la interfaz de usuario. [Link](Test-types.md#end-to-end)
- **Components**: Este tipo de pruebas permiten probar componentes para ciertos frameworks web. Mediante este enfoque, se pueden ejecutar **pruebas unitarias** con cada componente. [Link](Test-types.md#components)

## Configuración e Instalación

### Instalación de dependencias

Una vez creado el proyecto, se instala las dependencias de Cypress.

Esto se puede realizar mediante *npm*,*yarn*, *pnpm*
```
npm install cypress --save-dev
``` 

Las versiones de Node con las que se pueden utilizar son:
- Node.js 18.x
- Node.js 20.x


### Correr aplicación

Una vez instaladas todas las dependencias, se puede abrir la aplicación.

Para realizar esto se pueden usar tanto *npx* como *yarn*

Se ubica en la raíz del proyecto.

```
npx cypress open
```

Esto lanzaría la aplicación y se procedería a seleccionar el tipo de prueba a realizar y el navegador. [Realizar pruebas](Example.md)

## Uso con Frameworks

De acuerdo a la documentación oficial de Cypress, estos son los frameworks y derivados con los que trabaja.

- React [Link](End-to-End.md)
  - CRA (Create React App) 
  - Next.js
  - React with Vite
  - React with Webpack

- Angular
  - Angular 13+
  
- Svelt
  - Vue CLI
  - Nuxt
  - Vue with Vite
  - Vue with Webpack

- Vue
  - Svelte with Vite
  - Svelte with Webpack

Tambien se pueden hacer implementaciones con otras herramientas:
  
- Remix [Link](Remix.md)