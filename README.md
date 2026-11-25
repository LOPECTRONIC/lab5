# Laboratorio 5 - Polimorfismo en Java

## Ejecución
Descomprimir el ZIP y abrir la carpeta PolimorfismoLab en Visual Studio Code con Extension Pack for Java instalado. Abrir src/main/Main.java y pulsar Run. El código es compatible con Java 8.

También se puede ejecutar desde la terminal, situada en la carpeta del proyecto:

```
javac -encoding UTF-8 -d bin src/modelo/*.java src/main/Main.java
java -cp bin main.Main
```

## Resultado esperado
El animal hace un sonido.
El perro ladra: ¡Guau!
El gato maúlla: ¡Miau!
Circulo - Area: 78.54
Rectangulo - Area: 24.00
Circulo - Area: 28.27
Rectangulo - Area: 16.00

## Conclusión
El polimorfismo permite utilizar referencias de una clase padre para ejecutar los métodos sobrescritos de sus clases hijas. La clase abstracta Figura define calcularArea(), y cada figura implementa su propia fórmula. El arreglo Figura[] permite procesar círculos y rectángulos sin separar su tratamiento por tipo.
