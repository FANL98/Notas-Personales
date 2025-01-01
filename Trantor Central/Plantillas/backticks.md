<%*
if (tp.file.selection()) {
    tR += `\`${tp.file.selection()}\``;
} else {
    tR += "``"; // Si no hay texto seleccionado, inserta backticks vacíos
}
%>
