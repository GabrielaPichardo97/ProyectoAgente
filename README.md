# ProyectoAgente

Plataforma adaptativa de aprendizaje técnico enfocada en llevar a una persona desde los fundamentos necesarios de programación, matemáticas, estadística, datos, machine learning, deep learning, arquitectura de software, cloud y MLOps hasta la capacidad de **diseñar, construir, evaluar, desplegar y orquestar agentes de IA de forma correcta**.

El objetivo no es construir solamente un chatbot que responda preguntas, sino una experiencia de aprendizaje continua, personalizada y medible, inspirada en la dinámica de productos como Duolingo: rutas progresivas, sesiones cortas, progreso visible, práctica, repaso, repetición espaciada y adaptación al nivel real de cada persona.

---

## 1. Visión del producto

Crear una plataforma de aprendizaje que ayude a responder no solo **“¿cómo hago esto?”**, sino también:

- ¿Qué necesito aprender antes?
- ¿Por qué funciona?
- ¿Qué sucede internamente?
- ¿Cuándo debo usar esta herramienta, técnica o arquitectura?
- ¿Cuándo no debo usarla?
- ¿Qué alternativa sería mejor?
- ¿Cómo se implementa correctamente?
- ¿Cómo se prueba?
- ¿Cómo se despliega?
- ¿Cómo sé si realmente entendí?

El objetivo final de aprendizaje es que una persona pueda tomar decisiones técnicas con criterio y sea capaz de construir sistemas reales de IA y agentes, en lugar de limitarse a copiar código o seguir tutoriales.

---

## 2. Principio pedagógico

Cada concepto debe enseñarse progresivamente, desde la intuición hasta la aplicación profesional.

### Estructura base de una lección

1. **Explícamelo como si tuviera 5 años** — explicación extremadamente sencilla, con analogías cotidianas.
2. **Definición formal** — la definición técnica correcta del concepto.
3. **¿Qué hay detrás?** — explicación detallada de cómo funciona internamente, sus componentes, supuestos y mecanismos.
4. **Ejemplo sencillo** — un ejemplo mínimo que permita entender la idea sin ruido adicional.
5. **Caso de uso real** — un escenario donde el concepto se utilizaría profesionalmente.
6. **Cuándo usarlo** — señales que indican que esa técnica, patrón o herramienta es apropiada.
7. **Cuándo NO usarlo** — limitaciones, riesgos, costos y alternativas.
8. **Ejemplo técnico o código**, cuando aplique.
9. **Errores comunes** — confusiones frecuentes y malas prácticas.
10. **Comprobación de comprensión** — la evaluación puede ser elegida por el estudiante.

---

## 3. Usuarios

La plataforma está diseñada para múltiples personas.

Cada usuario tendrá un perfil de aprendizaje independiente con información como:

- nivel por área;
- conceptos dominados;
- conceptos en progreso;
- conceptos con dificultad;
- historial de sesiones;
- resultados de evaluaciones;
- modalidad de evaluación preferida;
- proyectos realizados;
- objetivos de aprendizaje;
- temas pendientes de repaso;
- actividad reciente;
- ritmo de aprendizaje.

El nivel no será global. Una persona puede ser, por ejemplo:

```text
Python                   -> Intermedio
Estadística              -> Principiante
Machine Learning         -> Intermedio
Arquitectura de software -> Principiante
Git                      -> Intermedio
Agentes                  -> Principiante
```

---

## 4. Objetivo final de aprendizaje

La plataforma debe llevar progresivamente al estudiante hasta poder:

- entender qué es un agente y qué no lo es;
- construir agentes con herramientas;
- diseñar memoria de corto y largo plazo;
- usar recuperación de información y RAG;
- diseñar contratos entre agentes;
- implementar guardrails;
- evaluar agentes;
- decidir entre workflows determinísticos y agentes;
- construir sistemas multiagente;
- orquestar agentes;
- manejar estado;
- decidir cuándo utilizar un agente, una función, un workflow, una API o un modelo tradicional;
- desplegar sistemas de IA;
- monitorearlos;
- versionarlos;
- evaluar costo, calidad y latencia;
- trabajar profesionalmente con Git y GitHub.

---

## 5. Ruta de aprendizaje inicial

La ruta completa será representada como un grafo de conocimientos. Un concepto podrá tener prerrequisitos y desbloquear nuevos temas.

### Módulo 0 — Fundamentos digitales
- terminal, archivos y directorios;
- procesos y variables de entorno;
- HTTP, cliente/servidor, APIs y JSON;
- conceptos básicos de sistemas operativos.

### Módulo 1 — Programación
- lógica de programación;
- variables, tipos de datos, condicionales y ciclos;
- funciones y estructuras de datos;
- excepciones, módulos y paquetes;
- orientación a objetos;
- programación funcional básica;
- testing y debugging;
- complejidad algorítmica.

Lenguaje principal inicial: **Python**.

### Módulo 2 — Git y GitHub
Git será una competencia transversal durante todo el programa, no una lección aislada.

- repositorios, commits y staging;
- branches, merge, rebase y conflictos;
- tags y versionado semántico;
- pull requests y code review;
- conventional commits;
- GitFlow y trunk-based development;
- GitHub Issues;
- GitHub Actions.

### Módulo 3 — Matemáticas
- aritmética relevante para IA;
- funciones y álgebra;
- vectores, matrices y álgebra lineal;
- derivadas, gradientes y optimización;
- nociones de cálculo multivariable.

La matemática debe enseñarse vinculada a problemas reales de IA, no solo como teoría aislada.

### Módulo 4 — Probabilidad y estadística
- estadística descriptiva;
- distribuciones y probabilidad;
- probabilidad condicional y Bayes;
- muestreo y estimadores;
- intervalos de confianza y pruebas de hipótesis;
- correlación y regresión;
- sesgo, varianza y experimentación.

### Módulo 5 — Datos
- SQL y modelado de datos;
- ETL / ELT;
- limpieza y calidad de datos;
- Pandas / Polars;
- CSV, JSON y Parquet;
- data warehouses;
- feature engineering.

### Módulo 6 — Machine Learning
- aprendizaje supervisado y no supervisado;
- regresión y clasificación;
- árboles y ensembles;
- clustering;
- reducción de dimensionalidad;
- selección de variables;
- métricas y validación;
- leakage;
- interpretabilidad;
- tuning;
- diseño experimental de modelos.

### Módulo 7 — Deep Learning
- neuronas artificiales y perceptrón;
- redes neuronales;
- funciones de activación;
- backpropagation;
- optimizadores y regularización;
- embeddings;
- CNN y RNN;
- atención y Transformers.

### Módulo 8 — Inteligencia Artificial Generativa
- modelos de lenguaje;
- tokenización, embeddings y contexto;
- inferencia y temperatura;
- prompting;
- structured outputs;
- function calling;
- evaluación;
- alucinaciones y seguridad;
- costos y latencia.

### Módulo 9 — Ingeniería de software
- clean code y SOLID;
- testing;
- design patterns;
- arquitectura por capas;
- dependency injection;
- configuración;
- observabilidad y logging;
- manejo de errores;
- contratos y documentación;
- APIs robustas.

### Módulo 10 — Arquitectura de software y sistemas
- monolitos, servicios y microservicios;
- eventos y colas;
- caché;
- consistencia y disponibilidad;
- escalabilidad y tolerancia a fallos;
- bases de datos SQL y NoSQL;
- diseño de sistemas;
- arquitectura cloud.

### Módulo 11 — MLOps
- experiment tracking;
- versionado de datos y modelos;
- pipelines;
- MLflow y DVC;
- Docker;
- CI/CD;
- model registry;
- feature stores;
- monitoreo y drift;
- reproducibilidad;
- despliegues batch y online.

### Módulo 12 — Cloud
- conceptos de nube;
- IAM;
- compute, storage y networking;
- containers y serverless;
- bases administradas;
- observabilidad, costos y seguridad;
- despliegues en GCP y otros proveedores.

### Módulo 13 — RAG y sistemas de conocimiento
- embeddings y chunking;
- recuperación, ranking y reranking;
- vector databases;
- filtros y metadatos;
- grounding y citas;
- evaluación de RAG;
- actualización del conocimiento.

### Módulo 14 — Agentes de IA
- definición de agente;
- modelo + instrucciones + tools;
- estado y memoria;
- planificación y ejecución;
- function calling;
- herramientas;
- guardrails;
- structured outputs;
- human-in-the-loop;
- evaluación de agentes.

### Módulo 15 — Orquestación y sistemas multiagente
- workflows determinísticos;
- agentes autónomos;
- routers, planners y handoffs;
- supervisores;
- coordinación entre agentes;
- contratos entre agentes;
- manejo de errores y retries;
- idempotencia;
- persistencia de estado;
- tracing;
- evaluación end-to-end.

### Módulo 16 — Producción de agentes
- APIs, autenticación y autorización;
- rate limiting;
- colas;
- observabilidad y tracing;
- evaluación continua;
- seguridad;
- costos y caching;
- despliegue y escalamiento;
- monitoreo;
- CI/CD.

---

## 6. Grafo de conocimientos

La plataforma no debe tratar el contenido como una lista lineal rígida.

Cada concepto será un nodo con prerrequisitos y conceptos que desbloquea.

```text
Concepto: Embeddings

Prerrequisitos:
- vectores
- similitud coseno
- representación numérica

Desbloquea:
- búsqueda semántica
- vector databases
- RAG
- memoria semántica de agentes
```

Esto permitirá construir rutas diferentes dependiendo del objetivo y conocimiento previo del estudiante.

---

## 7. Diagnóstico de nivel

Antes de crear una ruta personalizada, el sistema podrá evaluar al usuario mediante una combinación de:

- preguntas conceptuales;
- ejemplos;
- ejercicios;
- código;
- autoevaluación;
- explicación con sus propias palabras.

El diagnóstico será adaptativo: una respuesta puede aumentar o disminuir rápidamente la dificultad de las siguientes preguntas.

El objetivo no es asignar solo una etiqueta, sino construir un **mapa inicial de conocimientos**.

---

## 8. Evaluación personalizada

Cada persona podrá seleccionar cómo desea ser evaluada.

Opciones iniciales:

- preguntas de opción múltiple;
- preguntas abiertas;
- explicar el concepto con sus propias palabras;
- completar código;
- corregir código con errores;
- resolver un caso práctico;
- enseñar el concepto a otra persona;
- mini proyecto.

El sistema podrá recomendar una modalidad distinta cuando considere que una evaluación no demuestra suficientemente el dominio del concepto.

---

## 9. Modelo de dominio de aprendizaje

Cada concepto tendrá un estado para cada usuario.

```text
NO_INICIADO
EN_APRENDIZAJE
PRACTICANDO
DOMINADO
NECESITA_REPASO
```

Además podrá existir un score de dominio calculado a partir de señales como:

- evaluaciones;
- número de intentos;
- ayudas utilizadas;
- tiempo desde la última práctica;
- capacidad de explicar el concepto;
- aplicación en proyectos;
- consistencia de respuestas.

No se utilizará únicamente una calificación de examen.

---

## 10. Repetición espaciada

La plataforma programará repasos de acuerdo con:

- dificultad del concepto;
- desempeño histórico;
- tiempo desde la última interacción;
- importancia del concepto para la ruta actual;
- errores recientes.

Ejemplo:

> Hace varios días estudiaste Dependency Injection y tuviste dificultad diferenciándola de Dependency Inversion. Antes de continuar con arquitectura por capas, conviene hacer un repaso corto.

---

## 11. Proyectos prácticos

La plataforma generará proyectos progresivos que integren lo aprendido.

```text
Nivel inicial
-> Crear una función en Python.

Nivel intermedio
-> Construir una API con FastAPI.

ML
-> Entrenar, evaluar y versionar un modelo.

MLOps
-> Dockerizar y desplegar el modelo.

RAG
-> Construir un buscador semántico sobre documentos.

Agentes
-> Construir un agente con tools y memoria.

Multiagente
-> Diseñar un sistema con router, especialista y evaluador.
```

Los proyectos se desarrollarán utilizando Git para reforzar buenas prácticas de ingeniería.

---

## 12. Material proporcionado por el estudiante

El usuario podrá subir material propio como complemento:

- PDFs;
- apuntes;
- documentación;
- notebooks;
- código;
- presentaciones;
- artículos;
- material de cursos.

El sistema deberá distinguir claramente entre:

1. contenido oficial de la plataforma;
2. fuentes externas recuperadas;
3. material proporcionado por el usuario;
4. explicaciones generadas por el modelo.

---

## 13. Contenido actualizado recurrentemente

El producto debe poder actualizar sus contenidos de manera continua.

### Conocimiento estable
Fundamentos cuyo significado cambia muy poco, por ejemplo:
- álgebra;
- probabilidad;
- estructuras de datos;
- redes neuronales;
- patrones de diseño;
- conceptos de sistemas distribuidos.

### Conocimiento dinámico
Contenido que puede cambiar con rapidez, por ejemplo:
- frameworks;
- SDKs;
- APIs;
- modelos disponibles;
- precios;
- características de servicios cloud;
- herramientas de agentes;
- librerías;
- mejores prácticas recientes.

El contenido dinámico deberá registrar:

- fuente;
- fecha de consulta;
- fecha de actualización;
- nivel de confianza;
- versión de la herramienta cuando aplique.

---

## 14. Política contra alucinaciones

> Si el sistema no dispone de evidencia suficiente para responder con confianza, debe decirlo explícitamente. Nunca debe inventar información para completar una respuesta.

La plataforma deberá:

- utilizar fuentes confiables;
- citar contenido recuperado cuando corresponda;
- diferenciar hechos de interpretaciones;
- no inventar bibliografía;
- no inventar APIs ni funciones de librerías;
- no inventar resultados;
- no afirmar que un documento contiene algo que no fue recuperado;
- indicar incertidumbre;
- buscar o pedir evidencia adicional cuando sea necesario.

---

## 15. Fuentes confiables

El sistema priorizará:

1. documentación oficial;
2. papers originales;
3. libros de referencia;
4. universidades y centros de investigación;
5. documentación técnica del proveedor;
6. fuentes secundarias reconocidas.

Blogs, foros y contenido comunitario pueden ser útiles como complemento, pero no deben reemplazar evidencia primaria para afirmaciones técnicas importantes.

---

## 16. Experiencia tipo Duolingo

La experiencia debe fomentar constancia sin sacrificar profundidad técnica.

Características deseadas:

- sesiones cortas;
- progreso visible;
- rutas por módulos;
- niveles;
- unidades;
- lecciones;
- proyectos;
- repasos;
- streak opcional;
- metas semanales;
- recomendaciones personalizadas;
- pequeñas victorias;
- feedback inmediato;
- explicación después de una respuesta incorrecta.

La gamificación nunca debe sustituir el aprendizaje real.

---

## 17. Flujo principal del producto

```text
Usuario
  ↓
Define objetivo
  ↓
Diagnóstico adaptativo
  ↓
Mapa de conocimientos
  ↓
Ruta personalizada
  ↓
Lección
  ↓
Práctica
  ↓
Evaluación elegida
  ↓
Actualización del dominio
  ↓
¿Continuar, reforzar o repasar?
  ↓
Siguiente actividad
```

---

## 18. Componentes funcionales esperados

La solución probablemente evolucionará hacia componentes como:

```text
Learning Path Engine
Tutor Engine
Assessment Engine
Knowledge Graph
Progress Engine
Spaced Repetition Engine
Content Engine
Source Verification Engine
RAG Engine
Project Generator
User Profile
Agent Runtime
Observability
```

Estos nombres representan responsabilidades y no implican necesariamente microservicios independientes.

---

## 19. Arquitectura técnica inicial

El producto debe comenzar simple, pero permitir crecimiento.

```text
Web App
   ↓
API Backend
   ↓
Application Layer
   ├── Learning Engine
   ├── Tutor
   ├── Assessment
   ├── Progress
   ├── Content
   └── Agent Runtime
   ↓
Data Layer
   ├── PostgreSQL
   ├── pgvector
   └── Object Storage
   ↓
External Services
   ├── LLM providers
   ├── trusted sources
   └── observability
```

### Stack candidato

**Frontend**
- Next.js / React

**Backend**
- Python
- FastAPI
- Pydantic

**Persistencia**
- PostgreSQL
- pgvector inicialmente para evitar introducir otra base de datos antes de necesitarla

**Contenido y archivos**
- almacenamiento de objetos compatible con cloud

**IA**
- abstracción de proveedores de LLM;
- structured outputs;
- tool calling;
- RAG;
- evaluación automática + reglas determinísticas.

**DevOps**
- Docker;
- GitHub Actions;
- infraestructura como código en etapas posteriores;
- despliegue cloud.

La primera versión puede desarrollarse como un **monolito modular bien estructurado** y dividir componentes únicamente cuando existan razones reales de escalabilidad, dominio u operación.

---

## 20. Aprender ingeniería de agentes construyendo la plataforma

Una meta adicional del proyecto es aprender cómo funcionan los agentes en lugar de ocultar toda la complejidad detrás de un framework.

Inicialmente se priorizará comprender e implementar:

- state;
- tools;
- planning;
- memory;
- routing;
- contracts;
- retries;
- evaluation;
- tracing;
- guardrails.

Frameworks de agentes como LangGraph u otros podrán utilizarse posteriormente cuando aporten una ventaja clara y después de comprender los mecanismos que abstraen.

---

## 21. Principios de ingeniería

1. **No inventar conocimiento.**
2. **Fuente antes que confianza aparente.**
3. **Explicar primero simple y luego profundo.**
4. **Aprender haciendo.**
5. **Medir dominio, no solamente completar lecciones.**
6. **Adaptar la ruta a cada usuario.**
7. **Git como parte del aprendizaje.**
8. **Arquitectura simple antes que arquitectura compleja.**
9. **Contratos explícitos entre componentes.**
10. **Observabilidad desde etapas tempranas.**
11. **Evaluar la calidad de las respuestas del agente.**
12. **Separar conocimiento estable de conocimiento dinámico.**
13. **Diseñar componentes extensibles para agregar nuevas áreas de estudio.**

---

## 22. MVP propuesto

La primera versión no intentará construir toda la plataforma. Debe demostrar el ciclo central de aprendizaje.

### El usuario puede

1. crear una cuenta;
2. seleccionar un objetivo de aprendizaje;
3. realizar un diagnóstico corto;
4. recibir una ruta personalizada;
5. estudiar una lección;
6. recibir la explicación en los cuatro niveles base:
   - como para 5 años;
   - definición formal;
   - qué hay detrás;
   - caso de uso;
7. realizar una evaluación;
8. guardar su progreso;
9. recibir una recomendación de la siguiente actividad;
10. visualizar qué conceptos domina y cuáles necesita reforzar.

### Primer vertical sugerido para el MVP

```text
Python básico
   ↓
Funciones
   ↓
APIs
   ↓
LLMs
   ↓
Tool Calling
   ↓
Primer agente
```

Esta ruta permitiría validar la arquitectura pedagógica completa antes de escalar el contenido.

---

## 23. Evolución posterior al MVP

### Fase 1 — Learning Core
- usuarios;
- diagnóstico;
- rutas;
- lecciones;
- evaluaciones;
- progreso.

### Fase 2 — Adaptive Learning
- knowledge graph;
- score de dominio;
- repetición espaciada;
- recomendaciones.

### Fase 3 — Knowledge Platform
- carga de documentos;
- RAG;
- citas;
- pipeline de fuentes;
- actualización de contenido.

### Fase 4 — Projects & Coding
- ejercicios de programación;
- validación automática;
- proyectos;
- integración con GitHub.

### Fase 5 — Agent Learning Platform
- agentes especializados;
- tool usage;
- evaluadores;
- generación dinámica de actividades;
- orquestación.

### Fase 6 — Escala
- observabilidad avanzada;
- colas;
- jobs asíncronos;
- caching;
- multi-provider LLM;
- optimización de costos;
- escalamiento horizontal.

---

## 24. Métricas de éxito

La plataforma no deberá optimizar únicamente el tiempo dentro de la aplicación.

Métricas relevantes:

- porcentaje de conceptos realmente dominados;
- retención después de 7, 30 y 90 días;
- disminución de errores después de repasos;
- progreso dentro de una ruta;
- proyectos completados;
- capacidad de explicar conceptos sin ayuda;
- capacidad de aplicar conceptos en nuevos casos;
- frecuencia de estudio;
- abandono por módulo;
- efectividad de cada tipo de evaluación.

---

## 25. North Star

> Una persona entra diciendo “quiero aprender a construir agentes” y la plataforma es capaz de descubrir qué sabe, identificar qué le falta, construir una ruta personalizada, enseñarle cada concepto desde una explicación extremadamente sencilla hasta su fundamento técnico, hacerla practicar, verificar que realmente aprendió y acompañarla hasta construir y desplegar sistemas de agentes reales con criterio de ingeniería.

---

## Estado del proyecto

**Etapa:** definición de producto y arquitectura inicial.

Próximos pasos:

- definir PRD;
- diseñar el knowledge graph inicial;
- definir contratos de contenido y evaluación;
- definir modelo de datos;
- diseñar arquitectura del repositorio;
- definir MVP técnico;
- crear backlog inicial;
- construir el primer vertical slice end-to-end.
