# Plan Visual: Curso Mindset Millonario

> **Nota de corrección (enriquecimiento 2026-07-27):** este plan se redactó contra un borrador de temario anterior, cuya numeración de módulos no coincide con el curso final generado. Los 3 conceptos de este plan sí existen en el curso, pero viven en el **Módulo 0 (nivelación)**, no en los módulos 2/3/4 originalmente referenciados. Las referencias de módulo abajo ya están corregidas y los 3 artefactos fueron generados e integrados.

## 1. Diagramas (Agente 6: Diseñador Gráfico)

### Módulo 0 / Concepto 2: Activos vs. Pasivos ✅ Integrado

- **Prompt para Agente 6:** "Diseña una ilustración clara y minimalista estilo editorial que muestre el flujo de dinero: los activos (izquierda) alimentan el bolsillo (ingreso), mientras que los pasivos (derecha) drenan el dinero del bolsillo (gasto). Usa paleta de colores corporativa (Navy/Oro)."
- **Mermaid:**

  ```mermaid
  graph LR
      A[Activos] -->|Generan| B(Bolsillo/Ingresos)
      C[Pasivos] -->|Absorben| B
      B -->|Financian| C
  ```

- **Integrado en:** `modulos/modulo_0/concepto_2_activos_pasivos.md`

### Módulo 0 / Concepto 4: Ciclo de Ahorro/Inversión ✅ Integrado

- **Prompt para Agente 6:** "Crea un diagrama circular de flujo (infografía) que represente el ciclo de creación de riqueza: Ingresos -> Ahorro -> Inversión -> Nuevos Ingresos (Reinversión). Estilo limpio, iconos financieros sutiles."
- **Mermaid:**

  ```mermaid
  graph TD
      A[Ingresos] --> B[Ahorro/Fondo Emergencia]
      B --> C[Inversión Productiva]
      C --> D[Retorno/Dividendos]
      D --> A
  ```

- **Integrado en:** `modulos/modulo_0/concepto_4_ahorro_inversion.md`

## 2. Simulaciones Interactivas (Agente 4: Simulador)

### Módulo 0 / Concepto 3: El Poder del Interés Compuesto ✅ Integrado

- **Parámetros para Agente 4:**
  - **Variables de entrada:**
    - Inversión inicial (rango: 100 - 10,000 USD).
    - Aportación mensual (rango: 50 - 2,000 USD).
    - Tasa de interés anual estimada (rango: 5% - 15%).
    - Plazo (rango: 5 - 40 años).
  - **Salida esperada:**
    - Gráfico comparativo: Valor final de la inversión vs. Aportaciones acumuladas.
    - Tabla de crecimiento anual.
- **Artefacto generado:** `media/simulacion_interes_compuesto.html` (HTML autocontenido, sin dependencias externas de JS; interés compuesto con aportes mensuales, gráfico SVG comparativo y tabla año a año). Adaptado al lenguaje simple de la audiencia (complejidad Baja) con la metáfora "bola de nieve" ya usada en el concepto.
- **Integrado en:** `modulos/modulo_0/concepto_3_interes_compuesto.md`
