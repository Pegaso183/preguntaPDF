# Realiza una consulta a tu PDF (ChatGPT 3.5)

## Descripción
Aprovecha las posibilidades que ofrece ChatGPT y realiza consultas sobre cualquier documento PDF de manera interactiva.

## Algoritmo
1. Cargamos el documento PDF a tratar.
2. Dividimos el documento en Chunks (trozos de texto).
3. Creamos los Embeddings de los Chunks.
4. Guardamos los Chunks y los Embeddings en una base de conocimiento.
5. Buscamos los Chunks más similares semánticamente a la consulta del usuario.
6. Pasamos los Chunks seleccionados junto a la consulta a chatGPT 3.5 y recogemos su respuesta.

## Istalación y Uso
1. Clonar o descargar el repositorio en su máquina local.
2. Instalar las bibliotecas requeridas ejecutando el siguiente comando en su terminal:
```console
    pip install -r requirements.txt
```
4. Ejecutar la aplicación con el siguiente comando:
```console
    streamlit run app.py
```
5. Obtener una [clave API](https://platform.openai.com/api-keys) de OpenAI para usar su API ChatGPT.
6. Subir documento PDF a la aplicación.
7. Escribir consulta y visualizar la respuesta proporcionada por ChatGPT.
