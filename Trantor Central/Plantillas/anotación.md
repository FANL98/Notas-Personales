<%*
let topicsAndLinks = ""; // Inicializar una variable para almacenar todos los temas y notas
let continueAdding = true; // Variable para controlar el bucle

while (continueAdding) {
  const topic = await tp.system.prompt("¿Cuál es el tema?"); // Solicitar tema
  const link = await tp.system.prompt("¿Cuál es la nota a consultar?"); // Solicitar nota

  // Agregar el nuevo tema y nota al texto
  topicsAndLinks += `> - ==${topic}== consultar la nota [[${link}]].\n`;

  // Preguntar si el usuario desea agregar otro
  const addAnother = await tp.system.prompt("¿Deseas agregar otro? (si/no)");
  if (addAnother.toLowerCase() !== "si") {
    continueAdding = false; // Terminar el bucle si el usuario no quiere agregar más
  }
}

// Devolver el resultado final con todos los temas y notas
tR += `> [!NOTE] Anotación\n${topicsAndLinks}`;
%>
