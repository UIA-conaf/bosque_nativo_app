# Bosque Nativo · Herramientas

Páginas HTML estáticas de apoyo al **Fondo de Conservación, Recuperación y Manejo Sustentable del Bosque Nativo (Ley 20.283)**. No hay backend, build ni dependencias: cada página es un único archivo con su CSS y su JavaScript en línea (solo cargan la tipografía desde Google Fonts).

| Archivo | Qué es |
|---|---|
| `index.html` | Portada con enlaces a `calculadora.html` y `simulador.html`. |
| `calculadora.html` | «Calculadora del polinomio 2027»: puntaje de un proyecto con el polinomio vigente (Res. Ex. N° 76/2022) y con la propuesta 2027. |
| `calculadora2.html` | Otra versión de la misma calculadora (mismo título y mismo `<h1>`). **No está enlazada desde `index.html`.** |
| `simulador.html` | «Simulador de cupos regionales»: cómo se reparte el dinero del concurso entre regiones. |
| `docs/CONSTRUCCION.md` | Rastro de la consulta a la fábrica (IGNUS) cuando se creó `index.html`. |

## Cómo usarlo

Abrir `index.html` en el navegador, o servir la carpeta:

```bash
python -m http.server 8000   # y abrir http://localhost:8000/
```

No hay workflows de despliegue en el repositorio (no existe `.github/`). Dónde se publica: no comprobado.

Revisado el 2026-11-24: comprobé que los enlaces de `index.html` apuntan a archivos existentes. No comprobado: el render de las páginas ni sus cálculos.
