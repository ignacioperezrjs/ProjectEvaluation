# README - Informe N°4: Evaluación de Proyecto Centro Médico en Molina

## Descripción del Proyecto
Este informe evalúa la viabilidad de apertura de un centro médico integral en la comuna de Molina, Región del Maule (Chile). El análisis incluye estudios financieros, estratégicos y operativos para cuatro alternativas de servicios de salud: consultas médicas, laboratorio clínico, imagenología y centro dental. El documento concluye con recomendaciones basadas en rentabilidad, sinergias y flexibilidad del proyecto.

---

## Estructura del Documento
1. **Formulación**: Contexto organizacional, descripción del proyecto y alternativas evaluadas.
2. **Análisis Estratégico**: FODA, Cinco Fuerzas de Porter y modelo de negocio.
3. **Evaluación**: Modelos financieros, análisis de casos, sensibilidad y **simulación de Montecarlo**.
4. **Conclusiones**: Recomendación final basada en VAN, TIR y análisis de riesgo.

---

## Contribuciones Clave

### Simulación de Montecarlo (Responsable: [Tu nombre])
- **Objetivo**: Evaluar la incertidumbre en variables críticas (tasa de descuento, demanda, costos operativos).
- **Metodología**:
  - Variables analizadas: 
    - Tasa de descuento (rango: 15%-25%).
    - Sueldos (distribución normal: media 526M CLP, DE 105M CLP).
    - Demanda de consultas médicas (uniforme: 70%-98% ocupación).
  - Resultados:
    - VAN promedio: 567.470M CLP.
    - Probabilidad de VAN negativo: 10.6%.
    - TIR promedio: 48.55%.
  - Herramientas: Excel y gráficos de distribución (ver Anexo 48).
- **Conclusiones**: El proyecto muestra resiliencia ante escenarios adversos, con baja probabilidad de pérdidas.

---

## Equipo de Trabajo
- **Líder de Análisis Cuantitativo** (Montecarlo): Ignacio Pérez
- **Colaboradores**:
  - T. Barros.
  - A. Varela (líder de equipo). 
  - J. Avello. 
  - I. Pérez.
  - V. Ramírez. 
  - A. Henríquez. 

---

## Archivos Adjuntos
- `Informe 4.docx.pdf`: Documento principal con 49 páginas y 50 anexos.
- `Anexos/`: Datos brutos, tablas detalladas y gráficos de sensibilidad.
  - Destacados: 
    - `Anexo 48 - Gráfico TIR Montecarlo.png`.
    - `Anexo 33 - Descripción metodología sensibilidad.xlsx`.

---

## Instrucciones para Replicación
1. **Requisitos**: Excel (versión 2019 o superior), acceso a datos del INE y CENABAST.
2. **Modelos Financieros**: 
   - Abrir `Anexo 27 - Flujo de Caja.xlsx`.
   - Ajustar variables en hoja `Montecarlo` para nuevos escenarios.
3. **Visualización**: Los gráficos de tornado y distribuciones se generaron con `Excel Data Analysis Toolpak`.

---

## Contacto
Para consultas técnicas o acceso a datos complementarios, contactar a Ignacio Pérez en ignacioperez@uc.cl.
