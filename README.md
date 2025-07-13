# analisis-energia-eolico
<img width="1599" height="762" alt="image" src="https://github.com/user-attachments/assets/beb872c0-3ae5-4e1f-86d5-3d8d938cb931" />

## 📌 Descripción
Dashboard interactivo para análisis de performance de parques eólicos que incluye:
- Visualización de generación energética por turbina
- Monitoreo de disponibilidad y eficiencia
- Análisis del recurso eólico (rosa de vientos y curva de potencia)
- Tendencias históricas y comparativas

## 🎨 Paleta de Colores
#017c42 #209559 #3eae6f #5dc686 #7bdf9c

## 📊 Gráficos Incluidos
### Sección Resumen
1. **Generación Mensual por Turbina**: Evolución temporal comparada
2. **Factor de Capacidad**: Eficiencia operativa mensual (%)
3. **Disponibilidad**: Horas operativas vs fallos
4. **Eficiencia Comparada**: Rendimiento por velocidad de viento

### Sección Tendencias
5. **Generación Anual**: Evolución interanual (GWh)
6. **Comparación Turbinas**: Diagrama de cajas de distribución

### Sección Viento
7. **Rosa de los Vientos**: Frecuencia y velocidad por dirección
8. **Curva de Potencia**: Teórica vs real con eficiencia

## 🛠️ Tecnologías Utilizadas
- **Python 3.10+**
  - Pandas (manipulación de datos)
  - NumPy (generación de datos simulados)
  - Plotly (visualizaciones interactivas)
- **HTML/CSS**: Para el dashboard integrado

## 📂 Estructura del Proyecto
```bash
/datos_eolicos/
├── generacion_mensual.csv
├── factor_capacidad.csv
├── disponibilidad_turbinas.csv
├── eficiencia_comparada.csv
├── tendencia_anual.csv
├── rosa_vientos.csv
└── curva_potencia.csv

/graficas_eolicas/
├── generacion_mensual.html
├── factor_capacidad.html
├── disponibilidad_turbinas.html
├── eficiencia_comparada.html
├── tendencia_anual.html
├── rosa_vientos.html
├── curva_potencia.html
└── index.html (dashboard completo)

/scripts/
├── 01_generacion_datos.py
└── 02_generacion_graficas.py
```


## 🚀 Instalación y Uso
1. **Requisitos previos**:
   ```bash
   pip install pandas numpy plotly
Generar datos:

```bash
python scripts/01_generacion_datos.py
```
Crear visualizaciones:

```bash
python scripts/02_generacion_graficas.py
```
Abrir dashboard:

Abrir graficas_eolicas/index.html en cualquier navegador moderno

## 🌟 Características Clave
Datos simulados realistas con patrones estacionales

Visualizaciones responsivas que se adaptan a distintos dispositivos

Interactividad completa: tooltips, zoom, filtros

Diseño cohesivo con paleta de colores profesional

## 📝 Personalización
Para modificar:

Datos: Editar scripts/01_generacion_datos.py

Ajustar parámetros de turbinas

Modificar patrones de viento

Cambiar rangos de eficiencia

Visualizaciones: Editar scripts/02_generacion_graficas.py

Cambiar tipos de gráficos

Ajustar paleta de colores

Modificar títulos y etiquetas

## 📄 Licencia
MIT License - Ver LICENSE para más detalles
