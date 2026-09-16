# PetCare — Prototipo académico v9

## Qué conserva
- Biblioteca cerrada de 50 artículos.
- Tofi usa únicamente la biblioteca de PetCare como fuente de respuesta.
- La comunidad no es fuente de Tofi.
- Información verificada (🟢) y experiencia comunitaria (🔵) permanecen separadas.
- Cuenta/perfil y funciones de comunidad del prototipo anterior.

## Nueva funcionalidad de Tofi
Tofi incorpora una clasificación previa de consultas:

- 🟢 **VERIFIED**: existe coincidencia temática en la biblioteca; responde con resumen y fuente.
- 🟡 **REVIEW_BELIEF**: detecta una duda genuina sobre una creencia/costumbre; no la valida, muestra temas relacionados y permite proponerla a la comunidad.
- 🟡 **REVIEW_AMBIGUOUS**: consulta genuina pero insuficientemente clara o fuera de la biblioteca; puede pasar a segunda revisión.
- 🔴 **RISKY_MEDICAL**: evita inventar tratamientos, dosis o métodos caseros y no deriva automáticamente a la comunidad como sustituto de atención veterinaria.
- 🚫 **TROLL**: no genera artículos ni deriva a moderación cuando identifica una provocación/spam evidente.
- ⚪ **OUT_OF_LIBRARY**: informa que no hay información verificada suficiente.

## Moderación híbrida del prototipo
La moderación humana funciona como **segunda revisión**, no como paso obligatorio para todo contenido. Solo se propone cuando Tofi considera que una consulta puede ser una publicación comunitaria válida o necesita revisión.

La publicación comunitaria requiere cuenta. El contenido aprobado seguirá marcado como **no verificado por PetCare** y nunca se convierte en fuente de Tofi.

> Nota: esta es una demostración estática. En una versión productiva, el clasificador, la autenticación, la cola de moderación y las decisiones de publicación deben ejecutarse en servidor y persistirse en una base de datos.


## v10 — Renovación visual
Se mejoró la interfaz visual de PetCare sin modificar la lógica funcional de Tofi, los 50 artículos, comunidad, cuenta y moderación.
