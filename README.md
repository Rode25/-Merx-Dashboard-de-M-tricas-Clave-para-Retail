# -Merx-Dashboard-de-M-tricas-Clave-para-Retail
📌 Descripción

Merx es un dashboard corporativo desarrollado en Power BI para una compañía del sector retail de consumo masivo. Consolida en una sola interfaz los principales indicadores comerciales (ventas, utilidad y margen) y permite analizarlos por periodo, categoría, subcategoría, etiqueta de producto y canal de venta (En Línea vs. Física).

El objetivo del proyecto es ofrecer a las áreas comerciales y de dirección una herramienta que responda tres preguntas de negocio:

¿Cómo estamos vendiendo? Evolución de ventas y utilidad, trimestral e histórica (2010-2020).
¿Qué es realmente rentable? Margen por categoría, subcategoría y producto individual.
¿Dónde compran nuestros clientes? Peso de cada canal y su evolución en el tiempo.
✨ Características clave
KPIs ejecutivos en tarjetas: Total Ventas, Total Utilidad y Margen (%), con evolución trimestral.
Filtros dinámicos globales (Año, Categoría, Subcategoría y Etiquetas) que actualizan todos los visuales de la página.
Navegación por botones entre tres páginas: Inicio, Histórico y Detalle.
Análisis multinivel: desde el total corporativo hasta el producto individual, mediante tablas jerárquicas con capacidad de expansión (drill-down).
Análisis por canal: comparativo En Línea vs. Física, tanto en composición porcentual como en evolución histórica.
Formato condicional en tablas: barras de datos en ventas y utilidad, y escala de color en el margen para identificar rápidamente las subcategorías más y menos rentables.
Serie histórica de 11 años (2010-2020) con visión combinada de ventas y margen.
Búsqueda de productos en la vista de detalle.
🎨 Diseño visual

El dashboard sigue una identidad visual coherente con la marca Merx:

Paleta: degradados de morado profundo a rosa/coral, con acentos en salmón para los indicadores de margen.
Layout: panel lateral oscuro con logo, misión, navegación y filtros; área principal en tarjetas blancas con esquinas redondeadas sobre fondo gris claro.
Jerarquía visual: cada tarjeta lleva un encabezado con degradado e ícono temático, lo que facilita distinguir de un vistazo el tipo de métrica.
Diseño limpio con espaciado uniforme, tipografía sobria y sin exceso de elementos decorativos.
🧰 Tecnologías
Herramienta	Uso
Power BI Desktop	Modelado, visualización y diseño del reporte
DAX	Medidas de ventas, utilidad, margen y análisis temporal
Power Query (M)	Extracción, limpieza y transformación de datos
Modelo dimensional (esquema estrella)	Relación entre tabla de hechos (ventas) y dimensiones (fecha, producto, canal)
🗂️ Estructura del dashboard
🏠 Página 1 — Inicio (KPIs)

Vista ejecutiva del año seleccionado (por defecto, 2020).

Tarjetas de KPI: Total Ventas ($3.16 M), Total Utilidad ($693.6 K) y Margen (22 %), cada una con su gráfico de barras por trimestre (Qtr 1 – Qtr 4).
Ventas por Categorías: dos gráficos de dona: uno por categoría (A&B, S&B, HO) y otro por tipo de compra (En Línea vs. Física).
Totales por Subcategorías y Etiquetas de Productos: tabla con ventas, utilidad y margen por subcategoría, ordenada por ventas y con formato condicional.
🕒 Página 2 — Histórico

Análisis de tendencia de largo plazo (2010-2020).

Gráfico de líneas combinado: ventas vs. margen histórico.
Gráfico de áreas: evolución comparada de ventas En Línea vs. Física.
Tabla detallada mes a mes para consulta y validación de cifras.
🔍 Página 3 — Detalle

Análisis a nivel de producto.

Tabla jerárquica (Categoría → Subcategoría → Producto) con ventas, utilidad y margen por ítem individual.
Cuadro de búsqueda para localizar productos específicos.
🧭 Panel lateral (todas las páginas)
Botones de navegación: Inicio, Histórico, Detalle.
Filtros: Year, Categoría, Subcategoría y Etiquetas.
