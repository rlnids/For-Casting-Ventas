
# ForCastingVentas: Forecasting de Ventas con Machine Learning

Este proyecto utiliza técnicas de Machine Learning para predecir ventas de productos deportivos, integrando análisis de datos, modelado y visualización interactiva con Streamlit.

## 📊 Descripción
El objetivo es analizar datos históricos de ventas y competencia para construir modelos predictivos que ayuden a la toma de decisiones comerciales.

## 🗂️ Estructura del Proyecto

- **data/**: Datos utilizados en el proyecto.
  - `raw/entrenamiento/ventas.csv`: Ventas históricas.
  - `raw/entrenamiento/competencia.csv`: Precios de la competencia.
  - `processed/`: Datos procesados para modelado.
- **notebooks/**: Análisis exploratorio y entrenamiento de modelos (`entrenamiento.ipynb`).
- **app/**: (Opcional) Código para la app de Streamlit.
- **models/**: Modelos entrenados y artefactos.
- **requirements.txt**: Dependencias del proyecto.

## 🚀 ¿Cómo usar este proyecto?

1. **Clona el repositorio:**
	```bash
	git clone https://github.com/rlnids/For-Casting-Ventas.git
	cd For-Casting-Ventas
	```
2. **Instala las dependencias:**
	```bash
	pip install -r requirements.txt
	```
3. **Explora los notebooks:**
	- Abre `notebooks/entrenamiento.ipynb` para ver el análisis y entrenamiento.
4. **Ejecuta la app (opcional):**
	```bash
	streamlit run app/app.py
	```

## 🧩 Tecnologías utilizadas
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn, streamlit, holidays)
- Jupyter Notebook

## 📁 Variables principales
- **ventas_df**: contiene las variables `['fecha', 'producto_id', 'nombre', 'categoria', 'subcategoria', 'precio_base', 'es_estrella', 'unidades_vendidas', 'precio_venta', 'ingresos', ...]`
- **competencia_df**: contiene las variables `['fecha', 'producto_id', 'Amazon', 'Decathlon', 'Deporvillage']`

## ✨ Autoría
Proyecto realizado por  MELVIN NAVAS SANTOS para portfolio profesional. 

---
¡No dudes en contribuir o consultar cualquier duda!
