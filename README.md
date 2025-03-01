# Proyecto de Transformación de Lenguaje Natural a SQL

Este proyecto ha sido desarrollado como parte de la formación en la escuela [**KeepCoding**](https://keepcoding.io/), con el objetivo de construir una herramienta que transforme instrucciones en lenguaje natural a consultas SQL precisas y efectivas. A través de este proyecto, se busca facilitar la interacción con bases de datos logísticas de manera intuitiva.

## Descripción del Proyecto

El proyecto se estructura en las siguientes fases:

### 1. **Generación de Datos de Prueba (CSV)**
Se elaboran archivos CSV aleatorios que contienen información logística, como:
- **Referencias**
- **Pedidos de clientes**
- **Fechas de entrega**
- **Stock disponible**
- **Necesidades de producción**
- **Componentes y materiales**

Estos datos servirán como base para la construcción y validación de consultas SQL.

### 2. **Integración con el Modelo GPT-4o-mini de OpenAI**
Los archivos CSV generados se utilizan como contexto en el prompt de OpenAI (modelo GPT-4o-mini). Mediante esta integración, el modelo:
- **Interpreta** instrucciones en lenguaje natural.
- **Traduce** estas instrucciones a consultas SQL.
- **Ejecuta** las consultas y devuelve el **output** correspondiente.

### 3. **Siguientes Pasos: Fine-Tuning del Modelo SQL**
En la siguiente fase, se realizará el **fine-tuning** de un modelo especializado en SQL utilizando:
- El **dataset** visto en clase de **Hugging Face**.
- Las consultas SQL generadas y validadas con el modelo de OpenAI.

Este proceso permitirá mejorar la precisión y personalizar la generación de consultas SQL, adaptándolas a los datos específicos de la empresa.

## Requisitos
- **Python 3.8+**
- **Librerías**: `pandas`, `openai`, `sqlalchemy`
- **Cuenta de OpenAI** con acceso al modelo GPT-4o-mini
- **Conocimientos básicos** de SQL y Python


## Contribuciones
¡Las contribuciones son bienvenidas! Por favor, abre un **issue** o haz un **pull request** si deseas colaborar.

## Contacto
Para cualquier duda o sugerencia, no dudes en contactar conmigo o a través de la comunidad de **KeepCoding**.

---
Este proyecto es parte del aprendizaje y crecimiento dentro del programa de **KeepCoding**, enfocado en el desarrollo de habilidades avanzadas en **IA** y análisis de datos.

