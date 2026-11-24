# CLAUDE.md — bosque_nativo_app

## Qué es y en qué estado está (revisado el 2026-11-24)
Herramientas HTML estáticas del Fondo de Bosque Nativo (Ley 20.283): calculadora del polinomio de puntaje y simulador de cupos regionales. Qué hay en cada archivo y cómo abrirlo: [README.md](README.md), que manda en eso.

## Lo que no se ve leyendo el código
- Cada página es autocontenida (CSS y JS en línea). No hay `package.json`, build, pruebas ni lint: no inventes un pipeline para "comprobar" cambios; se comprueba abriendo la página y mirándola.
- `calculadora.html` y `calculadora2.html` son dos versiones de la misma calculadora (mismo título). Solo la primera está enlazada en `index.html`. Cuál es la vigente: no comprobado; preguntar antes de borrar una o de cambiar el enlace.
- Las fórmulas (polinomio Res. Ex. N° 76/2022, propuesta 2027, reparto de cupos) viven en el JavaScript de cada página; no hay una especificación aparte en el repo.
- Antes de construir algo nuevo se consulta la fábrica y se deja el rastro en `docs/CONSTRUCCION.md` (así se hizo con `index.html`).

## Git
Rama por defecto `main`. No hay CI ni despliegue en el repositorio.
