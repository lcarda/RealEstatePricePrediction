# RealEstatePricePrediction


### Resumen
RealEstatePricePrediction es un proyecto de análisis de datos y predicción centrado en la tasación de inmuebles en Argentina. Utiliza anuncios clasificados de Properati, obtenidos del [dataset de Kaggle](https://www.kaggle.com/datasets/tomasaccini/propiedadesproperati). La valuación inmobiliaria es un tema crucial para agentes y compradores potenciales, y este proyecto busca predecir precios de propiedades basándose en sus características. Los datos abarcan desde 2013 hasta 2017, ofreciendo una perspectiva única sobre el mercado sudamericano.

### Características
- **Limpieza de datos**: Eliminación de datos irrelevantes o incompletos para garantizar un análisis sólido.
- **Visualizaciones**: Representaciones gráficas para identificar tendencias y correlaciones.
- **Modelado predictivo**: Uso de aprendizaje automático para estimar precios de propiedades en USD.
- **Enfoque en Argentina**: Dinámica del mercado inmobiliario argentino.

### Tecnologías Utilizadas
- Librerías de Python: `pandas`, `matplotlib`, `seaborn`, `numpy`, `math`, `missingno`
- Jupyter Notebook para el desarrollo y documentación

### Instalación
1. Clona este repositorio:
    ```bash
    git clone https://github.com/lcarda/RealEstatePricePrediction.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd RealEstatePricePrediction
    ```
3. Instala las librerías necesarias:
    ```bash
    pip install -r requirements.txt
    ```

### Uso
1. Abre el archivo `RealEstatePricePrediction.ipynb` en Jupyter Notebook.
2. Sigue el notebook para:
   - Explorar el conjunto de datos.
   - Visualizar relaciones entre características de las propiedades y sus precios.
   - Entrenar y evaluar modelos predictivos.
3. Ajusta parámetros y características según sea necesario para mejorar las predicciones.

### Cómo Contribuir
1. Haz un fork del repositorio.
2. Crea una nueva rama para tu función:
    ```bash
    git checkout -b nombre-de-la-funcion
    ```
3. Haz commit de tus cambios y empújalos a tu fork:
    ```bash
    git commit -m "Descripción de tus cambios"
    git push origin nombre-de-la-funcion
    ```
4. Abre un pull request para proponer tus cambios.

### Agradecimientos
- El conjunto de datos fue obtenido de [Kaggle](https://www.kaggle.com/datasets/tomasaccini/propiedadesproperati).

