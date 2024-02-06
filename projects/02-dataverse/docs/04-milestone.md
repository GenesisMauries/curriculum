# **HITO 4:** Cálculo

El propósito de este hito es realizar cálculos con
la información. Recuerda la importancia de seguir
la práctica de
emplear al menos una
[rama](https://www.atlassian.com/es/git/tutorials/comparing-workflows/feature-branch-workflow)
por hito o característica.

## Tareas de este hito

- [Cálculos estadísticos del dataset](#cálculos-estadísticos-del-dataset)
- [Test de la funcion del calcular](#test-de-la-funcion-del-calcular)
- [Test OAS](#test-oas)
- [Hacker edition](#hacker-edition)

### Cálculos estadísticos del dataset

La función `computeStats` debe recibir la `data` y realizar
cálculos según los criterios que estás estableciendo.

1. Selecciona el tipo de cálculo que deseas realizar y
evalúa la necesidad de un activador, como un botón o
un menú desplegable, para llevar a cabo la operación.
Asegúrate de considerar la experiencia de usuaria
y el contexto de la aplicación al tomar esta decisión.
2. En el archivo principal `src/main.js`, utiliza un
selector del DOM y un manejador de eventos para
seleccionar y vincular un evento al elemento `<button>` o `<select>`.
3. En `src/dataFunctions.js`, crea la función `computeStats(data)`
encargada de realizar los cálculos según el criterio.
4. En `src/main.js`, invoca la función `computeStats`
y proporciona la `data` como argumento para realizar los
cálculos necesarios.
5. Regresa a `src/dataFunctions.js` y verifica que la
función esté recibiendo los valores;
puedes hacerlo mediante un `console.log`.
6. Una vez confirmados los valores, realiza los cálculos necesarios,
por ejemplo la longitud promedio de los nombres, usando el metodo
[reduce](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
y devuelve el resultado.
7. Una vez obtenido el valor de retorno en `src/main.js`,
llama a la función encargada de mostrar los resultados `renderItems`,
pasando como argumento el nuevo arreglo con los resultados de los cálculos.
8. [Aplica estilos al elemento creado](./03-milestone.md/#estilos)

> [!TIP]
> [reduce](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

### Test de la funcion del calcular

Realiza las pruebas; ahora que has implementado
la función de cálculo, procede a escribir los tests.
Puedes utilizar esta
[guía](./test.md)
como punto de referencia.

### Test OAS

En este punto, la verificación constante de los tests debe formar
parte de tu rutina diaria. Ejecuta las pruebas y realiza los cambios
o ajustes necesarios para que todas y cada una de ellas pasen
satisfactoriamente. Este proceso continuo garantiza la calidad
y fiabilidad del código a lo largo del desarrollo del proyecto.

``` sh
npm run test:oas-html
npm run test:oas-css
npm run test:oas-web-api
npm run test:oas-js
```

### Hacker edition

Antes de embarcarte en la sección de "Hacker Edition", es
crucial que valores tu disponibilidad de tiempo. No es aconsejable
prolongar la ejecución de un proyecto más allá de lo necesario,
ya que el bootcamp tiene un límite de tiempo establecido, y quedarse
indefinidamente en el mismo proyecto no es viable. Siempre puedes
consultar esta decisión con tus coaches para obtener orientación adicional.

[Hacker Edition](../README.md/#8-hacker-edition)

[👈Todos los hitos](../README.md#6-hitos)
