function generarNumerosAleatorios(cantidad, minimo, maximo) {
  const numerosAleatorios = [];
  
  for (let i = 0; i < cantidad; i++) {
    const numeroAleatorio = Math.floor(Math.random() * (maximo - minimo + 1)) + minimo;
    numerosAleatorios.push(numeroAleatorio);
  }
  
  return numerosAleatorios;
}

// Ejemplo de uso:
const arregloAleatorio = generarNumerosAleatorios(5, 1, 10);
console.log(arregloAleatorio);
