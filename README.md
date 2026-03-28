# Identificación de “Ventas Climáticas” por Sector

Detección del pico de pánico y capitulación colectiva

## 📌Descripción General

Este proyecto identifica ventas climáticas a nivel sectorial, es decir, el punto donde el pánico alcanza su máxima intensidad y la probabilidad de una caída adicional se reduce de forma significativa.

La señal combina tres dimensiones críticas:
- Momentum extremo (RSI muy bajo),
- Volumen anómalo (capitulación),
- Riesgo estadístico elevado (kurtosis alta).

Cuando estas tres condiciones ocurren simultáneamente en varios tickers de un mismo sector, el mercado suele estar forzando ventas indiscriminadas, típicas de un suelo.

## 📍Insight Clave

- ¿En qué sector el mercado está vendiendo “a cualquier precio”?

Una venta climática se caracteriza por:
- agotamiento de vendedores,
- liquidaciones forzadas,
- emociones dominando decisiones.

Paradójicamente, es ahí donde mejora el perfil riesgo/retorno para entradas contrarian bien gestionadas.

## 💼Valor de Negocio

- Identifica oportunidades de compra por capitulación.

Permite entrar cuando:
- el consenso es totalmente negativo,
- el riesgo marginal empieza a disminuir.

Muy útil para:
- estrategias contrarian,
- asignación táctica sectorial,
- detección de suelos de ciclo.

Complementa señales técnicas clásicas, evitando entradas prematuras.

Fuentes de Datos
- tickers
- ticker_id
- sector
- precios_diarios
- ticker_id
- fecha
- volume
- indicadores_tecnicos
- ticker_id
- fecha
- rsi_14
- kurtosis

## 🧠Lógica del Análisis

Se analizan los datos más recientes del mercado.

Se filtran tickers que cumplan simultáneamente:
- RSI < 25 (sobreventa extrema),
- Kurtosis > 6 (movimientos extremos no normales).

Se agrupan los resultados por sector.

Para cada sector se calcula:
- cantidad de tickers en pánico,
- RSI promedio,
- spike de volumen relativo.

Se consideran solo sectores con múltiples tickers afectados, evitando falsos positivos individuales.

## 📊Interpretación de Resultados

Muchos tickers + RSI extremadamente bajo + volumen explosivo
→ Capitulación sectorial.
→ Posible suelo técnico.

RSI bajo sin volumen
→ Debilidad gradual, no clímax.

Volumen alto sin kurtosis
→ Rotación, no pánico.

## 🧩Casos de Uso

- Detección de suelos sectoriales.
- Estrategias de reversión a la media.
- Timing de entrada post-crisis.
- Análisis de stress de mercado.
- Complemento a análisis macro y de sentimiento.

## 🚀Posibles Extensiones

- Confirmar con recuperación del RSI en días posteriores.
- Analizar retornos a 5 y 10 días post-señal.
- Combinar con divergencias de volumen.
- Integrar con señales de “Iceberg” institucional.
- Ajustar umbrales por régimen de volatilidad.

## ✒️Nota Final

El mercado no cae en silencio.
Cae gritando, con volumen, extremos y miedo.

## 👤Autora
Flavia Hepp Proyecto de SQL aplicó un análisis de riesgo basado en eventos.
Este insight no busca comprar barato.
Busca comprar cuando ya no queda nadie más vendiendo 📉🔥

****
🔥 **Cuando todos venden… ¿es exactamente cuando deberías mirar para comprar?**

Hay un punto en el mercado donde el miedo alcanza su máximo.

No es una caída normal.
Es **capitulación**.

---

📊 En este análisis detecté sectores donde ocurre lo siguiente al mismo tiempo:

👉 **RSI extremadamente bajo (<25)**
👉 **Volumen muy alto (pico de actividad)**
👉 **Kurtosis elevada (movimientos extremos)**

---

⚠️ ¿Qué significa esta combinación?

* Venta masiva
* Pánico generalizado
* Movimientos no lineales

💡 En otras palabras:
👉 El mercado está “forzando” ventas.

---

🧠 Pero acá está lo interesante:

Cuando todos los indicadores apuntan a extremo…
muchas veces estamos cerca de un **piso**.

---

🚨 Insight clave:
**Las mejores oportunidades no aparecen cuando el mercado está tranquilo…
aparecen cuando el miedo es máximo.**

---

🔍 ¿Qué permite este análisis?

✔️ Detectar eventos de capitulación sectorial
✔️ Identificar posibles puntos de reversión
✔️ Encontrar oportunidades contrarian

---

📉 Porque en trading, el edge muchas veces está en hacer lo contrario…
pero con datos que lo respalden.

---

#Quant #Trading #DataScience #Contrarian #MarketPanic #RSI #RiskManagement #Finanzas

