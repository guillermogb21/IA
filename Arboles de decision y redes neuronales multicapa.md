1.  Un árbol de decisión es una estructura gigante de sentencias if-else anidadas que el algoritmo construye por si solo. Su objetivo
en un problema de clasificación es tomar un conjunto de datos desordenados y encontrar las reglas lógicas mas eficientes para
dividirlo

2.
Nodo raíz:Es la entrada de la estructura. Es la primera vacacional, el if inicial para dividir los datos basándose en la variable
que aporta mayor información
Nodo interno: Son las validaciones intermedias osea else-if. Reciben datos que ya pasaron por un filtro previo y los vuelven a
evaluar con otra condición para seguir refinando la clasificación
Rama: Es un flujo lógico de ejecución que se toma cuando se evalúa una condición
Hoja: Es el return final de la función o el endpoint de destino

3.
Una red neuronal multicapa es un modelo matemático inspirado en el cerebro humano
Capa de entrada: Son los sentido de la red. Su única función es recibir la información del mundo exterior y meterla al cerebro
del sistema
Capa oculta: Es el cerebro pensando. Son capas internas donde las neuronas se pasan la información unas a otras buscando
patrones ocultos, formas o detalles que te ayuden a entender lo que estás viendo
Capa de salida: Es la voz de la red. Es la neurona final que te da la conclusión o su mejor suposición

4.
Los pesos determinan el nivel de prioridad o influencia que tiene una coneccion entre dos neuronas
Los sesgos son valores de compensacion. Aseguran que la neurona pueda activarse incluso si las señales de entrada son nulas
dándoles flexibilidad al modelo
La  red aprende de sus errores. Al principio, la red intenta adivinar una respuesta y se equivoca Va ajustando esos pesos
y sesgos poco a poco, repitiendo el proceso miles de veces, hasta que afina su puntería y deja de equivocarse

5.
La diferencia es cómo toman decisiones y qué tan transparentes son
El árbol de decisión aprende creando reglas claras. Es transparente
La red neuronal aprende ajustando miles de conexiones matemáticas. Es una caja negra. Es muchísimo más poderosa y puede
reconocer cosas complejas como caras o voces

6.
Árbol de decisión
Ventajas: Es fácil entender por qué se bloqueó una tarjeta
Desventajas: Los estafadores son creativos y cambian sus tácticas constantemente. Un árbol de decisión es rígido
si los ladrones encuentran una combinación que el árbol no tiene contemplada el sistema fallara

Red neuronal multicapa
Ventajas: Es excelente para encontrar patrones invisibles o comportamientos extraños que a un humano se le pasarían por alto
Desventajas: Si bloquea la tarjeta de un cliente legítimo, el banco no sabrá exactamente por qué lo hizo, lo que puede generar 
una mala experiencia de atención al cliente.
Utilizaría la red neuronal. En el fraude financiero, el comportamiento criminal es extremadamente complejo y cambia rápido. 
La prioridad número uno del banco es detener la pérdida de dinero y proteger al usuario de inmediato, y la red neuronal es 
mucho más capaz de detectar esos fraudes sutiles, aunque cueste un poco más explicar el bloqueo por teléfono al cliente

7.
Si ambos modelos obtienen la misma precisión, elegiría sin dudarlo el árbol de decisión
Los factores decisivos aquí son la transparencia y la capacidad de acción. El objetivo de este sistema no es solo adivinar
quién va a reprobar, sino intervenir para ayudarlo
Con un árbol de decisión, puedes llamar al estudiante o a sus padres y decirles: El sistema indica riesgo porque tienes 3 faltas
y no entregaste las últimas 2 tareas. Esto te permite crear un plan de estudio personalizado para salvar su semestre
Con una red neuronal, solo sabrías que hay riesgo, pero no sabrías qué aconsejarle al alumno para que mejore, 
haciendo que la predicción sea inútil en la práctica

8.
No, la mayor precisión matemática no es suficiente para elegir la red neuronal a ciegas en un entorno médico.
En la salud, las decisiones son de vida o muerte y la responsabilidad legal y ética recae en el médico, no en la máquina
Consecuencias de esta decisión:
Pérdida de confianza y riesgo médico: Si la red neuronal decide que un paciente con dolor de pecho leve puede esperar,
pero el médico intuye que es un pre-infarto, el médico no tiene forma de revisar la lógica de la máquina para ver si se le
escapó algo
Sesgos ocultos: La red neuronal podría haber aprendido cosas incorrectas de los datos históricos
Como es una caja negra, el hospital no se daría cuenta del error hasta que haya consecuencias fatales
En medicina, el sistema debe ser un apoyo para el médico, y si el médico no puede entender el razonamiento de la máquina
no puede confiar en ella

9.
Para determinar cuál modelo tiene la razón en ese momento específico, no puedes confiar solo en la predicción final
Debes analizar el por qué y el contexto evaluando esta información adicional:
Revisar la lógica del árbol: Como el árbol es transparente, puedes ver qué camino tomó
Buscar variables inusuales: Las redes neuronales son mejores conectando múltiples factores complejos
Historial de éxito: Miraría cuál de los dos modelos ha acertado más veces en el pasado cuando se enfrentan a condiciones climáticas
o de tráfico similares a las de ese pedido en particular

10.
Utilizaría ambos modelos trabajando en equipo dentro del mismo sistema osea un enfoque híbrido
Puedes usar la red neuronal como el motor principal para tomar la decisión, ya que garantizará que el banco gane más dinero al
predecir mejor quién sí pagará y quién no. Sin embargo, por ley, en muchos países los bancos están obligados a explicarle a un
cliente por qué se le negó un crédito
Ahí entra el árbol de decisión: se puede entrenar un árbol en paralelo para que observe las decisiones de la red y genere una
explicación en lenguaje claro que se le pueda entregar al cliente
El unico riesgo es que mantener dos sistemas es más caro, requiere más poder de computación y el equipo de desarrollo debe
asegurarse de que el árbol de explicación no se desincronice demasiado de la decisión real que tomó la red neuronal

No existe un algoritmo perfecto para todo
La afirmación es completamente cierta porque cada problema en la vida real exige un equilibrio distinto entre diferentes necesidades
Complejidad del problema y Cantidad de datos: Si tienes un problema enorme, con millones de fotos, audios o historiales de
transacciones complejas, necesitas un modelo robusto como una red neuronal que pueda digerir esa masiva cantidad de datos y
encontrar el hilo conductor. Un árbol colapsaría
Interpretabilidad y Consecuencias: Por el contrario, si las consecuencias de equivocarse implican arruinarle la vida a un 
estudiante, negarle un tratamiento a un paciente o cometer un acto de discriminación ilegal, necesitas interpretabilidad 
Prefieres sacrificar un poco de precisión a cambio de poder entender, auditar y justificar la decisión con un modelo más simple
