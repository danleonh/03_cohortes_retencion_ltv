# Proyecto 3 – Análisis de Juegos y Éxito Comercial

## 📋 Descripción general
El objetivo de este proyecto es identificar los factores clave que influyen en el éxito de los videojuegos, basándose en datos históricos de ventas, calificaciones y reseñas.  
El análisis busca entender cómo las características del producto (plataforma, género, críticas, región, etc.) impactan en la rentabilidad y popularidad de los títulos.

---

## 🎯 Objetivos
- Analizar las ventas globales y por región de diferentes títulos de videojuegos.  
- Identificar las plataformas y géneros con mejor desempeño.  
- Evaluar la relación entre reseñas de usuarios/medios y ventas.  
- Determinar patrones que expliquen el éxito de los juegos.  
- Desarrollar recomendaciones para estrategias de lanzamiento futuras.

---

## 🧮 Datos utilizados
**Dataset principal:** `games.csv`  
Contiene información sobre videojuegos lanzados hasta 2016, incluyendo:

- `Name` – Nombre del juego  
- `Platform` – Consola o sistema  
- `Year_of_Release` – Año de lanzamiento  
- `Genre` – Género  
- `Critic_Score`, `User_Score` – Calificaciones  
- `Global_Sales`, `NA_Sales`, `EU_Sales`, `JP_Sales` – Ventas por región  

---

## 🧰 Herramientas y librerías
- Python  
- pandas, numpy, scipy  
- matplotlib, seaborn  
- Jupyter Notebook  

---

## 📊 Etapas del análisis
1. **Limpieza y preparación del dataset**: tratamiento de valores faltantes y conversión de tipos.  
2. **Análisis exploratorio de datos (EDA)**: estudio descriptivo de ventas y puntuaciones.  
3. **Comparación de géneros y plataformas**: análisis del ciclo de vida de cada consola.  
4. **Evaluación de correlaciones** entre calificaciones y ventas.  
5. **Pruebas de hipótesis** sobre diferencias en ventas por género y plataforma.  
6. **Conclusiones estratégicas** basadas en los hallazgos.

---

## 🔍 Resultados principales
- Los géneros **Acción** y **Deportes** concentraron más del **50 % de las ventas globales**.  
- Las plataformas **PS4 y Xbox One** mostraron mayor crecimiento en los años recientes.  
- Se detectó **correlación positiva moderada (r ≈ 0.4)** entre la puntuación de críticos y las ventas.  
- Japón y América del Norte presentaron patrones de consumo muy distintos.  

---

## 💡 Conclusiones
- El éxito de un juego está influenciado tanto por su género como por la estrategia de lanzamiento.  
- Las calificaciones de críticos impactan más que las reseñas de usuarios en las ventas iniciales.  
- Se recomienda priorizar lanzamientos multiplataforma en géneros de alta demanda.  
- Las campañas deben adaptarse al contexto regional según preferencias locales.  

---

## 🗂 Estructura del repositorio
