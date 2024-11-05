# Dr Potasio, supongo?
## Autores: 
Ignacio Martínez Soriano, Manuel A. Belda Palazón 

## Presentador: 
Ignacio Martínez Soriano 

## Abstract: 
En cualquier administración pública o privada y especialmente en el ámbito sanitario, el poder consultar el contenido de la documentación interna generada por la propia entidad de una manera rápida, eficaz y segura, se ha convertido en una necesidad principal y clave para la buena gestión. 
Se hace necesario la utilización de herramientas que proporcionen dicha información detallada, ordenada y resumida.  
Para alcanzar dicho objetivo hemos desarrollado un asistente virtual “Dr. Potasio (K)”, que nos permite buscar internamente en nuestros documentos, con la premisa de hacerlo en local sin sacar datos al exterior. 
El enfoque aplicado ha sido la utilización de un sistema de recuperación aumentada generativa (RAG)[1], utilizando modelos de lenguaje (LLM) open source. 
La metodología aplicada ha sido la siguiente: 
Fuente de datos: Documentos en formato texto y pdf, de distintos servicios de la organización.  
Para orquestar la implementación se ha utilizado el framework de Langchain[2].  
Modelo de lenguaje utilizado: LLAMA2 en formato cuantificado del repositorio de Huggingface[3].  
La base de datos vectorial, Chroma[4] y la interface de usuario mediante streamlit[5]. 
Las respuestas obtenidas por el sistema (RAG) nos proporcionan información ordenada y coherente sobre los documentos almacenados de carácter médico o administrativo de forma precisa y contextualmente relevante. 

## REFERENCIAS BIBLIOGRAFICAS 
[1] Patrick Lewis et al. Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks. NeurIPS 2020. 
[2] https://python.langchain.com/docs/get_started/introduction 
[3] https://huggingface.co/MBZUAI/LaMini-T5-738M 
[4] https://python.langchain.com/docs/integrations/vectorstores/chroma/ 
[5] https://streamlit.io/ 
