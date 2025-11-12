## Optimización de gastos de Marketing — Proyecto Showz
### Descripción del proyecto

Este proyecto fue desarrollado como parte de las prácticas del programa de Data Analyst de TripleTen, en colaboración con el departamento de analítica de Showz, una empresa dedicada a la venta de entradas para eventos.

El objetivo principal fue optimizar los gastos de marketing, analizando datos de tráfico, comportamiento de usuarios, ventas y rentabilidad por fuente de adquisición.

Fuentes de datos disponibles:

Registros del servidor (visitas al sitio web entre enero 2017 y diciembre 2018)

Archivo con los pedidos realizados durante el mismo periodo

Estadísticas de gastos en marketing

Preguntas de negocio:

- ¿Cómo usan los clientes el servicio?

- ¿Cuándo comienzan a comprar?

- ¿Cuánto aporta cada cliente a la compañía?

- ¿Cuándo los ingresos cubren el costo de adquisición (CAC)?

### Análisis realizado
1. Tráfico y comportamiento del usuario

En promedio, 908 usuarios únicos visitan el sitio web cada día, generando 987 sesiones.

La duración promedio de sesión es de 643.5 segundos, aunque la moda es de 60 segundos, lo que sugiere que la mayoría de los usuarios pasan poco tiempo en el sitio.

Solo el 22.8% de los usuarios regresan, con una adherencia semanal del 15.9% y una mensual del 3.9%.

#### Oportunidad: implementar campañas de retargeting o promociones que incentiven el regreso de los usuarios tras periodos de inactividad.

2. Ventas y conversión

En promedio, 24 usuarios se convierten por día, aumentando a 125 por día dentro de los primeros 30 días tras su primera visita.

La mayor parte de las conversiones ocurre el mismo día de la primera sesión.

#### Recomendación: diseñar estrategias que fomenten la conversión inmediata (por ejemplo, descuentos por primera compra).

El mes con mayor número de pedidos fue diciembre de 2017, con un promedio general de 3,878 pedidos mensuales.

Se observa una estacionalidad positiva en los últimos tres meses del año.

El LTV promedio es de 6.90, con un valor máximo de 11,810.18 y una moda de 2.44, mostrando una distribución desigual donde pocos clientes generan la mayoría de los ingresos.

#### Estrategia sugerida: incentivar compras múltiples por cliente mediante promociones o beneficios escalables.

3. Marketing y rentabilidad

Inversión total: $329,131.62 distribuidos en 7 fuentes de adquisición.

La fuente 3 concentró la mayor inversión y el CAC más alto, lo que sugiere baja rentabilidad.

El ROMI (Retorno sobre la inversión en marketing) identificó:

Fuente 1 → más rentable

Fuente 9 → rentable, pero con bajo volumen

Fuente 5 → sostenible a largo plazo

Fuente 3 → alto costo, bajo retorno

Métricas clave:

LTV promedio: 6.90

CAC promedio: 9.01

ROMI global: 0.77

Esto indica que actualmente la estrategia de adquisición no es rentable, por lo que se recomienda optimizar la distribución del presupuesto antes de aumentar la inversión.

### Recomendaciones de inversión:

Fuente	Recomendación	Justificación
1	Aumentar inversión	Alta rentabilidad
9	Aumentar ligeramente	Buen rendimiento pero bajo volumen
5	Mantener	Rentable y sostenible
3	Reducir o suspender	Alto CAC, bajo retorno
4. Dispositivos y experiencia de usuario

29,211 usuarios accedieron desde desktop vs 7,312 desde dispositivos móviles.

La brecha también se refleja en los ingresos por tipo de dispositivo.

Recomendación: optimizar el sitio web para móviles (rendimiento, tiempos de carga y experiencia de compra), y fortalecer campañas móviles (especialmente en redes sociales).

### Métricas y herramientas utilizadas

Para obtener los resultados se calcularon:

LTV (Lifetime Value) → valor que cada cliente aporta a lo largo de su ciclo de vida.

CAC (Customer Acquisition Cost) → costo de adquisición de cada cliente.

ROMI (Return on Marketing Investment) → rentabilidad de cada fuente.

Frecuencia de compra y adherencia → detección de oportunidades de fidelización.

Duración de sesiones y conversión diaria → identificación de puntos clave de comportamiento.

Herramientas:

- Python (pandas, matplotlib, seaborn)

- Jupyter Notebook

### Conclusión general

El análisis evidencia que:

El CAC promedio (9.01) supera al LTV (6.90) → estrategia actual no rentable.

El ROMI global (0.77) confirma la necesidad de optimizar el mix de canales.

Existen picos de rentabilidad y conversión en los últimos meses del año → oportunidad de replicar campañas exitosas.

El rendimiento móvil es bajo, lo que representa un área clara de mejora técnica y comercial.

### Conclusión final:
Redistribuir la inversión hacia las fuentes rentables, mejorar la experiencia móvil y aplicar estrategias de conversión inmediata permitirá reducir el CAC, incrementar el LTV y alcanzar una rentabilidad positiva en el marketing digital de Showz.
