<%* let content = tp.file.selection(); // Obtiene el texto seleccionado 
let tags = content.split(" "); // Divide las palabras por espacios 
tags.sort((a, b) => a.slice(1).localeCompare(b.slice(1))); // Ordena ignorando el primer carácter 
tR = tags.join(" "); // Devuelve el resultado %>