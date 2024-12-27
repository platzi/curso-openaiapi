<h1 align="center">💡 Curso OpenAI API 💻</h1>

<p align="center">
  Repositorio del Curso de OpenAI API
</p>

👋 ¡Hola! Este repositorio contiene todos los ejercicios prácticos realizados con OpenAI API.

Durante el curso de OpenAI API utilizamos la versión `1.55.3` de la librería `openai` para Python.

## 🌲 Commits y carpetas de las clases

| Clase                                                      | Commit                      | Carpeta                      |
| ---------------------------------------------------------- | --------------------------- | ---------------------------- |
| ChatCompletion API: API para chat                          | `ChatCompletionAPI`         | `/ChatCompletionAPI`         |
| ToolsAPI: Herramientas en ChatCompletion API               | `ToolsAPI`                  | `/ToolsAPI`                  |
| Image API: Procesamiento de imágenes en ChatCompletion API | `Images`                    | `/Images`                    |
| DALL·E 3 API: Generación de imágenes utilizando DALL·E 3   | `Dalle3`                    | `/Dalle3`                    |
| BatchAPI: Lotes de solicitudes                             | `Batch`                     | `/Batch`                     |
| Assistants: Asistentes de OpenAI                           | `Assistants`                | `/Assistants`                |
| Transcripción y síntesis de voz                            | `SpeechToText-TextToSpeech` | `/SpeechToText-TextToSpeech` |
| Ejecución del Fine-Tuning y Monitoreo                      | `Fine-Tuning`               | `/Fine-Tuning`               |

De esta forma, cada commit representa una clase del curso, si deseas navegar a una parte específica del curso, puedes hacerlo usando el comando `git checkout <commit>`.

## 📝 Notas sobre cada clase

A continuación encontrarás una lista de notas sobre cada clase del curso:

### ChatCompletion API

La **ChatCompletion API** de OpenAI permite interactuar con los modelos de lenguaje mediante un flujo de conversación basado en mensajes. Este enfoque utiliza un historial de interacciones donde los mensajes son clasificados como del asistente, del usuario o de un sistema (como instrucción hacia el asistente).

### Tools API

La **ToolsAPI** de OpenAI extiende la funcionalidad de los modelos al permitirles interactuar con herramientas externas dentro de una conversación. Actualmente, estas herramientas se limitan a **funciones** específicas definidas por el usuario, pero el soporte futuro incluirá capacidades avanzadas como **Code Interpreter** y **File Search**.

### Image API

OpenAI ahora nos permite integrar el procesamiento de imágenes directamente dentro de las interacciones con la **ChatCompletion API**. Gracias a esto podemos incluir imágenes en las conversaciones, y el asistente puede interpretarlas.

### DALL·E 3 API

La **DALL·E 3 API** proporciona acceso al modelo generativo de imágenes más avanzado de OpenAI, que permite crear imágenes a partir de prompts. También podemos generar imágenes a través de la API de OpenAI.

### Fine-Tuning

El **Fine-Tuning** es una técnica de entrenamiento de modelos de lenguaje que nos permite mejorar el rendimiento de un modelo existente. En este caso, entrenamos un modelo para que pueda responder preguntas sobre cursos de Platzi.

### BatchAPI

La **BatchAPI** de OpenAI optimiza los costos y la eficiencia al procesar múltiples solicitudes de forma asincrónica. Ofrece un descuento del 50% en comparación con las solicitudes estándar, con la condición de que las respuestas se completen dentro de un plazo máximo de 24 horas. Esto es ideal para tareas que no requieren respuestas inmediatas.

### Assistants (Beta)

La funcionalidad de **Assistants** en OpenAI permite crear asistentes virtuales que interactúan con los modelos de lenguaje de forma distinta a la **ChatCompletion API**. Los asistentes soportan hilos de conversación persistentes y tienen la capacidad de integrar herramientas externas como **Code Interpreter** y **File Search**, lo que los hace ideales para casos de uso avanzados.

### Speech-to-Text y Text-to-Speech

1. **Speech-to-Text:** Para convertir voz en texto, OpenAI ofrece el modelo **Whisper**, diseñado para transcribir audio con alta precisión. Basta con proporcionar un archivo de audio para obtener la transcripción correspondiente en el idioma original.

2. **Text-to-Speech:** La funcionalidad de **TTS** permite transformar texto en voz sintetizada utilizando una amplia variedad de voces como `alloy`, `echo`, `fable`, `onyx`, `nova` y `shimmer`.
