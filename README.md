# #9 - Practica de while-loop

## Consigna

- Suma de números naturales:

Pedir a los estudiantes que escriban un programa que calcule la suma de los primeros n números naturales utilizando un bucle while. Por ejemplo, si n es 5, la suma sería 1 + 2 + 3 + 4 + 5 = 15.

## Código

```javascript
const n = 15;

let i = 1;
let sum = 0;

while (i <= n) {
	sum += i;
	i++;
}
```
