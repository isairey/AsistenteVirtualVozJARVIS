# 🤖 JARVIS - Asistente Virtual por Voz en Python

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge\&logo=python)
![Voice Assistant](https://img.shields.io/badge/Voice-Assistant-green?style=for-the-badge)
![AI](https://img.shields.io/badge/Artificial-Intelligence-orange?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open-Source-red?style=for-the-badge)

### 🎙️ Tu asistente virtual inteligente controlado por voz

Convierte tu computadora en un asistente personal capaz de escuchar comandos, responder preguntas, abrir sitios web, realizar cálculos matemáticos, buscar información en Wikipedia y mucho más.

</div>

---

## ✨ Características

### 🎤 Reconocimiento de Voz

* Conversación mediante comandos de voz.
* Conversión de voz a texto utilizando los servicios de Google.
* Respuestas habladas mediante síntesis de voz.

### 🧠 Inteligencia Conversacional

* Utiliza la base AIML de ALICE para mantener conversaciones naturales.
* Responde preguntas frecuentes y conversaciones básicas.
* Interacción fluida mediante lenguaje natural.

### 🌐 Apertura de Sitios Web

Abre automáticamente páginas web mediante comandos de voz:

* Google
* Facebook
* Twitter
* YouTube
* GitHub
* Otros sitios populares

**Ejemplo:**

```text
"Jarvis, abre Twitter"
"Jarvis, open Facebook"
```

### 📚 Búsquedas en Wikipedia

Obtén información rápida sobre cualquier tema.

**Ejemplo:**

```text
"Busca Microsoft"
"¿Quién es Elon Musk?"
"Información sobre Inteligencia Artificial"
```

### ➗ Operaciones Matemáticas

Realiza cálculos básicos mediante comandos de voz.

**Ejemplos:**

```text
¿Cuánto es 25 por 8?
¿Cuánto es 100 dividido entre 4?
Suma 50 más 20
```

### 📍 Ubicación Actual

Detecta y proporciona información aproximada sobre tu ubicación.

**Ejemplos:**

```text
¿Dónde estoy?
¿Dónde estamos?
```

### 🎵 Reproducción de Música

* Soporte experimental para reproducción de música.
* Funcionalidad en desarrollo.

---

## 🛠️ Tecnologías Utilizadas

* Python
* Google Speech Recognition
* Google Text-to-Speech
* AIML (Artificial Intelligence Markup Language)
* Wikipedia API
* BeautifulSoup
* Requests
* PyAudio
* PyDub

---

## 📦 Instalación

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/usuario/jarvis.git

cd jarvis
```

### 2️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

O manualmente:

```bash
pip install beautifulsoup4
pip install pyaiml
pip install pyaudio
pip install pydub
pip install requests
pip install pyyaml
```

---

## ⚙️ Dependencias

| Librería       | Descripción                         |
| -------------- | ----------------------------------- |
| BeautifulSoup4 | Procesamiento de páginas web        |
| PyAIML         | Motor conversacional basado en AIML |
| PyAudio        | Captura de audio desde micrófono    |
| PyDub          | Manipulación de audio               |
| Requests       | Solicitudes HTTP                    |
| PyYAML         | Gestión de configuraciones YAML     |

---

## 💻 Compatibilidad

### 🐧 Linux

Instalar dependencias adicionales:

```bash
sudo apt-get install libjack-jackd2-dev portaudio19-dev
```

### 🍎 macOS

Instalar PortAudio:

```bash
brew install portaudio
```

### ❌ Windows

Actualmente no existe soporte oficial para Windows.

---

## 🚀 Uso

Ejecutar el asistente:

```bash
python jarvis.py
```

Una vez iniciado, simplemente habla con Jarvis utilizando tu micrófono.

---

## 💬 Comandos Disponibles

### Abrir páginas web

```text
Abre Google
Abre Twitter
Abre Facebook
Abre YouTube
```

### Buscar información

```text
Busca Microsoft
Busca Python
¿Qué es la inteligencia artificial?
```

### Matemáticas

```text
2 más 2
50 dividido entre 10
100 por 5
```

### Ubicación

```text
¿Dónde estoy?
¿Dónde estamos?
```

---

## 🏗️ Arquitectura del Proyecto

```text
Usuario
   │
   ▼
Micrófono
   │
   ▼
Speech Recognition
   │
   ▼
Procesamiento AIML
   │
   ├── Wikipedia
   ├── Navegador Web
   ├── Calculadora
   └── Ubicación
   │
   ▼
Text To Speech
   │
   ▼
Respuesta de Voz
```

---

## 🔮 Mejoras Futuras

* Soporte completo para Windows.
* Reproducción avanzada de música.
* Integración con modelos de IA modernos.
* Automatización del sistema operativo.
* Control de aplicaciones.
* Interfaz gráfica.
* Integración con ChatGPT.
* Control de dispositivos IoT.

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas.

1. Haz un Fork del proyecto.
2. Crea una rama:

```bash
git checkout -b feature/nueva-funcionalidad
```

3. Realiza tus cambios.
4. Envía un Pull Request.

---

## 👨‍💻 Desarrollador

**Isai Reyes — AI & Full Stack Developer**

Especializado en Inteligencia Artificial, Desarrollo Web, Automatización y Plataformas de Productividad 🚀

---

## 📄 Licencia

Este proyecto se distribuye bajo licencia Open Source.

---

<div align="center">

### ⭐ Si te gusta este proyecto, no olvides dejar una estrella ⭐

**JARVIS - Tu asistente virtual inteligente desarrollado en Python**

</div>
