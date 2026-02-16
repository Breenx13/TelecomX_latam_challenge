# TelecomX_latam_challenge
<div align="center">

# ✨ CHALLENGE - TelecomX LATAM ✨

## 📊 Análisis de Deserción de Clientes (Churn)

![Badge](https://img.shields.io/badge/ENTREGA-16/02/2026-pink)

</div>

---

# 📌 Introducción

Este proyecto desarrolla un análisis de deserción de clientes (*Churn Analysis*) para TelecomX LATAM.

Actualmente, la empresa presenta una tasa considerable de cancelaciones de servicio, lo que impacta directamente en su rentabilidad y crecimiento. Por este motivo, el objetivo principal de este análisis es:

* Identificar los factores asociados a la deserción de clientes.
* Comprender el comportamiento de los usuarios.
* Generar estrategias que permitan mejorar la retención.

---

# 🧹 Limpieza y Tratamiento de Datos

Para garantizar la calidad del análisis, se realizó un proceso completo de preparación de los datos:

* Importación de datos desde una API en formato JSON.
* Normalización de la estructura para facilitar su manipulación.
* Eliminación de valores nulos e inconsistentes.
* Transformación de variables categóricas binarias (Yes / No) a formato numérico (0 / 1), optimizando su análisis.

---

# 📊 Análisis Exploratorio de Datos (EDA)

Se desarrollaron diversas visualizaciones para detectar patrones y comprender los factores que influyen en la deserción.

---

## 💰 1. Distribución de costos

**Costo mensual y total**

* La mayoría de los clientes presenta cargos mensuales bajos (moda ≈ 20).
* Existe una alta dispersión, indicando que algunos clientes tienen gastos significativamente mayores.
* Los clientes que permanecen en la empresa presentan un gasto total más alto que aquellos que desertan.

---

## 📉 2. Deserción general

* La tasa de deserción total es del **26.54%**.
* Este valor es elevado y representa un punto crítico que requiere acciones estratégicas.

---

## 👥 3. Género

* La tasa de deserción es similar entre hombres y mujeres (≈ 26%).
* El género no representa un factor determinante en la cancelación del servicio.

---

## 📄 4. Tipo de contrato

Se identificaron diferencias importantes según el tipo de contrato:

* **Contrato mensual**

  * Representa el 55% de los clientes.
  * Presenta la menor tasa de deserción: **2.8%**

* **Contrato anual**

  * Tasa intermedia: **11.3%**

* **Contrato de dos años**

  * Mayor tasa de deserción: **42.7%**

Esto indica que los contratos largos no garantizan la fidelización.

---

## ⏳ 5. Antigüedad del cliente

* La mayor deserción ocurre en los primeros meses.
* Los clientes con menor antigüedad tienen mayor probabilidad de cancelar.
* Los contratos flexibles muestran mejor retención a largo plazo.

---

## 💳 6. Método de pago

Se observó una relación significativa entre el método de pago y la deserción:

* **Cheque electrónico**

  * Mayor tasa de deserción: **45.3%**

* **Transferencia automática**

  * Menor tasa de deserción: **15.2%**

Los pagos automáticos se asocian con mayor permanencia.

---

## 🛠️ 7. Uso de servicios adicionales

Los clientes que permanecen presentan mayor uso de servicios como:

* Seguridad online
* Soporte técnico
* Respaldo de datos

En contraste, los clientes que desertan utilizan menos servicios, lo que indica menor nivel de compromiso con la empresa.

---

## 👴 8. Perfil del cliente

Se observó mayor deserción en:

* Clientes senior (> 40%)
* Clientes sin pareja
* Clientes sin dependientes

Estos segmentos requieren estrategias específicas de retención.

---

# 📌 Conclusiones

Principales hallazgos del análisis:

* La deserción no depende del género.

* Está fuertemente relacionada con:

  * Tipo de contrato
  * Método de pago
  * Nivel de uso de servicios

* Los clientes con menor gasto y menor uso de servicios desertan con mayor frecuencia.

* Los métodos de pago automáticos ayudan a mejorar la retención.

---

# 🚀 Recomendaciones

En base al análisis, se proponen las siguientes estrategias:

## 📄 Optimizar los contratos

* Incentivar contratos flexibles.
* Ofrecer beneficios progresivos según la antigüedad.

---

## 🛠️ Fomentar el uso de servicios

* Crear paquetes personalizados.
* Incentivar servicios de valor agregado.

---

## 💳 Mejorar los métodos de pago

* Promover pagos automáticos mediante beneficios.
* Facilitar la migración desde cheque electrónico.

---

## 🎯 Estrategias de segmentación

* Detectar clientes con alto riesgo de deserción.
* Implementar campañas de retención específicas.

---

## ⏱️ Seguimiento temprano

* Realizar seguimiento durante los primeros 6 meses.
* Mejorar la experiencia inicial del cliente.

---

# 📌 Resultado Final

Este análisis permitió identificar factores clave que influyen en la deserción, proporcionando información valiosa para la toma de decisiones estratégicas y la mejora de la retención de clientes.

---

# 🧠 Herramientas utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

---

# 👩‍💻 Autor

Proyecto desarrollado por **Brenda Galván**
Como parte del Challenge de análisis de datos de Alura LATAM.

---
