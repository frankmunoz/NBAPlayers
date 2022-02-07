## NBA Players match

### Project

El proyecto consiste en crear una funcion que busca los jugadores de la NBA
basado en la entrada del usuario.  Los datos originalmente vienen de
[aquí](https://www.openintro.org/data/index.php?data=nba_heights).  Los datos
son servidos en formato json [aquí](https://mach-eight.uc.r.appspot.com/).

La tarea es crear una aplicación que solicita al usuario que ingrese una entrada
numérica. La aplicación descarga los datos del sitio web arriba
(https://mach-eight.uc.r.appspot.com) e imprime todos los pares de jugadores
cuyas alturas en pulgadas se suman al número de entrada. Si no se encuentran
coincidentes, la aplicación imprime "No coincidentes encontrada"

Ejemplo de salida de la siguiente manera:
```
> app 139

- Brevin Knight         Nate Robinson
- Nate Robinson         Mike Wilks
```

El algoritmo para encontrar los pares debe ser más rápido que O(n^2). Debe
funcionar correctamente en todos los casos extremos.

