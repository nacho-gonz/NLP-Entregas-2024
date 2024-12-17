# Instrucciones.

## Ejecución del código:

  Al Abrir el archivo `.ipynb` en Google Colab verá todos los títulos de diferentes partes del código, para el funcionamiento completo del código no es necesario ejecutar los conjuntos de bloques de celdas que esten bajo el título (NO ES NECESARIO EJECUTAR) 

## Keys

En el código encontrará un título así: `Clasificador con LLM (HUGGINGFACE_TOKEN O API_KEY)` en el primer bloque de código de este apartado encontrará una variable llamada: `api_key_hf`. El valor de esta variable esta asignado a un valor secreto de Google Colab, el cual tendra que crear en caso de no tener una `TOKEN` de `Hugging Face` o en caso de tener su TOKEN de Hugging Face ya en los secretos, pero con otro nombre de variable secreta, modifique el valor dentro de `userdata.get()` el cual esta por predeterminado como: `HUGGINGFACE_TOKEN`

## Recomendaciones

La mayoría de modelos utilizados estan pensados para ser ejecutados con CPU propia, excepto el agente el cual esta pensado para ser ejecutado con la GPU de prestamo de colab ya sea T4 o cualquiera de sus versiones.
