# https://python.langchain.com/docs/modules/model_io/models/llms/integrations/openai
# langchaing, modelos(de lenguaje y de chat) word2ved(corpus nube de palabras),onehotcoder(transformar variables categoricas a 1 - 0), embed(representacion vectorial), LLMs vs Chat Models, transformer vs redes neuronales 
# vector de (5,1536)
# stuf permite alojar documentos pequeños, y obtiene el contexto concatena el promt y documentos en una estructura llamada template 
# Refine varios pdf, itera entre el promt y el documento, genera una respuesta parcial (informacion compactada) no se puede obtener datos especificos
# Map reduce resume la informacion, crea vaarios documentos y despues lo concatena al promt 
# map re-rank enviar el promt y el contexto y le asigna scores, el score mas alto asigna la respuesta correcta
# chroma almacen de embeddings 
# tiktoken libreria de openai que permite transformar el texto a ...
# RLHF aprendizaje reforzado por feedback humano, durante el entrenamiento genera 4 respuestas y las personas califican esas respuestas segun la mas correcta
# fastapi, cliente y 
# al app de la prueba integrar lo de erick
