📊 Proyecto RappiPlus: de datos a decisiones de negocio
Análisis integral en Python para validar la calidad de los datos, medir la rentabilidad financiera y respaldar decisiones de negocio en RappiPlus.

🧭 Flujo del proyecto
Limpieza y validación: Conversión de tipos numéricos, tratamiento de nulos, recálculo de monto_total, filtrado de anomalías y eliminación de duplicados (orders_clean.csv, catalog_clean.csv, marketing_clean.csv).
Rentabilidad y ventas: Cruce de órdenes con catálogo de costos y gasto en marketing para obtener métricas clave y visualizaciones.
Alcance complementario: Funnel de conversión, retención por cohortes y test A/B en checkout.

📈 Resultados clave
Indicador
ValorIngreso Total (Revenue) $9,631,647.78
Costo de Productos $3,832,997.75
Inversión en Marketing $2,871,843.53
Ganancia Bruta $5,798,650.03
Ganancia Neta $2,926,806.50
Ticket promedio: $385.95 | Productos/orden: 1.50 | Top producto: Blender-XL-RedGasto por canal: social ($918K), organic ($913K), paid_search ($863K), desconocido ($177K).

🧰 Stack y ejecución
Herramientas: Python (pandas, numpy, seaborn, matplotlib) en Jupyter Notebook.
Uso: Verifica las rutas en /datasets/ y ejecuta las celdas en orden para reproducir la limpieza, KPIs y gráficos.
