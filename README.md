# Análisis de Ventas — Superstore Dataset

## Descripción
Análisis exploratorio de datos de ventas de una tienda en Estados Unidos
usando Python y pandas, con el objetivo de identificar patrones de 
rentabilidad y estacionalidad.

## Tecnologías utilizadas
- Python 3.11
- pandas
- numpy
- matplotlib
- Jupyter Notebook / VS Code

## Estructura del proyecto
proyecto_ventas/
├── data/
│   └── Sample - Superstore.csv
├── notebooks/
│   └── analisis_ventas.ipynb
├── outputs/
│   ├── ventas_por_categoria.png
│   ├── profit_por_categoria.png
│   ├── ventas_por_mes.png
│   └── ventas_por_region.png
└── README.md

## Hallazgos principales
1. **Technology** es la categoría con mayores ventas ($836,154) y profit ($145,454)
2. **Furniture** tiene ventas altas pero profit muy bajo ($18,451) debido a 
   altos costos y descuentos elevados
3. Descuentos mayores al **20%** generan pérdidas en promedio
4. **Noviembre y Diciembre** son los meses de mayor venta (estacionalidad navideña)
5. **West** lidera en ventas por región con $725,457

## Cómo ejecutar este proyecto
1. Clona el repositorio
2. Instala las dependencias: `pip install pandas numpy matplotlib jupyter`
3. Abre `notebooks/analisis_ventas.ipynb` en VS Code o Jupyter