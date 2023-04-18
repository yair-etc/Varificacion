# Varificacion
//Verifica si el usuario tiene las credenciales para manejar 
<meta charset="UTF-8">

<script>
     function saltarLinea() {
        document.write("<br>");
    }
    function imprimir(frase) {
        document.write(frase);
        saltarLinea();
    }
    var edad = parseInt(prompt("¿Cuál es tu edad? "));

if (edad >= 18) {
  var licencia = prompt("¿Tienes licencia de conducir? (sí, s ó si/no) ");
  if (licencia === "si" || licencia == "s" || licencia == "sí") {
    imprimir("¡Puedes conducir!");
  } else {
    imprimir("Lo siento, no puedes conducir sin licencia.");
  }
} else if (edad > 0 && edad < 18) {
  imprimir("Lo siento, debes tener al menos 18 años para conducir.");
} 

</script>
