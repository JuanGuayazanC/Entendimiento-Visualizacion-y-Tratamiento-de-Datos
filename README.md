# Entendimiento, Visualización y Tratamiento de Datos (EVTD)

Agrupa los talleres, recursos y el proyecto del curso.

## Estructura del proyecto

```
Entendimiento-Visualizacion-y-Tratamiento-de-Datos/
├── Talleres/
│   └── Medidas-y-Estadisticos-EVTD/
├── Recursos/
│   └── Visualizacion-Exploratoria-Exoplanetas-EVTD/
└── Proyectos/
    └── Analisis-Exploratorio-y-Visualizacion-del-Desempeno-ICFES-EVTD/
```

## Temas del curso

- Medidas de tendencia central y cuantiles sobre variables ordinales.
- Calidad de datos, datos faltantes y reportes automáticos de exploración.
- Visualización exploratoria de datos: histogramas, boxplots, densidad, dispersión, QQ-plots.
- Correlación y análisis bivariado.
- Aplicaciones interactivas básicas con Shiny.

## Cosas a tener en cuenta

- Cada repositorio corresponde a una actividad puntual (taller o recurso) o al proyecto del curso; el tipo de actividad está indicado en la descripción de cada repositorio, no en su nombre.
- El recurso (`Visualizacion-Exploratoria-Exoplanetas-EVTD`) son ejercicios de clase trabajados a partir de material del profesor, sin entrega individual.
- El taller (`Medidas-y-Estadisticos-EVTD`) se entregó junto con Daniel Esteban Rodríguez Suárez.
- El proyecto del curso tiene una estructura de README distinta a la del resto de actividades académicas, ya que corresponde a un trabajo de análisis extendido y no a una entrega puntual.

## Profesor

Jaime Roberto Muñoz Luque.

## Cómo usar este repositorio

Este repositorio no contiene código directamente: es una colección de repositorios independientes, uno por actividad, organizados por carpetas (`Talleres/`, `Recursos/`, `Proyectos/`). Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Entendimiento-Visualizacion-y-Tratamiento-de-Datos.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
