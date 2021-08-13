# Robo Compi Code

Ejemplo utilizando Java 11, JFlex y CUP.

## Instruccioness 

### Mover 
Permite mover X cantidad de pasos hacia la dirección indicada. 

#### Direcciones 
Las direcciones permitidas son: 
- Arriba
- Abajo
- Izquierda
- Derecha

##### Sintaxis
```
Mover <EXPRESION> <MOVIMIENTO> puntoycoma
```

##### Ejemplo
```
Mover 10 + 10 a la izquierda;
Mover 100/100 a la derecha;
Mover 15*2*(10+10) hacia arriba;
Mover 4-3*(100/2) hacia abajo;
```

### Saludar
Permite mostrar un mensaje.

##### Sintaxis
```
Saludar <CADENA> puntoycoma
```

##### Ejemplo
```
Saludar "Con un mensaje interesante";
```


### Expresiones
Una expresión se entiende como una operación aritmética con números enteros. 
Las operaciones aceptadas son: 
- Suma
- Resta
- Multiplicación
- División

