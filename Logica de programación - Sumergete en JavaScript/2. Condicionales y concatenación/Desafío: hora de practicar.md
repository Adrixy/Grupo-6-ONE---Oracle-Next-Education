# Solución de desafíos

1. Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!".
```javascript
let semanadia = prompt("¿Que día de la semana es?");
if (semanadia === "Sabado" || semanadia === "Domingo"){
  alert("¡Buen fin de semana!");
  }
  else {
  alert("Buena semana");
  }
```
2. Verifica si un número ingresado por el usuario es positivo o negativo. Muestra una alerta informativa.
```javascript
let num = prompt("Digite un numero negativo o positivo: ");
if (num > 0) {
  alert ("Número positivo");
} else if (num < 0) {
  alert ("Numero negativo"); 
} else {
  alert ("El número es cero");
}
```
3. Crea un sistema de puntuación para un juego. Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". En caso contrario, muestra "Intenta nuevamente para ganar.
```javascript
let puntaje = prompt("Cuanto es tu puntaje?");
if (puntaje >= 100) {
  console.log("¡Felicidades, has ganado!");
} else {
  console.log("Intenta nuevamente para ganar");
}
```
4. Crea un mensaje que informe al usuario sobre el saldo de su cuenta, utilizando un template string para incluir el valor del saldo.
```javascript
let saldoCuenta = 750000;
let mensajeSaldo = `Su saldo actual es: $${saldoCuenta}`;
alert(mensajeSaldo);
```
5. Pide al usuario que ingrese su nombre mediante un prompt. Luego, muestra una alerta de bienvenida usando ese nombre.
```javascript
let nombre = prompt("ingrese su nombre: ")
let mensaje = "Bienvenido ${nombre}";
alert(mensaje);
```
