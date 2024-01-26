# Para crear un proyecto en Vue.js, puedes seguir estos pasos básicos. Asegúrate de tener Node.js y npm instalados en tu sistema antes de comenzar.

# Instalar Vue CLI:
Vue CLI es una interfaz de línea de comandos para Vue.js que facilita la creación de nuevos proyectos. Instálala globalmente usando npm:
npm install -g @vue/cli

# Crear un nuevo proyecto:
Una vez instalado Vue CLI, puedes crear un nuevo proyecto. Ejecuta el siguiente comando y sigue las instrucciones:
vue create nombre-de-tu-proyecto

# Para usar las imagenes en vue
En proyectos Vue.js creados con Vue CLI, las rutas a los archivos en src/assets deben ser resueltas usando Webpack. Esto significa que debes importar la imagen en tu componente y luego usar esa variable importada como la fuente de la imagen.
Miralo como esta hecho en GaleriaCientificos

# vue-componentes
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
