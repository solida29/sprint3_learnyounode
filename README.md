https://github.com/solida29/sprint3_learnyounode

# Entrega 3.1: LearnYouNode

En aquesta entrega farem servir LearYouNode com a introducció a Node. Aprendràs els següents conceptes:

- Introducció a Node.js i la programació del costat del servidor
- Utilització del mòdul "fs" per llegir i escriure fitxers en el sistema de fitxers del servidor
- Creació d'un servidor web bàsic i processament de les sol·licituds HTTP entrants
- Enviament de sol·licituds HTTP a altres servidors i processament de les respostes
- Ús del mòdul "async" per treballar amb funcions asíncrones i callbacks
  A través d'aquests coneixements es poden construir aplicacions web i de servidor més complexes i útils.

-> github.com/workshopper/learnyounode

### Nivell 1

Fes servir el programa LearnYouNode per verificar que els exercicis estan ben resolts.

### Nivell 2

Crea els teus propis scripts (i l'escenari que calgui) de cada exercici per provar cadascun d'ells.

### Nivell 3

Fes els exercicis amb TypeScript i afegeix testing per comprovar el correcte funcionament de cadascun.

<hr>

### Nivell 1

Hay que transpilar todos los archivos de la carpeta src y ejecutar los js de la carpeta dist, con el programa Learnyounode, desde la Terminal:

```
learnyounode
learnyounode verify program.js
```

### Nivell 2

- Para ejecutar los scripts de los ejercicios 01 a 09, se se puede hacer con:

```
npx ntl
```

y ejecutar el ejercicio deseado.
También se puede hacer uno por uno con:

```
npx run ex01
```

- Para los ejercicios 10, 11, 12 y 13, hay que primero ejecutar el server en la Terminal vía los metodos arriba, y después el cliente en otra Terminal, para que el cliente y el server levantado puedan comunicar entre si.

- Para el ejercicio 10, primero en una Terminal, levantamos el servidor ejecutando:

```
npx run ex10server
```

Después, abrimos otra Terminal y ejecutamos:

```
npx run ex10Client
```

- Para el ejercicio 11, primero en una Terminal, levantamos el servidor ejecutando:

```
npx run ex11server
```

Después, abrimos otra Terminal y ejecutamos:

```
npx run ex11Client
```

- De la misma manera para el 12 y el 13.

### Nivell 3

En la carpeta src están los programas en Ts.
