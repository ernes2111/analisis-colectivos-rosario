🌐 [Read this in English](README_en.md)


# 🚍 Análisis de Colectivos en Rosario

Este repositorio contiene un análisis exploratorio de los datos de frecuencia de colectivos
en Rosario, Argentina. Los datos se obtuvieron mediante un script que consulta las API
cada 5 minutos, registrando posición y tiempo de arribo de las unidades.

---

## Ejemplo de Resultados

| Línea | Gráfico |
|------|---------|
| 122 ROJA | ![Frecuencia 122 ROJA](images/grafico1.png) |
| 122 VERDE | ![Frecuencia 122 VERDE](images/grafico2.png) |
| 153 N | ![Frecuencia 153 N](images/grafico3.png) |
| 153 R | ![Frecuencia 153 R](images/grafico4.png) |

> **Nota:** Las barras muestran la cantidad de coches únicos detectados por hora.
> Si el rango incluye varios días, la frecuencia se calcula como promedio diario.

---

## Contenido

- `analisis_colectivos_rosario.ipynb` → Notebook en español  
- `analisis_colectivos_rosario_en.ipynb` → Notebook traducido al inglés  
- `/images` → Gráficos generados para referencia rápida  

---

## Tecnologías utilizadas

- **Python 3.10+**
- **Pandas** (limpieza y análisis de datos)
- **Matplotlib** (visualización)
- **NumPy** (operaciones numéricas)
- **Jupyter Notebook** (entorno interactivo)

---

## Cómo reproducir el análisis

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/ernes2111/analisis_colectivos_rosario.git

🌐 [Read this in English](README_en.md)
