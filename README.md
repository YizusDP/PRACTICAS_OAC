# Prácticas OAC — Laboratorio

Reportes en LaTeX de las prácticas de laboratorio de **Organización y Arquitectura de Computadoras**  
Facultad de Ingeniería, UNAM.

**Autor:** Jesús Alejandro Domínguez Palacios

## Estructura

```
Reportes_Practicas/
├── plantilla/            # Plantilla base del reporte
│   ├── reporte.tex
│   └── imagenes/
├── Practica_01/          # Copia de la plantilla por cada práctica
│   ├── reporte.tex
│   └── imagenes/
└── ...
```

## Nueva práctica

1. Copia la carpeta `plantilla/` y renómbrala `Practica_XX`.
2. Edita número, título y fecha en `reporte.tex`.
3. Compila con `pdflatex reporte.tex` (dos veces para el índice) o desde Overleaf / VS Code + LaTeX Workshop.

## Subir cambios

```bash
git add .
git commit -m "Práctica XX"
git push
```
