[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mmitxel/Telecom_X_customer_churn/blob/main/churn_analysis.ipynb)

# Telecom X Customer Churn
### (Cancelación de clientes de Telecom X)

Proyecto de Predicción de Abandono de Clientes (Churn)
en Telecomunicaciones para el programa de Data Science del
programa ONE - Oracle Next Education en la plataforma Alura.

El objetivo de este proyecto es analizar un conjunto de datos
para identificar clientes en riesgo de abandono, y generar
recomendaciones con base en las conclusiones alcanzadas.

Se incluye la base de datos utilizada.

## Tecnologías y Librerías

- Lenguaje: Python
- Librerías:
  - Pandas y NumPy  para análisis.
  - Matplotlib y Seaborn para gráficas.

## Instalación y Uso

1. Clonar este repositorio.
2. Se recomienda usar un entorno virtual:
    ```
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```
3. Instalar las dependencias:
    ```
    pip install -r requirements.txt
    ```
4. Ejecutar el notebook `churn_analysis.ipynb`

O abrir en Google Colab con el botón al inicio de este Readme.

## Análisis Exploratorio

Se realizó una exploración del conjunto de datos para entender las
variables disponibles, así como su limpieza y transformación para
su uso en análisis por medio de gráficos estadísticos y mapas
de correlación.

De esta forma, se identificaron las variables que tienen más
impacto en el churn, como los gastos más altos y los tiempos de
contrato. Así como el comportamiento de los clientes dependiendo
de las distintas combinaciones de estas variables.

## Conclusiones e Insights

Los hallazgos principales revelan una vulnerabilidad crítica en
clientes adultos mayores (con tasas de baja cercanas al 50%)
y en usuarios de fibra óptica con cargos mensuales elevados
que carecen de servicios de valor agregado. A través de este
análisis, se proponen estrategias de retención enfocadas en la
migración proactiva hacia contratos anuales y la personalización
de beneficios para los segmentos más volátiles, con el fin de
transformar la percepción de costo alto en una experiencia de
servicio premium.