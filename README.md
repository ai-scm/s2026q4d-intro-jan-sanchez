# Assignment 1: consolidado semanal de inducción

Durante las primeras sesiones se realizó una introducción a la forma de trabajo de la empresa y a algunos conceptos técnicos relacionados con Houndoc, inteligencia artificial, búsqueda de información, levantamiento de requisitos, metodologías ágiles y control de versiones.

## Mapa de los temas vistos

![Mapa de introducción a Blend](Assignment/Blend%20introduction.drawio.svg)

## 1. Houndoc e inteligencia artificial

Houndoc se presentó como una plataforma que integra diferentes módulos y servicios. Dentro de su arquitectura se revisaron los siguientes conceptos:

- **LLM:** modelo de lenguaje capaz de comprender y generar texto.
- **Amazon Bedrock:** servicio que permite utilizar modelos fundacionales como Claude y otros modelos de lenguaje.
- **RAG:** técnica que complementa las respuestas del modelo con información obtenida desde documentos o fuentes de conocimiento.
- **Embeddings:** representaciones numéricas del contenido que permiten encontrar coincidencias semánticas según el contexto.
- **Transformers:** arquitectura utilizada por los modelos de lenguaje para procesar y relacionar la información.

También se habló del uso de cookies y proveedores de identidad, como Google, para administrar la autenticación y el acceso de los usuarios.

## 2. Indexación y búsqueda

Para consultar archivos y documentos es necesario indexar su contenido. Los índices pueden trabajar con información sin esquema definido o con una estructura previamente establecida.

Entre las tecnologías mencionadas se encuentran:

- **Elastic:** motor para almacenar, indexar y buscar información.
- **ELK:** conjunto formado por Elasticsearch, Logstash y Kibana para procesar, consultar y visualizar datos.
- **OpenSearch:** alternativa para la búsqueda y el análisis de información.
- **Solr y Lucene:** herramientas relacionadas con la indexación y la búsqueda de texto.

Este proceso permite que los documentos se conviertan en una fuente de conocimiento que pueda ser consultada por los diferentes módulos de la plataforma.

## 3. Modelo y levantamiento de requisitos

Antes de desarrollar una solución se debe entender el negocio y analizar la necesidad real del usuario. A partir de esta información se plantea la arquitectura, dando prioridad al problema que se quiere resolver y al valor entregado, no solamente al código.

Se revisaron los siguientes enfoques:

- **Domain-Driven Design (DDD):** organiza la solución a partir del dominio y las reglas del negocio.
- **Scrum:** metodología ágil para trabajar de forma iterativa y entregar valor continuamente.
- **SMART:** ayuda a definir objetivos específicos, medibles, alcanzables, relevantes y con un tiempo determinado.
- **Planning Poker:** técnica colaborativa para estimar el esfuerzo de las tareas.

La gestión de tareas y actividades se realiza con herramientas como **ClickUp** y **Calendar**.

## 4. Git y GitHub

Git y GitHub se utilizan para manejar, compartir y controlar los cambios realizados sobre el código. También se introdujo el uso de **Conventional Commits**, una convención para escribir mensajes de commit claros y útiles que permitan identificar fácilmente el propósito de cada cambio.