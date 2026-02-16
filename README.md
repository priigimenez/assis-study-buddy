# Assis: el refuerzo para no quedarse atrás en la cursada 🎓🇦🇷

Assis es un tutor inteligente diseñado para cerrar la brecha entre los temas complejos de la cursada de Data Science y la comprensión real del estudiante. 
No es solo un chatbot; es un compañero de estudio que "traduce" tecnicismos a lenguaje claro.

## Intro: el problema a abordar
Muchos estudiantes de Data Science sufren de **infoxicación**. Entre herramientas y librerías, los fundamentos (como la estadística) suelen quedar en segundo plano. Assis ataca este problema ofreciendo un refuerzo paralelo, enfocado y fácil de digerir.

## Tecnologías y herramientas
* **Modelo de IA:** Gemini 2.5 Flash (Google).
* **Técnicas de Prompting:** * *System Instruction* para definición de personalidad.
    * *Few-Shot Prompting* para estandarizar el formato de respuesta.
    * *Chain of Thought* para razonamiento pedagógico.
* **Entorno:** Google Colab / Python.

## Metodología (Fast Prompting) 🧠
Para optimizar costos y eficiencia, este proyecto implementa:
1.  **Sesión de Chat Continua:** Evita reenviar el prompt de sistema en cada consulta, ahorrando tokens.
2.  **Estructura de Respuesta Atómica:** (Analogía -> Uso en DS -> Check-point) para asegurar que el aprendizaje sea activo y no pasivo.
3.  **Bajo Latencia:** El uso del modelo 'Flash' garantiza respuestas instantáneas.

## Contenido del repo 📂
* `assis_v1_borrador.ipynb`: Primera aproximación al asistente.
* `assis_v2_poc_optimizada.ipynb`: Prueba de concepto (POC) con técnicas de Fast Prompting y manejo de sesión.
