# company_analysis
English
This notebook processes and analyzes billing data from multiple sources to evaluate margins, costs, and profitability by client and vendor.
The workflow begins by reading several sheets from an Excel file containing monthly call records (January to March), along with specific client and carrier rate tables.
Main technical steps include:
Data integration: merges and standardizes multi-month datasets.
Column cleaning: fixes naming and formatting inconsistencies.
Unit conversion: transforms call duration from seconds to minutes.
Rounding rules: applies vendor-specific billing rules to adjust billed duration.
Rate matching: merges client and vendor rates, correcting for per-second or per-minute discrepancies.
Revenue and cost computation: calculates effective rates, call-level costs, and transaction margins.
Margin analysis: evaluates profitability by country, number type, and vendor.
Visualization: uses matplotlib and seaborn to display margin trends and detect inconsistencies.
Technically, the project is implemented in Python using pandas, numpy, matplotlib, and seaborn for data handling, vectorized computation, and visual analysis.
The modular notebook structure supports scalability for new billing periods and integration with automated reconciliation systems.

Spanish
Este notebook procesa y analiza datos de facturación provenientes de múltiples fuentes para evaluar márgenes, costos y rentabilidad por cliente y proveedor.
El flujo de trabajo inicia con la lectura de diferentes hojas de un archivo Excel que contiene registros mensuales de llamadas (enero a marzo), junto con tarifas específicas para clientes y carriers.
El código realiza los siguientes pasos técnicos:
Integración de datos: combina y normaliza la información de varios meses.
Limpieza de columnas: corrige nombres y formatos inconsistentes.
Conversión de unidades: transforma la duración de llamadas de segundos a minutos.
Aplicación de reglas de redondeo: ajusta la duración facturada según políticas específicas de cada proveedor.
Unificación de tarifas: enlaza las tarifas de clientes y proveedores, corrigiendo diferencias de escala (por minuto o por segundo).
Cálculo de ingresos y costos: determina las tarifas efectivas, el costo por llamada y el margen por transacción.
Análisis de márgenes: evalúa la rentabilidad por país, tipo de número y proveedor.
Visualización: genera gráficos con matplotlib y seaborn para comparar tendencias y detectar posibles inconsistencias o desviaciones.
Técnicamente, el proyecto está desarrollado en Python, utilizando pandas, numpy, matplotlib y seaborn para manipulación de datos, cálculo vectorizado y análisis visual.
La estructura del notebook permite escalar el análisis a nuevos periodos de facturación o integrarse con sistemas de conciliación automatizada.
