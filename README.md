# Análisis de negocio.
En tus prácticas en analítica de Showz optimizarás el gasto de marketing. Usarás logs de visitas (ene-2017–dic-2018), pedidos y gastos publicitarios. Analizarás: uso del servicio, momento de primera compra, aportación de cada cliente (LTV) y el punto en que los ingresos recuperan el costo de adquisición (CAC payback).

## MÉTODOS DE DATA:
1. Preparación de datos
1.1 Importar librerías
1.2 Cargar los datasets
1.3 Inspección y optimización de tipos

## 2. Cálculo de métricas e informes
2.1 Visitas
Usuarios por día, semana y mes
Sesiones por día
Duración promedio de sesión
Frecuencia de retorno (p. ej. cohortes semanales)

2.2 Ventas Tiempo a primera compra (cálculo de cohortes Conversion Xd):
Número de pedidos por cohorte o periodo
Tamaño promedio de compra (revenue.mean())
LTV: ingreso acumulado por usuario a lo largo del tiempo

2.3 Marketing Gasto total y por fuente (tablas y gráficos)
CAC = gasto_agregado / número_de_nuevos_clientes
ROMI = (LTV – CAC) / CAC



##Conclusiones y recomendaciones
Tras analizar los datos de visitas, pedidos y gastos de marketing de Showz (enero 2017–diciembre 2018), llegamos a las siguientes conclusiones:

1. Preparación de datos
Unificación y limpieza de los tres datasets, renombrando columnas y ajustando tipos (datetime, category).
Generación de campos clave: start_date, session_duration, order_date.
Datos listos para análisis sin inconsistencias de formato.

2. Análisis de visitas
Usuarios y sesiones: picos de tráfico en fines de semana y temporadas altas.
Duración media de sesión: aproximadamente XX min, indicador de un engagement razonable.
Retención: Z % de usuarios regresa en los primeros 7 días; existe un segmento tardío que conviene reactivar.

3. Análisis de ventas
Tiempo a conversión: más de A % convierte en 0–1 días; segmento tardío tarda > B días.
Tamaño medio de pedido: $C; LTV medio por cliente: $D.
Cohortes 0–1 días generan un LTV E % superior al promedio.

4. Análisis de marketing
Distribución del gasto: la fuente X absorbió F % del presupuesto total.
CAC varía entre $G y $H; la fuente Z es la más eficiente (CAC más bajo).
ROMI: invertir en Z arroja un retorno de I %, mientras que Y queda en breakeven.

5. Recomendaciones
Reasignar presupuesto: aumentar inversión en la fuente Z y reducir en Y.
Optimizar retención temprana: campañas de re-enganche (email/SMS) para conversiones > 7 días.
Foco en mobile: potenciar creatividades y ofertas en dispositivos móviles, donde la conversión es superior.
Próximos pasos:
Validar conclusiones con datos de Q1 2019.
Realizar tests A/B de anuncios y landing pages.
Monitorizar semanalmente CAC y ROMI para ajustes dinámicos.


## Comentario del revisor:
Buenas conclusiones basadas en lo visto durante el proyecto, están bastante completas y con sus recomendaciones sobre el presupuesto para marketing

## Comentario del revisor
Hola, Roberto.

Te quiero felicitar por tu proyecto, está bastante completo y bien realizado. Me gustó bastante la manera en que calculaste las métricas y en como se realizaron las evaluaciones de cada una de las fuentes de marketing. Este es un proyecto importante pues los prepara para un problema bastante común en cualquier empresa.

Saludos, Marcos

