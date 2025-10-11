# Sistema de Anotación de Video para Análisis de Actividades Motoras

Análisis y clasificación de 5 actividades motoras mediante visión computacional: caminar hacia la cámara, caminar de regreso, girar, sentarse y ponerse de pie.

## Estructura del Proyecto

```text
video-annotation-system/
├── data/                 # Videos
├── results/              # Reportes generados 
├── notebooks/            # Notebooks de análisis
│   └── eda_videos.ipynb  # EDA de metadatos de videos
└── Entrega1/             # Primera entrega
    └── Informe1.md
```

## Uso

### 1. Preparar datos

Coloca los videos en `data/raw/`

### 2. Ejecutar EDA

```bash
jupyter notebook notebooks/eda_videos.ipynb
```

El notebook analiza metadatos de videos (tamaño, formato, fechas) y genera `results/video_eda_report.json`

## Equipo - Grupo 3

- Sebastian Erazo Ochoa (A00400086)
- Gabriel Ernesto Escobar Bravo (A00399291)
- Rony Farid Ordoñez García (A00397968)

Universidad ICESI - APO3 - 2025-2
