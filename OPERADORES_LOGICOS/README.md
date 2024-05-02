# OPERADORES LOGICOS
Estos operadores se utilizan principalmente en estructuras de control de flujo, como condicionales if, else if, else y bucles for, while, para tomar decisiones basadas en múltiples condiciones.
## AND (Y): 
Representado por el operador &&. Devuelve verdadero si ambas condiciones son verdaderas, de lo contrario, devuelve falso.
## OR (O): 
Representado por el operador ||. Devuelve verdadero si al menos una de las condiciones es verdadera, de lo contrario, devuelve falso.
## NOT (NO): 
Representado por el operador !. Devuelve el valor opuesto de la condición; es decir, si la condición es verdadera, devuelve falso, y si la condición es falsa, devuelve verdadero.
>EJEMPLO
```python
var edad = 20;
var ciudad = "Nueva York";

if (edad >= 18 && ciudad === "Nueva York") {
    console.log("Eres mayor de edad y vives en Nueva York");
} else if (edad >= 18 || ciudad === "Nueva York") {
    console.log("Eres mayor de edad o vives en Nueva York");
} else {
    console.log("No eres mayor de edad ni vives en Nueva York");
}
```