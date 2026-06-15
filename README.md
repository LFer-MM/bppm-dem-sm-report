# Trabajo Terminal – Maestría en Ciencias de Datos, UNISON

> **Título:** Título del trabajo terminal  
> **Alumno:** Nombre completo del alumno  
> **Director:** Dr(a). Nombre del director  
> **Institución:** Universidad de Sonora – Departamento de Matemáticas

---

## Estructura del repositorio

```
thesis-mcd/
├── index.md                         # Portada / página principal
├── myst.yml                         # Configuración de MyST / Jupyter Book
├── references.bib                   # Referencias bibliográficas (BibTeX)
├── requirements.txt                 # Dependencias Python
│
├── 01_declaracion_logros/
│   └── logros.md                    # Descripción del trabajo y logros
│
├── 02_resumen_ejecutivo/
│   ├── contexto.md
│   ├── ciclo_ciencia_datos.md
│   ├── descripcion_producto.md
│   ├── resultados_conclusiones.md
│   └── impacto.md
│
├── 03_reporte_tecnico/
│   ├── 01_contexto.ipynb
│   ├── 02_analisis_datos_entrada.ipynb
│   ├── 03_ingenieria_caracteristicas.ipynb
│   ├── 04_modelo_linea_base.ipynb
│   ├── 05_configuracion_modelo_propuesto.ipynb
│   ├── 06_metodologia_entrenamiento.ipynb
│   ├── 07_medicion_desempeno.ipynb
│   ├── 08_conclusiones.md
│   └── 09_equipo_trabajo.md
│
├── 04_apendice/
│   └── documentacion_libreria.md
│
└── .github/workflows/
    └── deploy.yml                   # Auto-deploy a GitHub Pages
```

---

## Cómo usar este repositorio

### 1. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 2. Construir el libro localmente

```bash
myst build --html
```

Luego abre `_build/html/index.html` en tu navegador.

### 3. Publicar en GitHub Pages

1. Sube el repositorio a GitHub.
2. Ve a **Settings → Pages** y selecciona **GitHub Actions** como fuente.
3. Cada `push` a `main` desplegará el libro automáticamente.

---

## Personalización

- Edita `myst.yml` para cambiar el título, autor y estructura de navegación.
- Agrega referencias en `references.bib`.
- Los notebooks en `03_reporte_tecnico/` admiten código Python, ecuaciones LaTeX y markdown enriquecido.

---

*Universidad de Sonora · Maestría en Ciencias de Datos · 2024*
