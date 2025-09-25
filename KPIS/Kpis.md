# 📊 Fichas de KPI – Cencosud

---

## 1. Ticket Promedio
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | Ticket Promedio |
| **Objetivo estratégico** | Medir el gasto promedio por transacción |
| **Definición** | Valor promedio de las ventas netas por ticket |
| **Fórmula** | Σ(mto_venta_neta) ÷ Nº de tickets |
| **Unidad de medida** | S/. |
| **Frecuencia de medición** | Diario / Mensual |
| **Fuente de datos** | trx_ticket |
| **Responsable** | Área Comercial |

---

## 2. Margen Promedio por Ticket
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | Margen Promedio por Ticket |
| **Objetivo estratégico** | Evaluar la rentabilidad de las transacciones |
| **Definición** | Margen promedio obtenido por ticket |
| **Fórmula** | Σ(mto_margen) ÷ Nº de tickets |
| **Unidad de medida** | S/. |
| **Frecuencia de medición** | Mensual |
| **Fuente de datos** | trx_ticket |
| **Responsable** | Finanzas |

---

## 3. % Descuento aplicado
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | % de Descuento aplicado |
| **Objetivo estratégico** | Controlar el impacto de las promociones |
| **Definición** | Porcentaje de descuento sobre la venta bruta |
| **Fórmula** | Σ(mto_descuento) ÷ Σ(mto_venta_bruta) × 100 |
| **Unidad de medida** | % |
| **Frecuencia de medición** | Mensual |
| **Fuente de datos** | trx_ticket |
| **Responsable** | Área de Promociones |

---

## 4. % Tickets con Promoción
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | % de Tickets con Promoción |
| **Objetivo estratégico** | Medir la penetración de promociones |
| **Definición** | Proporción de tickets que incluyeron alguna promoción |
| **Fórmula** | Nº tickets con cod_promocion ÷ Nº total de tickets × 100 |
| **Unidad de medida** | % |
| **Frecuencia de medición** | Diario / Mensual |
| **Fuente de datos** | trx_ticket |
| **Responsable** | CRM y Analytics |

---

## 5. Venta Neta por Tipo de Cliente
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | Venta Neta por Tipo de Cliente |
| **Objetivo estratégico** | Identificar qué segmento de clientes genera mayor valor |
| **Definición** | Suma de ventas netas por cada tipo de cliente |
| **Fórmula** | Σ(mto_venta_neta) agrupado por cod_tipo_cliente |
| **Unidad de medida** | S/. |
| **Frecuencia de medición** | Mensual |
| **Fuente de datos** | trx_ticket |
| **Responsable** | CRM |

---

## 6. Frecuencia Promedio de Compra
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | Frecuencia Promedio de Compra |
| **Objetivo estratégico** | Medir cuántas veces compra un cliente en promedio |
| **Definición** | Número promedio de transacciones por cliente |
| **Fórmula** | Σ(trx_acum) ÷ Nº clientes |
| **Unidad de medida** | Nº de transacciones |
| **Frecuencia de medición** | Mensual |
| **Fuente de datos** | rfm_wong, rfm_metro |
| **Responsable** | CRM |


---

## 7. Monto Promedio de Compra por Cliente
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | Monto Promedio de Compra por Cliente |
| **Objetivo estratégico** | Evaluar el gasto total de los clientes |
| **Definición** | Gasto promedio acumulado por cliente |
| **Fórmula** | Σ(venta_acum) ÷ Nº clientes |
| **Unidad de medida** | S/. |
| **Frecuencia de medición** | Mensual |
| **Fuente de datos** | rfm_wong, rfm_metro |
| **Responsable** | Área Comercial |

---

## 8. Recencia Promedio
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | Recencia Promedio |
| **Objetivo estratégico** | Medir la fidelidad de los clientes |
| **Definición** | Días promedio desde la última compra de los clientes |
| **Fórmula** | AVG(recencia_dias) |
| **Unidad de medida** | Días |
| **Frecuencia de medición** | Mensual |
| **Fuente de datos** | rfm_wong, rfm_metro |
| **Responsable** | CRM |
---

## 9. Visitas Promedio por Cliente al Mes
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | Visitas Promedio por Cliente al Mes |
| **Objetivo estratégico** | Identificar la intensidad de la relación cliente-tienda |
| **Definición** | Número promedio de visitas mensuales por cliente |
| **Fórmula** | Σ(visitas_mes) ÷ Nº clientes |
| **Unidad de medida** | Nº de visitas |
| **Frecuencia de medición** | Mensual |
| **Fuente de datos** | rfm_wong, rfm_metro |
| **Responsable** | CRM |

---

## 10. Participación de Canal (Wong vs. Metro)
| CAMPO | DESCRIPCIÓN |
|-------|-------------|
| **Nombre del KPI** | Participación de Canal (Wong vs. Metro) |
| **Objetivo estratégico** | Comparar el desempeño de cada cadena |
| **Definición** | Porcentaje de ventas que aporta cada canal |
| **Fórmula** | Σ(venta_mes_canal) ÷ Σ(venta_mes_total) × 100 |
| **Unidad de medida** | % |
| **Frecuencia de medición** | Mensual |
| **Fuente de datos** | rfm_wong, rfm_metro |
| **Responsable** | Dirección Comercial |
