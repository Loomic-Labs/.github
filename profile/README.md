# 🚀 Loomic Tech | AI Inventory Backend

🌐 Visión General
**Loomic Tech** es una plataforma de automatización diseñada para escalar operaciones de E-commerce masivo. Este repositorio contiene el **Backend Lógico** del Chatbot de Inventario, integrando modelos de lenguaje avanzados (LLMs) para la gestión inteligente de stock y pedidos.

---

## 🛠️ Stack Tecnológico
* **Core:** Python 3.10+
* **IA Engine:** Ollama API (Llama 3 / Mistral)
* **Database:** **Supabase (PostgreSQL)** - Gestión de datos en la nube.
* **Auth & Storage:** Supabase Auth (para futuros accesos seguros).
* **Infrastructure:** GitHub Organizations para despliegue colaborativo

---

## 🏗️ Arquitectura del Sistema
Como **Arquitecto** del proyecto, los estándares de desarrollo para este sistema son:

1.  **Escalabilidad:** El código debe soportar picos de tráfico generados por campañas de Ads.
2.  **Seguridad:** Implementación de capas seguras para la manipulación de datos sensibles del inventario.
3.  **RAG (Retrieval-Augmented Generation):** Conexión directa entre el LLM y la base de datos SQL para respuestas precisas sobre stock.

---

## 📂 Estructura del Proyecto (Propuesta)
```text
loomic-tech-backend/
├── src/                # Código fuente principal
├── docs/               # Documentación técnica adicional
├── tests/              # Pruebas unitarias
└── requirements.txt    # Dependencias del proyecto
