# Needs Statement - Proyecto HemoKid

## 1. Problemática Detectada
Según la Encuesta Nacional de Demografía y Salud (ENDES 2023), en Lima Metropolitana, el **34.9%** de los niños de entre 6 a 35 meses padecen de anemia infantil[cite: 8]. Esta condición afecta el desarrollo cognitivo, la conducta y la productividad del infante[cite: 12].

### Desafíos Actuales:
* Falta de dispositivos de diagnóstico portátiles y **no invasivos**[cite: 128].
* Dependencia de laboratorios clínicos externos para el tamizaje municipal[cite: 129].
* Necesidad de ajustes de hemoglobina por altitud para diagnósticos precisos[cite: 13, 14].

## 2. Declaración de la Necesidad (Needs Statement)
Una forma de detectar y cuantificar la anemia en niños menores de 5 años en el distrito de San Miguel para identificar casos de riesgo de forma inmediata y reducir la dependencia de laboratorios clínicos externos en el tamizaje municipal.

**Objetivo:** Desarrollar una forma de detectar y cuantificar la anemia en niños menores de 5 años en el distrito de San Miguel para identificar casos de riesgo de forma inmediata[cite: 129].

## 3. Especificaciones Técnicas y Referencias
### Puntos de Corte para Diagnóstico (g/dL)
| Población | Severa | Moderada | Leve | Sin Anemia |
| :--- | :---: | :---: | :---: | :---: |
| Niños 6-23 meses | < 7.0 | 7.0 - 9.4 | 9.5 - 10.4 | >= 10.5 |
| Niños 24-59 meses | < 7.0 | 7.0 - 9.9 | 10.0 - 10.9 | >= 11.0 |
*[cite: 16]*

### Fórmula de Ajuste por Altitud (CDCPNSS)
Para alturas mayores a 500 m.s.n.m.[cite: 20]:
* **Factor Altitud (alt):** $[(\text{altura en metros})/1000] \times 3.3$ [cite: 24]
* **Ajuste:** $0.022 \times (alt)^2 - 0.032 \times (alt)$ [cite: 23]
* **Hb Ajustada:** $Hb_{observada} - \text{Ajuste}$ [cite: 22]

## 4. Análisis de Errores Comunes
Para asegurar la precisión del dispositivo, se deben mitigar los siguientes errores[cite: 35]:
* **Lecturas Falsas Bajas:** Dilución por alcohol/sudor, exceso de presión en el dedo (\"ordeñado\") o burbujas de aire en la microcubeta[cite: 37, 38, 39].
* **Lecturas Falsas Altas:** Microcubeta mal llenada, uso de reactivos vencidos o muestra coagulada por espera excesiva[cite: 41, 43, 45].

## 5. Stakeholders (Interesados)
* **Primarios:** Niños < 5 años, Personal de Salud de San Miguel, Padres[cite: 106, 109, 111].
* **Secundarios:** Municipalidad de San Miguel (Financiador), MINSA (Regulador)[cite: 113, 114].
* **Terciarios:** Laboratorios locales y proveedores de tecnología[cite: 117, 118]." > NeedsStatement.md