# IronClad Capital 🔗

**Proyecto de Ingeniería**

> Análisis avanzado de criptomonedas, predicción de precios y presencia web integrada

---
## 🔗 Links

- Documentación Oficial: https://adrian-duque.github.io/ironclad-fase2/documentacion.html
- Documentación Visual: https://adrian-duque.github.io/ironclad-fase2/
- Presentación: https://adrian-duque.github.io/ironclad-fase2/ppt.html
- Blog: https://substack.com/@ironcladcapital

---

## 📋 Descripción General

IronClad Capital es la entrega del proyecto de ingeniería que combina **análisis de datos**, **machine learning** y **desarrollo web**. Este proyecto se enfoca en la predicción de precios de criptomonedas (Bitcoin, Dogecoin, Ethereum, etc.) utilizando modelos de aprendizaje automático y proporciona una presencia web moderna mediante un tema de WordPress personalizado.

---

## 🎯 Objetivos

- ✅ Predecir precios de criptomonedas con modelos XGBoost
- ✅ Realizar análisis exploratorio de datos (EDA)
- ✅ Implementar una interfaz web intuitiva
- ✅ Desarrollar un tema WordPress personalizado
- ✅ Crear plugins de funcionalidad extendida

---

## 📁 Estructura del Proyecto

```
ironclad-fase2/
├── bitcoin-dogecoin-etc-price-prediction-xgboost.ipynb   # Notebook principal de predicción
├── Plugins/                                                # Extensiones personalizadas
├── Tema Wordpress/                                         # Tema personalizado de WordPress
├── images/                                                 # Recursos visuales
├── index.html                                              # Página principal web
└── README.md                                               # Este archivo
```

### Componentes Principales

#### 🔬 **Notebook Jupyter - Predicción de Precios**
- **Archivo**: `bitcoin-dogecoin-etc-price-prediction-xgboost.ipynb`
- **Descripción**: Análisis completo de precios históricos y predicción usando XGBoost
- **Criptomonedas analizadas**: Bitcoin, Dogecoin, Ethereum y otras altcoins
- **Técnicas aplicadas**:
  - Extracción y procesamiento de características
  - Normalización de datos
  - Validación cruzada
  - Optimización de hiperparámetros

#### 🎨 **Tema WordPress**
- **Ubicación**: `Tema Wordpress/`
- **Propósito**: Presencia web profesional del proyecto
- **Características**: Diseño responsive, integración con datos en tiempo real

#### 🔌 **Plugins Personalizados**
- **Ubicación**: `Plugins/`
- **Funcionalidad**: Extensiones para WordPress que mejoran la experiencia del usuario

#### 🌐 **Página Principal Web**
- **Archivo**: `index.html`
- **Descripción**: Landing page con interfaz moderna e intuitiva

#### 🖼️ **Recursos Visuales**
- **Carpeta**: `images/`
- **Contenido**: Gráficos, iconos y elementos visuales del proyecto

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
|-----------|------------|
| **Python** | Lenguaje principal para análisis de datos |
| **XGBoost** | Modelo de Machine Learning para predicción |
| **Jupyter Notebook** | Ambiente interactivo de análisis |
| **Pandas** | Manipulación y análisis de datos |
| **Scikit-learn** | Herramientas de machine learning |
| **WordPress** | Plataforma web CMS |
| **HTML5/CSS3** | Desarrollo web frontend |
| **JavaScript** | Interactividad en la web |

---

## 📊 Análisis y Predicciones

### Modelos Implementados

El notebook principal utiliza **XGBoost** para realizar predicciones de precios con:

- **Preparación de datos**: Limpieza, normalización y feature engineering
- **División train/test**: Validación del modelo en datos no vistos
- **Métricas de evaluación**: MAE, RMSE, R² Score
- **Visualizaciones**: Gráficos de tendencias y predicciones

### Datos Analizados

- Series temporales históricas de precios
- Volúmenes de transacción
- Indicadores técnicos (RSI, MACD, Bandas de Bollinger)
- Datos de mercado complementarios

---

## 🚀 Cómo Usar Este Proyecto

### Requisitos Previos

```bash
# Python 3.8+
# Jupyter Notebook
# pip o conda
```

### Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/Adrian-Duque/ironclad-fase2.git
   cd ironclad-fase2
   ```

2. **Instalar dependencias**
   ```bash
   pip install -r requirements.txt
   ```
   
   *O manualmente:*
   ```bash
   pip install pandas numpy scikit-learn xgboost jupyter matplotlib seaborn
   ```

3. **Ejecutar Jupyter**
   ```bash
   jupyter notebook bitcoin-dogecoin-etc-price-prediction-xgboost.ipynb
   ```

### Uso del Notebook

- Abre el notebook en Jupyter
- Ejecuta las celdas en orden secuencial
- Observa los gráficos y resultados de las predicciones
- Ajusta parámetros según sea necesario

### Implementar WordPress

1. Coloca el contenido de `Tema Wordpress/` en tu instalación de WordPress
2. Activa el tema desde el panel de administración
3. Instala los plugins desde la carpeta `Plugins/`
4. Configura los ajustes según tus necesidades

---

## 📈 Resultados y Hallazgos

### Métricas del Modelo

- **Precisión R²**: [Consultar notebook para valores actualizados]
- **Error Medio Absoluto (MAE)**: [Consultar notebook para valores actualizados]
- **Raíz del Error Cuadrático Medio (RMSE)**: [Consultar notebook para valores actualizados]

### Insights Principales

- Análisis de tendencias a largo plazo
- Identificación de patrones cíclicos
- Evaluación de volatilidad

---

## 👥 Autores

- **Adrian-Duque**
- **Jose Pablo Aceves**
- **Ignacio del Peso**
