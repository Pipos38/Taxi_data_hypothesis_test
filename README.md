# Taxi_data_hypothesis_test
Recopilación y almacenamiento de datos (SQL)

# 🚕 Análisis Exploratorio y Prueba de Hipótesis – Datos de Taxis en Chicago

Este proyecto analiza datos de compañías de taxi y viajes finalizados en distintos barrios de Chicago. También incluye una prueba de hipótesis sobre cómo el clima afecta la duración de los viajes desde el Loop hasta el Aeropuerto O'Hare.

---

## 🎯 Objetivos

- Estudiar el volumen de viajes por compañía y por barrio.
- Identificar los 10 barrios con mayor cantidad de finalizaciones de viaje.
- Visualizar comparativas entre compañías de taxi y zonas más transitadas.
- Probar la hipótesis:  
  *"La duración promedio de los viajes desde el Loop al Aeropuerto O'Hare cambia los sábados lluviosos."*

---

## 📁 Datasets utilizados

- `project_sql_result_01.csv`: número de viajes por compañía (15-16 nov 2017)
- `project_sql_result_04.csv`: promedio de viajes por barrio (nov 2017)
- `project_sql_result_07.csv`: duración y condiciones climáticas de los viajes del Loop a O'Hare

---

## 🛠️ Tecnologías y herramientas

- Python  
- Pandas, SciPy, Matplotlib, Seaborn  
- Estadística inferencial (prueba U de Mann–Whitney)  
- Visual Studio Code / Jupyter Notebook

---

## 📊 Análisis realizado

### Parte 1 – EDA (Exploración de datos)
- Limpieza y tipado de los datos
- Agrupación por compañía y por barrio
- Visualización de:
  - Número de viajes por compañía
  - Top 10 barrios por viajes finalizados

### Parte 2 – Prueba de hipótesis
- Definición de H₀ y H₁
- Segmentación por clima (lluvia vs. no lluvia)
- Aplicación de prueba de Mann–Whitney
- Análisis del valor-p y conclusiones sobre diferencias en duración

---

## 📂 Estructura del repositorio

chicago_taxi_analysis/ │ ├── chicago_taxi_analysis.ipynb # Jupyter Notebook con el análisis completo ├── datasets/ │ ├── project_sql_result_01.csv │ ├── project_sql_result_04.csv │ └── project_sql_result_07.csv ├── README.md


---

## 📝 Conclusiones

- Se identificaron las compañías y barrios con mayor actividad.
- El clima influye en la duración promedio de los viajes desde el Loop al aeropuerto.
- Se validó estadísticamente que los sábados lluviosos presentan diferencias significativas.

---

## ✍️ Autor

**Felipe Rodríguez Castaño**  
Bootcamp TripleTen – Análisis de Datos  
📫 felipe.tuemail@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/felipe-rodriguez-datos)  
🔗 [GitHub](https://github.com/Pipos38)

