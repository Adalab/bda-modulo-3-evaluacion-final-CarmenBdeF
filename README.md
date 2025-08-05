# 📊 Análisis de Clientes de Aerolínea - Módulo 3 DA

Este repositorio contiene el ejercicio de evaluación final del Módulo 3 del Bootcamp de Análisis de Datos. El objetivo es analizar el comportamiento de los clientes dentro de un programa de lealtad de una aerolínea, utilizando dos conjuntos de datos complementarios.

---

## 📁 Estructura del Proyecto


- `Files/`: Carpeta que contiene los archivos CSV originales.
- `eval-mod-03-parte-1-EDA_.ipynb`: Exploración inicial de los datos.
- `eval-mod-03-parte-2-limpieza.ipynb`: Limpieza y preparación de los datos.
- `eval-mod-03-parte-3-visualizacion.ipynb`: Visualización y análisis gráfico.

```plaintext
├── Files/
│   ├── customer_flight_activity.csv
│   └── customer_loyalty_history.csv
├── eval-mod-03-parte-1-EDA_.ipynb
├── eval-mod-03-parte-2-limpieza.ipynb
└── eval-mod-03-parte-3-visualizacion.ipynb
```


---

## 📦 Datasets

### ✈️ customer_flight_activity.csv

Contiene información mensual sobre la actividad de vuelo de los clientes. Columnas principales:

- `Loyalty Number`: Identificador único del cliente.
- `Year` y `Month`: Fecha de la actividad.
- `Flights Booked`, `Flights with Companions`, `Total Flights`: Información de vuelos.
- `Distance`: Distancia volada ese mes.
- `Points Accumulated`, `Points Redeemed`: Puntos ganados y usados.
- `Dollar Cost Points Redeemed`: Valor en dólares de los puntos redimidos.

### 👤 customer_loyalty_history.csv

Contiene información demográfica y del programa de lealtad de los clientes:

- `Loyalty Number`: Identificador para relacionar con el otro archivo.
- `Country`, `Province`, `City`, `Postal Code`: Ubicación.
- `Gender`, `Education`, `Salary`, `Marital Status`: Perfil demográfico.
- `Loyalty Card`, `CLV`, `Enrollment Type`: Detalles del programa de fidelidad.
- `Enrollment Year/Month` y `Cancellation Year/Month`: Fechas de alta y baja.

---

## ✅ Fases del Proyecto

### 🧪 1. Exploración y Análisis Preliminar (`eval-mod-03-parte-1-EDA_.ipynb`)

- Análisis de estructura, tipos de datos y valores nulos.
- Unión de ambos datasets por `Loyalty Number`.

### 🧹 2. Limpieza de Datos (`eval-mod-03-parte-2-limpieza.ipynb`)

- Tratamiento de nulos y tipos de datos.
- Homogeneización y preparación para análisis gráfico.

### 📈 3. Visualización de Datos (`eval-mod-03-parte-3-visualizacion.ipynb`)

Se abordan las siguientes preguntas mediante visualizaciones:

1. **¿Cómo se distribuye la cantidad de vuelos reservados por mes durante el año?**
2. **¿Existe una relación entre la distancia de los vuelos y los puntos acumulados?**
3. **¿Cuál es la distribución de los clientes por provincia o estado?**
4. **¿Cómo se compara el salario promedio entre los diferentes niveles educativos?**
5. **¿Cuál es la proporción de tipos de tarjetas de fidelidad?**
6. **¿Cómo se distribuyen los clientes según su estado civil y género?**

---

## 🛠 Herramientas Usadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Notas

- Este ejercicio forma parte del proceso de evaluación del módulo y simula un caso real de análisis de datos de cliente.
- Se permite el uso de internet y apuntes personales como recursos de apoyo.

---

## 🚀 Autoría

Proyecto realizado por Carmen Bermejo de Fuentes para el Bootcamp de Análisis de Datos de **Adalab** – 2025, dentro del **Módulo 3: Limpieza, análisis y visualización de datos**.
