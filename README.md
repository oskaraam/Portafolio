# 💼 Portafolio de Análisis de Datos & Business Intelligence

> **Portafolio especializado en el ciclo completo del análisis de datos:** desde la extracción, depuración y modelado cuantitativo en **Python / SQL**, hasta la creación de *dashboards* ejecutivos interactivos en **Power BI / Tableau**.

---

## 🛠️ Competencias Técnicas Clave

* **Programación y Análisis Estadístico:** Python (Pandas, NumPy, SciPy), SQL, R, Excel Avanzado.
* **Inteligencia de Negocios (BI):** Power BI (DAX avanzado, Inteligencia de Tiempo/YTD, Modelado 1:M, tablas puente), Tableau, Seaborn, Matplotlib.
* **Metodologías de Negocio:** Análisis correlacional y exploratorio (EDA), segmentación de clientes, diagnóstico estacional mediante el marco **SCQA** (*Situación-Complicación-Pregunta-Respuesta*), cálculo de rentabilidad (*Profit*, AOV, márgenes) y control de calidad de datos.

---

## 🚀 Proyectos Seleccionados

### 1. 📊 Commercial Performance Dashboard (Andes Retail Group)
El objetivo de este proyecto es analizar el desempeño comercial de Andes Retail Group entre 2024 y 2025 mediante la consolidación de un flujo de datos transaccionales e interaccionables. El estudio busca brindar una visibilidad clara sobre las tendencias de ingresos, márgenes de ganancia y rendimiento por región y línea de productos para guiar decisiones estratégicas directivas.

* **Herramientas y tipo de proyecto:** `Power BI` · `DAX` · `Tableau` · `Business Intelligence` · `Análisis Financiero`

#### ❓ Preguntas clave
1. ¿Cuáles son los principales motores de rentabilidad y cómo evolucionan los ingresos interanuales?
2. ¿Qué factores explican las variaciones de rendimiento entre regiones y líneas de productos?
3. ¿Cómo se comportan los márgenes de ganancia y el ticket promedio a lo largo de los trimestres?

#### 🧩 Metodología
* **Preparación y transformación de datos:** Estructuración y depuración del dataset transaccional (`Andes_Retail_Group_2024_2025`), aplicación de reglas condicionales de negocio (`Nivel_Venta`).
* **Modelado de datos y DAX:** Configuración de jerarquía temporal dinámica (*Año > Trimestre > Mes*) y creación de métricas personalizadas e inteligencia de tiempo (*YTD*, margen %, AOV).
* **Diseño de dashboard ejecutivo:** Creación de vistas de nivel directivo con KPIs principales y un panel de diagnóstico con profundización (*drill-down*) por segmento y geografía.
* **Análisis bajo marco SCQA:** Diagnóstico estructurado (*Situación-Complicación-Pregunta-Respuesta*) para aislar causas de caídas estacionales.

#### 💡 Conclusiones y recomendaciones
* **Factores críticos de rendimiento:**
  * Se detectó una expansión general de las ventas durante 2024 y 2025, pero con caídas estacionales significativas en los ingresos durante el primer (Q1) y cuarto trimestre (Q4).
  * El análisis de diagnóstico reveló que la causa principal fue la reducción en el gasto del **Segmento de Clientes Premium** en las regiones del sur.
* **Estrategias recomendadas:**
  * **Incentivos a clientes Premium:** Diseñar campañas de fidelización y beneficios exclusivos para mantener el nivel de gasto en clientes Premium durante Q1 y Q4.
  * **Estrategia regional focalizada:** Ajustar las promociones y la mezcla de productos en la región sur antes del inicio de los periodos de contracción.
  * **Seguimiento continuo de KPIs:** Utilizar los indicadores YTD y el monitoreo por cohortes para anticipar fluctuaciones trimestrales.

#### 📈 Visualizaciones destacadas
1. **Evolución YTD de ingresos y ganancias:** Gráfico de líneas con inteligencia de tiempo que muestra el crecimiento acumulado mes a mes (*Enero $\rightarrow$ Diciembre*) identificando el cambio de tendencia en Q1 y Q4.
   <img width="1684" height="392" alt="image" src="https://github.com/user-attachments/assets/5dccece7-2e6e-4278-a538-8e8292b238c3" />
3. **Distribución geográfica por segmento:** Comparativa de rendimiento por país y región que evidencia el impacto diferencial del segmento Premium en el sur.
   <img width="1576" height="342" alt="image" src="https://github.com/user-attachments/assets/f92afd94-3d3e-45bd-9d57-3c052f0ec115" />

👉 *Explora más detalles del proyecto en el repositorio completo.*

---

### 2. 🚀 Proyecto Rappi Plus (NovaRetail+ / Retención & Growth)
Este proyecto consiste en un análisis correlacional exploratorio sobre un conjunto de 15,000 registros de clientes de e-commerce. Desarrollado para el equipo de **Growth & Retention**, el estudio evalúa las relaciones entre el comportamiento del usuario, el gasto publicitario y los ingresos anuales generados, con el fin de optimizar la conversión y los programas de fidelización.

* **Herramientas y tipo de proyecto:** `Python` · `Pandas` · `SciPy` · `Seaborn` · `Análisis Exploratorio (EDA)` · `Análisis Correlacional`

#### ❓ Preguntas clave
1. ¿Qué factores del comportamiento del cliente están asociados de manera más sólida con los ingresos anuales generados?
2. ¿Cómo impacta el gasto en publicidad dirigida sobre las visitas y las compras mensuales?
3. ¿Existen diferencias significativas en la conversión según el segmento de usuario?

#### 🧩 Metodología
* **Preprocesamiento y limpieza:** Identificación y tratamiento de valores nulos, formateo de variables continuas y verificación de calidad de datos.
* **Análisis correlacional (Pearson y Spearman):** Evaluación de relaciones lineales y monótonas entre métricas de atracción (publicidad), uso (visitas) y transacción (compras).
* **Segmentación de comportamiento:** Clasificación de usuarios según la frecuencia de acceso y patrones de compra para identificar perfiles de alto valor.
* **Evaluación de causalidad vs. correlación:** Validación estadística rigurosa sobre el impacto real del presupuesto publicitario en el embudo de conversión.

#### 💡 Conclusiones y recomendaciones
* **Hallazgos del comportamiento de usuarios:**
  * **Gasto en publicidad vs. Visitas ($r = 0.58$ Pearson / $0.56$ Spearman):** Existe una correlación positiva moderada, confirmando la efectividad de las campañas para atraer tráfico a la plataforma.
  * **Visitas vs. Compras ($r = 0.35$ Pearson / $0.33$ Spearman):** Mayor frecuencia de acceso genera más oportunidades de compra, aunque la relación no es strictly lineal.
  * **Publicidad vs. Compras ($r = 0.21$ Pearson / $0.19$ Spearman):** La publicidad atrae visitas con éxito, pero tiene un impacto directo menor en la decisión final de compra.
* **Recomendaciones:**
  * **Optimización del embudo de conversión:** Reorientar esfuerzos de la mera atracción de visitas hacia la conversión dentro de la app (CRO).
  * **Fidelización de usuarios frecuentes:** Crear incentivos para convertir las visitas mensuales recurrentes en suscripciones activas del programa Plus.

#### 📈 Visualizaciones destacadas
1. **Matriz de correlación de Pearson / Spearman:** Mapa de calor que contrasta la fuerza de asociación entre gasto publicitario, visitas mensuales, frecuencia de compras e ingresos anuales.
2. **Distribución de visitas vs. compras por segmento:** Gráficos de dispersión y caja que muestran la variación en el comportamiento transaccional según el canal de adquisición.

👉 *Explora más detalles del proyecto en el repositorio completo.*

---

### 3. 🏢 Análisis Comercial Inmobiliario
Este proyecto evalúa las dinámicas del mercado inmobiliario y la productividad comercial mediante el cruce de datos urbanos, características de propiedades y métricas económicas. El objetivo es identificar las zonas prioritarias de inversión, evaluar la rentabilidad por m² y desarrollar modelos predictivos para respaldar decisiones de adquisición y fijación de precios.

* **Herramientas y tipo de proyecto:** `Python` · `SQL` · `Matplotlib` · `Data Wrangling` · `Análisis Financiero & Inmobiliario`

#### ❓ Preguntas clave
1. ¿Cuáles son las zonas urbanas con mayor potencial de revalorización y rendimiento de inversión?
2. ¿Cómo se relacionan la densidad, ubicación y conectividad urbana con el precio final por m²?
3. ¿Existen variaciones o anomalías en la relación entre oferta inmobiliaria y absorción del mercado?

#### 🧩 Metodología
* **Extracción y limpieza de datos:** Integración de fuentes transaccionales e indicadores urbanos/económicos mediante SQL y Python.
* **Estandarización y filtrado:** Corrección de formatos, manejo de valores atípicos (*outliers*) y agregación de métricas de precio y superficie por ubicación.
* **Análisis comparativo de zonas:** Evaluación del rendimiento histórico, tasa de vacancia y absorción comercial por sector geográfico.
* **Modelado de valoración:** Construcción de análisis exploratorio para determinar los principales impulsores del valor comercial.

#### 💡 Conclusiones y recomendaciones
* **Dinámica del mercado e inversión:**
  * Se identificó una alta variabilidad en el valor por m² impulsada principalmente por la conectividad y la densidad de servicios comerciales en la zona.
  * Ciertas zonas emergentes muestran un rendimiento comercial superior frente a mercados saturados, ofreciendo mejores márgenes de retorno sobre la inversión.
* **Recomendaciones:**
  * **Priorización de cartera:** Focalizar la adquisición e inversión inmobiliaria en sectores identificados con alta absorción y menor vacancia.
  * **Ajuste de estrategia de precios:** Establecer precios dinámicos por m² fundamentados en la disponibilidad de servicios y densidad urbana de la zona.

#### 📈 Visualizaciones destacadas
1. **Mapa de calor de precio por m² por zona:** Visualización espacial que resalta los sectores de mayor valor comercial y oportunidades de inversión.
2. **Análisis comparativo de absorción y precio:** Gráficos de dispersión que contrastan el valor de mercado con el tiempo de permanencia en inventario.

👉 *Explora más detalles del proyecto en el repositorio completo.*

---

## ⭐ Valor Diferencial
Combinación única de **formación económica-financiera** con **competencias técnicas avanzadas en analítica de datos**. Capacidad para automatizar procesos de reporte, comunicar hallazgos técnicos de forma clara (*Data Storytelling*) y enfocar cada proyecto hacia el retorno de inversión y la eficiencia operativa.
