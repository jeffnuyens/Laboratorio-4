Laboratorio \#4
================
Jeff
2023-08-30

## Distruibuidora del Sur, S.A.

Esta es una empresa dedicada a la distribución y entrega de bebidas
carbonatadas en lata en la región sur de Guatemala. La empresa opera en
el sector logístico y de distribución, colaborando con una variedad de
clientes para asegurar el flujo eficiente de productos desde el centro
de distribución hasta los centros de recolección.

## Análisis de Distribuidora del Sur, S.A.

En este informe se presenta un análisis de la situación financiera y
operativa de Distribuidora del Sur, S.A. Se abordaron diversas hipótesis
para comprender el flujo de caja, la rentabilidad de los clientes y la
eficiencia operativa de pilotos, y para proporcionar recomendaciones que
guíen las decisiones futuras de la empresa.

## Supuestos

- Considerar entregas completas como aquellas sin faltantes ni
  devoluciones.
- Los ingresos monetarios solo están conformados por las entregas
  completas.
- Las pérdidas monetarias se derivarán de los pedidos que presenten
  faltantes y devoluciones, ya que estos aún no generan ingresos o
  implican la reducción de los fondos disponibles.
- Al multiplicar la cantidad de viajes por la proporción de entregas
  completas, se crea una métrica que recompensa tanto la cantidad de
  trabajo como la calidad de ese trabajo.

## Hipótesis 1: Análisis del Flujo de Caja

Los problemas operativos, como las devoluciones y los faltantes, tienen
un impacto directo en la estabilidad del flujo de caja.

| MES | Ingresos | Perdidas |
|:----|---------:|---------:|
| 01  | 34763.00 |    82614 |
| 02  | 37173.75 |    76211 |
| 03  | 30716.00 |    71003 |
| 04  | 30357.75 |    85399 |
| 05  | 37376.50 |    90794 |
| 06  | 32253.50 |    80034 |
| 07  | 34255.00 |    89711 |
| 08  | 32769.75 |    81971 |
| 09  | 30166.75 |    85410 |
| 10  | 32908.75 |    89083 |
| 11  | 34080.50 |    95878 |

![](Laboratorio-4_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

Los ingresos varían de manera consistente en diferentes meses, con
algunos meses generando mayores ingresos que otros. Las pérdidas también
muestran fluctuaciones mensuales. Los meses con pérdidas más altas
pueden estar relacionados con una mayor cantidad de devoluciones o
faltantes por parte de los clientes. Al comparar los ingresos y las
pérdidas, podemos observar que las pérdidas superan a los ingresos. Las
pérdidas continuas pueden llevar a una situación en la que la empresa no
pueda cumplir con sus obligaciones financieras. También, las pérdidas
podrían limitar la capacidad de la empresa para invertir en nuevas
oportunidades de crecimiento y los fondos para afrontar situaciones de
emergencia.

## Hipótesis 2: Evaluación de Rentabilidad de Clientes

Al aplicar el principio 80-20 para identificar los clientes más
importantes en términos de ingresos, se establece una relación entre la
rentabilidad de los clientes y su contribución al flujo de caja.

| CLIENTE_FINAL                   | Ingresos | Pct_Ingresos |
|:--------------------------------|---------:|-------------:|
| TAQUERIA EL CHINITO             | 38274.00 |    0.1043396 |
| UNIVERSIDAD FRANCISCO MARROQUIN | 37889.25 |    0.1032908 |
| ABARROTERIA EBENEZER            | 37129.00 |    0.1012182 |
| EL PINCHE OBELISCO              | 35555.00 |    0.0969273 |
| TIENDA LA BENDICION             | 35338.00 |    0.0963357 |
| BAR LA OFICINA                  | 35163.50 |    0.0958600 |
| EL GALLO NEGRO                  | 34485.00 |    0.0940104 |
| UBIQUO LABS                     | 32125.75 |    0.0875788 |
| POLLO PINULITO                  | 32100.00 |    0.0875086 |
| HOSPITAL ROOSEVELT              | 26275.75 |    0.0716309 |
| HOSPITAL LAS AMERICAS           | 22486.00 |    0.0612996 |

![](Laboratorio-4_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

En el análisis de evaluación de rentabilidad de clientes, en función del
80-20 de clientes y cuáles de ellos son los más importantes, se han
identificado y priorizado a los principales clientes en función de los
ingresos generados por las entregas completas. Para esto, se utilizó un
porcentaje acumulativo de ingresos para determinar qué porcentaje de los
ingresos totales es aportado por cada cliente, específicamente, el
porcentaje acumulado se calculó dividiendo los ingresos acumulados de
cada cliente entre el total de ingresos totales de todos clientes. Se
identificó que el 80% de los ingresos totales no es generado por el 20%
de los clientes. En realidad, un número sustancialmente mayor de
clientes representa el 80% de los ingresos. En la gráfica se puede
observar que no hay una clara concentración de ingresos en un grupo
pequeño de clientes.

## Hipótesis 3: Eficiencia de Pilotos

La eficiencia de los pilotos en completar entregas sin devoluciones ni
faltantes contribuye a la mejora del flujo de caja.

![](Laboratorio-4_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->

| PILOTO                        | Cantidad_Viajes | Proporcion_Entregas_Completas | Puntaje_Eficiencia |
|:------------------------------|----------------:|------------------------------:|-------------------:|
| Fernando Mariano Berrio       |             167 |                     0.1237954 |           20.67383 |
| Luis Jaime Urbano             |             162 |                     0.1200890 |           19.45441 |
| Felipe Villatoro              |             159 |                     0.1178651 |           18.74055 |
| Hector Giron                  |             152 |                     0.1126761 |           17.12676 |
| Pedro Alvarez Parejo          |             152 |                     0.1126761 |           17.12676 |
| Ismael Rodero Monteagudo      |             145 |                     0.1074870 |           15.58562 |
| Hector Aragones Frutos        |             143 |                     0.1060044 |           15.15864 |
| Angel Valdez Alegria          |             138 |                     0.1022980 |           14.11712 |
| Juan Francisco Portillo Gomez |             131 |                     0.0971090 |           12.72128 |

Los resultados muestran la cantidad de viajes realizados por cada piloto
y la proporción de entregas completas que realizaron en relación con el
total de entregas completas (1349 en total). Se ha calculado un puntaje
de eficiencia para cada piloto, considerando tanto la cantidad de viajes
que realizaron como la proporción de entregas completas que llevaron a
cabo. Este puntaje busca evaluar la eficiencia general de los pilotos en
términos de realizar una mayor cantidad de entregas completas. Los
pilotos más eficientes en términos de entregas completas son aquellos
que tienen puntajes más altos. Estos pilotos son quienes han logrado
mantener una alta proporción de entregas completas en relación con la
cantidad de viajes que realizaron. En resumen, Fernando Mariano Berrio
muestra un alto rendimiento en términos de entregas completas y cantidad
de viajes. El gráfico de dispersión muestra la relación entre la
cantidad de viajes realizados por un piloto y la proporción de entregas
completas que lograron. Esto permite visualizar cómo se distribuyen los
pilotos en términos de eficiencia en las entregas.

## Recomendaciones

- Revisar los procesos de manejo de inventario, logística y calidad de
  productos para implementar estrategias para reducir las pérdidas.
- Dado que los ingresos pueden verse afectados por las políticas de
  crédito, es importante revisar y ajustar estas políticas según el
  comportamiento de pago de los clientes.
- Debido a que varios clientes contribuyen a los ingresos de la empresa,
  es importante implementar estrategias para fidelizar a estos clientes,
  identificar cambios en sus patrones de compra y tomar medidas
  proactivas en consecuencia.
- Ofrecer entrenamiento adicional, compartir mejores prácticas y brindar
  retroalimentación específica a los pilotos para ayudar a mejorar su
  eficiencia.
- Considerar la implementación de sistemas de incentivos para
  recompensar a los pilotos más eficientes. El reconocimiento público o
  monetario por su trabajo eficiente puede motivar a otros pilotos a
  mejorar su rendimiento.
- Antes de invertir en la contración de más personal y más vehículos de
  distribución, se podrían asignar rutas de entregas de manera más
  efectiva. Asignar a los pilotos más eficientes a rutas más desafiantes
  o a clientes con historiales de entregas incompletas podría ayudar a
  mejorar la satisfacción del cliente y la eficiencia general.
