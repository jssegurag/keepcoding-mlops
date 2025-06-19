# 🤖 ML Services API - FastAPI + Streamlit

## 📋 Repositorio del Código

### 🔗 **https://github.com/jssegurag/fastapi-mlops-keepcoding**

## 🎥 Video Explicativo

[![Video Explicativo ML Services API](https://img.youtube.com/vi/LXt3aEVPDsk/maxresdefault.jpg)](https://www.youtube.com/watch?v=LXt3aEVPDsk)

### 📺 **[Ver en YouTube](https://www.youtube.com/watch?v=LXt3aEVPDsk)**

Una aplicación completa de Machine Learning con 5 servicios implementados usando FastAPI y una interfaz web con Streamlit.

## 🚀 Servicios Disponibles

### Endpoints FastAPI

1. **📊 Análisis de Sentimientos**
   - `GET /ml/sentiment?text=<texto>`
   - Analiza sentimientos en texto (positivo/negativo/neutral)

2. **📝 Resumen de Texto**
   - `GET /ml/summarization?text=<texto>&max_length=100&min_length=10`
   - Genera resúmenes automáticos de textos largos

3. **🌍 Traducción**
   - `GET /ml/translation?text=<texto>&target_language=es`
   - Traduce texto de inglés a español

4. **✍️ Generación de Texto**
   - `GET /ml/text-generation?prompt=<prompt>&max_length=50`
   - Genera texto coherente basado en un prompt inicial

5. **❓ Respuesta a Preguntas**
   - `GET /ml/question-answering?question=<pregunta>&context=<contexto>`
   - Responde preguntas basándose en un contexto dado

6. **🏥 Health Check**
   - `GET /ml/health`
   - Verifica el estado de todos los servicios

## 🖥️ Aplicación Streamlit

La aplicación web incluye:
- Interfaz de chat interactiva para todos los servicios
- Selector dinámico de servicios ML
- Validación de entrada en tiempo real
- Historial de conversaciones
- Indicadores de estado de la API

## 🚀 Instalación y Ejecución

```bash
# Clonar el repositorio
git clone https://github.com/jssegurag/fastapi-mlops-keepcoding.git
cd fastapi-mlops-keepcoding

# Instalar dependencias
pip install -r requirements.txt

# Iniciar servicios automáticamente
python start_local.py
```

**Acceso:**
- FastAPI: http://localhost:8000
- Documentación: http://localhost:8000/docs
- Streamlit: http://localhost:8501 
