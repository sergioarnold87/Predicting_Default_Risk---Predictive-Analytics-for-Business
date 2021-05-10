# Predicting Default Risk - Predictive Analytics for Business
 tercer proyecto del nanogrado de Udacity
 
 
Trabaja para un banco pequeño y es responsable de determinar si los clientes son solventes para otorgar un préstamo. Por lo general, su equipo recibe 200 solicitudes de préstamo por semana y las aprueba a mano.

Debido a un escándalo financiero que afectó a un banco competitivo la semana pasada, de repente tiene una afluencia de nuevas personas que solicitan préstamos para su banco en lugar del otro banco de su ciudad. ¡De repente, tiene casi 500 solicitudes de préstamos para procesar esta semana!

Su gerente ve esta nueva afluencia como una gran oportunidad y quiere que descubra cómo procesar todas estas solicitudes de préstamos en el plazo de una semana.

Afortunadamente para usted, acaba de completar un curso de modelado de clasificación y sabe cómo evaluar sistemáticamente la solvencia de estos nuevos solicitantes de préstamos.

Para este proyecto, analizará el problema comercial utilizando el marco de resolución de problemas y proporcionará una lista de clientes solventes a su gerente en los próximos dos días.

Tiene la siguiente información para trabajar:

Datos sobre todas las aplicaciones pasadas
La lista de clientes que deben procesarse en los próximos días.
Pasos hacia el éxito
Paso 1: Comprensión empresarial y de datos
Su proyecto debe incluir una descripción de las decisiones comerciales clave que deben tomarse.

Paso 2: Explore y limpie los datos
Para construir correctamente el modelo y seleccionar variables predictoras, necesita explorar y limpiar sus datos.

Aquí hay algunas pautas que lo ayudarán a limpiar los datos:

¿Alguno de sus campos de datos numéricos está altamente correlacionado entre sí? La correlación debe ser de al menos .70 para ser considerada "alta".
¿Faltan datos para cada uno de los campos de datos? Los campos con muchos datos faltantes deben eliminarse
¿Hay solo unos pocos valores en un subconjunto de su campo de datos? ¿El campo de datos se ve muy uniforme (solo hay un valor para todo el campo?). Esto se denomina "variabilidad baja" y debe eliminar los campos que tengan una variabilidad baja. Consulte la sección "Sugerencias" para encontrar ejemplos de campos de datos con baja variabilidad.
Su conjunto de datos limpios debe tener 13 columnas donde el promedio de Age Yearsdebe ser 36 (redondeado)
Nota: Si decide imputar cualquier campo de datos, en aras de la coherencia en el proceso de limpieza de datos, impute los datos utilizando la mediana de todo el campo de datos.

Paso 3. Entrene sus modelos de clasificación
Debe elegir el 70% para crear el conjunto de estimación y el 30% para crear el conjunto de validación. Establezca Random Seed en 1 si está usando Alteryx.

Entrene su conjunto de datos con estos modelos:

Regresión logística
Árbol de decisión
Modelo forestal
Árbol potenciado
Paso 4. Redacción
Compare el rendimiento de todos los modelos entre sí. Decide cuál es el mejor modelo y puntúa a tus nuevos clientes.

Importante : Su gerente solo se preocupa por la precisión con la que puede identificar a las personas que califican y no califican para préstamos para este problema.

Escriba un breve informe sobre cómo se le ocurrió su modelo de clasificación y anote cuántos de los nuevos clientes calificarían para un préstamo.
