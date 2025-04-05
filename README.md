🧠 Análisis de Sentimiento del Discurso de Javier Milei en Davos
Desde la Perspectiva del Público Estadounidense

📌 Descripción del Proyecto

Este proyecto tiene como objetivo inferir el grado de aceptación del discurso pronunciado por el presidente argentino Javier Milei en el Foro Económico Mundial de Davos, tomando como fuente más de 8.000 comentarios de usuarios estadounidenses en YouTube.

Se aplicó análisis de sentimiento automático utilizando el algoritmo VADER, especialmente diseñado para lenguaje informal en redes sociales. La elección del modelo se basó en su robustez frente a expresiones coloquiales, ironías y estructuras lingüísticas comunes en plataformas digitales.

🛠️ Tecnologías y Herramientas

    Python 3

    Pandas para el manejo de datos

    VADER (vaderSentiment) para el análisis de sentimiento

    Jupyter Notebook como entorno de desarrollo

    TQDM para seguimiento de procesos en tiempo real

📈 Metodología

    Recolección de Datos:
    Se extrajeron comentarios de un video en YouTube con el discurso completo del presidente Milei, filtrando los textos originados desde cuentas en Estados Unidos.

    Preprocesamiento:
    Limpieza básica del texto para evitar errores en el análisis de sentimiento.

    Clasificación de Sentimiento:
    Se utilizó el modelo VADER para etiquetar cada comentario como positivo, negativo o neutral.

    Visualización e Inferencia:
    Se graficó la distribución de opiniones y se calcularon porcentajes de apoyo general.

🔍 Principales Hallazgos

    La mayoría de los comentarios presentan un sentimiento positivo hacia el discurso.

    Se evidencia una alta recepción favorable por parte del público estadounidense.

    Esto sugiere una fuerte conexión del discurso con audiencias internacionales alineadas ideológicamente.

🎯 Propósito y Aplicabilidad

Este tipo de análisis permite:

    Evaluar el impacto internacional de discursos políticos sin recurrir a encuestas.

    Detectar patrones espontáneos de opinión pública.

    Comprender la percepción extranjera de líderes políticos en tiempo real.
