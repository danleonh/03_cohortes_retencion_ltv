📋 Descripción general

Proyecto enfocado en medir la retención de usuarios, analizar cohortes por mes de primera compra/registro y calcular LTV frente a CAC para determinar la rentabilidad y el payback de las inversiones de adquisición. Incluye métricas de producto (DAU/WAU/MAU), análisis de embudo y visualizaciones clave para guiar decisiones.

🎯 Objetivos

Construir cohortes por primera interacción/compra y medir retención.

Calcular LTV (por cohorte y global) y compararlo con CAC.

Medir DAU, WAU, MAU y ratio DAU/MAU (engagement).

Identificar palancas de crecimiento y riesgos (churn temprano, payback).

Recomendar acciones tácticas para mejorar retención y unit economics.

🧮 Dataset utilizado

users.csv → usuarios con user_id, signup_date, fuente de adquisición.

events.csv → eventos por usuario: event_time, event_type (view, add_to_cart, purchase…).

orders.csv → pedidos: order_id, user_id, order_date, revenue.

costs.csv → gastos de marketing por canal/fecha (channel, cost, date).

Tamaño estimado: 50k–150k filas combinadas · Periodo: 6–12 meses

🧰 Tecnologías y herramientas
Categoría	Herramientas
Lenguaje	Python
Librerías	pandas, numpy, matplotlib, seaborn
Producto	cohort tables, retention curves, LTV/CAC
Entorno	Jupyter Notebook
Control de versiones	Git, GitHub
📈 Visualizaciones clave

Curvas de retención por cohorte (M0–M6).

Tabla de cohortes con % de usuarios activos y ARPU por periodo.

DAU / WAU / MAU y DAU/MAU ratio (engagement).

LTV vs CAC por canal/cohorte y tiempo de payback.

Embudo (visitas → add_to_cart → purchase).

🔍 Principales hallazgos (ejemplo típico del análisis)

Retención M1 ~38 %, con caída pronunciada en M2–M3 → foco en onboarding y valor temprano.

LTV promedio ≈ 42 y CAC ≈ 30 → ROI positivo a partir de Mes 3 (payback < 90 días).

Canales orgánicos y referidos muestran mejor DAU/MAU y retención; pago por click requiere optimización de targeting.

Usuarios con 2+ compras en los primeros 30 días tienen 3× LTV versus el resto → oportunidad de activación temprana.

📊 Métricas destacadas
Indicador	Valor
Retención M1	~38 %
LTV promedio	≈ 42
CAC promedio	≈ 30
Payback	~3 meses
DAU/MAU	0.18–0.22

Los valores pueden variar ligeramente según el filtro de outliers y la ventana de cohortes.

💡 Recomendaciones

Onboarding con “aha moment” antes de 24–48h; email/push de activación.

Bundles/upsell en primeras 2 semanas para elevar ARPU y LTV.

Optimizar CAC: priorizar canales con mejor retención (orgánico/referidos).

Probar paywalls/ensayos diferenciados por cohorte/canal.
