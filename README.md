# Pruebas CI/CD
### Nombre de los integrantes

- Julián Enrique Correa Guzmán.
- Bryan Andrés López Palacios.
- Juan David Romero Rodas.
- Juan Diego Estupiñán Restrepo.


### Herramientas Utilizadas
- [React js](https://reactjs.org/): framework de interfaces gráficas de JavaScript | V16.13.1.
- [Node js](https://nodejs.org/en/): entorno de tiempo de ejecución de JavaScript | V14.17.0.
- [Jest](https://jestjs.io/): crear los marcos de pruebas para JavaScript | V25.5.4.
- [Cypress](cypress.io): Herramienta de testing de construida para la web moderna | V8.2.0.
- [Eslint](https://eslint.org/): herramienta para identificar los patrones problemáticos dentro del código | V^6.8.0
- [WebPack](https://webpack.js.org/): empaquetar la aplicación para prepararla en su totalidad y poder subirla al servidor | V^4.43.0
- [Git](https://github.com/): sistema de control de versiones distribuido | V2.36.1
- [GitHub actions](https://github.com/features/actions) : extensión de GitHub para crear acciones y poder integrar las diferentes continuidades.
- [Heroku](https://www.heroku.com/) : servidor y alojamiento de aplicaciones de forma gratis para poder tener las aplicaciones web en internet de forma gratis | V7.65.0.

¿Que hace la aplicación?
-------------
La aplicación es muy sencilla, simplemente obtiene los datos de un api externo la cual ofrece toda la información de los diferentes pokemones que existen, con esta información lo que podemos hacer es crear una lista muy grande de los mismos mostrando lo que es su imagen, su nombre, al entrar a alguna de estos nos ofrece un detalle más amplio del Pokémon, con la posibilidad de pasar al siguiente o el anterior Pokémon en la lista.

La finalidad de la misma es practicar como implementar CI/CD en un proyecto y su funcionamiento.

### Instrucciones
                
----

#### **Clonar**

Para clonar el repositorio utilice el siguiente comando en su línea de comandos de [Git](https://git-scm.com/)

```sh
git clone https://github.com/jestupinanr/testCD.git
```

Si lo desea también puede dirigirse al repositorio del proyecto, allí seleccione 'code' y podrá también descargar el proyecto en formato ZIP.

Para que el proyecto funcione correctamente no olvide ejecutar el comando inferior para descargar las dependencias del proyecto.

```sh
npm install
```

#### **Ejecutar**

Si desea ejecutar el proyecto en su ambiente local dirijase a la terminal de comandos de su preferencia y ejecute el comando que encontrará en la parte inferior

```sh
npm run dev
```

Una vez ejecutado el proyecto correrá por defecto en el puerto que encontrará debajo.

```sh
http://localhost:8080/
```

#### **Pruebas**
Para ejecutar el ambiente de pruebas impulsado por Cypress ejecute el siguiente comando.

```sh
npm run test:e2e
```

Para ejectar el ambiente de pruebas impulsado por jest ejecute el siguiente comando.

```sh
npm run test
```

Para ejecutar el analisis del codigo con Eslint ejecute el siguiente comando.

```sh
npm run eslint
```

### **Desplegar en producción**

Para desplegar a produccion se tiene que hacer push a la rama main, de alli automaticamente se desplegara en produccion si todo el proceso de pruebas sale correcto.

```sh
git add .
git commit -m 'Commit'
git branch -M main
```

### Conclusiones
Gracias a github action, jenkins y demas provedores de automatizacion de procesos podemos podemos convertir algo muy monótono en una gran ampliacion y reduccion de trabajo, con github actions podemos automatizar las pruebas, testing, entregas y desplieges a produccion de una manera muy sencilla y lo mejor es que se ofrece gratis con lo que podemos simplemente hacer un push en nuestra aplicación y en cuestion de minutos o hasta segundos (dependiendo de la cantidad de paquetes, pruebas que tenga la aplicación) podamos ver nuestros cambios en producción.

Es realmente alucinante ver como se hace cada proceso y como ahorra tiempo de trabajo, esta aplicación nos dejo una amplio conocimiento en como la automatizacion de trabajo se puede hacer, ninguno del equipo habia entrado a esta area a ver como funciona y ahora que sabemos como es y para que realmente sirve nos sirve como empujon para empezarlo a aplicar en nuestros entornos laborales e individuales.