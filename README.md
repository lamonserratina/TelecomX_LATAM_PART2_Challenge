# 📊 Predicción de Cancelación de Clientes

Este proyecto analiza los factores que influyen en la cancelación de clientes en una empresa de telecomunicaciones, utilizando modelos de machine learning para identificar patrones y proponer estrategias de retención basadas en datos.

---

## 🧠 Objetivo

- Identificar las variables más relevantes que afectan la cancelación de clientes.
- Evaluar el rendimiento de modelos predictivos (Regresión Logística y Random Forest).
- Proponer estrategias de retención basadas en los resultados obtenidos.

---

## 🛠️ Tecnologías utilizadas

- **Python** (Google Colab)
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn** (modelado y evaluación)
- **Markdown** (documentación técnica)
- **GitHub** (versionado y portafolio)

---

## 📈 Modelos implementados

| Modelo               | Exactitud | ROC-AUC | Recall | Precisión |
|----------------------|-----------|---------|--------|-----------|
| Regresión Logística  | 0.85      | 0.926   | 0.88   | 0.82      |
| Random Forest        | 0.88      | 0.948   | 0.78   | 0.97      |

Ambos modelos coinciden en variables clave, lo que refuerza su relevancia para la toma de decisiones.

---

## 🔍 Variables más influyentes

- **StreamingTV_Yes** → Aumenta cancelación
- **MultipleLines_Yes** → Aumenta cancelación
- **InternetService_Fiber optic** → Reduce cancelación
- **PaperlessBilling_Yes** → Aumenta cancelación
- **Contract_One year** → Aumenta cancelación
- **Charges.Total bajos** → Asociados a mayor riesgo

---

## 🧭 Estrategias de retención propuestas

1. **Segmentación inteligente**: Identificar perfiles de riesgo combinando servicios, contrato y facturación.
2. **Comunicación personalizada**: Mensajes proactivos y beneficios exclusivos para segmentos vulnerables.
3. **Revisión de precios**: Reforzar la percepción de valor en clientes con cargos bajos.
4. **Ajuste de contratos**: Incentivar migración a contratos más largos con beneficios tangibles.
5. **Monitoreo continuo**: Dashboards con variables clave y actualización periódica de modelos.

---

## 📂 Estructura del repositorio


---

## ✨ Reflexión

Este proyecto no solo busca predecir cancelaciones, sino comprenderlas como señales de desconexión entre cliente y servicio. Cada variable es una pista, cada modelo una brújula, y cada estrategia una oportunidad de reconectar.

> “Las raíces del abandono: señales que anticipan la salida”  
> — Glosario técnico, Joselin
