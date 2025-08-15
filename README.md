# Challenge Alura Store

## Descripción
Este proyecto realiza un análisis completo de las ventas de diferentes tiendas, con el objetivo de identificar patrones, tendencias y oportunidades de negocio.  
Se analizan factores como ingresos totales, categorías de productos más y menos vendidas, calificaciones promedio de los clientes, productos más y menos vendidos y costes de envío medios.  
El análisis incluye gráficos para facilitar la interpretación de los resultados y respaldar la toma de decisiones.

---

## Objetivo
Determinar en qué tienda el Sr. John debería concentrar sus ventas, considerando:  
- Rentabilidad (ingresos totales)  
- Popularidad de categorías y productos  
- Satisfacción de los clientes (calificaciones promedio)  
- Costes de envío  

---

## Dataset
El análisis se realiza sobre un dataset que contiene las siguientes columnas:

| Columna                 | Descripción                                |
|--------------------------|--------------------------------------------|
| Producto                 | Nombre del producto vendido                |
| Categoría del Producto   | Categoría del producto                      |
| Precio                   | Precio de venta del producto                |
| Costo de envío           | Costo del envío del producto                |
| Fecha de Compra          | Fecha en la que se realizó la compra       |
| Vendedor                 | Nombre del vendedor                         |
| Lugar de Compra          | Ciudad o tienda donde se vendió el producto|
| Calificación             | Valoración del cliente (1 a 5)             |
| Método de pago           | Método utilizado para el pago               |
| Cantidad de cuotas       | Número de cuotas si fue pago a crédito     |
| lat                      | Latitud de la tienda                        |
| lon                      | Longitud de la tienda                       |

---

## Análisis Realizado
1. **Ingresos totales por tienda**  
   Se sumaron los precios de todos los productos vendidos por tienda para identificar las más rentables.

2. **Cantidad de productos por categoría**  
   Se contó cuántos productos se vendieron por categoría, destacando las más y menos populares.

3. **Calificación promedio de clientes**  
   Se calculó el promedio de las calificaciones para evaluar la satisfacción de los clientes.

4. **Productos más y menos vendidos**  
   Se identificaron los productos con mayor y menor frecuencia de venta.

5. **Coste de envío medio por tienda**  
   Se calculó el promedio de costos de envío por tienda para analizar la rentabilidad.

---

## Visualizaciones
Se generaron al menos tres tipos de gráficos diferentes para interpretar los resultados:  

1. **Gráfico de barras**: Cantidad de productos por categoría.  
2. **Gráfico de barras horizontal**: Productos más vendidos.  
3. **Gráfico de dispersión**: Relación entre Precio y Costo de envío.

---

## Conclusión
Tras el análisis de los ingresos, la popularidad de categorías y productos, la satisfacción de los clientes y los costes de envío, se recomienda que el Sr. John enfoque sus ventas en la tienda **[Nombre de la tienda recomendada]**, ya que presenta las mejores condiciones en todos los factores evaluados.

---

## Requisitos
- Python 3.x  
- Librerías: `matplotlib`, `pandas` (opcional si quieres usar DataFrame)  

---


