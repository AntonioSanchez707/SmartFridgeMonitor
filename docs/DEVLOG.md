# Diario de desarrollo

## 2026-07-10

### Avances

- Se validó la conectividad WiFi del ESP32.
- Se implementó un servidor web básico.
- Se definió la arquitectura general del proyecto.
- Se seleccionaron los sensores SB-41 Full Gauge (NTC 10 kΩ).
- Se seleccionó el transformador de corriente SCT-013-000.
- Se decidió utilizar un LM358P para el acondicionamiento de la señal analógica del SCT-013-000.

### Próximos pasos

1. Diseñar el circuito de acondicionamiento con LM358P.
2. Validar la señal con osciloscopio o ADC del ESP32.
3. Implementar el cálculo RMS.
4. Integrar la lectura al dashboard web.
