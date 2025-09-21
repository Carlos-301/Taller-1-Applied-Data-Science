# Informe Ejecutivo - Taller 1 CDA

## Resumen de datos
- Tasa global de cancelación: 0.411

## Insights clave:
- Grupo con mayor tasa de cancelación por lead_time: >365d con tasa=0.764 (n=1238)
- Tipo de hotel con mayor tasa de cancelación: City Hotel con tasa=0.696 (n=18832)
- ADR promedio reservas canceladas: 105.12, no canceladas: 90.06
- Top features predicting cancelación: lead_time, adr, deposit_type_No Deposit, hotel_City Hotel, hotel_Resort Hotel

## Recomendaciones:
- Implementar políticas de pre-pago o no reembolsables para reservas con alto lead_time (>90 días) en hoteles con alta tasa de cancelación.
- Ofrecer promociones dirigidas a segmentos de mercado con alta probabilidad de cancelar (usar market_segment y distribution_channel para segmentar).
- Implementar recordatorios y confirmaciones automáticas por e-mail/SMS a reservas con lead_time alto, incluyendo facilidades para cambiar fecha en lugar de cancelar.
- Ajustar estrategia de precios (ADR) para segmentos con mayor cancelación; considerar seguros de cancelación o añadir coste reducido por cambio.
- Para clientes con historial de cancelaciones previas, requerir tarjeta con pre-autorización o condiciones especiales.