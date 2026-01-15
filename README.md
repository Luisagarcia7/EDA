📊 Análisis de Ventas: Exploración de devolución y cancelación de pedidos

Este proyecto tiene como objetivo analizar las devoluciones y cancelaciones en relación con las ventas, con el fin de identificar métricas y patrones que puedan estar contribuyendo al incremento de dichas incidencias. El análisis permitirá detectar factores clave que influyen en el comportamiento del cliente y en el rendimiento de los productos, facilitando la toma de decisiones orientadas a la mejora continua.


 🛍️Estructura del Proyecto 

├── Amazon / 	# Datos primarios
├── Dashboard excel/	 # Procesamiento y análisis de datos
├── Análisis de ventas/ 	# Descripción del proyecto

Este conjunto de datos contiene 100.000 transacciones sintéticas de ventas de comercio electrónico al estilo Amazon, diseñadas para parecerse mucho al comportamiento real del comercio minorista online. Con 20 columnas limpias y bien estructuradas, recoge información detallada sobre clientes, productos, precios, pagos, logística y resultados de pedidos.
Aunque los datos se generan artificialmente, reflejan patrones realistas como:fijación  dinámica de precios de productos, descuentos e impuestos variables, múltiples categorías de productos y marcas, tendencias de pedidos estacionales, diversidad de métodos de pago, nombres y ubicaciones realistas de los clientes, estatus de pedido como Entregado, Cancelado, Enviado y Devuelto. Esto hace que el conjunto de datos sea muy adecuado para analítica, aprendizaje automático, visualización de datos, paneles de control y estudios de caso empresarial.
📊 Resumen de la columna
El conjunto de datos incluye:
🧾 Detalles del pedido
OrderID, Fecha de pedido, Estado de la Orden, SellerID
👤 Información para clientes
CustomerID, ClienteName, Ciudad, Estado, País
📦 Información del producto
Productid, Nombre del producto, Categoría, Marca, Cantidad
💰 Precios y métricas de ingresos
Precio unitario, Descuento, Impuesto, Coste de envío, TotalAmount
💳 Detalles de pago
Método de Pago
He creado una columna denominada “Profits”, en la cual se calcula el beneficio estimado total de cada pedido restando los impuestos y gastos de envío al valor registrado en TotalAmount. Este indicador permite obtener una estimación más precisa de la rentabilidad real por transacción.

🧮 Resultados y Conclusiones
Durante los dos últimos años se observa un patrón consistente en el comportamiento de devoluciones y cancelaciones. Las categorías que presentan mayor incidencia son Menaje y Juegos, concentrando un volumen significativamente superior al del resto del catálogo. El análisis de los porcentajes trimestrales de devoluciones y cancelaciones muestra dos comportamientos diferenciados entre ambos años. Durante 2023 se observa un incremento progresivo, pasando de 12.44% a 12.65%, lo que sugiere un deterioro gradual en la satisfacción del cliente o en la calidad del servicio.
En contraste, 2024 inicia con los valores más altos de toda la serie (12.90% y 13.01% en los dos primeros trimestres), indicando un empeoramiento significativo respecto al año anterior. Sin embargo, a partir del tercer trimestre se produce una reducción notable, cerrando el año en 12.26%, el nivel más bajo del periodo analizado.
Esta mejora en la segunda mitad de 2024 sugiere la implementación de medidas correctivas efectivas, posiblemente relacionadas con ajustes operativos, control de calidad o gestión postventa. En conjunto, aunque 2024 comienza con un repunte negativo, finaliza con un desempeño más favorable que 2023.
Además, se detecta un aumento de devoluciones y cancelaciones asociado al método de pago con tarjeta de crédito. Este patrón podría estar relacionado con compras impulsivas, mayor facilidad de reembolso o diferencias en el perfil del cliente que utiliza este método de pago.
En conjunto, estos hallazgos permiten identificar áreas prioritarias de revisión tanto a nivel de categorías de producto como de comportamiento del cliente y estacionalidad.

🏷️ Procedencia
Fuentes
Este conjunto de datos fue creado como parte de un proyecto personal de análisis de ventas de comercio electrónico. Todos los registros están estructurados manualmente según patrones comunes de venta online, rangos de precios y flujos de trabajo de pedidos. No se han utilizado datos externos ni oficiales de Amazon.
Metodología de la colección
Los campos de datos (pedidos, productos, marcas, clientes, precios, pagos, envíos) se diseñaron usando reglas de negocio realistas. Se generaron y revisaron valores para mantener la consistencia, precisión y comportamiento real en 100.000 filas.
Citas
Conjunto de datos de ventas de Amazon

Colaboradores
Rohit Kumar (Propietario)
