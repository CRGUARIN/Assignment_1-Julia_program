# Informe IEEE en LaTeX

## Compilación

Desde esta carpeta:

```bash
latexmk -pdf main.tex
```

El PDF resultante se crea como `build/main.pdf`.

Para eliminar archivos auxiliares:

```bash
latexmk -c
```

## Organización

- `main.tex`: configuración general y orden de las secciones.
- `sections/`: contenido del informe.
- `figures/`: esquema del sistema y futuras figuras exportadas por Julia.
- `code/`: código Julia definitivo; por ahora contiene una guía breve para su incorporación.
- `references.bib`: fuentes bibliográficas.

Antes de entregar, reemplazar los nombres de las integrantes y completar todos los avisos marcados como “Pendiente de completar”. El apéndice ya está conectado con `sections/09_codigo.tex`; al existir el programa definitivo, solo es necesario activar allí la instrucción que lee `code/assignment1.jl`.
