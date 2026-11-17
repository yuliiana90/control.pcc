# App de Control de Puntos Críticos de Cocción (HACCP)

## Descripción del Problema
En la línea de cocción de una planta de pulpa de cacao, las temperaturas se anotaban tradicionalmente de forma manual, lo que generaba retrasos, pérdida de registros y ausencia de respuestas inmediatas ante valores que superaban el límite crítico de seguridad[span_3](start_span)[span_3](end_span).

## Qué hace la aplicación
* *Formulario interactivo:* Permite registrar la hora, el operario, el lote y la temperatura de cocción[span_4](start_span)[span_4](end_span).
* *Alertas automáticas:* Muestra una advertencia visual inmediata si la temperatura supera los 85°C (Límite Crítico HACCP)[span_5](start_span)[span_5](end_span).
* *Gráficos y Descarga:* Incluye un gráfico de tendencias y un botón para descargar todos los registros en formato CSV[span_6](start_span)[span_6](end_span).

## Cómo instalar y ejecutar localmente
1. Clona este repositorio.
2. Instala las dependencias necesarias:
   ```bash
   pip install streamlit pandas# control.pcc
