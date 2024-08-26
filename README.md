# Saludo

Este es un pequeño programa en Node.js que solicita al usuario su nombre a través de la consola y muestra un mensaje de saludo personalizado.

## Descripción

El programa utiliza la biblioteca `prompt-sync` para capturar la entrada del usuario desde la consola. Luego, muestra un mensaje de saludo que incluye el nombre ingresado por el usuario.

## Instalación

Para ejecutar el programa, necesitas tener Node.js instalado en tu máquina. Si aún no lo tienes, puedes descargarlo desde [nodejs.org](https://nodejs.org/).

1. Clona este repositorio o descarga los archivos del proyecto.
2. Abre una terminal en el directorio del proyecto.

   ```bash
   cd ruta/a/tu/proyecto
   ```

3. Instala las dependencias necesarias ejecutando el siguiente comando:

   ```bash
   npm install prompt-sync
   ```

## Uso

1. Crea un archivo llamado `saludo.js` y copia el siguiente código en él:

   ```javascript
   const prompt = require('prompt-sync')();

   // Solicita al usuario que ingrese su nombre
   const nombre = prompt('Por favor, ingresa tu nombre: ');

   // Muestra el saludo con el nombre ingresado
   console.log(`Hola ${nombre}`);
   ```

2. Ejecuta el programa con Node.js:

   ```bash
   node saludo.js
   ```

3. El programa pedirá que ingreses tu nombre y, una vez ingresado, te saludará con un mensaje personalizado.

## Autores

- Diego Corsi
- Miguel Silva
- Alumnos varios

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

```

### Explicación del `README.md`:

- **Descripción**: Explica qué hace el programa y cómo utiliza `prompt-sync`.
- **Instalación**: Detalla los pasos para instalar las dependencias necesarias (`prompt-sync`).
- **Uso**: Proporciona instrucciones para crear el archivo JavaScript y ejecutar el programa.
- **Autores**: Enumera a los autores del programa.
- **Licencia**: Menciona la licencia del proyecto (en este caso, MIT).

Este `README.md` proporciona toda la información necesaria para que alguien pueda entender, instalar y ejecutar el programa.
