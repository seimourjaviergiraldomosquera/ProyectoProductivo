function calcularDistancia(x1, y1, x2, y2) {
    var distancia = Math.sqrt(Math.pow(x2 - x1, 2) + Math.pow(y2 - y1, 2));
    return distancia;
}

// Ejemplo de uso
var distancia = calcularDistancia(0, 0, 3, 4);
console.log("La distancia entre los puntos es: " + distancia);
