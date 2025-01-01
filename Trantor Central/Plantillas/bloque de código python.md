<%*
let comment = await tp.system.prompt("¿Qué título deseas para tu código?");
tR = `\`\`\`python title:${comment ? `${comment}` : ""}
# Escribe aquí tu código Python
\`\`\``;
%>
