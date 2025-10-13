# 🎮 Análisis de Datos de Ventas de Videojuegos

Este proyecto presenta un análisis descriptivo completo de las ventas globales de videojuegos desde 1980 hasta 2020, utilizando Python y bibliotecas de análisis de datos.

## 📊 Resumen del Proyecto

Este análisis explora las tendencias y patrones en las ventas de videojuegos a nivel mundial, proporcionando insights sobre:
- Evolución temporal de las ventas por regiones
- Distribución de ventas por género, plataforma y editor
- Identificación de los juegos más exitosos comercialmente
- Análisis comparativo entre diferentes mercados regionales

## 📈 Dataset

### Información General
| Aspecto | Descripción |
| ------- | ----------- |
| **Nombre del DataSet** | vgsales.csv |
| **Período cubierto** | 1980 - 2020 |
| **Total de Registros** | 16,598 |
| **Total de Variables** | 11 columnas |
| **Fuente de Datos** | Kaggle |
| **Propósito del Análisis** | Análisis Descriptivo |

### Estructura de Variables

| Variable | Descripción | Tipo |
| -------- | ----------- | ---- |
| **Rank** | Ranking de ventas globales | int64 |
| **Name** | Nombre del Juego | object |
| **Platform** | Plataforma de lanzamiento | object |
| **Year** | Año de lanzamiento del juego | float64 |
| **Genre** | Género del juego | object |
| **Publisher** | Editor de juego | object |
| **NA_Sales** | Ventas en América del Norte (millones) | float64 |
| **EU_Sales** | Ventas en Europa (millones) | float64 |
| **JP_Sales** | Ventas en Japón (millones) | float64 |
| **Other_Sales** | Ventas en el resto del mundo (millones) | float64 |
| **Global_Sales** | Ventas globales (millones) | float64 |

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas**: Manipulación y análisis de datos
- **Matplotlib**: Visualización de datos
- **Jupyter Notebook**: Entorno de desarrollo interactivo

## 🔍 Análisis Realizados

### 1. Limpieza de Datos
- **Identificación de valores nulos**: Se encontraron 271 valores nulos en la columna `Year` (1.6%) y 58 en `Publisher` (0.3%)
- **Tratamiento de datos faltantes**: Eliminación de registros con datos críticos faltantes
- **Verificación de duplicados**: No se encontraron registros duplicados en el dataset

### 2. Análisis Estadístico Descriptivo
- **Estadísticas por región**: Medias, desviaciones estándar y distribuciones
- **Identificación de outliers**: Juegos con ventas excepcionales
- **Análisis de tendencias temporales**: Evolución de ventas por año

### 3. Análisis por Regiones
Las regiones analizadas incluyen:
- **NA_Sales**: América del Norte
- **EU_Sales**: Europa  
- **JP_Sales**: Japón
- **Other_Sales**: Resto del mundo

### 4. Funcionalidades Implementadas
- **Función de agrupación personalizada**: `agruparBy()` para análisis flexibles por diferentes criterios
- **Visualizaciones interactivas**: Gráficos para representar tendencias temporales
- **Análisis comparativo**: Entre regiones, géneros y plataformas

## 📁 Estructura del Proyecto

```
proyectos de data analytics/
├── README.md
├── Analisis de Jugos.ipynb    # Notebook principal con el análisis
└── CSV/
    └── vgsales.csv           # Dataset de ventas de videojuegos
```

## 🚀 Cómo Ejecutar el Proyecto

### Prerrequisitos
```bash
pip install pandas matplotlib jupyter
```

### Ejecución
1. Clona o descarga el repositorio
2. Navega al directorio del proyecto
3. Ejecuta Jupyter Notebook:
   ```bash
   jupyter notebook "Analisis de Jugos.ipynb"
   ```

## 📊 Principales Hallazgos

### Top 5 Juegos Más Vendidos (Global)
1. **Wii Sports** (82.74M) - Nintendo, 2006
2. **Super Mario Bros.** (40.24M) - Nintendo, 1985  
3. **Mario Kart Wii** (35.82M) - Nintendo, 2008
4. **Wii Sports Resort** (33.00M) - Nintendo, 2009
5. **Pokemon Red/Pokemon Blue** (31.37M) - Nintendo, 1996

### Análisis Temporal
- **Período de mayor crecimiento**: 2006-2009 (era de Nintendo Wii)
- **Pico de ventas**: 2008 con 678.90M de unidades vendidas globalmente
- **Declive reciente**: Reducción significativa post-2015

### Distribución Regional
- **América del Norte**: Mayor mercado individual
- **Europa**: Segundo mercado más grande
- **Japón**: Mercado importante para géneros específicos
- **Otros**: Mercados emergentes en crecimiento

## 🎯 Insights Clave

1. **Dominio de Nintendo**: Presencia fuerte en los juegos más vendidos
2. **Importancia de las consolas familiares**: Wii como plataforma dominante
3. **Variación regional**: Diferentes preferencias por género según la región
4. **Estacionalidad**: Patrones de lanzamiento influyen en las ventas anuales

## 📝 Metodología

El análisis sigue una metodología estructurada:

1. **Exploración inicial** de los datos
2. **Limpieza y preparación** del dataset
3. **Análisis estadístico descriptivo**
4. **Visualización** de tendencias y patrones
5. **Interpretación** de resultados y conclusiones

## 🔮 Posibles Extensiones

- Análisis predictivo de tendencias futuras
- Segmentación de mercado por demografía
- Análisis de correlación entre variables
- Implementación de modelos de machine learning
- Análisis de rentabilidad por plataforma

## 👤 Autor

Proyecto de análisis de datos desarrollado como parte del portafolio de Data Analytics.

## 📄 Licencia

Este proyecto es de uso educativo y de análisis personal.

---

*Última actualización: Octubre 2025*