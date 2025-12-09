# Texto completo de foro de desarrollo del indicador csDash
csDash (medidor de fortaleza monetaria)
https://www.forexfactory.com/thread/537107-csdash-currency-strength-meter

P1
 26 de abril de 2015, 7:28 a. m. | Editado el 26 de diciembre de 2020, 12:35 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Última versión: 1.31

---------------------------------------------------------
Existe una hoja de cálculo de Excel bastante conocida que utiliza las capacidades DDE de MT4 para calcular la fortaleza de la divisa mediante una fórmula basada en el máximo de D1, el mínimo de D1 y la oferta:

Como una derivación de un proyecto diferente en el que estoy trabajando, la he portado a MT4.

Es un indicador EA simple que debería replicar los resultados de la hoja de cálculo de Excel. Tiene algunas otras mejoras (alertas, capacidad para seleccionar otros marcos temporales para el cálculo, clic para abrir con plantilla aplicada para cada par), pero en general es algo relativamente simple. Estoy creando un hilo aquí porque: 1. Algunos sistemas diferentes en FF usan el medidor de fortaleza de la divisa, por lo que tiene más sentido tener un solo hilo para ello; y 2. Evita desviarse del tema en esos hilos. Tenga en cuenta: es un EA (no comercial), por lo que debe colocarlo en la carpeta de Expertos. Información de fondo y preguntas respondidas. Primera publicación Mensajes de advertencia / Pares faltantes Alertas y espera

Imagen(es) adjunta(s) (haga clic para ampliar)
Haga clic para ampliar Nombre: dashboard.png Tamaño: 38 KB
Haga clic para ampliar Nombre: spreadsheet.png Tamaño: 68 KB
2
Cita
26 de abril de 2015, 7:43 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Tenga en cuenta: no estoy pensando en hacer mucho desarrollo en esta versión porque mi enfoque principal está en una versión MTF (aún no está lista):
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: #.png Tamaño: 151 KB
2
3
Cita
26 de abril de 2015, 8:59 a. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Hola,

acabo de encontrar esto y le eché un vistazo rápido.
Se ve genial.
Lo revisaré en vivo la semana que viene.
¿Quizás podrías considerar hacerlo compatible con x/y simples si trabajas en ello de nuevo? ¡
Gracias por compartir!
¡¡¡No te limites!!!
4
Cita
26 de abril de 2015, 10:09 a. m.
 chaveznqoosSe unió en junio de 2006 | Estado: Comerciante | 457 publicaciones
Citando a honestknave
Existe una hoja de cálculo de Excel muy conocida que utiliza las funciones DDE de MT4 para calcular la fortaleza de la divisa mediante una fórmula basada en el máximo, el mínimo y la oferta de D1: {image} Como resultado de otro proyecto en el que estoy trabajando, la he adaptado a MT4. Es un asesor experto (EA) sencillo que debería replicar los resultados de la hoja de cálculo de Excel. Incluye algunas mejoras adicionales (alertas, posibilidad de seleccionar otros marcos temporales para el cálculo, clic para abrir con plantilla aplicada para cada par), pero en general es relativamente sencillo. {image} Estoy creando...
Antes que nada, gracias por esta excelente herramienta y por el excelente trabajo... 

Mi pregunta es si podrían implementar una opción para seleccionar los pares a seguir.
Por ejemplo, solo hago el seguimiento de 4 pares: EURUSD, EURJPY, GBPUSD y GBPJPY (sin cálculo, porque creo que se hace con 28 pares) solo cuando visualizo estos cuatro pares.

No sé si me expliqué bien; mi inglés es un desastre. 
5
Cita
26 de abril de 2015, 12:54 p. m.
 mokuro89Se unió en marzo de 2015 | Estado: Trader | 449 publicaciones
suscrito, gracias por compartir tu arduo trabajo
6
Cita
26 de abril de 2015, 16:25
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Interesante medidor de fuerza, gracias por publicarlo.
Lo observaré durante los mercados en vivo.
El único límite es el que tú mismo te pones - Felix Baumgartner
7
Cita
26 de abril de 2015, 16:30
 Borradores| Se unió en septiembre de 2011 | Estado: Comerciante | 93 publicaciones
A mí también me gusta. Gracias.

Lo probaré en unas horas.
8
Cita
26 de abril de 2015, 17:50
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mosiskv
Hola, acabo de encontrar esto y le eché un vistazo rápido. Se ve genial. Lo revisaré en vivo la semana que viene. ¿Quizás podrías considerar hacerlo compatible con x/y simples si trabajas en ello de nuevo? ¡Gracias por compartir!
Gracias por la sugerencia, mosiskv.
Lo haré en la próxima versión porque sé que no todos quieren que esté centralizado.
9
Cita
26 de abril de 2015, 17:52
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a chaveznqoos
{quote} Antes que nada, gracias por esta excelente herramienta y por el excelente trabajo... Mi pregunta es si podrían implementar una opción para seleccionar los pares a seguir. Por ejemplo, solo hago el seguimiento de 4 pares: EURUSD, EURJPY, GBPUSD y GBPJPY (sin cálculo, porque creo que se hace con 28 pares) solo cuando visualizo estos cuatro pares. No sé si me expliqué bien, mi inglés es un desastre. 
Hola chaveznqoos, gracias por la sugerencia.
Entiendo lo que quieres decir, pero eso requeriría muchas modificaciones, así que si tengo tiempo le echaré un vistazo. Aunque no será inmediato.
10
Cita
26 de abril de 2015, 17:52
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mokuro89
suscrito, gracias por compartir tu arduo trabajo

Citando a Shabs19
Interesante medidor de fuerza, gracias por publicarlo. Lo observaré durante los mercados en vivo.

Citando a Draffi
A mí también me gusta. Gracias. Lo probaré en unas horas.

11
Cita
26 de abril de 2015, 20:08
 YardiFX| Se unió en junio de 2014 | Estado: Trader | 324 publicaciones
Sería genial agregar notificaciones push o notificaciones por correo electrónico...

bien hecho, gran trabajo.
Paz y Pips
12
Cita
27 de abril de 2015, 4:00 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Cotización de YardiFX
Sería genial agregar notificaciones push o notificaciones por correo electrónico... bien hecho, gran trabajo.
Hola YardiFX, sí, es fácil. Lo añadiré en la próxima versión.
13
Cita
27 de abril de 2015, 7:04 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
honestknave,

la pregunta sobre la proporción de pujas.

La barra verde es larga, pero el verde pálido significa... ¿?
La barra verde es larga, pero el verde brillante significa... ¿
? Lo mismo ocurre con la longitud y el color de la barra roja, ¿?

No quiero asumir su significado. ¿Podrías explicarlo?
Gracias.
El único límite es el que tú mismo te pones - Felix Baumgartner
14
Cita
27 de abril de 2015, 7:25 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Shabs19
honestknave, la pregunta sobre la proporción de pujas. La barra verde es larga, pero el verde pálido significa... ¿? La barra verde es larga, pero el verde brillante significa... ¿? Lo mismo ocurre con la longitud y el color de la barra roja, ¿? No quiero asumir su significado. ¿Podrías explicarlo? Gracias.
Buena pregunta, Shabs19.

A ver si esto responde a tu pregunta.

Si no, por favor, házmelo saber.

Los colores pálidos/brillantes son solo una escala simple. Los colores pálidos están más cerca del centro de la gama. Los colores más brillantes, cerca de los extremos.
15
Cita
27 de abril de 2015, 8:03 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Ya lo vi antes, pero no me queda claro. ¿

Una barra verde brillante significa que el precio ha superado el máximo del día anterior? ¿
Una barra roja brillante significa que el precio ha superado el mínimo del día anterior?

La longitud de la barra roja no coincide con la longitud de la barra verde, como en la venta más fuerte o la compra más fuerte, respectivamente. ¿

Lo estoy interpretando correctamente?
El único límite es el que tú mismo te pones - Felix Baumgartner
16
Cita
27 de abril de 2015, 8:18 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Shabs19
Ya lo vi antes, pero no me queda claro. ¿Una barra verde brillante significa que el precio ha superado el máximo del día anterior? ¿Una barra roja brillante significa que el precio ha superado el mínimo del día anterior? La longitud de la barra roja no coincide con la longitud de la barra verde, como en la venta más fuerte o la compra más fuerte, respectivamente. ¿Lo estoy interpretando correctamente?
Esto solo utiliza el método de cálculo de la hoja de cálculo original de Excel, que no hace referencia a los datos del día anterior.

La fórmula para calcular la relación de puja es: (Oferta actual - Mínimo diario) / (Máximo diario - Mínimo diario).

El medidor de barra muestra la relación de puja real para ese par; no se ha ajustado ni factorizado de ninguna manera.

Ejemplo:
Oferta: 1,0175
Máximo diario: 1,0200
Mínimo diario: 1,0100

(1,0175-1,0100) / (1,0200-1,0100) = 0,0075 / 0,01 = 0,75 = 75 % .
Por lo tanto, la barra se dibujaría en verde, llena hasta 3/4

de su capacidad. Espero que te sirva.
2
17
Cita
27 de abril de 2015, 8:42 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Gracias por la explicación, honestknave.

Estamos viendo dónde se encuentra el precio de oferta actual en relación con el mínimo actual en comparación con el rango del día actual.
Si el precio de oferta actual es el mínimo actual, no se mostrará ninguna barra.

El color de la barra se relaciona con la fortaleza relativa de cada par de divisas, como se muestra en la columna del extremo derecho (~).
¿Sería posible colorear estos números?
Superior a +4.0: Verde brillante.
Inferior a -4.0: Rojo brillante.

Esto ayudaría a ver los cambios en las fortalezas.
El único límite es el que tú mismo te pones - Felix Baumgartner
1
18
Cita
27 de abril de 2015, 8:52 a. m. | Editado a las 9:03 a. m.
 Juan007Se unió en agosto de 2012 | Estado: Trader | 1275 publicaciones
Gracias
de verdad
19
Cita
27 de abril de 2015, 8:54 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Shabs19
Gracias por la explicación, honestknave. Estamos viendo dónde se encuentra el precio de oferta actual en relación con el mínimo actual en comparación con el rango del día actual. Si el precio de oferta actual es el mínimo actual, no se mostrará ninguna barra.
Sí, exactamente.
De igual manera, si la oferta es el máximo diario, se muestra el 100 % de la barra.

Citando a Shabs19
El color de la barra se relaciona con la fuerza relativa de cada par de divisas, como se muestra en la columna del extremo derecho (~). ¿Sería posible colorear estos números? Superior a +4.0 Brillante
Por el momento, el color no tiene nada que ver con la intensidad relativa. Sin embargo, es una buena sugerencia y la consideraré.

Estoy corrigiendo errores del proyecto principal, pero cuando termine, volveré a revisarlo para ver qué mejoras puedo hacer. Ya tengo algunas en proceso.
1
20
Cita
27 de abril de 2015, 9:33 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Juan007
Gracias de verdad
De nada

P2
 ksiadz| Se unió en julio de 2012 | Estado: Comerciante | 8 publicaciones
Hola,
tengo un pequeño problema con este asesor experto. ¿Cómo lo configuro? No me funciona porque es un error: Par(es) no disponible(s) en tu bróker. ¿Cómo lo soluciono? ¡
Saludos!
22
Cita
28 de abril de 2015, 6:26 a. m.
 Mwsteiner| Se unió en abril de 2009 | Estado: Comerciante | 354 publicaciones
Citando a ksiadz
Hola, tengo un pequeño problema con este asesor experto. ¿Cómo lo configuro? No me funciona porque es un error: Par(es) no disponible(s) en tu bróker. ¿Cómo lo soluciono? ¡Saludos!
¡Quizás sufijo! ¡

Saludos!
23
Cita
28 de abril de 2015, 6:30 a. m.
 Mwsteiner| Se unió en abril de 2009 | Estado: Comerciante | 354 publicaciones
Citando a honestknave
{quote} Sí, es exacto. De igual forma, si la oferta es el máximo diario, se muestra el 100% de la barra. {quote} Por ahora, el color no tiene nada que ver con la intensidad relativa. Sin embargo, es una buena sugerencia y la consideraré. Estoy corrigiendo errores del proyecto principal, pero en cuanto termine, volveré a esto para ver qué mejoras se pueden hacer. Ya tengo algunas en proceso.
Hola Honestknave,

¿sería posible ordenar el CSM de izquierda a derecha (de fuerte a débil)? Sería genial, así tendríamos los más fuertes y los más débiles a primera vista y no tendríamos que buscar.

Gracias de antemano. Saludos, Michael.
24
Cita
28 de abril de 2015, 6:49 a. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Hola Honestknave,

revisé el asesor experto unos minutos esta mañana (desafortunadamente, surgió algo que limitará mi tiempo en forex esta semana).

Es un excelente trabajo; la selección de pares funciona de maravilla. Pensé durante mucho tiempo en pedirle a alguien que simplemente colocara
una tabla de selección de pares junto a algo como el Giraya, pero nunca lo hice.

Actualmente, descarta/pierde cualquier otro indicador, como por ejemplo, Newscal, si lo colocas en el mismo gráfico que el asesor experto; ¿quizás
se deba a que está centrado? (Guardé una plantilla, pero al colocarla en un gráfico solo se muestra el asesor experto (build 765).

La tabla superior (CSM) está en un buen orden alfabético, pero sigo notando que los valores numéricos están en orden aleatorio.
Quizás también podrías considerar hacerla más dinámica y ordenarla en orden numérico decreciente (de fuerte a débil) de izquierda a derecha, manteniendo
la misma funcionalidad que la actual.

Gracias de nuevo por compartir.
¡¡¡No te limites!!!
25
Cita
28 de abril de 2015, 7:48 a. m. | Editado a las 10:26 a. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Hola Honestknave,

lo olvidé (me estoy haciendo viejo).

Quizás una última reflexión personal: mantén esto SIMPLE. Veo muchos paneles impresionantes y cosas así, tan sobrecargadas de información
que apuesto mi último centavo a que toda esa información no se tiene en cuenta para un intercambio y simplemente se desperdicia.

Saludos.
¡¡¡No te limites!!!
1
26
Cita
28 de abril de 2015, 13:25
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a ksiadz
Hola, tengo un pequeño problema con este asesor experto. ¿Cómo lo configuro? No me funciona porque es un error: Par(es) no disponible(s) en tu bróker. ¿Cómo lo soluciono? ¡Saludos!
Citando a Mwsteiner
¡Quizás sufijo! ¡Saludos!
Hola ksiadz, la sugerencia de mwsteiner también es mi primera impresión. ¿Qué ves en la pestaña de registro de expertos?

Citando a Mwsteiner
{quote} Hola Honestknave, ¿sería posible ordenar el CSM de izquierda a derecha (de fuerte a débil)? Sería genial, así tendríamos los más fuertes y los más débiles a primera vista y no tendríamos que buscar. Gracias de antemano. Saludos, Michael.
Hola mwsteiner, gracias por la sugerencia. Sin duda la consideraré para una versión posterior.
En aquel momento, mi objetivo era simplemente portar la hoja de cálculo "tal cual".
Pero coincido en que ordenarlas es más intuitivo (su hermano mayor sí las ordena y lo prefiero).

Citando a mosiskv
Hola Honestknave, revisé el asesor experto unos minutos esta mañana. (Desafortunadamente, surgió algo que limitará mi tiempo en forex esta semana). Es un trabajo excelente; la selección de pares funciona de maravilla. Pensé durante mucho tiempo en pedirle a alguien que simplemente colocara una tabla de selección de pares junto a algo como el Giraya, pero nunca lo hice. Actualmente, descarta/pierde cualquier otro indicador, como por ejemplo Newscal, si lo colocas en el mismo gráfico que el asesor experto. ¿Quizás sea porque está centrado? (Guardo una plantilla, pero al colocarla en un gráfico, simplemente...)
Gracias por los comentarios. Sí, se apropia del gráfico al que se aplica (que era lo que necesitaba en ese momento), pero reduciré su predominio en futuras versiones y cambiaré las opciones de posicionamiento.

Citando a mosiskv
La tabla superior (CSM) está bien ordenada alfabéticamente, pero sigo notando que los valores numéricos están en orden aleatorio. Quizás también podrías considerar hacerla más dinámica y ordenarla en orden numérico decreciente (de fuerte a débil) de izquierda a derecha, manteniendo la misma funcionalidad que la actual. Gracias de nuevo por compartir.
Por favor, vean mi publicación anterior para mwsteiner.

Gracias por sus comentarios.

Citando a mosiskv
Hola Honestknave, lo olvidé (me estoy haciendo viejo). Quizás una última reflexión personal: mantén esto SIMPLE. Veo muchos paneles impresionantes y cosas así, tan sobrecargadas de información que apuesto mi último centavo a que toda esa información no se tiene en cuenta para un intercambio y simplemente se desperdicia. Saludos.

27
Cita
28 de abril de 2015, 13:34
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Solo una cosa rápida: gracias a todos por el apoyo y los comentarios positivos.

Tengo muchísimos proyectos atrasados, así que puede que pase un tiempo hasta que pueda añadir nuevas funciones.

Sin embargo, siempre corrijo errores lo antes posible.
28
Cita
29 de abril de 2015, 3:16 a. m.
 BubinckaSe unió en noviembre de 2009 | Estado: Eres lo que eres | 1961 publicaciones | En línea ahora
Hola Honestknave,

usando tu panel, gracias también al gran aumento del dólar australiano, ayer pude recuperar casi un 10 % de descuento .
Es una gran herramienta que hay que manejar con cuidado, pero es otra arma más en nuestro arsenal.

Gracias por compartir,
Bubincka.
Porta itineris dicitur longissima esse
29
Cita
29 de abril de 2015, 7:37 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a honestknave
{quote} Sí, es exacto. De igual forma, si la oferta es el máximo diario, se muestra el 100% de la barra. {quote} Por ahora, el color no tiene nada que ver con la intensidad relativa. Sin embargo, es una buena sugerencia y la consideraré. Estoy corrigiendo errores del proyecto principal, pero en cuanto termine, volveré a esto para ver qué mejoras se pueden hacer. Ya tengo algunas en proceso.
Tal vez codificar por colores la diferencia en fortalezas mayores a un cierto número ayudaría a seleccionar pares comercializables.

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: c dash mod.jpg Tamaño: 188 KB
El único límite es el que tú mismo te pones - Felix Baumgartner
30
Cita
3 de mayo de 2015, 10:33 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Bubincka
Hola Honestknave, usando tu panel, gracias también al gran aumento del dólar australiano, ayer pude recuperar casi un 10 % de descuento . Es una gran herramienta que hay que manejar con cuidado, pero es otra arma más en nuestro arsenal. Gracias por compartir, Bubincka.
Gracias bubincka
31
Cita
3 de mayo de 2015, 10:34 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Shabs19
{quote}Tal vez codificar por colores la diferencia en fortalezas mayores a un cierto número ayudaría a seleccionar pares comercializables. {image}
Por favor vea mi siguiente publicación
32
Cita
3 de mayo de 2015, 10:40 a. m. | Editado a las 12:30 p. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Tuve la oportunidad de revisar csDash este fin de semana y realicé algunos cambios.

La versión anterior de csDash no tiene ningún problema, así que si no te gustan los cambios, puedes seguir usando la versión anterior.

No he probado la nueva versión en el mercado, así que pido disculpas de antemano si detecta algún fallo.

Ahora es un indicador (no un experto).
¿Por qué? Solo puedes añadir un experto por gráfico, pero puedes añadir varios indicadores.
¿Qué significa esto? Debes colocar csDash.ex4 en la carpeta de Indicadores.

Los elementos visuales son más configurables.
¿Por qué? Preferencias del usuario.
¿Qué significa esto? Ahora puedes especificar los colores:
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: colors.png Tamaño: 128 KB

También puede especificar la esquina (o centrarla como antes) y los desplazamientos. Nota: x es una medida horizontal. y y es una medida vertical. Recuerde cambiar la configuración de posición si agrega varias instancias al mismo gráfico.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: offsets.png Tamaño: 133 KB


Ahora puedes ordenar las divisas o la lista de pares.
¿Por qué? Preferencias del usuario.
¿Qué significa esto? Puedes ordenar las divisas de mayor a menor valor (sin ordenar significa que están ordenadas alfabéticamente).
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: sortcurrencies.png Tamaño: 56 KB

Puedes ordenar pares según su diferencial (sin ordenar significa que están ordenados alfabéticamente)
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: sortpairs.png Tamaño: 122 KB


Puedes alternar entre la vista condensada (solo las fortalezas de las divisas) y la vista ampliada (todos los pares listados).
¿Por qué? Ocupa menos espacio.
¿Qué significa esto? Haz clic en cualquier parte de la sección de divisas (arriba) para alternar entre la vista condensada y la ampliada.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: view.png Tamaño: 40 KB


Coloración y alertas modificadas.
¿Por qué? Consistencia y preferencia del usuario.
¿Qué significa esto? Establecer los umbrales superior e inferior para la fortaleza de la moneda.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: ccycols.png Tamaño: 55 KB

Establecer el umbral diferencial
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: pairscol.png Tamaño: 87 KB

Las alertas ahora se activan según los siguientes criterios:
Spread por debajo del máximo

(Moneda base >= Umbral superior y moneda de cotización <= Umbral inferior) o Diferencial >= Umbral diferencial


(el reverso para vender)

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: alerts.png Tamaño: 66 KB


Visualización de la relación de oferta modificada
¿Por qué? No era particularmente intuitivo
¿Qué significa esto? La relación de oferta es donde el precio de oferta actual es relativo al máximo y al mínimo.
El inicio de la barra es 50%.
Si la barra es de color rojo , significa que la relación de oferta es inferior al 50% . Cuanto más larga sea la barra, más cerca del 0%. Por debajo del 25% es un rojo sólido. Entre el 25 y el 50% es rojo hueco.
Si la barra es de color verde , significa que la relación de oferta es superior al 50% . Cuanto más larga sea la barra, más cerca del 100%.
Por encima del 75% es un verde sólido. Entre el 50-75% es verde hueco.
Esto es bastante difícil de explicar con palabras, por lo que en esta captura de pantalla he ajustado la columna de spread para mostrar los valores reales de la relación de oferta. Puede comparar los valores reales de la oferta con cómo se ven en la barra.
Imagen adjunta

3
33
Cita
3 de mayo de 2015, 10:45 a. m. | Editado a las 6:51 p. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Se alcanzó el número máximo de archivos adjuntos en la publicación anterior, así que aquí está el archivo.

He intentado simplificarlo al máximo, pero añadir más opciones es inevitable cuando se busca satisfacer las preferencias de diferentes usuarios.

Ya no es necesario configurar el prefijo/sufijo del broker, ya que esto se hace automáticamente. Así que al menos hay dos opciones menos.
1
34
Cita
3 de mayo de 2015, 11:01 a. m.
 Juan007Se unió en agosto de 2012 | Estado: Trader | 1275 publicaciones
Gracias honestknave,

lo estoy comprobando.
35
Cita
3 de mayo de 2015, 11:20 a. m. | Editado a las 11:37 a. m.
 tradistaSe unió en mayo de 2011 | Estado: - | 784 publicaciones
¡Excelente trabajo! ¡Probaré la versión con indicador! ¡Gracias!

Editar: Creo que los valores verdadero/falso de "sort" se están comportando al revés (¿un error?).
36
Cita
3 de mayo de 2015, 11:47 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Juan007
Gracias honestknave, lo estoy comprobando.

37
Cita
3 de mayo de 2015, 11:49 a. m. | Editado a las 12:39 p. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a tradista
¡Excelente trabajo! ¡Probaré la versión con indicador! ¡Gracias! Editar: Creo que los valores verdadero/falso de "sort" se están comportando al revés (¿un error?).
Gracias, tradista.
No puedo replicar tu error.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: sort.png Tamaño: 65 KB

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: unsorted.png Tamaño: 66 KB


¿Podrías subir una captura de pantalla, por favor?

Edito: Creo que mi nombre es ambiguo (actualicé mi publicación inicial).
Con "ordenados" me refiero a "ordenados por fuerza". "Sin ordenar" significa alfabéticamente (que es el orden en el que ingresé los pares).
38
Cita
3 de mayo de 2015, 12:10 p. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a honestknave
{quote} Gracias, tradista. No puedo replicar tu error: {image} {image} ¿Podrías publicar una captura de pantalla?
¡Gracias, honestknave !
Veo que para ordenar monedas , "verdadero" se ordena de más fuerte a más débil,
pero ¿verdadero o falso para ordenar pares aplicados a qué columna?

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: 2015-05-03_10-55-27.png Tamaño: 87 KB
39
Cita
3 de mayo de 2015, 12:29 p. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Pax
{quote} ¡Gracias, honestknave! Veo que para ordenar monedas, "verdadero" se ordena de más fuerte a más débil, pero ¿verdadero/falso para ordenar pares a qué columna? {image}
De nada, Pax.
Disculpen la ambigüedad del nombre... con "ordenado" me refiero a "ordenar por fuerza". "Sin ordenar" significa alfabéticamente.

Para los pares, la ordenación se realiza por diferencial (es decir, compra-venta = diferencial).
Si la divisa base es muy fuerte mientras que la divisa cotizada es muy débil, se observará un diferencial grande.
Lo mismo ocurre a la inversa.
40
Cita
3 de mayo de 2015, 13:00 horas
 YardiFX| Se unió en junio de 2014 | Estado: Trader | 324 publicaciones
Genial... Pero aún no hay notificaciones push. Ohhh... Lo haría yo mismo... Pero es tu código.
Paz y Pips

P3
Se unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a honestknave
{quote} De nada, Pax. Disculpen la ambigüedad del nombre... con "ordenado" me refiero a "ordenar por fuerza". "Sin ordenar" significa alfabéticamente. Para los pares, la ordenación se realiza por diferencial (es decir, compra-venta = diferencial). Si la moneda base es muy fuerte mientras que la moneda cotizada es muy débil, se observará un diferencial grande. Lo mismo ocurre a la inversa.
Gracias por la aclaración.
42
Cita
3 de mayo de 2015, 13:18 | Editado a las 18:52
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Cotización de YardiFX
Genial... pero aún no hay notificaciones push
Tienes toda la razón, lo había olvidado por completo. Cambios

de la versión 1.06

:
 

Aclaración del significado de “sort”


Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: sortclarification.png Tamaño: 65 KB
 

Se agregaron notificaciones push (no probadas, por lo que le pedimos que nos informe).


Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: push.png Tamaño: 59 KB
43
Cita
3 de mayo de 2015, 13:19
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Pax
{quote}Gracias por la aclaración.
De nada
44
Cita
3 de mayo de 2015, 14:15
 YardiFX| Se unió en junio de 2014 | Estado: Trader | 324 publicaciones
Cinco estrellas para usted, amable señor... ¡Bravo!
Paz y Pips
45
Cita
3 de mayo de 2015, 14:41
 tradistaSe unió en mayo de 2011 | Estado: - | 784 publicaciones
Citando a honestknave
{quote} Gracias, tradista. No puedo replicar tu error: {image} {image} ¿Podrías publicar una captura de pantalla, por favor? Edito: Creo que mi nombre es ambiguo (actualicé mi publicación inicial). Con "ordenados" me refiero a "ordenados por fuerza". "Sin ordenar" significa alfabéticamente (que es el orden en el que ingresé los pares).
Vale, tienes razón. Pensé que estaba ordenado alfabéticamente por nombre. Ordenar por "fuerza" funciona correctamente. 
Fue culpa mía no haber leído detenidamente tus publicaciones anteriores, donde todo está claramente explicado. 
En fin, los últimos cambios que hiciste en la descripción aclararán cualquier ambigüedad. ¡Gracias!
46
Cita
3 de mayo de 2015, 15:16
 tradistaSe unió en mayo de 2011 | Estado: - | 784 publicaciones
Honestknave,
¿sería posible tener un parámetro de espaciado vertical o un tamaño de fuente personalizable? Algo que ayudaría a condensar la altura del tablero para que pudiera caber en una resolución de pantalla más pequeña. Estoy intentando tener tres ventanas en mosaico vertical para que el panel siempre esté visible junto a las demás ventanas de gráficos (es decir, no a pantalla completa). Una opción sería eliminar el borde exterior.

Aquí tienes una captura de pantalla de lo que quiero decir: independientemente de la alineación, la cuadrícula superior de "fuerzas" no es visible o la inferior no lo es.

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: csDash-fit.png Tamaño: 39 KB


Sólo hago sugerencias 
. Gracias.
47
Cita
3 de mayo de 2015, 15:32
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Hola Honestknave, ¡

Qué buen indicador!

¡Muy bien hecho!
El único límite es el que tú mismo te pones - Felix Baumgartner
48
Cita
3 de mayo de 2015, 15:48
 MerrygoldSe unió en julio de 2014 | Estado: Trader | 744 publicaciones
¡Cuenten conmigo! - ¡Gran herramienta!
¡MI SENTADO, NUNCA MI PENSAMIENTO!
49
Cita
3 de mayo de 2015, 15:51
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Cotización de YardiFX
Cinco estrellas para usted, amable señor... ¡Bravo!
No hay problema. Avísame si funciona como se anuncia.
50
Cita
3 de mayo de 2015, 15:53​​| Editado a las 18:52
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a tradista
Honestknave, ¿sería posible tener un parámetro de espaciado vertical o un tamaño de fuente personalizable? Algo que ayudaría a condensar la altura del tablero para que pudiera caber en una resolución de pantalla más pequeña. Estoy intentando tener tres ventanas en mosaico vertical para que el panel siempre esté visible junto a las demás ventanas de gráficos (es decir, no a pantalla completa). Una opción sería eliminar el borde exterior. Aquí tienes una captura de pantalla de lo que quiero decir: independientemente de la alineación, la cuadrícula superior de "fortalezas" no es visible o la inferior...
Prueba esto tradista:

Versión 1.07

Cambios:
Capacidad de cambiar el tamaño de fuente y la altura de fila.


Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: row height.png Tamaño: 75 KB
Cambio menor en las descripciones de las opciones

51
Cita
3 de mayo de 2015, 15:54
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Shabs19
Hola Honestknave, ¡Qué buen indicador! ¡Muy bien hecho!
Citando a Merrygold
¡Cuenten conmigo! - ¡Gran herramienta!
Gracias chicos
52
Cita
3 de mayo de 2015, 16:00 horas
 BicarusSe unió en noviembre de 2014 | Estado: Yoda | 931 publicaciones
¿Cómo soluciono el mensaje de error de pares faltantes? El enlace que proporcionaste en tu primera publicación no proporciona la respuesta.
53
Cita
3 de mayo de 2015, 16:16
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Bicarus
¿Cómo soluciono el mensaje de error de pares faltantes? El enlace que proporcionaste en tu primera publicación no proporciona la respuesta.
Podría ser un fallo en mi código de detección automática de broker... Por favor, ¿podrías facilitarme:
Un ejemplo del nombre de par de su bróker (por ejemplo, EURUSD-xx)
Una captura de pantalla del registro de sus expertos

54
Cita
3 de mayo de 2015, 16:23
 BicarusSe unió en noviembre de 2014 | Estado: Yoda | 931 publicaciones
Citando a honestknave
{quote} Podría ser una falla en mi código de detección automática de broker... ¿Puede proporcionarme: Un ejemplo del nombre de par de su broker (por ejemplo, EURUSD-xx)? Una captura de pantalla del registro de sus expertos
Todos mis pares tienen un "+" en la parte posterior. ¿Podría ser ese el problema?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Capture.PNG Tamaño: 125 KB
55
Cita
3 de mayo de 2015, 16:32
 conseguir| Se unió en junio de 2009 | Estado: Comerciante | 266 publicaciones
Citando a honestknave
{quote} {quote} Gracias chicos
Fantástico... Me encanta ordenar por "diferencial" y ForceLoadHistoricalData. 
Estaba a punto de ordenar por "alfabéticamente", pero creo que "diferencial" es mejor idea... probaré la entrada manual en la demo.
¡Excelente trabajo!
56
Cita
3 de mayo de 2015, 16:47 | Editado a las 18:52
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Bicarus
{quote} Todos mis pares tienen un "+" atrás. ¿Podría ser ese el problema? {image}
Hola Bicarus. Primero veamos si funciona la opción fácil:
57
Cita
3 de mayo de 2015, 16:50
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando conseguir
{quote} ¡Genial! Me encanta ordenar por "diferencial" y ForceLoadHistoricalData. Estaba a punto de ordenar por "alfabéticamente", pero creo que "diferencial" es mejor idea... probaré la entrada manual en la demo. ¡Excelente trabajo!
Gracias por recibir
58
Cita
3 de mayo de 2015, 16:58
 BicarusSe unió en noviembre de 2014 | Estado: Yoda | 931 publicaciones
Citando a honestknave
Hola Bicarus. Primero veamos si funciona la opción fácil: {file}
Gracias por tu ayuda, amigo, realmente lo aprecio. Sin embargo, cuando lo cargo desde experto, obtengo la primera imagen. No soy un experto OO.
Intenté cargarlo desde el indicador personalizado y obtuve la segunda imagen.
Imagen(es) adjunta(s) (haga clic para ampliar)
Haga clic para ampliar Nombre: Capture.PNG Tamaño: 13 KB
Haga clic para ampliar Nombre: Capture2.PNG Tamaño: 34 KB
59
Cita
3 de mayo de 2015, 17:18
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Bicarus
{quote} gracias por tu ayuda amigo, realmente lo aprecio. Sin embargo, cuando lo cargo desde experto obtengo la primera imagen. No soy un experto OO, intenté cargarlo desde el indicador personalizado y obtuve la segunda imagen {image} {image}
Hola Bicarus,

las primeras versiones eran EA. Las últimas versiones son indicadores.

Como solución provisional para tu problema: Cambios

de la versión 1.09.

Anulación manual para la detección automática de intermediarios


No necesitas esta versión si no tienes ningún problema.

Si recibe un mensaje sobre pares faltantes, puede ingresar manualmente el prefijo y/o sufijo de su corredor

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: autodetect.png Tamaño: 56 KB

Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   118 KB | 2833 descargas
60
Cita
3 de mayo de 2015, 17:26
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Hola Honestknave,

¡Excelente y rápido trabajo!

La corrección del tamaño de fuente y la altura de fila me permitió configurarlo incluso en mi portátil sin problemas.

También funciona en mi bróker ECN con sufijo.

Sin embargo, descubrí dos cosas extrañas que ocurren de vez en cuando al jugar con el indicador:
1) A veces, al minimizarlo, el texto se enrolla correctamente, pero el cuadro exterior permanece expandido.
2) Ver adjunto: al cambiar la configuración, el período de tiempo, etc., no se elimina la primera instancia, sino que
se genera una segunda instancia que funciona correctamente.

En fin, ¡gracias por su generosidad!

Saludos.

Imagen adjunta

¡¡¡No te limites!!!

P4
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mosiskv
Hola Honestknave, ¡Excelente y rápido trabajo! La corrección del tamaño de fuente y la altura de fila me permitió configurarlo incluso en mi portátil sin problemas. También funciona en mi bróker ECN con sufijo. Sin embargo, descubrí dos cosas extrañas que ocurren de vez en cuando al jugar con el indicador: 1) A veces, al minimizarlo, el texto se despliega correctamente, pero el cuadro exterior permanece expandido. 2) Ver adjunto: al cambiar la configuración, el período de tiempo, etc., no se elimina la primera instancia, sino que se genera una segunda instancia que funciona correctamente. En fin, gracias.
Gracias por tus comentarios, mosiskv.
Para ayudarme a identificar el comportamiento extraño, la próxima vez que lo veas, por favor, presiona Ctrl+I para abrir la ventana del indicador y comprobar cuántas instancias de csDash se muestran. ¡Saludos!
62
Cita
3 de mayo de 2015, 18:09
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Una breve nota para quienes estén atentos al indicador durante la apertura de los mercados:

los valores fluctuarán significativamente hasta que haya una distancia considerable entre el máximo y el mínimo. Hasta entonces, pequeños movimientos de pips se traducen en grandes variaciones porcentuales.

Esto es perfectamente normal.
63
Cita
3 de mayo de 2015, 18:11
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Hola Honestkanve.

Todavía tenía abierto el gráfico de ejemplo, solo una instancia.

¿Podrías considerar cambiar la visualización del spread para que detecte automáticamente el tipo de bróker que usas y muestre el spread
adecuado para ese bróker?

Gracias de nuevo; lo revisaré mañana; ahora es hora de dormir para las personas mayores como yo.

Saludos.
¡¡¡No te limites!!!
64
Cita
3 de mayo de 2015, 18:12
 tradistaSe unió en mayo de 2011 | Estado: - | 784 publicaciones
Citando a honestknave
{quote} Pruebe esto tradista: Versión 1.07 Cambios: Capacidad para cambiar el tamaño de fuente y la altura de fila {image} Cambio menor en las descripciones de las opciones {file}
¡¡Perfecto!! 
65
Cita
3 de mayo de 2015, 18:15
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mosiskv
Hola Honestkanve. Todavía tenía abierto el gráfico de ejemplo, solo una instancia. ¿Podrías considerar cambiar la visualización del spread para que detecte automáticamente el tipo de bróker que usas y muestre el spread adecuado para ese bróker? Gracias de nuevo; lo revisaré mañana; ahora es hora de dormir para las personas mayores como yo. Saludos.
Vale, gracias mosiskv. Por favor, avísame si puedes replicar el error.
No estoy seguro de entender lo del spread... El spread que se muestra es (¿debería ser?) el de tu bróker.
66
Cita
3 de mayo de 2015, 18:16
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a tradista
{quote} ¡¡Perfecto!!

67
Cita
3 de mayo de 2015, 19:21
 Edward rápido| Se unió en mayo de 2009 | Estado: Comerciante | 122 publicaciones
Gracias, se agradece mucho.

Rápido .
68
Cita
3 de mayo de 2015, 23:44
 ShomariG| Se unió en febrero de 2015 | Estado: Que la paz te acompañe... | 75 publicaciones
¡Buen trabajo! ¡Gracias!
69
Cita
4 de mayo de 2015, 4:32 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
Se alcanzó el número máximo de archivos adjuntos en la publicación anterior, así que aquí está el archivo. He intentado simplificarlo al máximo, pero añadir más opciones es inevitable cuando se busca satisfacer las preferencias de diferentes usuarios. Ya no es necesario configurar el prefijo/sufijo del broker, ya que esto se hace automáticamente. Así que al menos hay dos opciones menos.
Excelente trabajo de Andrew 

Shalom
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
70
Cita
4 de mayo de 2015, 9:19 a. m.
 Godwin IgiliSe unió en mayo de 2011 | Estado: Trader | 559 publicaciones
Honestknave,

excelente indicador. Gracias.

El spread no se muestra correctamente en mi bróker Global Prime.
Por ejemplo, muestra
26 en lugar de 2,6 para GBPCAD,
33 en lugar de 3,3 para GBPAU,
etc.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Global Prime - MetaTrader 4.png Tamaño: 123 KB
71
Cita
4 de mayo de 2015, 9:45 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a rapidedward
Gracias, se agradece mucho. Rápido.
Citando a ShomariG
¡Buen trabajo! ¡Gracias!
Citando a 919gilead
{quote} Excelente trabajo de Andrew Shalom
Me alegra que a todos les resulte útil.
72
Cita
4 de mayo de 2015, 9:50 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Godwin Igili
Honestknave, excelente indicador. Gracias. El spread no se muestra correctamente en mi bróker Global Prime. Por ejemplo, muestra 26 en lugar de 2,6 para GBPCAD, 33 en lugar de 3,3 para GBPAUDE, etc. {imagen}
Hola Godwin Igili,

te devuelve los valores del spread directamente de tu bróker en puntos (no pips).

Si usas un bróker de 5 dígitos (como la mayoría hoy en día), un pip equivale a 10 puntos.

Espero que te sirva.
73
Cita
4 de mayo de 2015, 12:02 p. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Citando a honestknave
{quote} Vale, gracias mosiskv. Por favor, avísame si puedes replicar el error. No estoy seguro de entender lo del spread... el spread que se muestra es (¡¿debería ser?!) el spread de tu bróker.
Hola Godwin Igili,
te devuelve los valores del spread directamente de tu bróker en puntos (no pips).
Si usas un bróker de 5 dígitos (como la mayoría hoy en día), hay 10 puntos por "pip".

Disculpas por la vaguedad de mi descripción. Entiendo que obtienes el spread directamente del bróker, pero
quizás podrías automatizar la visualización "correcta" por dígito del bróker (4/5), etc., o dar una opción en la configuración
para la visualización.

Saludos.
¡¡¡No te limites!!!
74
Cita
4 de mayo de 2015, 12:33 p. m. | Editado a las 12:49 p. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mosiskv
{quote} "Hola Godwin Igili, te devuelve los valores del spread directamente de tu bróker en puntos (no pips). Si usas un bróker de 5 dígitos (como la mayoría hoy en día), hay 10 puntos por "pip". Disculpas por la vaguedad de mi descripción. Entiendo que obtienes el spread directamente del bróker, pero quizás podrías automatizar la visualización "correcta" por dígito del bróker (4/5), etc., o dar una opción en la configuración para la visualización. Saludos.
Hola mosiskv,

lo revisaré cuando pueda; ese cambio es un poco más complejo de lo que crees (tiene múltiples repercusiones en este indicador en particular).

PD: Me morderé los labios sobre qué es "correcto" para el riesgo de adentrarme en otra discusión sobre pips, puntos y ticks.
75
Cita
4 de mayo de 2015, 12:48 p. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Citando a honestknave
{quote} Hola mosiskv, lo revisaré cuando pueda. Ese cambio es un poco más complejo de lo que crees (tiene múltiples repercusiones en este indicador en particular). PD: Me morderé los labios sobre qué es "correcto" para el riesgo de adentrarme en otra discusión sobre pips, puntos y ticks.
Hola
Gracias por tu pronta respuesta
Hazlo cuando te convenga
Sí, dejemos "pips vs puntos vs ticks" para aquellos que quieran volverse locos

Saludos
¡¡¡No te limites!!!
76
Cita
5 de mayo de 2015, 10:13 a. m.
 mokuro89Se unió en marzo de 2015 | Estado: Trader | 449 publicaciones
Hola, honestknave, mi csDash es ligeramente diferente a mi hoja de cálculo de forexGrail. ¿Sabes a qué se debe esta diferencia? (El número de fortaleza de la divisa).
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: 01.png Tamaño: 95 KB
77
Cita
5 de mayo de 2015, 10:57 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mokuro89
Hola, honestknave, mi csDash es ligeramente diferente a mi hoja de cálculo de forexGrail. ¿Sabes a qué se debe esta diferencia? (El número de fortaleza de la divisa) {imagen}
Hola mokuro89,

no estoy familiarizado con la hoja de cálculo forexGrail, pero puedo ver una diferencia significativa: csDash usa un total de 28 pares y cada moneda tiene 7 puntos de evaluación:

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: eval points.png Tamaño: 65 KB
78
Cita
5 de mayo de 2015, 12:19 p. m.
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{quote} Hola mokuro89, no estoy familiarizado con la hoja de cálculo forexGrail, pero puedo ver una diferencia significativa: csDash usa un total de 28 pares y cada moneda tiene 7 puntos de evaluación: {image}

¿Podrías definir un punto de evaluación?
79
Cita
5 de mayo de 2015, 12:32 p. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dagoods
{quote}¿Podrías definir un punto de evaluación?
Claro.

Solo uso el término "punto de evaluación" porque así los llama la hoja de cálculo.

Pero en realidad, nos referimos a pares donde la divisa en cuestión es la base o la cotización.

Tomemos el dólar estadounidense como ejemplo.

Para calcular la fortaleza del dólar estadounidense , se analizan siete pares:
USD CHF
USD YEN
Dólar estadounidense canadiense
EUR USD
GBP USD
AUD USD
Dólar neozelandés dólar estadounidense
Ignore las cifras (un sistema diferente), pero esto le muestra qué pares se utilizan para cada moneda:

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: evaluation points.png Tamaño: 75 KB
2
80
Cita
5 de mayo de 2015, 12:37 p. m.
 mokuro89Se unió en marzo de 2015 | Estado: Trader | 449 publicaciones
Citando a honestknave
{quote} Claro. Solo uso el término "punto de evaluación" porque así los llama la hoja de cálculo. Pero en realidad, nos referimos a pares donde la divisa en cuestión es la base o la cotización. Tomemos el dólar estadounidense como ejemplo. Para calcular la fortaleza del dólar estadounidense, se observan 7 pares: USDCHF USDJPY USDCAD EURUSD GBPUSD AUDUSD NZDUSD. Ignore las cifras (un sistema diferente), pero esto le muestra qué pares se utilizan para cada divisa: {image}
También me preguntaba cuáles son los puntos de evaluación, gracias honestknave por la explicación.

Tiene más sentido usar 7 en cada moneda entonces, realmente estoy disfrutando del csDash, gracias de nuevo.


P5
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mokuro89
{quote} También me preguntaba cuáles son los puntos de evaluación, gracias honestknave por la explicación. Tiene más sentido usar 7 en cada moneda entonces, realmente estoy disfrutando del csDash, gracias de nuevo.

82
Cita
5 de mayo de 2015, 13:30
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{cita}

¡Gracias, honestknave! ¿Qué hay de la correlación?

JibalaPasan, en la publicación 1087 del hilo del panel, escribió sobre la correlación

http://www.forexfactory.com/showthre...23#post8211923.

Habla de cómo se correlacionan los pares entre sí. Nasap habla de la sincronización de los pares.

¿Podrías definir la correlación?

¡Gracias!
83
Cita
5 de mayo de 2015, 13:46
 patas| Se unió en marzo de 2010 | Estado: Comerciante | 168 publicaciones
¡Excelente trabajo, Andrew!

Quizás no sea un factor relevante ni práctico siquiera, pero es solo una reflexión:
¿vale la pena (o incluso es posible) ponderar la fuerza relativa de una divisa por algún tipo de volumen?

Es decir, si el volumen del EURUSD es el doble que el del AUDUSD, entonces el EURUSD tendría el doble de ponderación al calcular la fuerza relativa del USD.
84
Cita
5 de mayo de 2015, 14:54
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dagoods
{quote} ¡Gracias, honestknave! ¿Qué hay de la correlación? JibalaPasan, en la publicación 1087 del hilo del panel, escribió sobre la correlación http://www.forexfactory.com/showthre...23#post8211923. Habla de cómo se correlacionan los pares entre sí. Nasap habla de la sincronización de los pares. ¿Podrías definir la correlación? ¡Gracias!
Me interesa que menciones esto, ya que he estado reflexionando sobre la correlación estos últimos días.

Estoy sobrepasando mis límites de conocimiento, así que, por favor, tómate todo lo que digo con pinzas (y con gusto me corregirán quienes tengan más conocimientos sobre el tema):

la correlación, en su forma más simple, significa una conexión entre dos o más cosas.

Cuando veas una tabla de correlación como esta:
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: correction.png Tamaño: 82 KB


Estás viendo una comparación de dos pares. Cuando un par sube, ¿qué hace el otro? ¿Sube la misma cantidad? ¿Sube un poco más? ¿Un poco menos? ¿Se mueve en la dirección opuesta?

Si hay una correlación del 100 %, significa que lo que hace un par, el otro también lo hace exactamente.

Verás el 100 % en la tabla siempre que ambos pares sean iguales: los pares se mueven igual porque son iguales (una cifra irrelevante en la tabla, pero ilustra el punto).
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: 100%.png Tamaño: 10 KB


Si ves -100%, los pares están haciendo exactamente lo contrario. Uno sube, el otro baja. Iguales y opuestos.

Lo que naturalmente nos lleva a la pregunta: "¿Cómo medimos la correlación?". Normalmente, implica algo de matemáticas.
Imagen adjunta



Pero es importante tener en cuenta que existen diferentes maneras de medir la correlación. Diferentes técnicas arrojarán resultados diferentes.
De la misma manera que existen varias maneras de medir la fortaleza de una moneda (csDash usa un método, pero yo tengo varios otros que arrojan resultados diferentes).

Existe una zona gris entre -100% y +100%, donde los pares se comportan de forma similar o opuesta, pero no del todo. ¿Qué nivel de correlación consideramos significativo?

La razón por la que me interesan estas tablas de correlación es que solo comparan dos pares a la vez. ¿Qué aportan exactamente, por así decirlo? (¡perdón por el juego de palabras!)

Cuando medimos la fortaleza de una cesta (como csDash o las hojas de cálculo en las que se basa), medimos indirectamente la correlación y, además, obtenemos una visión más amplia del mercado. Las tablas de correlación solo analizan dos pares, pero la fortaleza de una cesta incluye siete pares. Si lo piensas bien, generalmente solo obtendrás las mediciones de fortaleza extrema cuando todo se mueve en conjunto, es decir, correlacionado. Y no solo correlacionado, sino correlacionado en un espectro más amplio.

Sin duda, la correlación nos ofrece una perspectiva diferente sobre la fortaleza de la moneda, pero me gustaría explorar su utilidad.

Disculpen si la explicación es vaga, pero apenas he comenzado a explorarla.

Quizás alguien con más conocimientos pueda aportar algo.
1
85
Cita
5 de mayo de 2015, 14:59
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando patas
¡Excelente trabajo, Andrew! Quizás no sea un factor relevante ni práctico siquiera, pero es solo una reflexión: ¿vale la pena (o incluso es posible) ponderar la fuerza relativa de una divisa por algún tipo de volumen? Es decir, si el volumen del EURUSD es el doble que el del AUDUSD, entonces el EURUSD tendría el doble de ponderación al calcular la fuerza relativa del USD.
Gran idea, Paws.
Nunca había pensado en eso. La única preocupación que se me ocurre ahora mismo es la precisión del volumen al que la mayoría tenemos acceso a través de nuestros corredores...
86
Cita
5 de mayo de 2015, 15:06 | Editado a las 18:21
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{quote} Es interesante que menciones esto, ya que he estado reflexionando sobre la correlación estos últimos días. Estoy sobrepasando mis límites de conocimiento, así que, por favor, tómate todo lo que digo con pinzas (y con gusto me corregirán quienes tengan más conocimientos sobre el tema): La correlación, en su forma más simple, significa una conexión entre dos o más cosas. Cuando ves una tabla de correlación como esta: {image}, estás viendo una comparación de dos pares. Cuando un par sube, ¿qué hace el otro par? ¿Sube la misma cantidad?...

Buen post honesto. Entiendo que cuando una ramita pequeña se convierte en una ramita más grande y luego tiene un tronco y luego comienza a ramificarse, puedes contar más con eso... en otras palabras, el orden en que suceden las cosas importa... es decir, movimientos constantes... es decir, 1 minuto se convierte en 5 minutos y luego en 15 minutos... cuando se trata de correlación... eso es algo que hay que buscar, hay un video que puedo encontrar al respecto si quieres... la otra cosa, por lo poco que he entendido de mis lecturas, es que si una fuerte correlación es real, el precio normalmente no se desacopla de ella... en otras palabras, cuando el precio se aleja un std o 2 de una correlación, entonces tienes la oportunidad de garantizar virtualmente alguna ganancia. en teoría de todos modos... espero que tenga sentido... es decir, si uchf y eu estuvieron correlacionados negativamente en un 99% durante los últimos 3 meses y este mes de repente se movieron juntos... 1 de 2 cosas DEBE ser cierta... 1. se están desacoplando y la correlación ha terminado y eso es negociable o 2. el caso habitual más confiable... volverán a la correlación negativa... así que cuando la fuerza muestra el retorno negativo en un par o mejor aún en ambos... ¡zas! tienes la operación de mayor probabilidad disponible en todo el trading... las especificaciones exactas no se conocen... pero ese es mi limitado entendimiento...

de verdad... vi a alguien hacer esto en un video pero no puedo encontrarlo de nuevo... si superpones dos gráficos altamente correlacionados uno encima del otro deberían verse casi idénticos... cuando ves un espacio significativo entre ellos... entonces tienes una situación negociable porque si están altamente correlacionados TIENEN que tocarse de nuevo o casi tocarse... y volver a estar juntos... de lo contrario se desacoplan... ¡lo mejor que puedo hacer es explicar algo que ni yo mismo entiendo del todo! jaja

Citando a honestknave
{quote} Es interesante que menciones esto, ya que he estado reflexionando sobre la correlación estos últimos días. Estoy sobrepasando mis límites de conocimiento, así que, por favor, tómate todo lo que digo con pinzas (y con gusto me corregirán quienes tengan más conocimientos sobre el tema): La correlación, en su forma más simple, significa una conexión entre dos o más cosas. Cuando ves una tabla de correlación como esta: {image}, estás viendo una comparación de dos pares. Cuando un par sube, ¿qué hace el otro par? ¿Sube la misma cantidad?...

Si los dos son similares a los que encontraste... me pregunto si las matemáticas realmente miden la correlación.

Por lo que entiendo, la correlación mide la unidad y el CSM mide la fuerza... creo que uno no debería afectar al otro, ¿


no?
Gracias por dejarme regurgitar, jaja.


Vídeo insertado



Aquí hay otra fórmula http://www.forexhit.com/analyze-fore...relations.html

También me parece interesante... sincronización cuántica de Google
Archivo(s) adjunto(s)
Tipo de archivo: pdf Hojas de referencia de correlación.pdf   380 KB | 18.011 descargas
1
87
Cita
5 de mayo de 2015, 17:34 | Editado a las 17:51
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Gracias por la información adicional, dagoods. Buscaré el video en Google y lo añadiré a mi investigación. Si te refieres al cambio en la correlación, es un dato muy interesante. Pero como medida en frío... todavía estoy decidiendo cómo la usaría (a menos que busques específicamente abrir operaciones simultáneas o mitigar la exposición).

Volviendo al CSM versus correlación: hay muchos criterios diferentes para medir la fortaleza de las divisas.

Las hojas de cálculo utilizan el concepto de ratio de oferta: ¿dónde está el precio de oferta en relación con el máximo del día? Si la oferta es el máximo diario, el ratio de oferta es del 100 %. Si la oferta es el mínimo diario, el ratio de oferta es del 0 %.

Este número se ajusta, se factoriza y se promedia, pero en última instancia tiene que ver con cómo se mueven los 7 pares.

Usando el ejemplo del JPY simplemente porque no necesitas preocuparte por la base/cotización (el JPY siempre es la cotización):
si los 7 pares están cerca del mínimo diario, esto implica que el JPY está muy fuerte. Démosles valores ficticios:
USD JPY 5%
EUR JPY 7%
GBP JPY 4%
CHF JPY 2%
CAD JPY 4%
AUD JPY 3%
NZD JPY 5%
El promedio es 4.3%... un número bajo. Como es la moneda de cotización, debes darle la vuelta y considerarlo 95.7%.

Sería justo decir que, en términos generales (todo depende de cómo midas la correlación), todos los pares están altamente correlacionados y la moneda es fuerte.

Eliminas parte de la correlación (menos consistencia en las proporciones de oferta) y eliminas la fortaleza:

USD JPY 12%
EUR JPY 83%
GBP JPY 16%
CHF JPY 23%
CAD JPY 76%
AUD JPY 54%
NZD JPY 93%
El promedio es 51%... un número intermedio.

Entonces, no hay mucha correlación y no hay mucha fortaleza o debilidad.

Sí, he manipulado las matemáticas y he pasado por alto muchas cosas (¡disculpas a todos los matemáticos y puristas!), pero la cuestión sigue siendo la misma: una vez que he identificado una moneda fuerte y una moneda débil a través del CSM, ¿qué información adicional busco obtener de la correlación de dos pares específicos?

Pero me alegra seguir explorando.
2
88
Cita
5 de mayo de 2015, 17:37
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Lo siento, dagoods, no actualicé antes de publicar y veo que añadiste información adicional. Lo leeré todo.
89
Cita
6 de mayo de 2015, 19:44
 mokuro89Se unió en marzo de 2015 | Estado: Trader | 449 publicaciones
¡Buena discusión! Muy interesante e informativa.
90
Cita
6 de mayo de 2015, 20:02
 mokuro89Se unió en marzo de 2015 | Estado: Trader | 449 publicaciones
Citando a dagoods
{quote} Bonita y honesta publicación. Entiendo que cuando una ramita pequeña crece y se convierte en una ramita más grande, luego tiene un tronco y luego comienza a ramificarse, puedes contar más con eso... en otras palabras, el orden en que suceden las cosas importa... es decir, movimientos constantes... es decir, 1 minuto se convierte en 5 minutos y luego en 15 minutos... cuando se trata de correlación... eso es algo que hay que buscar, hay un video que puedo encontrar al respecto si lo desea... la otra cosa, por lo poco que he entendido de mis lecturas, es que si una fuerte correlación es real, el precio generalmente no se desacopla...
En el archivo "correlation cheatsheets.pdf" se menciona otro PDF que viene primero, "Secretos de la Correlación", pero los enlaces en el PDF están rotos. ¿Lo tienes o sabes dónde conseguirlo? ¡

Gracias!
91
Cita
6 de mayo de 2015, 20:15
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mokuro89
{quote} dagoods en las hojas de trucos de correlación.pdf menciona otro PDF que viene primero, "Secretos de correlación", pero los enlaces en el PDF están rotos. ¿Lo tienes o sabes dónde conseguirlo? ¡Gracias!
Creo que esto podría ser
1
92
Cita
7 de mayo de 2015, 8:28 a. m.
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{quote}Creo que esto podría ser

Genial, ¿has visto el indicador ABR (rango promedio de la barra)? También existe un indicador llamado correlaciones negociables... así que sé que puedes extraer datos de correlaciones... ¿

Podrías crear un MQL de código abierto que use la idea del PDF sobre el seguimiento del rango?

Sería genial.
93
Cita
7 de mayo de 2015, 13:38
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dagoods
{quote} ¡Genial! ¿Has visto el indicador llamado ABR (rango promedio de la barra)? También existe un indicador llamado Correlaciones Comercializables... así que sé que puedes extraer datos de correlaciones... ¿Podrías crear un MQL de código abierto que use la idea del PDF sobre el seguimiento del rango? Sería genial.
No, nunca los he visto. Cuando tenga un poco más de tiempo les echaré un vistazo. Gracias.
94
Cita
7 de mayo de 2015, 13:43
 ShomariG| Se unió en febrero de 2015 | Estado: Que la paz te acompañe... | 75 publicaciones
¡Excelente trabajo! ¡Gracias por tu esfuerzo, bribón!
95
Cita
7 de mayo de 2015, 13:46
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a ShomariG
¡Excelente trabajo! ¡Gracias por tu esfuerzo, bribón!
De nada. ¡Espero que te sea útil!
96
Cita
7 de mayo de 2015, 14:49
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{quote} No, nunca los he visto. Cuando tenga un poco más de tiempo les echaré un vistazo. Gracias.

Genial... otra forma de ver "seguir" es ver a uno de los pares que está correlacionado para ascender en los rangos y pasar de, digamos, el nivel 3 al nivel 8 en el CSM de 8 niveles, y el otro no... digamos que el otro va del nivel 2 al nivel 5 o algo así... entonces puedes apostar que el otro seguirá al líder... espero tener algo de sentido aquí porque mi maní se confunde muy fácilmente, broma, jajaja
97
Cita
7 de mayo de 2015, 18:19
 del10s| Se unió en abril de 2014 | Estado: Trader | 15 publicaciones
El indicador no funciona.
¿Puedes arreglarlo en
mis pares con punto
AUDUSD.
EURUSD?
Imagen adjunta

98
Cita
7 de mayo de 2015, 18:27
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando del10s
El indicador no funciona. ¿Puedes arreglarlo? Mis pares son AUDUSD y EURUSD. {imagen}
Esto se debe a la información del bróker, no al indicador.
Para que la "espera" desaparezca, el par debe:
1. Haber entrado en la misma barra diaria que los demás pares; y
2. Haberse movido al menos un pip (para que el máximo y el mínimo no coincidan).

Espere un tiempo y vea si mejora.

Si no, abra los gráficos en D1 y compruebe que los ticks están llegando.

Mi bróker dejó de cotizar en USDCAD durante 40 minutos la semana pasada sin motivo alguno.
99
Cita
7 de mayo de 2015, 18:33
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dagoods
{quote} genial... otra forma de ver "seguir" es ver a uno de los pares que está correlacionado para ascender en los rangos y pasar de, digamos, el nivel 3 al nivel 8 en el CSM de 8 niveles, y el otro no... digamos que el otro va del nivel 2 al nivel 5 o algo así... entonces puedes apostar que el otro seguirá al líder... espero tener algo de sentido aquí porque mi maní se confunde muy fácilmente, broma, jajaja
Gracias, dagoods, entiendo lo que dices. Sería interesante investigarlo. Sigue al líder por la fortaleza de la moneda en lugar del rango de pips.

100
Cita
8 de mayo de 2015, 4:01 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Una cosa rápida:

elimino las versiones antiguas del indicador del hilo. Si quieres encontrar la versión actual de csDash:

1. Haz clic en el clip al principio del hilo.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: paperclip.png Tamaño: 21 KB


2. Seleccione el archivo que desea ver
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: file.png Tamaño: 32 KB


P6
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Seguiré compartiendo mis ideas y espero que creen un gran EA para beneficio de todos...

No es para ser honestos, sino para quienes aún no quieren compartir su código... entiendo y respeto su postura. De verdad. Pero... por favor, envíenme el MQL por privado. Lo pregunto porque opero con cuentas reales. No creo que nadie apueste dinero real por algo oculto. ¿Qué pasa si mueres o desapareces y necesito una versión actualizada? Vamos, chicos... creo que es justo que todos los que trabajan duro compartan... no soy egoísta...
En fin, volviendo a las ideas:

aquí tienen... adjunto,


dediquen tiempo a todo esto.
Imagen(es) adjunta(s) (haga clic para ampliar)
Haga clic para ampliar Nombre: estrategias monetarias.PNG Tamaño: 101 KB
Haga clic para ampliar Nombre: secretos de correlación revelados.PNG Tamaño: 101 KB
1
102
Cita
8 de mayo de 2015, 11:15 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dagoods
Seguiré compartiendo mis ideas y espero que creen un gran asesor experto para el beneficio de todos... No es para ser honestos, sino para quienes aún no quieren compartir su código... entiendo y respeto su postura. De verdad. Pero... por favor, envíenme el MQL por privado. Lo pregunto porque opero con cuentas reales. No creo que nadie apueste dinero real en algo oculto. Creo que es justo que todos los que trabajan duro compartan... no soy egoísta... En fin, volviendo a las ideas: aquí tienen... adjunto...
Gracias por tu publicación, dagoods.

Antes, MQL4 era increíblemente fácil de descompilar. Invariablemente, cualquier ejecutable que compartieras libremente acababa en algún sitio fraudulento donde se vendía. O, modificado y defectuoso, pero aún llevaba tu nombre. De ahí que mucha gente se resistiera a compartir nada en internet. A diario veo código descompilado en foros. 

Programar grandes proyectos puede llevar cientos de horas. Creo que muchos no programadores no comprenden cuánto tiempo pueden llevar estas cosas. Y eso sin contar los años de estudio necesarios para aprender a hacerlo. Lo que puede tardar 5 minutos en concebirse como una idea, puede llevar muchísimo tiempo materializarse (solo para que el programador descubra que la persona inicial perdió el interés o que la idea no tenía ningún mérito). Pero ahora me he desviado del tema. Para acelerar las cosas, muchos programadores crean bibliotecas con su código personalizado. Estas bibliotecas serán el resultado de años de trabajo duro y, para algunos, la base de su sustento como programadores.

El problema de compartir el código fuente es que se revelan todas las bibliotecas asociadas. Años de programación totalmente ajenos al indicador se divulgan simplemente porque están en la misma biblioteca. Un complejo algoritmo de cifrado termina compartiéndose con el mundo en un indicador que indica la hora en Tokio... ¡poco ideal!

Piénsalo así: algunos programadores comparten la idea X con gusto, pero prefieren mantener las ideas Y y Z en privado (quizás Y y Z sean ideas de alguien que no quiere compartirlas con todo el mundo). De la misma manera, algunos operadores comparten la Estrategia A con gusto, pero no las estrategias B y C.

El problema con internet es que, una vez que algo está "ahí fuera", a menudo no hay forma de recuperarlo o desactivarlo si es incorrecto o se ha abusado de él.

Ahora que Metaquotes ha reforzado su protección, encontrarás más programadores dispuestos a compartir sus ejecutables para el beneficio de todos. Esto es positivo. Antes, mucha gente no compartía nada porque no podía proteger su código.

También encontrarás cada vez más gente en los foros dispuesta a dedicar horas y horas a programar para beneficio de otros, pero que no comparte su código fuente por las razones que he mencionado. A menudo, ni siquiera usamos lo que programamos. Simplemente lo hacemos para ayudar a otros o nos parece un reto interesante.

Sin embargo, entiendo tu preocupación por saber qué hay dentro de la caja negra. Sería extremadamente cauteloso con cualquier asesor experto en trading que no haya escrito yo o que no pueda comprobar. Al menos con csDash, puedes comprobar manualmente los datos en cualquier momento para verificar su integridad. Es una tarea laboriosa (por eso automatizamos las cosas), pero es posible.

Solo necesitas la fórmula:
(oferta-baja) / (alta-baja)


Y el factoring:
0,00-0,03 = 0

0,03-0,10 = 1

0,10-0,25 = 2

0,25-0,40 = 3

0,40-0,50 = 4

0,50-0,60 = 5

0,60-0,75 = 6

0,75-0,90 = 7

0,90-0,97 = 8

0,97-1,00 = 9


Espero que esto haya ayudado a responder algunas de las preguntas sobre por qué generalmente no comparto mi código fuente (con algunas excepciones).

1
103
Cita
8 de mayo de 2015, 11:23 a. m.
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{quote} Gracias por tu publicación, dagoods. Antes, MQL4 era facilísimo de descompilar. Invariablemente, cualquier ejecutable que compartieras libremente acababa en algún sitio web fraudulento. O, modificado y defectuoso, pero aún llevaba tu nombre. De ahí que mucha gente no estuviera dispuesta a compartir nada en internet. Programar grandes proyectos puede llevar literalmente cientos de horas. Creo que muchos no programadores no comprenden cuánto tiempo pueden tardar estas cosas. Y eso sin contar los años de estudio para aprender a hacerlo. ¿Qué...?
Estoy bastante seguro de que tengo más horas que tú... Por mi parte, entiendo perfectamente lo que dices.

Lo comparto, independientemente de ese tipo de preocupaciones. Esa es la decisión que he tomado. 


Mira mis ejemplos de arriba. ¡Gracias! ¡ 

Eres lo máximo!
104
Cita
8 de mayo de 2015, 21:06
 dlouw| Se unió en febrero de 2009 | Estado: Comerciante | 136 publicaciones
Citando patas
¡Excelente trabajo, Andrew! Quizás no sea un factor relevante ni práctico siquiera, pero es solo una reflexión: ¿vale la pena (o incluso es posible) ponderar la fuerza relativa de una divisa por algún tipo de volumen? Es decir, si el volumen del EURUSD es el doble que el del AUDUSD, entonces el EURUSD tendría el doble de ponderación al calcular la fuerza relativa del USD.
He dedicado tiempo a investigar esto. Con todo respeto, me arriesgaré a decir que no. La razón es que el único volumen que podemos ver es el de nuestro propio bróker minorista. No hay datos de volumen compilados para múltiples brókeres ni, aún más importantes, para transacciones bancarias mayoristas. Por lo tanto, los datos de volumen disponibles no representan el volumen real que impulsa el precio. Es bastante inútil; es como lanzar una moneda al aire.

Es un trabajo increíble, de verdad. Ojalá tuviera la mitad de tu talento para programar. Gracias por compartir. Creo que has dado en el clavo con la correlación. Otra cosa que he estado investigando es el cálculo del marco temporal de los medidores de fuerza. Se basa en una barra, no en un marco temporal fijo. Esto parece correcto para un indicador rezagado, pero para datos actuales puede generar grandes variables. Por ejemplo, el rango de precios puede basarse en un marco temporal de 0 a 23:59 en una barra diaria. Esto implica mucha varianza. Probablemente podría encontrar los cálculos para solucionar esto en MT4, pero no puedo hacerlo perfecto.

Green Pips,
dlouw
105
Cita
9 de mayo de 2015, 4:13 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dlouw
{quote} He dedicado tiempo a investigar esto. Con todo respeto, me arriesgaré a decir que no. La razón es que el único volumen que podemos ver es el de nuestro propio bróker minorista. No hay datos de volumen compilados para varios brókeres ni, aún más importantes, para transacciones bancarias mayoristas. Por lo tanto, los datos de volumen disponibles no representan el volumen real que impulsa el precio. Son bastante inútiles; es como lanzar una moneda al aire. Es un trabajo increíble, de verdad. Ojalá tuviera la mitad de tu talento para programar. Gracias por compartir. Creo que has dado con algo...
Gracias por tu aportación, dlouw. 

Si te entiendo bien, creo que esto es algo que también he estado considerando. En lugar de basarlo en la barra D1 (que significa solo 1 hora de datos a la 01:00 y 23 horas de datos a las 23:00), que sea un periodo continuo de 24 horas. O el período que se elija. ¿Es eso a lo que te referías o te he malinterpretado?
106
Cita
9 de mayo de 2015, 9:52 a. m.
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{quote} Gracias por tu aportación, dlouw. Si te entiendo bien, creo que esto es algo que yo también he estado considerando. En lugar de basarlo en la barra D1 (que significa solo 1 hora de datos a la 01:00 y 23 horas de datos a las 23:00), que sea un periodo continuo de 24 horas. O el período que se elija. ¿Es eso a lo que te referías o te he malinterpretado?

¡Suena genial, chicos! ¡Gracias!
107
Cita
10 de mayo de 2015, 17:01
 dlouw| Se unió en febrero de 2009 | Estado: Comerciante | 136 publicaciones
Citando a honestknave
{quote} Gracias por tu aportación, dlouw. Si te entiendo bien, creo que esto es algo que yo también he estado considerando. En lugar de basarlo en la barra D1 (que significa solo 1 hora de datos a la 01:00 y 23 horas de datos a las 23:00), que sea un periodo continuo de 24 horas. O el período que se elija. ¿Es eso a lo que te referías o te he malinterpretado?
¡Bingo, bribón! ¡Aquí está! Basado en iHighest, iLowest y Close. Esto no era fácil de hacer en las hojas .xls originales, pero con MT4 es posible. Creo que esto nos dará indicadores más estables y precisos.
108
Cita
12 de mayo de 2015, 18:20
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dlouw
{quote} ¡Bingo, bribón! ¡Aquí está! Basado en iHighest, iLowest y Close. Esto no era fácil de hacer en las hojas .xls originales, pero con MT4 es posible. Creo que esto nos dará indicadores más estables y precisos.
Definitivamente investigaré esto, voy a estar un poco ocupado durante las próximas semanas, pero continuaré tan pronto como tenga la oportunidad.
109
Cita
14 de mayo de 2015, 4:41 a. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a honestknave
Tuve la oportunidad de revisar csDash este fin de semana y le hice algunos cambios. La versión anterior de csDash no tiene ningún problema, así que si no te gustan los cambios, puedes seguir usando la versión anterior. No he probado la nueva versión en el mercado, así que pido disculpas de antemano si detecta algún fallo. Ahora es un indicador (no un experto). ¿Por qué? Solo puedes añadir un experto por gráfico, pero puedes añadir varios indicadores. ¿Qué significa esto? Debes guardar csDash.ex4 en la carpeta de Indicadores. Los elementos visuales son más configurables. ¿Por qué? Preferencias del usuario...

Hola honestknave :
Si es posible, por favor, añade una opción para que podamos seleccionar si iniciar la información en modo condensado o expandido .
¡Muchas gracias de nuevo!
pax
110
Cita
14 de mayo de 2015, 18:23
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Entonces tuve un poco de tiempo para abordar los problemas menores , pero no lo suficiente como para mirar la opción continua discutida anteriormente. 

Versión 1.10
Se cambió la visualización del spread de puntos a pips
Se agregó una opción para la vista predeterminada (expandida o condensada)
Se agregó una opción de alerta por correo electrónico
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   119 KB | 1214 descargas
111
Cita
15 de mayo de 2015, 5:01 a. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Citando a honestknave
Entonces tuve un poco de tiempo para abordar los problemas menores , pero no lo suficiente como para mirar la opción continua discutida anteriormente. Versión 1.10 Se cambió la visualización del spread de puntos a pips Se agregó una opción para la vista predeterminada (expandida o condensada) Se agregó la opción de alerta por correo electrónico {archivo}
Hola honestknave

Gracias por los cambios, como la opción de vista predeterminada. 

Gracias.
¡¡¡No te limites!!!
112
Cita
15 de mayo de 2015, 5:14 a. m.
 Kooza| Se unió en agosto de 2014 | Estado: Trader | 58 publicaciones
Citando a honestknave
Entonces tuve un poco de tiempo para abordar los problemas menores , pero no lo suficiente como para mirar la opción continua discutida anteriormente. Versión 1.10 Se cambió la visualización del spread de puntos a pips Se agregó una opción para la vista predeterminada (expandida o condensada) Se agregó la opción de alerta por correo electrónico {archivo}
Hola honestknave,
¿sería un problema importante incorporar una opción de selección de pares que permita seleccionar los pares favoritos (EU, EJ, GU, GJ, AU, AJ, NU, NJ)? Me resulta difícil seguir estos pares entre el panel completo de 28 pares que fluctúan constantemente. Si es posible, ¿podrías configurar este panel para que marque una señal de compra/venta cuando la diferencia de fuerza alcance +2,56 o -2,56 (el valor que el sistema de Nasap utiliza para filtrar si el mercado o los pares de divisas están en rango o en tendencia)?
Kooza
113
Cita
15 de mayo de 2015, 11:32 a. m.
 ShomariG| Se unió en febrero de 2015 | Estado: Que la paz te acompañe... | 75 publicaciones
Citando a honestknave
Entonces tuve un poco de tiempo para abordar los problemas menores , pero no lo suficiente como para mirar la opción continua discutida anteriormente. Versión 1.10 Se cambió la visualización del spread de puntos a pips Se agregó una opción para la vista predeterminada (expandida o condensada) Se agregó la opción de alerta por correo electrónico {archivo}
¡Genial! ¡Gracias por la actualización!
114
Cita
16 de mayo de 2015, 9:41 a. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a honestknave
Entonces tuve un poco de tiempo para abordar los problemas menores , pero no lo suficiente como para mirar la opción continua discutida anteriormente. Versión 1.10 Se cambió la visualización del spread de puntos a pips Se agregó una opción para la vista predeterminada (expandida o condensada) Se agregó la opción de alerta por correo electrónico {archivo}
¡Excelente actualización!
¡Gracias , honestknave !
115
Cita
16 de mayo de 2015, 14:24
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mosiskv
{quote} Hola honestknave Gracias por los cambios, como la opción de vista predeterminada. Gracias.
Me alegro que te guste
116
Cita
16 de mayo de 2015, 14:31
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Kooza
{quote} Hola, honestknave. ¿Sería un problema importante incorporar una opción de selección de pares que permita seleccionar los pares favoritos, por ejemplo, (EU, EJ, GU, GJ, AU, AJ, NU, NJ)? Me resulta difícil seguir estos pares entre el panel completo de 28 pares que fluctúan constantemente. Si es posible, ¿podrías configurar este panel para que marque una señal de compra/venta cuando la diferencia de fuerza alcance +2,56 o -2,56 (el valor que el sistema de Nasap utiliza para filtrar si el mercado o los pares de divisas están en rango o en tendencia)? Kooza
Hola Kooza,

podría seleccionar pares más adelante, cuando tenga más tiempo.

Puedes configurar la diferencia de potencia de las alertas como prefieras:
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: diff.png Tamaño: 111 KB

También puedes establecer el umbral inferior en 0 y el superior en 10. Esto significa que solo recibirás alertas sobre la diferencia de fuerza.

Sin embargo, acabo de notar un fallo en las alertas que revisaré y publicaré una nueva versión más adelante.
117
Cita
16 de mayo de 2015, 14:32
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a ShomariG
{quote} ¡Genial! ¡Gracias por la actualización!
De nada

Citando a Pax
{quote} ¡Excelente actualización! ¡Gracias, honestknave!
Gracias pax
118
Cita
16 de mayo de 2015, 16:24
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Versión 1.11

Corregido: error de alerta (no se generan alertas de compra)
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   119 KB | 1609 descargas
119
Cita
16 de mayo de 2015, 16:30 horas
 Kooza| Se unió en agosto de 2014 | Estado: Trader | 58 publicaciones
Citando a honestknave
{quote} Hola Kooza, podría seleccionar pares más adelante, cuando tenga más tiempo. Puedes configurar el diferencial de intensidad para las alertas como prefieras: {image} También puedes configurar el umbral inferior en 0 y el superior en 10. Esto significa que solo recibirás alertas sobre el diferencial de intensidad. Sin embargo, acabo de notar un fallo en las alertas que revisaré y publicaré una nueva versión más adelante.
Hola Honestknave,
gracias por tus comentarios informativos y por compartir desinteresadamente tu panel con nosotros
Kooza.
120
Cita
17 de mayo de 2015, 11:49 a. m.
 francisakz| Se unió en marzo de 2013 | Estado: Comerciante | 252 publicaciones
Citando a honestknave
Versión 1.11 Corregido: error de alerta (no se generan alertas de compra) {archivo}
No aparece en el gráfico y está en la carpeta Expert. ¿Alguien tiene este problema? Gracias, Honestnave


P7
 Luisetano| Se unió en marzo de 2014 | Estado: Comerciante | 66 publicaciones
Citando a francisakz
{quote} No aparece en el gráfico y está en la carpeta Expert. ¿Alguien tiene este problema? Gracias, Honestnave.
Carpeta incorrecta, ya no es un EA, sino que va a la carpeta del indicador.
122
Cita
17 de mayo de 2015, 15:52
 francisakz| Se unió en marzo de 2013 | Estado: Comerciante | 252 publicaciones
Citando a Louisetano
{quote} Carpeta incorrecta, ya no es un EA, sino que va en la carpeta del indicador.

Gracias amigo, te lo agradezco.
123
Cita
17 de mayo de 2015, 22:48
 HanneleSe unió en septiembre de 2012 | Estado: Trader | 210 publicaciones
Citando a francisakz
{quote} No aparece en el gráfico y está en la carpeta Expert. ¿Alguien tiene este problema? Gracias, Honestnave.
Intente instalarlo en la carpeta del indicador. Lo siento, acabo de ver la última respuesta. 
Saludos,
Hannele.
124
Cita
17 de mayo de 2015, 23:44
 san99| Se unió en enero de 2014 | Estado: Trader | 695 publicaciones
No me cargaba porque me daba un error porque mi bróker no ofrece NZD/CAD. Intenté revisar la configuración, pero no puedo activar ni desactivar pares individuales.
Introducir firma
125
Cita
18 de mayo de 2015, 4:24 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Buenos días Andrés
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: GU Trade 1 - 5182015.gif Tamaño: 63 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
126
Cita
18 de mayo de 2015, 6:36 a. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a 919gilead
Buenos días Andrew {imagen}
¡Excelente operación, 919gilead !
Si pudieras, por favor, comparte las configuraciones de los gráficos.
¡Gracias,
Pax !
127
Cita
18 de mayo de 2015, 7:05 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Kooza
{quote} Hola Honestknave, gracias por tus comentarios informativos y por compartir desinteresadamente tu panel con nosotros Kooza
De nada
128
Cita
18 de mayo de 2015, 7:06 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Louisetano
{quote} Carpeta incorrecta, ya no es un EA, sino que va en la carpeta del indicador.
Citando a Hannele
{quote} Intente instalarlo en la carpeta del indicador. Lo siento, acabo de ver la última respuesta. Saludos, Hannele.
Gracias por ayudar
129
Cita
18 de mayo de 2015, 7:09 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a san99
No me cargaba porque me daba un error porque mi bróker no ofrece NZD/CAD. Intenté revisar la configuración, pero no puedo activar ni desactivar pares individuales.
Lo sentimos, la versión actual no permite desactivar pares individuales.

¿Tu bróker no ofrece NZD/CAD? ¿Has probado a hacer clic derecho en la ventana de MarketWatch y seleccionar "Mostrar todo"?

Imagen adjunta

130
Cita
18 de mayo de 2015, 7:12 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a 919gilead
Buenos días Andrew {imagen}
Me alegro de que las herramientas te estén funcionando bien, George.
131
Cita
18 de mayo de 2015, 7:22 a. m. | Editado a las 7:40 a. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Citando a honestknave
Versión 1.11 Corregido: error de alerta (no se generan alertas de compra) {archivo}
Hola honestknave,

me preguntaba por qué no entendía algunas alertas, pero no tuve tiempo de investigar.

Lo comprobaré esta semana. Gracias por la solución.

Saludos.

PD: Sería bueno limitar los pares (solo visualización) si es posible sin afectar el cálculo general
. ¿Existe un límite de actualización óptimo (milisegundos)? Quizás podrías explicar más sobre esta función.

Lo olvidé. ¿Quizás también la opción de ubicación de ventanas?
¡¡¡No te limites!!!
132
Cita
18 de mayo de 2015, 22:55
 san99| Se unió en enero de 2014 | Estado: Trader | 695 publicaciones
Citando a honestknave
{quote} Lo sentimos, la versión actual no permite desactivar pares individuales. ¿Tu bróker no ofrece NZD/CAD? ¿Has probado a hacer clic derecho en la ventana de MarketWatch y seleccionar Mostrar todo? {image}
Hola, sí, volví a investigar esto (de hecho, ya lo había investigado antes y un CSM diferente tenía este par como parte de sus cálculos), pero mi corredor, por alguna razón, no ofrece este par.
Introducir firma
133
Cita
19 de mayo de 2015, 2:18 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
{quote} Me alegro de que las herramientas te estén funcionando bien, George.
Sí, las herramientas funcionan muy bien, Andrew, y muchas gracias por tu genial trabajo.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
134
Cita
19 de mayo de 2015, 2:25 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Pax
{quote} ¡Excelente operación, 919gilead! Si pudieras, por favor, comparte las configuraciones de los gráficos. ¡Gracias! pax
Gracias, Pax.

No quiero publicar ningún indicador ni plantilla aquí, ya que iría en contra del objetivo de este hilo, como lo indicó Andrew en la primera publicación.

Citando a honestknave
Estoy creando un hilo aquí porque:
1. Algunos sistemas diferentes en FF usan el medidor de fuerza monetaria, por lo que tiene más sentido tener un solo hilo para ello; y
2. Evita desviarse del tema en esos hilos.
Te enviaré un mensaje privado más tarde cuando esté libre y no esté operando.

Shalom.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
135
Cita
19 de mayo de 2015, 2:40 a. m.
 gaztrader29| Se unió en octubre de 2010 | Estado: Comerciante | 29 publicaciones
¿Podrías enviarme un correo electrónico también, por favor? 919gilead
Gracias Gazza
136
Cita
19 de mayo de 2015, 3:19 a. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a 919gilead
{quote} Gracias, Pax. No quiero publicar ningún indicador ni plantilla aquí, ya que anularía el objetivo de este hilo, como lo indicó Andrew en la primera publicación. {quote} Te enviaré un mensaje privado más tarde, cuando esté libre y no esté operando. Shalom
¡Gracias 919gilead !
Lo siento, honestknave , no fue mi intención.
Pax
137
Cita
19 de mayo de 2015, 3:25 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
{quote} Me alegro de que las herramientas te estén funcionando bien, George.
Hola Capitán,

estaba a punto de dormirme cuando noté que algo se estaba gestando en tus herramientas. Gracias una y otra vez, no puedo agradecerte lo suficiente, 

Shalom.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EJ Trade 1 - 5182015.gif Tamaño: 73 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
138
Cita
19 de mayo de 2015, 3:41 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Hola Pax y Gaztrader,

llevo varias semanas probando los medidores de fuerza de divisas con Andrew, y la configuración de mis gráficos no influye. Incluso el CSM es solo una herramienta de gestión de entradas y operaciones; no es un indicador independiente; necesitas tu propio sistema y estilo de trading. Eliminaré la mayoría de los indicadores que ven en mi gráfico, ya que no son necesarios. Los tenía activados mientras tomaba capturas de pantalla para ver cuál era el más efectivo para filtrar mis operaciones, ya que el CSM también genera señales falsas .

Voy 8 horas por detrás de Londres y me voy a dormir un poco, pero cuando tenga un poco más de tiempo, y con el permiso de Andrew, publicaré los nombres y las tintas de los indicadores, pero no el indicador en sí, para no distraer a los traders del objetivo principal de este hilo.

Gracias.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
139
Cita
19 de mayo de 2015, 4:38 a. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a 919gilead
Hola Pax y Gaztrader, llevo unas semanas probando los medidores de fuerza de divisas con Andrew, y no es la configuración de mis gráficos la que marca la diferencia. Incluso el CSM es solo una herramienta de gestión de entradas y operaciones; no es un indicador independiente; necesitas tu propio sistema y estilo de trading. Eliminaré la mayoría de los indicadores que ven en mi gráfico, ya que no son necesarios. Los tenía activados mientras tomaba capturas de pantalla para ver cuál era el más efectivo para filtrar mis operaciones, ya que el CSM también genera señales falsas. Estoy...
Entiendo perfectamente 919gilead , gracias
pax
140
Cita
19 de mayo de 2015, 8:55 a. m.
 rey de micro| Se unió en julio de 2011 | Estado: Comerciante | 251 publicaciones
Citando a 919gilead
{quote} Gracias, Pax. No quiero publicar ningún indicador ni plantilla aquí, ya que anularía el objetivo de este hilo, como lo indicó Andrew en la primera publicación. {quote} Te enviaré un mensaje privado más tarde, cuando esté libre y no esté operando. Shalom
no compartas. tal vez alguien se coma tu indi 

ja, jaaaa haaaaa mr shalom


P8
| Se unió en julio de 2014 | Estado: Trader | 250 publicaciones
Citando a 919gilead
{quote} Hola Capitán, estaba a punto de dormirme cuando noté que algo se estaba gestando en tus herramientas. Gracias una y otra vez, no puedo agradecerte lo suficiente, Shalom {image}
¡Guau! ¿Podrías explicarme qué está pasando con tus gráficos? Se ven geniales.
142
Cita
19 de mayo de 2015, 10:32 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Solo quiero agradecerles a todos por su paciencia. Actualmente, tengo entre 15 y 20 minutos al día para responder mensajes y corregir el código. 

Es probable que esto continúe durante algunas semanas más, así que tengan paciencia. ¡Espero que la normalidad vuelva pronto!
143
Cita
19 de mayo de 2015, 10:37 a. m.
 Fins.sbr.jr| Se unió en enero de 2014 | Estado: Trader | 42 publicaciones
Citando a honestknave
Tenga en cuenta: no estoy pensando en hacer demasiado desarrollo en esta versión porque mi enfoque principal está en una versión MTF (aún no está lista): {imagen}
¿Esto es inédito?
144
Cita
19 de mayo de 2015, 10:38 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mosiskv
Sería bueno limitar los pares (solo visualización) si es posible sin alterar el cálculo general.
Lo revisaré en cuanto tenga más tiempo libre. Creo que será útil para mucha gente.

Citando a mosiskv
¿Existe un "límite de actualización (milisegundos) óptimo"? ¿Quizás pueda explicar un poco más esta función?
El propósito de esta función es establecer la frecuencia con la que csDash revisa los 28 pares y recalcula los valores. Si se establece demasiado tiempo, la precisión disminuirá a medida que el precio fluctúe antes de que csDash se actualice. Si se establece demasiado corto, se aumenta la carga de procesamiento (pero consulte mi nota a continuación) y, además, los gráficos fluctuarán mucho durante períodos de volatilidad.
Configuración óptima: ninguna. Intento que todo mi código se ejecute con la mayor eficiencia posible. Por ejemplo, cada bucle de csDash registra menos de un milisegundo en mi (bastante mediocre) netbook.

Citando a mosiskv
Me olvidé. ¿Quizás también la opción de ubicación de ventanas?
Ya debería estar ahí:
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: screen position.png Tamaño: 89 KB
145
Cita
19 de mayo de 2015, 10:39 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a san99
{quote} Hola, sí, volví a investigar esto (de hecho, ya lo había investigado antes y un CSM diferente tenía este par como parte de sus cálculos), pero mi corredor, por alguna razón, no ofrece este par.
Lamento escuchar eso san99
146
Cita
19 de mayo de 2015, 10:40 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a 919gilead
{quote} Hola Capitán, estaba a punto de dormirme cuando noté que algo se estaba gestando en tus herramientas. Gracias una y otra vez, no puedo agradecerte lo suficiente, Shalom {image}
De nada George
147
Cita
19 de mayo de 2015, 10:42 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a 919gilead
Pero cuando tenga un poco más de tiempo y con el permiso de Andrew, publicaré los nombres y las tintas de los indicadores, pero no el indicador en sí, para no distraer a los traders del objetivo principal de este hilo. Gracias.
No hay problema conmigo
148
Cita
19 de mayo de 2015, 10:44 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Fins.sbr.jr
{quote}¿Esto es inédito?
Por el momento, solo está disponible para probar con un comerciante (¡no hay premio por adivinar quién!).

Necesitará algo de trabajo cosmético antes de ser lanzado, pero en este momento básicamente no tengo tiempo libre.
149
Cita
20 de mayo de 2015, 8:15 a. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Hola Honestknave,

gracias por tus respuestas.

Estoy empezando a usar tu indicador (intentando integrarlo/utilizarlo óptimamente con mi propio sistema/estilo de trading)
. Tras corregir la alerta de compra, se correlaciona mucho mejor con mi propio sistema/estilo de trading.

Ubicación de la ventana (disculpen la ambigüedad, en realidad me refería a la ventana 1, etc.
). Podría funcionar bien con una visualización de pares limitada.

"De todas formas, intento que todo mi código funcione de la forma más eficiente posible".
¡FELICIDADES por esto! Creo que hay mucho código espagueti por ahí.

Gracias de nuevo por compartir
. Saludos.
¡¡¡No te limites!!!
150
Cita
20 de mayo de 2015, 15:26
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
{quote}No hay problema conmigo
Gracias Andrew
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
151
Cita
20 de mayo de 2015, 16:51
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Hola Pax y Gaztrader,

disculpad la demora. Aquí tenéis.
 

La cinta MA que uso para mi canal MA se puede descargar aquí . La primera tiene una EMA de 35 de máximo y mínimo, mientras que la segunda tiene una EMA de 175 de máximo y mínimo. Experimento mucho con la configuración, que he modificado hoy. Así que debes encontrar la que mejor se adapte a ti.
El minigráfico de Pipware se puede descargar aquí y necesita tener las fuentes de ventana correctas para que se muestre correctamente.
Puede obtener la vela M desde aquí : mi gráfico muestra la vela M15 en el gráfico M1
También tengo el H1 alto y bajo y también puedes encontrarlo aquí con el H4 alto y bajo también
Yo uso la vela RSI y puedes encontrarla aquí si te interesa.
La línea abierta diaria con extensión al segundo día se puede encontrar aquí
Para los pivotes, uso el THV y aquí está el enlace.
No puedo encontrar inmediatamente el panel de visualización exacto para la extensión, el rango, los máximos y mínimos del día, etc. que estoy usando, pero esta es otra buena alternativa aquí.
Los indicadores en las ventanas inferiores son los indicadores del índice Didi. Puedes encontrar el indicador de línea aquí y el histograma aquí . Uso el M15 en la primera ventana y puedes ver mi configuración en las otras tres ventanas del gráfico.
Espero que esto ayude. Si no he incluido enlaces a alguno, significa que se trata de indicadores comerciales o de algo que aún está en pruebas y no está disponible públicamente.

Shalom 

George

Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
7
152
Cita
20 de mayo de 2015, 17:12
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a 919gilead
Hola Pax y Gaztrader, disculpen la demora. Aquí tienen la Cinta de Media Móvil (MA Ribbon) que uso para mi Canal de Media Móvil . La primera muestra la MME de 35 de máximo y mínimo, mientras que la segunda muestra la MME de 175 de máximo y mínimo. Experimento mucho con la configuración, que he modificado hoy. Así que deben encontrar la que les funcione. El Minigráfico de Pipware se puede descargar aquí ; necesitan tener la ventana correcta...
¡Muchas gracias George !

pax
153
Cita
20 de mayo de 2015, 17:27
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a yorkshirelad
{quote} ¡Guau! ¿Podrías explicarme qué sucede con tus gráficos? Se ven geniales.
Hola Yorkshirelad,

no sé exactamente qué explicar, ya que solo opero con fuerza y ​​debilidad alrededor del soporte y la resistencia. A veces ignoro por completo la fuerza y ​​la debilidad, ya que anticipo un posible fallo en los niveles de soporte/resistencia, como esta operación de la UE que tomé esta mañana y cerré por unos 9 pips.

Utilizo 2 canales MA (35 y 175): uno para M1 (EMA de 35) y el otro para M5 (EMA de 35 x 5 = 175). Por lo tanto, cuando encuentro que el precio en una tendencia bajista retrocede y va más allá del canal MA de M5 y el canal MA de M1 permanece por debajo del canal MA de M5, estoy listo para vender antes de que el CSM dé la señal, siempre que el precio flaquee en el nivel S/R, que fue lo que hice en esta operación. El precio flaqueó en un RN y yL (mínimo de ayer) y vendí con un riesgo de 12 pips, esperando una RRR de 1:1 si el precio continuaba hasta y por debajo del canal MA de M1. Cerré la operación ante la primera señal de debilidad, ya que no tenía confirmación del CSM de que la operación continuara y asumí mis 9 pips.

Normalmente, miro lo que muestra el medidor CSM en el HTF y el HTF inmediatamente inferior, luego reviso mi gráfico para ver si tengo una configuración similar en los canales de media móvil (MA). Si es así, empiezo a observar el CSM en el LTF y me preparo para entrar en el siguiente nivel S/R. Por eso me encuentro entrando casi cuando el precio se dispara por encima del nivel S/R, pero no siempre funciona así.

Espero que mis divagaciones tengan sentido.

Shalom
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EU Trade 1a - 5202015.gif Tamaño: 61 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
1
154
Cita
20 de mayo de 2015, 17:27
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Pax
{quote} ¡Muchas gracias George! pax

Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
155
Cita
20 de mayo de 2015, 17:40
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Este es otro ejemplo de una operación que acabo de realizar, pero con soporte del CSM. El precio retrocede más allá del canal de la media móvil de 5M, pero sin que el canal de la media móvil de 1M cierre por encima del canal de la media móvil de 5M; encuentra resistencia en la línea de apertura de ayer, y esperé a que el precio flaqueara. El CSM apoyó mi decisión de vender, incluso en el período bajo, y la operación generó ganancias casi de inmediato. Disculpen, este indicador aún está en fase de prueba y aún no está disponible públicamente.

Shalom.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: ACH Trade 2 - 5202015.gif Tamaño: 79 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
156
Cita
21 de mayo de 2015, 9:53 a. m. | Editado a las 10:12 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Buen día
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EU Trade 1 - 5212015.gif Tamaño: 77 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
157
Cita
21 de mayo de 2015, 10:10 a. m. | Editado a las 10:24 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a 919gilead
Buenos días {imagen}
Por eso debemos ser rápidos al mover el stop a BE y observar cuándo el precio empieza a flaquear con 15 velas M1 moviéndose lateralmente dentro de un rango de 2-3 pips. Cerraré la operación y esperaré otra oportunidad. Esta se cerró por 8 pips.
Imagen adjunta

Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
158
Cita
21 de mayo de 2015, 10:23 a. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a 919gilead
Este es otro ejemplo de una operación que acabo de realizar, pero con soporte del CSM. El precio retrocede más allá del canal de la media móvil de 5M, pero sin que el canal de la media móvil de 1M cierre por encima del canal de la media móvil de 5M; encuentra resistencia en la línea de apertura de ayer, y esperé a que el precio flaqueara. El CSM apoyó mi decisión de vender, incluso en el período bajo, y la operación generó ganancias casi de inmediato. Disculpen, este indicador aún está en fase de prueba y aún no está disponible públicamente. Shalom {imagen}
¡Bien hecho, George!
Nunca podría operar sin gráficos de MTF.
Y se me hace agua la boca mirando el medidor de fuerza de MTF.

¡Bien hecho!

Y gracias por todos los consejos.
159
Cita
21 de mayo de 2015, 10:26 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Pax
{quote} ¡Genial, George! Nunca podría operar sin gráficos MTF. Y se me hace agua la boca mirando el medidor de fuerza MTF. ¡Tranquilo!
Gracias Pax.

Todavía estoy en el laboratorio probando 

a Shalom.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
160
Cita
21 de mayo de 2015, 11:26 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Pax
{quote} ......... Y se me hace agua la boca mirando el medidor de fuerza MTF.................
Pero tienes uno que puedes adaptar.
Imagen adjunta

Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad



P9
919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Estaba probando esto para comprobar la fiabilidad del CSM sin siquiera esperar a que se rompiera el nivel S/R. Obtuve una ganancia de 4-5 pips y cerré inmediatamente, ya que siempre me gusta que se rompa el nivel S/R como confirmación adicional. Confía en tu ventaja y opera.

Listo por hoy a menos que algo inusual me llame la atención.

¡Buenas operaciones a todos! ¡Shalom! 

Gracias de nuevo, Andrew.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: GU Trade 1 - 5212015.gif Tamaño: 88 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
162
Cita
21 de mayo de 2015, 11:48 a. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a 919gilead
{quote}Pero tienes uno que puedes adaptar {image}
Sí, lo intenté con diferentes TF, pero no se me ocurrió usar varias instancias de csDash.
Gracias,
Pax.
163
Cita
21 de mayo de 2015, 12:02 p. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Pax
{quote} Sí, probé con diferentes TF, pero no se me ocurrió usar varias instancias de csDash. Gracias, Pax.
De nada. 

Me voy a trabajar ahora, pero mis días están contados, ya que me estoy preparando para dedicarme al trading a tiempo completo.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
164
Cita
22 de mayo de 2015, 7:54 a. m.
 masofras| Se unió en mayo de 2014 | Estado: Trader | 50 publicaciones
Hola honestknave y otros traders,

les preguntaría si podrían agregar una función adicional a su csDash. La diferencia promedio de pares (COMPRA - VENTA en fuerza relativa) nos permite ver el indicador de mercado (mercado alcista, etc.). Esto puede ayudar a recopilar información adicional. Es

solo mi opinión.


Que tengan un buen día, 

Masofras.
165
Cita
22 de mayo de 2015, 9:30 a. m.
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando masofras
Hola honestknave y otros traders, les preguntaría si podrían agregar una función adicional a su csDash. La diferencia promedio de pares (COMPRA - VENTA en fuerza relativa) nos permite ver el indicador de mercado (mercado alcista, etc.). Esto puede ayudar a recopilar información adicional. Es solo mi opinión. Que tengan un buen día, Masofras.

¿No lo hace ya? ¿No es esa misma fórmula en la hoja de cálculo? Si tienes otra fórmula, por favor, publica cuál es exactamente.

Gracias.
166
Cita
22 de mayo de 2015, 10:03 a. m.
 Kooza| Se unió en agosto de 2014 | Estado: Trader | 58 publicaciones
Citando a dagoods
{quote} ¿No lo hace ya? ¿No es esa misma fórmula en la hoja de cálculo? Si tienes otra fórmula, por favor, publica cuál es exactamente. Gracias.
Si leo entre líneas, su idea podría ser sumar la columna "Dif" de los 28 pares y dividirla entre 28 para obtener un promedio total. Donde los valores cercanos a cero confirmarán un sentimiento de mercado sin tendencia, mientras que los valores positivos y negativos confirmarán un sentimiento total del mercado, ya sea al alza o a la baja.
167
Cita
22 de mayo de 2015, 10:20 a. m.
 masofras| Se unió en mayo de 2014 | Estado: Trader | 50 publicaciones
Citando a dagoods
{quote} ¿No lo hace ya? ¿No es esa misma fórmula en la hoja de cálculo? Si tienes otra fórmula, por favor, publica cuál es exactamente. Gracias.

Puedes encontrar la explicación en la imagen.

Mi inglés no es muy bueno, así que si algo no está claro, no dudes en preguntar.

Que tengas un buen día,

masofras.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: bbbbbbbbbbb.jpg Tamaño: 241 KB
168
Cita
22 de mayo de 2015, 11:35 a. m.
 Fins.sbr.jr| Se unió en enero de 2014 | Estado: Trader | 42 publicaciones
Citando a honestknave
{quote} Por el momento, solo está disponible para probar con un comerciante (¡no hay premio por adivinar quién!). Necesitará algo de trabajo cosmético antes de ser lanzado, pero en este momento básicamente no tengo tiempo libre.
Ok,
¡gracias por responder!
169
Cita
26 de mayo de 2015, 22:20
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EA Trade 1a - 5262015.gif Tamaño: 88 KB

Este era el estado de los medidores de fuerza cuando tomé la operación, pero tengo otro CSM lineal para medir la tendencia actual de M1 y me advirtió que el poder del AUD estaba disminuyendo.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EA Trade 1 - 5262015.gif Tamaño: 71 KB

Así que cerré en la primera oportunidad por 2 pips. Desde entonces, PA ha intentado volver a probar la apertura diaria y me habría sacado. Esto demuestra que la fortaleza de la moneda no es suficiente.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EA Trade 1b - 5262015.gif Tamaño: 59 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
170
Cita
27 de mayo de 2015, 2:06 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EU Trade 1 - 5262015.gif Tamaño: 66 KB


Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
171
Cita
27 de mayo de 2015, 6:24 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: CC Trade 1 - 5272015.gif Tamaño: 64 KB

Demasiados obstáculos al principio: el mínimo de ayer, 7625 RN y el pivote S1, pero la abrumadora fortaleza y debilidad del CHF y el CAD forzaron la caída del par. ¡Nueve velas M1 ahora cotizan lateralmente, lo que indica una probable pausa! ¡

Voy a echarme una siesta, 

Shalom!
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
172
Cita
27 de mayo de 2015, 6:42 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: CAJ Trade 1 - 5272015.gif Tamaño: 67 KB

Me iba cuando este tipo atrajo mi atención, y sé que es un retroceso, pero tengo la confirmación de CSM de que probablemente sea bueno.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
173
Cita
27 de mayo de 2015, 8:14 a. m.
 Festival de PipsUsuario comercial | Se unió en mayo de 2015 | 654 publicaciones
Para HonestKnave,

tu indicador es realmente preciso y en tiempo real... proporciona una excelente señal para usar el concepto de fuerza relativa en forex. ¡Felicidades!

Vi este hilo y quise compararlo inmediatamente con mi Analizador de Fortaleza de Divisas... ¡Tenemos el mismo resultado! :)

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Image1.png Tamaño: 77 KB


Gracias por compartir.

Saludos.
174
Cita
28 de mayo de 2015, 18:27
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Citando a honestknave
Versión 1.11 Corregido: error de alerta (no se generan alertas de compra) {archivo}
Hola honestknave :

No sé si otros tienen el mismo problema, pero si guardé csDash (1.11) en una plantilla, al cargarla en un gráfico, csDash funciona correctamente.

Sin embargo, si elimino csDash del gráfico, la imagen del panel permanece en él.

Por favor, avísenme. Gracias,

Pax.
175
Cita
28 de mayo de 2015, 21:12
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Citando a Pax
Hola honestknave: No sé si otros tienen el mismo problema, pero si guardé csDash (1.11) en una plantilla, al cargarla en un gráfico, csDash funciona correctamente. Sin embargo, si elimino csDash del gráfico, la imagen del panel permanece en él. Por favor, avísenme. Gracias, Pax.
El guion que queda en el gráfico no es el que eliminaste, sino el que guardaste en tu plantilla. Creo que la forma en que se codificó (nombres de los objetos) no permite aplicar la herramienta con la plantilla.
Codificador de EA/Indicadores/Alertas MT4/MT5
176
Cita
29 de mayo de 2015, 1:33 a. m.
 pazSe unió en junio de 2014 | Estado: Trader | 375 publicaciones
Cotización de FerruFx
El guion que queda en el gráfico no es el que eliminaste, sino el que guardaste en tu plantilla. Creo que la forma en que se codificó (nombres de los objetos) no permite aplicar la herramienta con la plantilla.
Gracias, FerruFx, por la explicación.
No tengo ni idea de programación. Probé con "Lista de objetos "
, "Seleccionar todo", "Eliminar" y no pude eliminar la imagen.
Por ahora, puedo usar la herramienta tal cual, sin plantilla.

177
Cita
29 de mayo de 2015, 13:17
 KeroroQ| Usuario adicional | Se unió en octubre de 2013 | 92 publicaciones
Citando a 919gilead
{imagen} Me iba cuando este tipo atrajo mi atención, y sé que es un retroceso, pero tengo la confirmación de CSM de que probablemente sea bueno.
Gilead, ¿puedo saber qué indicador estás utilizando que pueda
mostrar mini gráficos de diferentes períodos de tiempo?
Un puñetazo, una muerte
178
Cita
29 de mayo de 2015, 15:37
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a KeroroQ
{quote}Gilead, ¿puedo saber qué indicador estás usando que pueda mostrar mini gráficos de diferentes períodos de tiempo?

Hola KeroroQ,

consulta la publicación 151 donde proporcioné el enlace para descargar el indicador: es el minigráfico de Pipware, elemento 2.

Shalom 

George
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
179
Cita
30 de mayo de 2015, 14:16
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
Citando a honestknave
Tuve la oportunidad de revisar csDash este fin de semana y le hice algunos cambios. La versión anterior de csDash no tiene ningún problema, así que si no te gustan los cambios, puedes seguir usando la versión anterior. No he probado la nueva versión en el mercado, así que pido disculpas de antemano si detecta algún fallo. Ahora es un indicador (no un experto). ¿Por qué? Solo puedes añadir un experto por gráfico, pero puedes añadir varios indicadores. ¿Qué significa esto? Debes guardar csDash.ex4 en la carpeta de Indicadores. Los elementos visuales son más configurables. ¿Por qué? Preferencias del usuario...
Hola, honestknave.
¿Podrías publicar la última versión de todo el panel de control? Por favor, que funcione con todos los brokers. "csdash" no funciona.
Lo siento, mi inglés es muy malo. Gracias.
180
Cita
30 de mayo de 2015, 21:18
 AkvistoUsuario comercial | Se unió en noviembre de 2014 | 145 publicaciones
Citando a Ahhamidz
Hola, honestknave. ¿Podrías publicar la última versión de todo el panel de control? Por favor, que funcione para todos los corredores. "csdash" no funciona. Lo siento, mi inglés es muy malo. Gracias.

Hola ahhamidz,

esa es la última versión

: http://www.forexfactory.com/showthre...90#post8266690

¿Qué no te funciona?


P10
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
Citando a Akvisto
{quote} Hola ahhamidz, esa es la última versión http://www.forexfactory.com/showthre...90#post8266690 ¿Qué no te funciona?
este masaje
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: FOREXer4.png Tamaño: 197 KB
182
Cita
31 de mayo de 2015, 10:28 a. m.
 AkvistoUsuario comercial | Se unió en noviembre de 2014 | 145 publicaciones
Citando a Ahhamidz
{quote} este masaje {imagen}
Eche un vistazo aquí y utilice ese script para cargar todo el historial de los pares faltantes.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot_2.png Tamaño: 79 KB
Archivo(s) adjunto(s)
Tipo de archivo: mq4 ForceLoadHistoricalData.mq4   5 KB | 1.683 descargas
183
Cita
31 de mayo de 2015, 11:09 a. m.
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
Citando a Akvisto
{quote} Eche un vistazo aquí y use ese script para cargar todo el historial de los pares faltantes {imagen} {archivo}


csDash.ex4 en la carpeta del indicador no está abierto para edición y en la carpeta del indicador no tiene csDash.MQL4
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: AUDNZDH1.png Tamaño: 138 KB
184
Cita
31 de mayo de 2015, 11:15 a. m.
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
Citando a Akvisto
{quote} Eche un vistazo aquí y use ese script para cargar todo el historial de los pares faltantes {imagen} {archivo}
este masaje
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Untitled.png Tamaño: 327 KB
185
Cita
31 de mayo de 2015, 11:27 a. m.
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Citando a Ahhamidz
{quote} este masaje {imagen}
No se puede abrir el archivo .ex4. Es el archivo que usa tu plataforma para mostrar el panel en tu gráfico.

El archivo .mq4 es para programadores... No lo necesitas.
Codificador de EA/Indicadores/Alertas MT4/MT5
186
Cita
31 de mayo de 2015, 11:43 a. m.
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
Cotización de FerruFx
{quote} El archivo .ex4 no se puede abrir. Es el archivo que usa tu plataforma para mostrar el panel en tu gráfico. El archivo .mq4 es para programadores... No lo necesitas.
¿Cómo uso el guión?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Untitled2.png Tamaño: 449 KB
187
Cita
1 de junio de 2015, 00:21
 Pila negra| Se unió en enero de 2010 | Estado: Comerciante | 317 publicaciones
Obtengo la misma fortaleza de la moneda independientemente del marco temporal que configure para los cálculos.

¿Qué hace la variable "Marco temporal del gráfico"? Estaba configurada en 1 hora, pero se actualiza cada 500 milisegundos. Para un marco temporal de 1 día, preferiría que se actualizara una vez por hora al cierre de la vela de 1 hora. O incluso con menos frecuencia. ¿Un intervalo de actualización de 3 600 000 milisegundos tendría el mismo efecto?
188
Cita
1 de junio de 2015, 00:36
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Citando a BlackStack
Obtengo la misma fortaleza de la moneda independientemente del marco temporal que configure para los cálculos. ¿Qué hace la variable "Marco temporal del gráfico"? Estaba configurada en 1 hora, pero se actualiza cada 500 milisegundos. Para un marco temporal de 1 día, preferiría que se actualizara una vez por hora al cierre de la vela de 1 hora. O incluso con menos frecuencia. ¿Un intervalo de actualización de 3 600 000 milisegundos tendría el mismo efecto?
Lo importante es configurar el marco temporal correcto en "Marco temporal para cálculos".

"Marco temporal del gráfico" es el marco temporal que se abrirá con la plantilla al hacer clic en un par... No tiene nada que ver con el cálculo del panel.
Codificador de EA/Indicadores/Alertas MT4/MT5
189
Cita
2 de junio de 2015, 4:26 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Buenos días y feliz mes nuevo y Pipping para todos.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EJ Trade 1 - 6022015.gif Tamaño: 81 KB


Shalom
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
190
Cita
2 de junio de 2015, 6:35 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a PipsFestival
Para HonestKnave, tu indicador es realmente preciso y en tiempo real... proporciona una excelente señal para usar el concepto de fuerza relativa en forex. ¡Felicidades! Vi este hilo y quise compararlo de inmediato con mi Analizador de Fortaleza de Divisas... Tenemos el mismo resultado :) {imagen} Gracias por compartir. Saludos.

191
Cita
2 de junio de 2015, 6:36 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Pax
Hola honestknave: No sé si otros tienen el mismo problema, pero si guardé csDash (1.11) en una plantilla, al cargarla en un gráfico, csDash funciona correctamente. Sin embargo, si elimino csDash del gráfico, la imagen del panel permanece en él. Por favor, avísenme. Gracias, Pax.
¡Abordaré este problema en la próxima versión (con suerte)!
192
Cita
2 de junio de 2015, 6:36 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Gracias a FerruFx y Akvisto por responder preguntas en mi ausencia. 

No he abandonado el hilo y pronto publicaré una versión mejorada de csDash. Pero creo que pasarán un par de semanas antes de que pueda revisar el código a fondo. 

Gracias a todos por su paciencia.
193
Cita
2 de junio de 2015, 8:38 a. m.
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Citando a honestknave
Gracias a FerruFx y Akvisto por responder preguntas en mi ausencia. No he abandonado el hilo y pronto publicaré una versión mejorada de csDash. Pero creo que pasarán un par de semanas antes de que pueda revisar el código a fondo. Gracias a todos por su paciencia.
De nada. Tómate tu tiempo... ¡este hilo es tuyo, así que no hay prisa por nuestra parte!
Codificador de EA/Indicadores/Alertas MT4/MT5
194
Cita
2 de junio de 2015, 14:08
 Comerciante 24 horas| Se unió en noviembre de 2007 | Estado: Comerciante | 261 publicaciones
Citando a honestknave
Gracias a FerruFx y Akvisto por responder preguntas en mi ausencia. No he abandonado el hilo y pronto publicaré una versión mejorada de csDash. Pero creo que pasarán un par de semanas antes de que pueda revisar el código a fondo. Gracias a todos por su paciencia.
Gracias por todos sus esfuerzos.
195
Cita
3 de junio de 2015, 00:09
 HanneleSe unió en septiembre de 2012 | Estado: Trader | 210 publicaciones
Citando a 919gilead
Buenos días y feliz mes nuevo y Pipping para todos {imagen} Shalom
Hola 919gilead y compañía :-)

¿Cómo consiguieron que el tablero hiciera eso? Me gusta el aspecto de los marcos temporales continuos. ¿Son las mismas páginas anteriores? Todavía en pruebas o ya está disponible en algún sitio. Por favor, avísenme .
Saludos,
Hannele.
196
Cita
3 de junio de 2015, 1:26 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Hannele
{quote} Hola 919gilead y compañía :-) ¿Cómo consiguieron que el guión hiciera eso? Me gusta el aspecto de los marcos temporales continuos. ¿Son las mismas páginas anteriores? Todavía en pruebas o ya está disponible en algún sitio. Por favor, avísenme . Saludos, Hannele.
Hola Hannele,

todavía está en pruebas, pero se lanzará pronto. ¡Ten cuidado! :nerd:
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
197
Cita
3 de junio de 2015, 2:05 a. m.
 HanneleSe unió en septiembre de 2012 | Estado: Trader | 210 publicaciones
Citando a 919gilead
{quote} Hola Hannele, todavía está en pruebas, pero se lanzará pronto. ¡Ten cuidado! :nerd:
Gracias, estaré esperando.
198
Cita
5 de junio de 2015, 3:56 a. m.
 AkvistoUsuario comercial | Se unió en noviembre de 2014 | 145 publicaciones
Citando a honestknave
Gracias a FerruFx y Akvisto por responder preguntas en mi ausencia. No he abandonado el hilo y pronto publicaré una versión mejorada de csDash. Pero creo que pasarán un par de semanas antes de que pueda revisar el código a fondo. Gracias a todos por su paciencia.

Un placer, Honestknave... tómate tu tiempo... este tipo de desarrollos requieren mucho tiempo y es genial que lo compartas con nosotros. Gracias.
199
Cita
10 de junio de 2015, 15:13
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Sigo experimentando y probando ambas versiones del medidor de fortaleza de divisas, y demostrando que un pip aquí, dos pip allá y cinco pip allá, aplicados varias veces al día, pueden duplicar una cuenta, lenta pero seguramente.

Pequeñas gotas de agua,
pequeños granos de arena,
crean el imponente océano
y la hermosa tierra.

Y los pequeños momentos,
por humildes que sean,
crean las poderosas eras
de la eternidad.

Shalom y buenas operaciones para todos.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Lista de Comercio - 6102015.gif Tamaño: 47 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
1
200
Cita
11 de junio de 2015, 6:33 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Una actualización rápida para abordar los problemas que algunas personas tenían con las plantillas y los fantasmas ocasionales que quedaban en la pantalla.
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   119 KB

P11
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Esta actualización no soluciona nada. Simplemente permite seleccionar cuál de los 28 pares se muestra:
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: csdashmod.png Tamaño: 109 KB


Algunas cosas a tener en cuenta:
Se debe configurar un par para que se muestre para poder recibir alertas para ese par.
Todavía se requieren los 28 pares para los cálculos (por lo que los números deberían ser exactamente los mismos independientemente de si ves 1 o 28 pares)
Quizás veas esta pantalla y te preguntes por qué no se han realizado los cálculos. La razón es que csDash aún espera la actualización de otros pares que no aparecen en la lista.
Imagen adjunta



Por favor, informe cualquier error. No he tenido la oportunidad de probarlo mucho.
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   127 KB | 1183 descargas
210
Cita
13 de junio de 2015, 6:14 a. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Citando a honestknave
Esta actualización no soluciona nada. Solo permite seleccionar cuál de los 28 pares se desea mostrar: {image} Nota: Es necesario configurar un par para que se muestre para recibir alertas. Los 28 pares siguen siendo necesarios para los cálculos (por lo que los números deberían ser exactamente los mismos, ya sea que se visualicen 1 o 28 pares). Es posible que vea esta pantalla y se pregunte por qué no se han realizado los cálculos. Esto se debe a que csDash aún espera la actualización de otros pares que no aparecen en la lista. {image} Por favor, informe cualquier error.
Hola honestknave.

Gracias. ¡Esto es una obra de arte! Lo intentaré la próxima semana.


¡¡¡No te limites!!!
211
Cita
13 de junio de 2015, 9:58 a. m.
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
Citando a honestknave
Una actualización rápida para abordar los problemas que algunas personas tenían con las plantillas y los fantasmas ocasionales que quedaban en la pantalla. {archivo}
Falso "eur nzd y nza cad" pero no puedo usarlo. Por favor, ayúdenme con
este mensaje.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: AUDCHFH1.png Tamaño: 101 KB
212
Cita
13 de junio de 2015, 10:24 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mosiskv
{quote} Hola honestknave. Gracias. ¡Esto es una obra de arte! Lo intentaré la próxima semana.
Gracias mosiskv, cuéntame cómo te va.
213
Cita
13 de junio de 2015, 10:26 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Ahhamidz
{quote} false "eur nzd & nza cad" pero no puedo usarlo. Por favor, ayúdenme con este mensaje {image}
Los 28 pares deben estar disponibles para csDash... solo controlas lo que ves en pantalla con "mostrar...".

¿Tu bróker ofrece EURNZD y NZDCAD? De lo contrario, lamentablemente csDash no funcionará para ti.
214
Cita
13 de junio de 2015, 10:38 a. m.
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
Citando a honestknave
{quote} Los 28 pares deben estar disponibles para csDash... solo controlas lo que ves en pantalla con "mostrar...". ¿Tu bróker ofrece EURNZD y NZDCAD? De lo contrario, lamentablemente csDash no te funcionará.
gracias
cual se rompio tengo todo par y demo
215
Cita
13 de junio de 2015, 12:10 p. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Ahhamidz
{quote} gracias Que se rompió tiene todo el par y demo
Todos los corredores que he usado tienen los 28 pares disponibles. Echa un vistazo aquí si quieres más ideas sobre corredores.

¡Mucha suerte!
216
Cita
13 de junio de 2015, 13:10
 juisen25Se unió en marzo de 2012 | Estado: Trader | 215 publicaciones
@honestknave,


¿cómo usas este CDASH en el trading? Me refiero a las reglas de entrada y salida. Gracias.
217
Cita
13 de junio de 2015, 13:17
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a juisen25
@honestknave, ¿cómo usas este CDASH en el trading? Me refiero a las reglas de entrada y salida. Gracias.
Hola juisen25,

csDash no está pensado como un sistema independiente; la gente suele integrarlo en otros sistemas. Puedes encontrar la idea de la fortaleza de la moneda (en diversas formas) como parte de varios sistemas en FF.

La idea básica es que se enfrenta una moneda fuerte contra una moneda débil; por ejemplo, si el EUR está fuerte y el USD está débil, esto apoya la idea de comprar EURUSD, etc.
218
Cita
13 de junio de 2015, 17:14
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Pasando al ámbito experimental: marcos temporales móviles.

La fórmula de csDash es bien conocida. Se basa en la relación de puja, es decir, donde es la puja actual en relación con el máximo y el mínimo.

El problema radica en que el rango máximo-mínimo es muy estrecho al inicio de una nueva barra y se amplía gradualmente con el tiempo.

Considere el marco temporal D1 clásico que usaba la hoja de cálculo original de Excel.

El viernes pasado, a las 00:05, había un rango de 6,3 pips en la barra D1. Esto significaba que un pip de movimiento representaba aproximadamente un 16 % de la relación de puja.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EURUSD-sbM5.png Tamaño: 25 KB


A las 04:00, la barra D1 tenía un rango de 20,7 pips. Esto significaba que un pip de movimiento representaba un ~5% del ratio de oferta.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EURUSD-sbH4.png Tamaño: 25 KB


Al cierre de la barra D1 del viernes, se registró un rango de 145,5 pips. Esto significó que un pip de movimiento fue inferior al 1 % en la relación de oferta.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EURUSD-sbDaily.png Tamaño: 25 KB


El resultado final de todo esto: la situación se vuelve un poco inestable al comienzo de una nueva barra y se estabiliza lentamente con el paso del tiempo.

La próxima versión de csDash permitirá rotar los marcos temporales.

Así, en lugar de trabajar con la barra D1, se puede trabajar con las últimas 24 barras H1. De esta forma, el cálculo siempre se realiza con datos de 24 horas, sin importar cuánto tiempo pase en la barra diaria.

Los resultados variarán a lo largo del día, pero deberían mostrar las mismas cifras al final:
(para los observadores que notaron que solo usé 23 barras; era viernes y mi bróker no tiene una barra H1 de las 23:00, pero quería mostrar el mismo resultado. Normalmente, se establecería en 24).
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: sidebyside.png Tamaño: 72 KB


Si no le gusta la idea de los períodos de tiempo continuos, simplemente configure el recuento de períodos de tiempo en 1 y se comportará como solía hacerlo.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: settings.png Tamaño: 113 KB


Ya se han producido 2 cambios sustanciales en csDash sin probarlos en el mercado abierto, por lo que es de esperar que haya errores.
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   129 KB | 1017 descargas
4
219
Cita
14 de junio de 2015, 8:14 a. m.
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
[quote=honestknave;8324890]Pasando al ámbito experimental: marcos temporales móviles.

Hola, honestknave,

avanzas rápido; parece que hay muchas permutaciones posibles.

Solo para aclarar, ¿la barra de formación actual está incluida en el ejemplo 24?

Imagen adjunta



¿Los pares encerrados en un círculo con B/R incompleto significan que aún se está formando o que no hay suficientes datos?
(Por ejemplo, tengo H4 + 6).

Por favor, avísenme

. Gracias.
¡¡¡No te limites!!!
220
Cita
14 de junio de 2015, 8:19 a. m.
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
Pasando al ámbito experimental: marcos temporales móviles. La fórmula de csDash es bien conocida. Se basa en la relación de puja, es decir, donde es la oferta actual en relación con el máximo y el mínimo. El problema radica en que el rango máximo-mínimo es muy estrecho al inicio de una nueva barra y se amplía lentamente con el tiempo. Considere el marco temporal D1 clásico que usaba la hoja de cálculo original de Excel. El viernes pasado, a las 00:05, había un rango de 6,3 pips en la barra D1. Esto significaba que 1 pip de movimiento representaba un ~16% de la relación de puja. {imagen} A las 04:00, había un 20,7...

 

P12
 sradia| Se unió en octubre de 2014 | Estado: Trader | 279 publicaciones
Citando a 919gilead
Buenos días {imagen}
Hola 919gilead,

¿podrías subir esta plantilla?

Saludos,

Sarju.
222
Cita
14 de junio de 2015, 11:53 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a mosiskv
Sólo para aclarar: ¿la barra de formación actual está incluida en el ejemplo 24?
Sí, lo es. Entonces, en tu H4x6, cuando el mercado abra en unas horas, usará la primera barra de esta semana más las últimas cinco de la semana pasada.

Citando a mosiskv
¿Los pares encerrados en un círculo con B/R incompleto significan que aún se está formando o que no hay suficientes datos? (Tengo H4 + 6 en el ejemplo). Por favor, avísenme.
Así es como MT4 dibuja una barra muy pequeña. Si los datos no estuvieran completos, no verías nada.

Espero que te sirva.
223
Cita
14 de junio de 2015, 11:54 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dagoods
{cita} 
Gracias dagoods, espero que te resulte útil.
224
Cita
14 de junio de 2015, 17:09
 dlouw| Se unió en febrero de 2009 | Estado: Comerciante | 136 publicaciones
¡Bien hecho! Tengo muchas ganas de usarlo y ver la reacción de los demás. 
225
Cita
15 de junio de 2015, 2:43 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a sradia
Hola 919gilead, ¿podrías subir esta plantilla? Saludos, Sarju.
Vea mi respuesta a una solicitud similar aquí
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
226
Cita
16 de junio de 2015, 14:03
 blou999| Usuario adicional | Se unió en junio de 2015 | 5 publicaciones
Es posible explicarlo
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Untitled1.png Tamaño: 294 KB
227
Cita
16 de junio de 2015, 15:20
 Borradores| Se unió en septiembre de 2011 | Estado: Comerciante | 93 publicaciones
Marco de tiempo para el cálculo = Base de la BD para el cálculo de la fuerza

Marco de tiempo del gráfico = Marco de tiempo del gráfico para abrir cuando hace clic en el nombre del par dentro de la BD
228
Cita
18 de junio de 2015, 8:14 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Draffi
Marco de tiempo para el cálculo = Base de la BD para el cálculo de la fuerza Marco de tiempo del gráfico = Marco de tiempo del gráfico para abrir cuando hace clic en el nombre del par dentro de la BD

229
Cita
18 de junio de 2015, 8:31 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Finalmente, he logrado implementar código experimental para mejorar el proceso de alertas. ¿

Por qué? El problema con las alertas es que, siempre que un valor ronda un umbral de alerta (en lugar de fluctuar claramente en un sentido u otro), se generan múltiples activadores en rápida sucesión. Estas múltiples alertas pueden dar la impresión de que se está recibiendo una señal muy fuerte, pero la realidad es la contraria: se está recibiendo una señal muy marginal.

Considere el siguiente ejemplo (el umbral diferencial es 4.0 ):
3.8

3.9

4.0 ¡ALERTA!

4.1

4.0

3.9

4.0 ¡ ALERTA!

3.9

4.0 ¡ALERTA!

3.9

3.9

4.0 ¡ALERTA!


Anteriormente, csDash utilizaba un retraso de 1 minuto entre alertas. Se trata de un mecanismo rudimentario basado en la teoría de que las cosas se moverán y se estabilizarán lejos del umbral en el minuto intermedio. Sin embargo, no siempre ocurre.

Ahora he codificado un nuevo método para reducir el número de alertas repetidas. La única configuración del usuario es la Sensibilidad del Disparador:
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: trigger.png Tamaño: 85 KB


En su configuración más alta, funciona como en el ejemplo anterior. En su configuración más baja, recibirá muy pocas alertas repetidas ( tenga en cuenta que la sensibilidad nunca afecta a la primera alerta ).

Si desea experimentar con esta nueva función, no dude en informarnos sobre cualquier error.
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   122 KB | 926 descargas
1
230
Cita
18 de junio de 2015, 8:36 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Siempre adiciones consideradas y sobresalientes. Buen trabajo Capitán.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
231
Cita
18 de junio de 2015, 13:12
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Solución: permite agregar múltiples versiones de csDash al mismo gráfico... siempre que no compartan exactamente la misma combinación de período de tiempo/período de rotación.
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   123 KB | 1639 descargas
232
Cita
18 de junio de 2015, 13:12
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a 919gilead
Siempre adiciones consideradas y sobresalientes. Buen trabajo Capitán.
Gracias George
233
Cita
18 de junio de 2015, 13:20
 dansmol| Se unió en octubre de 2006 | Estado: Comerciante | 276 publicaciones
Citando a honestknave
Solución: permite agregar múltiples versiones de csDash al mismo gráfico... siempre que no compartan exactamente la misma combinación de período de tiempo/período de rotación. {archivo}
GRACIAS
Dan
234
Cita
18 de junio de 2015, 15:56
 mosiskvSe unió en marzo de 2013 | Estado: Vagabundo | 377 publicaciones
Citando a honestknave
Solución: permite agregar múltiples versiones de csDash al mismo gráfico... siempre que no compartan exactamente la misma combinación de período de tiempo/período de rotación. {archivo}
GRACIAS. ¡Tengo que descubrir todos los usos con todas las permutaciones!

Solo un vistazo rápido.

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot1.png Tamaño: 78 KB




¡¡¡No te limites!!!
1
235
Cita
18 de junio de 2015, 16:45
 dlouw| Se unió en febrero de 2009 | Estado: Comerciante | 136 publicaciones
Hola,

gracias, Honest, por todas las mejoras. Estás haciendo un trabajo maravilloso.

He estado experimentando con marcos temporales móviles y me gustaría compartir mi progreso. El objetivo es calcular las barras en función del tiempo para tener en cuenta las barras y los fines de semana que faltan. Esto se basa en un CSM existente con alertas. Todo el crédito es de los desarrolladores anteriores. Soy un programador principiante, así que no se ofrecen garantías. Cualquier comentario, sugerencia o mejora será bienvenida.

Me gustaría que alguien me ayudara a hacer posible la creación de múltiples indies para diferentes marcos temporales en el mismo gráfico.

¡Que lo disfrutes
!
Archivo(s) adjunto(s)
Tipo de archivo: ex4 CurrencyStrengthAlerts_dl.ex4   51 KB | 1158 descargas
Tipo de archivo: mq4 CurrencyStrengthAlerts_dl.mq4   29 KB | 1832 descargas
236
Cita
18 de junio de 2015, 17:46
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dansmol
{quote} GRACIAS Dan
Citando a mosiskv
{quote} ¡GRACIAS! ¡Tengo que descubrir todos los usos con todas las permutaciones! Solo un vistazo rápido. {image}
Me alegra que les guste a ambos. ¡Espero que haya mucho con qué jugar!
237
Cita
18 de junio de 2015, 17:47
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dlouw
Hola, gracias, Honest, por todas las mejoras. Estás haciendo un trabajo maravilloso. He estado experimentando con marcos de tiempo variables y me gustaría compartir mi progreso. El objetivo es calcular las barras en función del tiempo para tener en cuenta las barras y los fines de semana que faltan. Esto se basa en un CSM existente con alertas. Todo el crédito es de los desarrolladores anteriores. Soy un programador principiante, así que no se ofrecen garantías. Cualquier comentario, sugerencia o mejora será bienvenida. Me gustaría que alguien me ayudara a crear varios indies para diferentes horarios...
Gracias por compartir, dlouw. Si puedo ayudarte en algo, por favor, házmelo saber.
238
Cita
18 de junio de 2015, 20:38
 piphunt11| Se unió en julio de 2014 | Estado: Comerciante | 39 publicaciones
Gracias, Honestknave.

Tu indicador csDash es excelente. Me gusta el último cambio con el marco temporal móvil, de modo que la fuerza relativa parece estable durante un período determinado.
piphunt11
1
239
Cita
19 de junio de 2015, 2:19 a. m.
 Zondervan| Se unió en julio de 2014 | Estado: Trader | 605 publicaciones
Hola honestknave, ¡un indicador genial! Llevo un tiempo experimentando con el trading de la fortaleza de las divisas. Me interesa mucho la capacidad del indicador para personalizar el número de periodos en el mismo marco temporal, por ejemplo, periodos de 24 horas para crear un día, etc.

Estoy probando varias teorías sobre la fortaleza de las divisas. Tu indicador csDash calcula la fortaleza de las divisas de forma bastante diferente a como yo la he estado calculando, pero me interesa ver qué resultados puedo obtener. Si encuentro algo que funcione de forma consistente, ¡te lo haré saber!
240
Cita
19 de junio de 2015, 3:55 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a piphunt11
Gracias, Honestknave. Tu indicador csDash es excelente. Me gusta el último cambio con el marco temporal móvil, de modo que la fuerza relativa parece estable durante un período determinado.
Gracias. ¡Me alegra que lo disfrutes!


P13
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Zondervan
Hola honestknave, ¡un indicador brillante! Llevo un tiempo experimentando con el trading de la fortaleza de las divisas. Me interesa mucho la capacidad del indicador para personalizar el número de periodos en el mismo marco temporal, por ejemplo, periodos de 24 horas para crear un día, etc. Estoy probando varias teorías sobre la fortaleza de las divisas. Tu indicador csDash calcula la fortaleza de las divisas de forma bastante diferente a como yo la he estado calculando, pero me interesa ver qué resultados puedo obtener. Si encuentro algo que funcione de forma consistente...
Me alegra saber que tienes algunas teorías para probar. Publica tus hallazgos; estoy seguro de que a todos nos interesará.
242
Cita
19 de junio de 2015, 4:07 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Confíe en que alguien esté corto en EURUSD o EURJPY
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: MADdash a las 12.06 am - 6192015.gif Tamaño: 51 KB
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
243
Cita
19 de junio de 2015, 19:08
 ismael360| Se unió en agosto de 2011 | Estado: Comerciante | 59 publicaciones
Citando a mosiskv
{quote} ¡GRACIAS! ¡Tengo que descubrir todos los usos con todas las permutaciones! Solo un vistazo rápido. {image}
Parece que todos los marcos de tiempo emiten casi la misma potencia. ¿Estás seguro de que funcionan correctamente?
244
Cita
19 de junio de 2015, 19:25
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a ismael360
Parece que todos los marcos de tiempo emiten casi la misma potencia. ¿Estás seguro de que funcionan correctamente?
Todas son variantes de 24 horas, por lo que los resultados serán similares (particularmente hacia el final del día):
1 vela D1
6 velas H4
24 velas H1
96 velas M15
245
Cita
19 de junio de 2015, 20:27
 ismael360| Se unió en agosto de 2011 | Estado: Comerciante | 59 publicaciones
Ya veo que al final se igualan porque se igualan con el horario diario.

Tiene mucho sentido. Gracias

por la rápida respuesta.

246
Cita
20 de junio de 2015, 6:37 a. m.
 Fin del día| Se unió en noviembre de 2013 | Estado: Comerciante | 444 publicaciones
Citando a honestknave
{quote} Todas son variantes de 24 horas, por lo que los resultados serán similares (particularmente hacia el final del día): 1 vela D1 6 velas H4 24 velas H1 96 velas M15


Hola, sinceramente... Tu indicador es maravilloso. Genial.
Pero las fuerzas son demasiado nerviosas. Cambian demasiado rápido. ¿Hay alguna manera de que sean menos nerviosas? De lo contrario, las señales se vuelven poco fiables.
¿Qué opinas?
247
Cita
20 de junio de 2015, 6:49 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Eod
{quote} Hola, sinceramente... Tu indicador es maravilloso. Genial. Pero las fuerzas son demasiado nerviosas. Cambian demasiado rápido. ¿Hay alguna manera de hacerlas menos nerviosas? De lo contrario, las señales se vuelven poco fiables. ¿Qué opinas?
Hola Eod,

echa un vistazo a esta publicación que explica algunos de los cambios recientes en el proceso de alertas.

Las alertas múltiples han sido un problema en el que sigo trabajando. ¿Has probado a configurar la sensibilidad al mínimo?

Probablemente intentaré ajustar aún más esos umbrales de sensibilidad y posiblemente reintroducir un retardo de tiempo.
248
Cita
20 de junio de 2015, 7:19 a. m.
 Fin del día| Se unió en noviembre de 2013 | Estado: Comerciante | 444 publicaciones
Citando a honestknave
Hola Eod, echa un vistazo a esta publicación que explica algunos de los cambios recientes en el proceso de alertas. Las alertas múltiples han sido un problema en el que sigo trabajando. ¿Has probado a configurar la sensibilidad al mínimo? Probablemente intentaré ajustar aún más esos umbrales de sensibilidad y posiblemente reintroducir un retardo de tiempo...


Eres una persona espléndida. Gracias por el consejo. Lo intentaré con el más bajo.
Si realizas cambios en tu indi, háznoslo saber. ¿De acuerdo?
249
Cita
21 de junio de 2015, 12:04 p. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Eod
{quote} Eres una persona espléndida. Gracias por el consejo. Intentaré con el más bajo. Si realizas cambios en tu indi, háznoslo saber. ¿De acuerdo?
seguro
250
Cita
25 de junio de 2015, 7:11 a. m.
 cara azul| Se unió en septiembre de 2014 | Estado: Trader | 234 publicaciones
Hola honestknave,

si podemos hacer que este histograma índi o el histograma de fuerza de la moneda-Giraia

tenga el estilo de visualización, podemos copiar estos dos índi



http://www.forexfactory.com/showthre...79#post8344479

Imagen adjunta




http://www.forexfactory.com/showthre...72#post7988772


Imagen adjunta




Muchas gracias.
251
Cita
26 de junio de 2015, 7:07 a. m.
 Trebrón| Se unió en agosto de 2014 | Estado: Comerciante | 7 publicaciones
Hola honestknave,

me gusta mucho tu indi. Mi bróker abre con un retraso de 5 minutos, así que el tuyo es el único CSM que me funciona.
Gracias por tu trabajo y por ponerlo a nuestra disposición.
252
Cita
28 de junio de 2015, 9:22 a. m.
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
Citando a Trebron
Hola honestknave, me gusta mucho tu indi. Mi bróker abre con un retraso de 5 minutos, así que el tuyo es el único CSM que me funciona. Gracias por tu trabajo y por ponerlo a nuestra disposición.
Hola honestknave, 919gilead.
Mi sistema necesita una moneda estable con arro. ¿Podrían ayudarme? Gracias.
Imagen(es) adjunta(s) (haga clic para ampliar)
Haga clic para ampliar Nombre: Untitled.png Tamaño: 329 KB
Haga clic para ampliar Nombre: Untitled1.png Tamaño: 161 KB
253
Cita
28 de junio de 2015, 11:02 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Trebron
Hola honestknave, me gusta mucho tu indi. Mi bróker abre con un retraso de 5 minutos, así que el tuyo es el único CSM que me funciona. Gracias por tu trabajo y por ponerlo a nuestra disposición.
Gracias, Trebron, de nada. Me alegra que te haya sido útil.
254
Cita
28 de junio de 2015, 11:03 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a Ahhamidz
Hola honestknave, 919gilead, mi sistema necesita fortalecer la moneda con arro. ¿Puedes ayudarme? Gracias.
Hola ahhamidz,

ahora mismo solo tengo tiempo para corregir errores, no para hacer cambios o mejoras.

Pero cuando tenga más tiempo libre, tendré en cuenta tu idea.
255
Cita
28 de junio de 2015, 11:16 a. m.
 AhhamidzUsuario comercial | Se unió en noviembre de 2014 | 3028 publicaciones
[quote=honestknave;8350690]{quote} Hola ahhamidz, por ahora solo tengo tiempo para corregir errores, no para hacer cambios o mejoras. Pero cuando tenga más tiempo libre, tendré en cuenta tu idea.[/qu

Gracias. Alarma, tu indicador (ccash) es correcto. Lo uso. Mi sistema con la fortaleza de la moneda y ccash está completo.
Espero tu ayuda.
256
Cita
29 de junio de 2015, 7:20 a. m.
 rey de micro| Se unió en julio de 2011 | Estado: Comerciante | 251 publicaciones
Citando a cara azul
Hola honestknave, si podemos hacer que este histograma indi o el histograma Currency Strength-Giraia tenga el estilo de visualización que podemos copiar estos dos indi http://www.forexfactory.com/showthre...79#post8344479 {image} http://www.forexfactory.com/showthre...72#post7988772 {image} muchas gracias.
Hola, cara azul,

¿podrías compartir tu primera información? No pude encontrar la página donde indicaste tu dirección.
Gracias.
257
Cita
29 de junio de 2015, 8:50 a. m.
 cara azul| Se unió en septiembre de 2014 | Estado: Trader | 234 publicaciones
Citando a kingofmicro
{quote} Hola, cara azul, ¿podrías compartir la primera información? No pude encontrar la página donde indicaste tu dirección. Gracias.
Hola kingofmicro,

puedes descargarlo aquí

http://www.forexfactory.com/showthread.php?t=541364

. Muchas gracias.
258
Cita
29 de junio de 2015, 9:05 a. m.
 rey de micro| Se unió en julio de 2011 | Estado: Comerciante | 251 publicaciones
Citando a cara azul
{quote} Hola kingofmicro, puedes descargarlo aquí http://www.forexfactory.com/showthread.php?t=541364 muchas gracias.
Gracias, amigo. 

Pero quiero el indicador de fortaleza de la divisa.
No hay indicador de patrón M&W.

Saludos.
259
Cita
30 de junio de 2015, 00:11
 cara azul| Se unió en septiembre de 2014 | Estado: Trader | 234 publicaciones
Citando a kingofmicro
{quote} Gracias, amigo. Pero quiero el indicador de fortaleza de la divisa. No hay indicador de patrón M&W. Saludos.
Hola amigo,

no tenía este indi, es el indi de PipsFestival, puedes preguntar si puede mostrarlo.

Muchas gracias.
260
Cita
30 de junio de 2015, 4:34 a. m.
 rey de micro| Se unió en julio de 2011 | Estado: Comerciante | 251 publicaciones
Citando a cara azul
{quote} Hola amigo, no tenía este indi, es el indi de PipsFestival, puedes preguntar si puede mostrarlo. Muchas gracias.
Ok, gracias hermano.


P14
Como se muestra, cambia todo a falso y obtendrás lo que quieres.
Imagen adjunta

Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
262
Cita
30 de junio de 2015, 7:27 a. m.
 rey de micro| Se unió en julio de 2011 | Estado: Comerciante | 251 publicaciones
Citando a 919gilead
{quote} Como se muestra, cambia todo a falso y obtendrás lo que quieres {image}
gracias 919, pero no tengo este indicador. ¿Dónde puedo descargarlo?
263
Cita
30 de junio de 2015, 7:44 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a kingofmicro
{quote} gracias 919, pero no tengo este indicador. ¿Dónde puedo descargarlo?
Seguí el mismo enlace que proporcionó Blueface, pero aquí está. Lea su explicación y descargue la versión beta que más le convenga, luego cambie todos los TF a falso como publiqué anteriormente.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
264
Cita
30 de junio de 2015, 8:26 a. m.
 rey de micro| Se unió en julio de 2011 | Estado: Comerciante | 251 publicaciones
Citando a 919gilead
{quote} Seguí el mismo enlace que proporcionó Blueface, pero aquí está. Lea su explicación y descargue la versión beta que más le convenga, luego cambie todos los TF a falso como publiqué anteriormente.
Gracias 919.
Pero repito: no quiero usar el indicador M&W.
La razón es muy clara: pipsfestival intenta crear una lista de direcciones de correo electrónico y es miembro comercial.
265
Cita
30 de junio de 2015, 11:14 a. m.
 ShomariG| Se unió en febrero de 2015 | Estado: Que la paz te acompañe... | 75 publicaciones
Citando a kingofmicro
{quote} Gracias 919. Pero repito: no quiero usar el indicador M&W. La razón es muy clara: pipsfestival intenta crear una lista de direcciones de correo electrónico y es miembro comercial.
Descargar desde la pág. 6, publicación 231. O haga clic aquí . MADdash está aquí .
266
Cita
30 de junio de 2015, 16:15
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a kingofmicro
{quote} Gracias 919. Pero repito: no quiero usar el indicador M&W. La razón es muy clara: pipsfestival intenta crear una lista de direcciones de correo electrónico y es miembro comercial.

Descargué el indicador sin que Pipsfestival me pidiera ninguna dirección de correo electrónico, y si no quieres correr el riesgo de que obtenga tu dirección de correo electrónico, deja su indicador en paz.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
267
Cita
1 de julio de 2015, 6:58 a. m.
 rey de micro| Se unió en julio de 2011 | Estado: Comerciante | 251 publicaciones
Citando a 919gilead
{quote} Descargué el indicador sin que Pipsfestival me pidiera ninguna dirección de correo electrónico, y si no quieres correr el riesgo de que obtenga tu dirección de correo electrónico, entonces deja su indicador en paz.
ok 919 gracias y gracias shomariG
268
Cita
1 de julio de 2015, 18:58
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a kingofmicro
{quote} ok 919 gracias y gracias shomariG
De nada
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
269
Cita
11 de julio de 2015, 10:54 a. m.
 BernardoUsuario comercial | Se unió en agosto de 2013 | 2932 publicaciones
Citando a 919gilead
Confía en que alguien esté corto en EURUSD o EURJPY {imagen}
Hola Gilead, ¿cómo se llama este indicador? Parece ofrecer una buena visión general.
Imagen adjunta

Escanee los 28 pares de divisas con UN gráfico... Indicadores de fortaleza de la moneda 28
270
Cita
11 de julio de 2015, 11:23 a. m.
 Bapakjason| Se unió en abril de 2014 | Estado: Trader | 1900 publicaciones
Citando a Bernhard
{quote} Hola Gilead, ¿cómo se llama este indicador? Parece ofrecer una buena visión general {image}
MADash, se puede encontrar en un hilo con ese título, también de Honestknave.
(Si no me equivoco). Espero que te sirva. -Jason
271
Cita
11 de julio de 2015, 14:02
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Bernhard
{quote} Hola Gilead, ¿cómo se llama este indicador? Parece ofrecer una buena visión general {image}
Se llama "Mobile Average Distance Dash" y se puede encontrar aquí. 
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
272
Cita
11 de julio de 2015, 14:03
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Bapakjason
{quote} MADash, se puede encontrar en un hilo con ese título, también de Honestknave. (Si no me equivoco). Espero que te sirva. -Jason
Gracias Jason
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
273
Cita
1 de agosto de 2015, 7:53 a. m.
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Citando a honestknave
Alertas y espera
Señor, usted es mi salvación.

Llevo mucho tiempo buscando un medidor de fortaleza monetaria que emita alertas.

Gracias.
274
Cita
1 de agosto de 2015, 7:57 a. m.
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Citando a kingofmicro
{quote} Gracias, amigo. Pero quiero el indicador de fortaleza de la divisa. No hay indicador de patrón M&W. Saludos.
¿Podría ser de alguna ayuda este enlace?

http://www.forexfactory.com/showthre...52#post8290652

Fue la fortaleza de la moneda de Hanover para Giraia.
275
Cita
1 de agosto de 2015, 8:01 a. m.
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{quote} Gracias, dagoods, entiendo lo que dices. Sería interesante investigarlo. Sigue al líder por la fortaleza de la moneda en lugar del rango de pips.

Por favor, actualice si hay algún progreso en un indicador que logre eso con alertas. 
276
Cita
1 de agosto de 2015, 8:05 a. m.
 dagoodsSe unió en noviembre de 2007 | Estado: Trader | 3060 publicaciones
Citando a honestknave
{quote} Gracias por tu aportación, dlouw. Si te entiendo bien, creo que esto es algo que yo también he estado considerando. En lugar de basarlo en la barra D1 (que significa solo 1 hora de datos a la 01:00 y 23 horas de datos a las 23:00), que sea un periodo continuo de 24 horas. O el período que se elija. ¿Es eso a lo que te referías o te he malinterpretado?

Tal vez si hubiera uno estático + otro rodante que se pudieran comparar, podríamos jugar más fácilmente a seguir al líder y tener el mayor EA del mundo... solo una idea
277
Cita
1 de agosto de 2015, 11:30 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Citando a dagoods
{quote} Por favor actualice si hay algún progreso en un indicador que logre eso con alertas.
Citando a dagoods
{quote} Tal vez si hubiera uno estático + otro rodante que se pudieran comparar, podríamos jugar más fácilmente a seguir al líder y tener el mayor EA del mundo... solo una idea
Hola, dagoods.

Las cosas van despacio ahora mismo, ya que estoy muy ocupado. Estoy modificando MADdash para que funcione con este tipo de moneda, que probablemente será la próxima versión.
278
Cita
31 de agosto de 2015, 7:13 a. m.
 kisaragi7| Se unió en agosto de 2015 | Estado: Trader | 6 publicaciones
Hola,　
introduje este indicador. Sin embargo, no aparece.　
¿Cómo puedo solucionarlo?
279
Cita
11 de septiembre de 2015, 17:00
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Hola, Honestknave
. Gracias por el indicador csDash.
Guardé el archivo en la carpeta del indicador MT4, pero no aparece al cargarlo.
¿Qué podría haber hecho mal? Por favor, ayuda.
Gracias.
280
Cita
11 de septiembre de 2015, 18:03
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Hola Honestknave.
Recibo el siguiente comentario en la pestaña Expertos cuando cargo csDash.
csDash se cargó correctamente
Versión experimental caducada
La inicialización falló
Razón 8 de desunión
remoto
Por favor ayuda, muchas gracias

P15
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a ntshanel
Hola Honestknave. Gracias por el indicador csDash. Guardé el archivo en la carpeta de indicadores de MT4, pero no aparece al cargarlo. ¿Qué podría haber hecho mal? Por favor, ayuda. Gracias.
¿Ha reiniciado Metatrader o ha actualizado la carpeta de indicadores haciendo clic derecho en el ícono de Indicadores en el Navegador y haciendo clic en "actualizar"?
El único límite es el que tú mismo te pones - Felix Baumgartner
282
Cita
15 de septiembre de 2015, 00:50
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Gracias, Shabs19, por responder.
Hice todo eso (actualizar y reiniciar), pero sigue sin mostrar nada al cargarlo. Es muy extraño porque los demás indicadores se cargan sin problemas.
283
Cita
15 de septiembre de 2015, 5:28 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
¿Lo estás cargando desde Archivo, Carpeta de Datos Abiertos, MQL4, Carpeta de Indicadores?

Elimina todas las versiones anteriores, si las hay.
El único límite es el que tú mismo te pones - Felix Baumgartner
284
Cita
15 de septiembre de 2015, 11:42 a. m.
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Gracias a Shabs19 por responder.
Lo estoy guardando en la carpeta de indicadores, pero por alguna extraña razón no carga. También eliminé el archivo anterior, guardé el nuevo y actualicé el navegador, pero obtengo los mismos resultados; es decir, no se muestra. Cualquier otro indicador que cargo se muestra correctamente.
285
Cita
15 de septiembre de 2015, 12:49 p. m.
 RGShock| Se unió en septiembre de 2015 | Estado: Trader | 52 publicaciones
¡GRACIAS, Honestknave! He estado usando un concepto similar con los gráficos multilínea. Es mucho más informativo y fácil de leer. Vi esto en otro sistema donde usaban cuadros para cada par de divisas y cambiaban de color para mostrar la fuerza. Empecé a usarlo hoy. ¡Me fue muy útil! Lo puse en un par que no uso y luego reduje el cuadro al tamaño del indicador. Luego se me ocurrió que sería aún más práctico si se configuraba en flotante. Así podría verlo siempre al navegar por los gráficos individuales. ¿Sería posible? Gracias de nuevo.
286
Cita
15 de septiembre de 2015, 20:30
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Citando a ntshanel
Gracias a Shabs19 por responder. Lo estoy guardando en la carpeta de indicadores, pero por alguna extraña razón no carga. También eliminé el archivo anterior, guardé el nuevo y actualicé el navegador, pero obtengo los mismos resultados; es decir, no se muestra. Cualquier otro indicador que cargo se muestra correctamente.
Es posible que tenga una compilación más antigua que aquella en la que se compiló la herramienta...
Codificador de EA/Indicadores/Alertas MT4/MT5
287
Cita
15 de septiembre de 2015, 23:04
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Cotización de FerruFx
{quote}Es posible que tengas una compilación más antigua que aquella en la que se compiló la herramienta...
Hola FerruFx
estoy un poco perdido, ¿podrías explicarme más?
288
Cita
15 de septiembre de 2015, 23:14
 RGShock| Se unió en septiembre de 2015 | Estado: Trader | 52 publicaciones
Cargué esto correctamente en uno de los gráficos de mi bróker. Pero en el otro no cargaba. Parece que leí en el foro que alguien tuvo problemas si los pares tenían nombres diferentes a los que indica el indicador. En mi caso, la cuenta que no carga tiene "ecn" después del nombre del par, como EURUSDecn. ¿Podría ser este el problema de que el archivo no cargue? Y si es así, ¿cómo puedo cambiar algo para que cargue?
289
Cita
15 de septiembre de 2015, 23:28
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Cotización de FerruFx
{quote}Es posible que tengas una compilación más antigua que aquella en la que se compiló la herramienta...
Esta es la versión del archivo que tengo (adjunto), ¿es la correcta?
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   129 KB | 648 descargas
290
Cita
16 de septiembre de 2015, 1:06 a. m.
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Citando a ntshanel
{quote}Esta es la versión del archivo que tengo (adjunto), ¿es la correcta? {file}
No me refería a si el archivo era correcto o incorrecto...

¿Cuál es el número de compilación de tu plataforma MT4 (Ayuda > Acerca de)? Si es anterior a la que se usó para compilar el indicador, ese podría ser el problema.
Codificador de EA/Indicadores/Alertas MT4/MT5
291
Cita
16 de septiembre de 2015, 1:43 a. m.
 infernal199| Membresía revocada | Se unió en abril de 2015 | 880 publicaciones
Citando a honestknave
{quote} Hola Bicarus, Las primeras versiones eran Asesores Expertos (EA). Las últimas versiones son todas indicadores. Como solución provisional para tu problema: Versión 1.09 Cambios Anulación manual para la detección automática de brokers. No necesitas esta versión si no tienes problemas. Si recibes un mensaje sobre pares faltantes, puedes introducir manualmente el prefijo o sufijo de tu broker. {image} {file}
Estoy enfrentando un problema extraño... simplemente se cargó exitosamente y luego al siguiente segundo se eliminó automáticamente
Es el polvo del que viniste y es el polvo al que volverás.
292
Cita
16 de septiembre de 2015, 5:42 a. m.
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Cotización de FerruFx
{quote} No me refería a si el archivo era correcto o incorrecto... ¿Cuál es el número de compilación de tu plataforma MT4 (Ayuda > Acerca de)? Si es anterior a la que se usó para compilar el indicador, ese podría ser el problema.

Gracias FerruFx, no iba a conseguir eso
Versión: 4.00 Build es 840
Saludos
293
Cita
16 de septiembre de 2015, 8:31 a. m.
 Súper Pipper| Se unió en septiembre de 2015 | Estado: Trader | 2 publicaciones
Llevo usando este indicador varias semanas y me encanta. Muchas gracias a todos los que participaron en la creación de este maravilloso indicador, que me ahorra mucho tiempo. Ayer a las 7 p. m. CST ocurrió algo extraño. Mientras lo observaba, la columna B/R se quedó en blanco y mostró un mensaje de " actualizando ". Después de unos minutos, la pantalla se quedó en blanco y, al revisar la lista de indicadores, el indicador desapareció. Ahora no puedo cargar csDash en el gráfico. Después, vi que varias personas tienen un problema similar. ¿Podría ser un problema de Windows 10? Agradecería cualquier ayuda para que el indicador vuelva a funcionar.
Gracias.
294
Cita
16 de septiembre de 2015, 12:18 p. m.
 arifa00000Se unió en octubre de 2011 | Estado: Comerciante | 26 publicaciones
¿Qué pasa con CSdash?
Ya no carga hoy.
Hola honestknave. Necesito tu ayuda. Es extraño.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot1.png Tamaño: 147 KB
295
Cita
16 de septiembre de 2015, 15:30
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Hola,
tengo el mismo problema al cargar csDash.
Agradecería cualquier ayuda.
Saludos .
296
Cita
17 de septiembre de 2015, 7:04 a. m.
 Todd Anderson| Se unió en julio de 2005 | Estado: Comerciante | 518 publicaciones
Me pasa lo mismo. ¿A alguien le funciona? ¿Qué versión funciona?

Gracias.


Citando a arifa00000
¿Qué pasa con CSdash? Ya no carga hoy. Hola honestknave. Necesito tu ayuda. Es extraño. {imagen}
297
Cita
17 de septiembre de 2015, 10:47 a. m.
 kisaragi7| Se unió en agosto de 2015 | Estado: Trader | 6 publicaciones
Hola,　　
este indicador es genial,
tengo una solicitud　
, hay una clasificación de monedas, quiero ver el cambio en el gráfico de líneas,　
agradezco su amable cooperación.
298
Cita
17 de septiembre de 2015, 10:49 a. m.
 RGShock| Se unió en septiembre de 2015 | Estado: Trader | 52 publicaciones
Esta mañana revisé todas las versiones de csDash desde la del 3 de mayo. Al mirar la pestaña de mi diario, aparecía la pantalla de inicio del indicador; el diario decía "Indicador personalizado csDash cargado correctamente". Pero al hacer clic en el botón "Aceptar" en csDash, mi diario decía "Indicador personalizado csDash eliminado". Así que algo falló en el código de MT4 y provocó un cambio que desconocemos. ¡Necesitamos la ayuda de Honestknave!
299
Cita
17 de septiembre de 2015, 14:06
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Honestknave, por favor, ven a rescatarnos, ¿dónde estás?
300
Cita
17 de septiembre de 2015, 14:08
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Citando a honestknave
Hola, dagoods. Las cosas van despacio ahora mismo, ya que estoy muy ocupado. Estoy modificando MADdash para que funcione con este tipo de moneda, que probablemente será la próxima versión.
Honestknave necesitamos tu ayuda aquí con csDash

P16
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Hola a todos, disculpen la ausencia.
Avísenme si esto soluciona el problema.
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   123 KB | 1542 descargas
302
Cita
18 de septiembre de 2015, 8:07 a. m.
 Súper Pipper| Se unió en septiembre de 2015 | Estado: Trader | 2 publicaciones
Hola honestknave,

muchas gracias por solucionar el problema. Ya funciona. Gracias de nuevo por desarrollar y compartir esta excelente herramienta; agradezco tu ayuda.
303
Cita
18 de septiembre de 2015, 8:35 a. m.
 ntshanel| Se unió en septiembre de 2015 | Estado: Trader | 33 publicaciones
Un millón de gracias Honestknave, está funcionando excelente.
Salvaste el día.
304
Cita
18 de septiembre de 2015, 8:40 a. m.
 Todd Anderson| Se unió en julio de 2005 | Estado: Comerciante | 518 publicaciones
Gracias por arreglar las cosas

Citando a honestknave
Hola a todos, disculpen la ausencia. Avísenme si esto soluciona el problema {file}.
305
Cita
18 de septiembre de 2015, 15:28
 RGShock| Se unió en septiembre de 2015 | Estado: Trader | 52 publicaciones
¡Gracias!
306
Cita
6 de octubre de 2015, 23:57
 kisaragi7| Se unió en agosto de 2015 | Estado: Trader | 6 publicaciones
Hola,
siempre lo uso. Es muy útil　
hoy. El valor numérico de este indicador ya no se muestra.　
Agradezco su amable colaboración.
307
Cita
7 de octubre de 2015, 1:25 a. m.
 kisaragi7| Se unió en agosto de 2015 | Estado: Trader | 6 publicaciones
Lo siento.　
Fue reparado .
308
Cita
26 de noviembre de 2015, 13:04
 omrangassan| Se unió en septiembre de 2007 | Estado: Comerciante | 157 publicaciones
Genial, ¿

podemos actualizar?
Es decir, ¿podemos mostrar todas las divisas como histograma debajo del gráfico, como Accustrength?
309
Cita
2 de diciembre de 2015, 23:40
 omrangassan| Se unió en septiembre de 2007 | Estado: Comerciante | 157 publicaciones
Hola, honestknave,

gracias por la mejora.

Pero: ¿hay alguna forma de representar las fortalezas de las divisas como líneas en un gráfico? Por ejemplo, una tabla muestra el valor instantáneo de la fortaleza de una divisa, mientras que un gráfico de líneas permite ver el comportamiento de la fortaleza de la divisa durante x horas, minutos o días en un solo gráfico. Esto puede ofrecer una mejor visualización.

Espero que entiendas mi idea. ¿Podríamos mejorar CSDash para que muestre un gráfico de líneas (en lugar del valor instantáneo de la tabla)?
310
Cita
4 de diciembre de 2015, 3:25 a. m.
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Citando a omrangassan
Hola, honestknave, gracias por la mejora. Pero: ¿hay alguna forma de representar las fortalezas de las divisas como líneas en un gráfico? Por ejemplo, una tabla muestra el valor instantáneo de la fortaleza de una divisa, mientras que un gráfico de líneas permite ver el comportamiento de la fortaleza de la divisa durante x horas, minutos o días en un solo gráfico. Esto puede ofrecer una mejor visualización. Espero que entiendas mi idea. ¿Podríamos mejorar CSDash para que muestre un gráfico de líneas (en lugar del valor instantáneo de la tabla)?
Quizás puedas comparar los datos de csdash de otro período. Por ejemplo, puedes comparar los datos de csdash diarios con los de semanal y de 4 horas para poder compararlos. Otra forma de solucionar esto es usar CCFp. Cada indicador tiene su punto fuerte (si sabes cómo buscarlo). 
311
Cita
11 de diciembre de 2015, 20:05
 hombre espíaSe unió en noviembre de 2010 | Estado: Atrapando Pips | 2159 publicaciones
Gran trabajo en este tablero HK,

muy útil...gracias.
312
Cita
14 de diciembre de 2015, 12:39 p. m.
 MtinifxSe unió en febrero de 2011 | Estado: Trader | 6018 publicaciones
Hola,

empecé a usar el indi. ¡Funcionaba perfectamente ayer!

Hoy, al intentar cargarlo, me aparece un mensaje de error: "Pares no disponibles; consulta la pestaña de expertos para más detalles".

Lo he probado todo, pero no encuentro el problema.

Saludos cordiales,

JM.
313
Cita
14 de diciembre de 2015, 15:23
 KubiastySe unió en noviembre de 2013 | Estado: Trader | 1094 publicaciones
¿Cómo instalarlo?

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: how to install it.png Tamaño: 76 KB
314
Cita
14 de diciembre de 2015, 18:09
 MtinifxSe unió en febrero de 2011 | Estado: Trader | 6018 publicaciones
Citando a Kubiasty
¿Cómo instalarlo? {imagen}
Hola Kubiasty,

sí, ese era el problema que tenía. Pero funciona bien en mi cuenta real, gracias. La cuenta demo de mi bróker no tiene todos los pares que tiene la cuenta real, ¿quizás sea eso?

Un amigo mío está experimentando el mismo mensaje de error: ¡no consigue que funcione en la plataforma de su bróker!

Saludos.
315
Cita
14 de diciembre de 2015, 20:32
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Citando a Kubiasty
¿Cómo instalarlo? {imagen}
Esto seguramente se debe al sufijo para todos tus pares...
Codificador de EA/Indicadores/Alertas MT4/MT5
316
Cita
14 de diciembre de 2015, 23:16
 comerciante de asientos888| Se unió en febrero de 2014 | Estado: Trader | 142 publicaciones
Citando a honestknave
Hola a todos, disculpen la ausencia. Avísenme si esto soluciona el problema {file}.
muchas gracias, honestknave....
317
Cita
15 de diciembre de 2015, 15:38
 Michael SchSe unió en diciembre de 2015 | Estado: Trader | 2530 publicaciones
Hola,

esta es mi primera publicación y tengo una pregunta sobre este indicador.
Necesito una buena configuración para mi sistema de scalping basado en M1 a M5.
He introducido el indicador en el gráfico H4. Necesito una breve introducción a las divisas y lo usaré si tengo una señal.
Espero que me entiendan, ya que soy de Alemania y el inglés no es mi idioma principal.

Saludos,

Michael.
El mercado es más simple de lo que piensas.
318
Cita
17 de diciembre de 2015, 4:40 a. m.
 ivan60| Se unió en julio de 2015 | Estado: Trader | 4 publicaciones
Buen momento. Hubo problemas con el indicador. Desde ayer se cargó (indicador personalizado csDash EURUSD H1: cargado correctamente) y luego se eliminó (indicador personalizado csDash EURUSD H1: eliminado). Por favor, dígame cuál es el problema.
319
Cita
17 de diciembre de 2015, 5:29 a. m.
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Citando a ivan60
Buen momento. Hubo problemas con el indicador. Desde ayer se cargó (indicador personalizado csDash EURUSD H1: cargado correctamente) y luego se eliminó (indicador personalizado csDash EURUSD H1: eliminado). Por favor, dígame cuál es el problema.
Yo también tengo el mismo problema con CSdash. Probé dos brokers y ambos fallaron.
320
Cita
17 de diciembre de 2015, 5:31 a. m.
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Citando a MichaelSch
Hola, esta es mi primera publicación y tengo una pregunta sobre este indicador. Necesito una buena configuración para mi sistema de scalping basado en M1 a M5. He introducido el indicador en el gráfico H4. Necesito una breve introducción a las divisas y lo usaré si tengo una señal. Espero que me entiendan, ya que soy de Alemania y el inglés no es mi idioma principal. Saludos, Michael.
Coloque dos CSDash m5 con diferentes periodos de balanceo uno al lado del otro. Observe qué ciclo de trabajo gana o pierde fuerza.


P17
 campo de oro| Se unió en noviembre de 2006 | Estado: Acepta la aleatoriedad del precio | 320 publicaciones
No puedo cargar el indicador por este problema... "Versión experimental expirada"
322
Cita
17 de diciembre de 2015, 9:34 a. m.
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Citando a GoldCourse
No puedo cargar el indicador por este problema... "Versión experimental expirada"
Aquí igual.

Imagen adjunta



Si desea alguna sustitución, pruebe la fortaleza de la moneda Giraia .
323
Cita
17 de diciembre de 2015, 15:27
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Hola a todos, una breve visita.
He incorporado código de MADdash que gestiona mejor las variaciones de sufijo de los brókeres y debería habilitar automáticamente los pares requeridos en la observación del mercado, si es posible.
También eliminará los mensajes de vencimiento que algunos usuarios han reportado.


Versión 1.23
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   127 KB | 1669 descargas
324
Cita
17 de diciembre de 2015, 21:28
 campo de oro| Se unió en noviembre de 2006 | Estado: Acepta la aleatoriedad del precio | 320 publicaciones
Citando a honestknave
Hola a todos, una breve visita. He incorporado código de MADdash que gestiona mejor las variaciones de sufijo de los brókeres y debería habilitar automáticamente los pares requeridos en la observación del mercado, si es posible. También eliminará los mensajes de vencimiento que algunos usuarios han reportado. Versión 1.23 {file}
Gracias
325
Cita
17 de diciembre de 2015, 22:11
 jjibl| Se unió en septiembre de 2007 | Estado: Comerciante | 205 publicaciones
Muchas gracias. Funciona perfectamente.
326
Cita
18 de diciembre de 2015, 4:54 a. m.
 falanca| Se unió en septiembre de 2007 | Estado: Comerciante | 379 publicaciones
¿Podemos organizar la plantilla de la misma manera que otros paneles (para que se abra con la plantilla seleccionada) y para que se abra automáticamente cuando llegue la señal como opción?
327
Cita
18 de diciembre de 2015, 4:55 a. m.
 falanca| Se unió en septiembre de 2007 | Estado: Comerciante | 379 publicaciones
Así que tal vez debería codificarse como un EA.
328
Cita
18 de diciembre de 2015, 8:27 a. m.
 Michael SchSe unió en diciembre de 2015 | Estado: Trader | 2530 publicaciones
Citando a redwed
{quote} Coloquen dos CSDash m5 con diferentes periodos de balanceo uno al lado del otro. Observen qué ciclo de vida aumenta o disminuye.
¿A qué te refieres con "con diferentes periodos de rodaje"? ¿
Podrías enviarme una plantilla con esto?

Gracias.


El mercado es más simple de lo que piensas.
329
Cita
18 de diciembre de 2015, 9:35 a. m.
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Citando a MichaelSch
{quote} ¿A qué te refieres con "con diferentes periodos de rotación"? ¿Podrías enviarme una plantilla con esto? Gracias.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: espero que entiendas la idea.png Tamaño: 29 KB


Espero que esto lo explique todo.

Me di cuenta de que querías saber cómo operar con CSdash.

Aquí tienes el hilo que podría ayudarte.

Ten cuidado. No operes basándote en CSDash.
2
330
Cita
20 de diciembre de 2015, 15:20
 dingdong99Se unió en octubre de 2014 | Estado: Relájate, disfruta del tiempo | 944 publicaciones
Citando a dlouw
Hola, gracias, Honest, por todas las mejoras. Estás haciendo un trabajo maravilloso. He estado experimentando con marcos de tiempo variables y me gustaría compartir mi progreso. El objetivo es calcular las barras en función del tiempo para tener en cuenta las barras y los fines de semana que faltan. Esto se basa en un CSM existente con alertas. Todo el crédito es de los desarrolladores anteriores. Soy un programador principiante, así que no se ofrecen garantías. Cualquier comentario, sugerencia o mejora será bienvenida. Me gustaría que alguien me ayudara a crear varios indies para diferentes horarios...
Prueba esto, si quieres el código fuente,
envía una dirección de correo electrónico, hermano....

Archivo(s) adjunto(s)
Tipo de archivo: ex4 CurrencyStrengthAlerts_dl.ex4   52 KB | 1788 descargas
Saludos, Ding Dong
331
Cita
5 de enero de 2016, 8:27 a. m.
 Comercio de Júpiter| Se unió en enero de 2016 | Estado: Trader | 24 publicaciones
Citando a honestknave
Hola a todos, una breve visita. He incorporado código de MADdash que gestiona mejor las variaciones de sufijo de los brókeres y debería habilitar automáticamente los pares requeridos en la observación del mercado, si es posible. También eliminará los mensajes de vencimiento que algunos usuarios han reportado. Versión 1.23 {file}
Hola Honestknave,

gracias por el indicador. Lo conecté a mi MT4, pero no funciona. A continuación se muestra el mensaje de error de la pestaña Experto:
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot1.png Tamaño: 12 KB


Espero su respuesta.

Saludos.
332
Cita
6 de enero de 2016, 15:41
 demostración de zerrowUsuario comercial | Se unió en enero de 2016 | 50 publicaciones
Hola a todos los que siguen este hilo. Uso algunos paneles, pero el problema es que parece que necesito un servidor, ya que mi portátil se congela. Creo que, en lugar de colocar muchos paneles, sería mejor obtener todos los datos necesarios en una base de datos o un archivo y luego hacer cálculos en Excel, Python o R y usar Excel solo para mostrar los resultados. Esto se debe a que no podemos exportar todos los datos de los indicadores si no tienen un búfer. Buscaba una solución para exportar datos en tiempo real, pero los scripts no funcionaban correctamente. Odio la terminal MT. Espero que algún día alguien cree una terminal de Python Community Edition con todos los futuros. 
Mi pregunta es para honestknave. ¿Podrías compartir las variables de maddash? Me gustaría exportar datos de Dash a CVS o Excel.
333
Cita
12 de febrero de 2016, 17:46
 Carina| Se unió en febrero de 2016 | Estado: Trader | 9 publicaciones
Hola.
Hace un tiempo descargué un indicador de la fortaleza de la moneda csdash y hoy ya no funciona. ¿Tienen alguna otra versión o algún otro indicador que demuestre la fortaleza relativa de las monedas? Les
agradecería mucho si pudieran ayudarme.


334
Cita
13 de febrero de 2016, 00:30
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Versión 1.24
Fecha de caducidad: 10 de agosto de 2016 (180 días)
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   126 KB | 1853 descargas
335
Cita
13 de febrero de 2016, 10:04 a. m.
 MtinifxSe unió en febrero de 2011 | Estado: Trader | 6018 publicaciones
Citando a honestknave
Un consejo rápido: elimino las versiones antiguas del indicador del hilo. Si quieres encontrar la versión actual de csDash: 1. Haz clic en el clip en la parte superior del hilo: {image} 2. Selecciona el archivo que quieres ver {image}
Honestknave,

¡muchísimas gracias de parte de todos! Es un indi maravilloso. La versión anterior funcionaba bien en la plataforma de mi bróker y tengo la extensión .i. Sin embargo, he descargado la última versión y se ha abierto perfectamente.

Gracias de nuevo.
336
Cita
15 de febrero de 2016, 9:17 a. m.
 Carina| Se unió en febrero de 2016 | Estado: Trader | 9 publicaciones
[Quote = honestknave; 8751589] Versión Fecha 1,24 Fecha: 10 de agosto de 2016 (180 días) {file} [/ quote]
Buenos días
. Intenté ingresar efectivo en el gráfico diario EUR/USD y me apareció el mensaje "Pares no disponibles: Expertos, consulten la pestaña para más detalles". ¿Qué estoy haciendo mal? ¿Ingresarlo en otro par? El archivo csDash está en la carpeta Marcadores.
337
Cita
21 de febrero de 2016, 8:31 a. m.
 MtinifxSe unió en febrero de 2011 | Estado: Trader | 6018 publicaciones
Citando a Carine
[Quote = honestknave; 8751589] Verso Data 1,24 Vencimiento: 10 de agosto de 2016 (180 días) {file} [/ quote] Buenos días de nuevo. Intenté ingresar efectivo en el gráfico diario EUR/USD y me apareció el mensaje "Pares no disponibles: Expertos, consulten la pestaña para más detalles". ¿Qué estoy haciendo mal? ¿Ingresarlo en otro par? El archivo csDash está en la carpeta de Marcadores.
Hola Carine,

creo que puedo ayudarte. Primero, el indicador debe ir a tu carpeta MQL4/indi. Haz clic en "Archivo"/Abrir carpeta de datos/MQL4/Indicadores.

Luego, haz clic en "Observación del mercado" y haz clic derecho en "Mostrar todo". Asegúrate de que tu plataforma tenga todos los pares de trading mencionados en las propiedades del indicador; de lo contrario, te mostrará el mensaje de error que recibiste. Por ejemplo, la plataforma demo de mi bróker no tiene GBPNZD ni otros pares menos negociados, así que no funciona en mi cuenta demo; solo funciona en la cuenta real, que tiene todas las combinaciones de pares.
338
Cita
21 de febrero de 2016, 11:11 a. m.
 Carina| Se unió en febrero de 2016 | Estado: Trader | 9 publicaciones
Gracias por la explicación, ahora entiendo por qué no funciona en ciertos correotras, ya encontré uno que está funcionando nuevamente gracias.
339
Cita
27 de febrero de 2016, 1:37 a. m.
 Artículos de Forex| Se unió en marzo de 2013 | Estado: "El dinero nunca duerme" | 504 publicaciones
Gracias Honestknave... Manos geniales
Los acreedores tienen mejor memoria que los deudores.
340
Cita
1 de marzo de 2016, 7:42 a. m.
 Softrader| Se unió en abril de 2011 | Estado: Comerciante | 69 publicaciones
Muchas gracias. Estoy probando diferentes medidores de divisas y este tuyo parece el mejor. Lo estoy probando en modo demo, pero creo que lo usaré en la cuenta real pronto. ¡Genial! Gracias por compartir. Les deseo todo lo mejor. Que Dios los bendiga.


P18
se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Citando a honestknave
Versión 1.24 Fecha de caducidad: 10 de agosto de 2016 (180 días) {archivo}
Gracias por esto. ¡Otros 180 días sin preocupaciones!
342
Cita
11 de marzo de 2016, 19:09
 disbelljSe unió en agosto de 2008 | Estado: Comerciante | 772 publicaciones
Citando a honestknave
Tenga en cuenta: no estoy pensando en hacer demasiado desarrollo en esta versión porque mi enfoque principal está en una versión MTF (aún no está lista): {imagen}
Me preguntaba si, en la segunda publicación del hilo, honestknave mencionó una versión MTF.

Parece que la imagen de esa publicación no muestra cifras que coincidan con el Bid Ratio de csDash para las divisas base, contraparte o diferencial. ¿Cómo calcularías un número para cada casilla? Supongo que se trata del Bid Ratio del par individual (y no de las divisas que lo componen). De ser así, ¿qué reglas usarías para colorear las casillas de forma que cada una sea verde o roja?

Pregunto porque, para MADdash, cuento el porcentaje de casillas verdes y, si supera el 75 %, lo considero una compra. Si es inferior al 25 % (es decir, más del 75 % de casillas rojas), lo considero una venta. ¡

Gracias por los indicadores! ¡Genial!

Saludos cordiales,

Don.
343
Cita
4 de abril de 2016, 14:14
 sholdea| Se unió en septiembre de 2015 | Estado: Trader | 111 publicaciones
Hola, si es posible, agregue en la parte inferior o superior de csDash el resumen de la fortaleza de todas las monedas en Compra y el resumen de la fortaleza de todas las monedas en Venta.
Perdón por mi mal inglés, todavía estoy aprendiendo.
344
Cita
9 de abril de 2016, 5:33 a. m.
 Gallauco| Se unió en abril de 2016 | Estado: Trader | 19 publicaciones
Hola, descargué el csdash, pero no puedo hacerlo funcionar... no pasa nada... ¿Alguien puede ayudarme?
Tengo que guardarlo en la carpeta de indicadores, ¿no?
345
Cita
9 de abril de 2016, 14:00 horas
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a Gallauco
Hola, descargué el csdash, pero no puedo hacerlo funcionar... no pasa nada... ¿Alguien puede ayudarme? Tengo que guardarlo en la carpeta de indicadores, ¿no?
La versión 1.24 funciona correctamente; descárgala desde la primera publicación. Es un indicador.
El único límite es el que tú mismo te pones - Felix Baumgartner
346
Cita
15 de abril de 2016, 13:45
 mokuro89Se unió en marzo de 2015 | Estado: Trader | 449 publicaciones
Hola
sobre CSM, ¿cómo se puede operar con retrocesos? Normalmente, cuando los números son 8+ o 2-, el movimiento fuerte ya está ocurriendo.
347
Cita
16 de mayo de 2016, 00:46 | Editado a las 02:08
 Yasirhawk| Se unió en febrero de 2016 | Estado: Trader | 66 publicaciones
Citando a dingdong99
{quote} Prueba esto, si quieres el código fuente, envía una dirección de correo electrónico, hermano.... {file}
Hola Dindong99, envíame ese archivo de código fuente, correo electrónico ( {dirección de correo electrónico eliminada por el personal} )

y mira en la imagen, quiero la fortaleza de la moneda de múltiples marcos de tiempo como en la primera imagen 1 para (semana, día, H4, H1, m30, m15, m5) como se muestra a continuación.

¿O algún miembro tiene ese otro CSM como en la primera imagen ? También compártalo, por favor.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: LuXing-Main-Indi.jpg Tamaño: 49 KB
Imagen adjunta

348
Cita
17 de mayo de 2016, 17:33
 piratachile| Se unió en marzo de 2015 | Estado: Comerciante | 86 publicaciones
Citando a Yasirhawk
{quote} Hola Dindong99, envíame ese archivo de código fuente, correo electrónico ({dirección de correo electrónico eliminada por el personal}) y mira en la imagen, quiero la fortaleza de la moneda de múltiples marcos de tiempo como en la primera imagen 1 para (semana, día, H4, H1, m30, m15, m5) como se muestra a continuación... o cualquier miembro tiene ese otro CSM como en la primera imagen, también compártalo por favor. {imagen} {imagen}
Hola Yasir,

¿podrías compartir tu CSM multi-período?

Saludos cordiales.
349
Cita
18 de mayo de 2016, 1:24 a. m.
 Yasirhawk| Se unió en febrero de 2016 | Estado: Trader | 66 publicaciones
Citando a piratachile
Hola Yasir, ¿podrías compartir tu CSM multi-período? Saludos cordiales.
No es mío CSM, también estoy buscando ese archivo, si lo encuentras compártelo conmigo también.
350
Cita
19 de mayo de 2016, 12:18 p. m.
 sueña en grande| Se unió en febrero de 2011 | Estado: Trader | 205 publicaciones
Gran trabajo honestknave...muy apreciado.


351
Cita
23 de mayo de 2016, 6:06 a. m. | Editado a las 3:13 p. m.
 hsoltan59| Se unió en mayo de 2015 | Estado: Trader | 53 publicaciones
Hola,
gracias por el gran trabajo honestkknave.
¿Podrías ayudarme a saber cuál es la configuración de la bestia para ( Scalp y Swing )?
Cálculos de marco de tiempo =
recuento de marco de tiempo =
umbral inferior Fuerza de CCY =
umbral superior Fuerza de CCY =
umbral diferencial =
para obtener la señal
y cómo los cálculos de alerta
gracias
352
Cita
30 de mayo de 2016, 7:01 a. m.
 joshychris| Se unió en octubre de 2014 | Estado: Trader | 28 publicaciones
Hola honestknave,
¿se puede hacer que csdash funcione solo con los pares que seleccionemos de los 28 pares en las versiones futuras? Me refiero a una opción para elegir los pares de la lista de 28 pares...
353
Cita
30 de mayo de 2016, 17:08
 hsoltan59| Se unió en mayo de 2015 | Estado: Trader | 53 publicaciones
Citando a joshychris
Hola honestknave, ¿se puede hacer que csdash funcione solo con los pares que seleccionemos de los 28 pares en las versiones futuras? Me refiero a una opción para elegir los pares de la lista de 28 pares...
gracias por responder,
pero estoy pidiendo
cálculos de marco de tiempo = 1 o 2 o 5 d, 4 h, 1 h ...
recuento de marco de tiempo = 1 o 2 o 3 .....
intensidad de ccy del umbral inferior = 6,1
intensidad de ccy del umbral superior = 2
umbral diferencial = 4 o 5 o ......
así, ¿cuál es la bestia?
gracias
354
Cita
1 de junio de 2016, 14:18
 ahmadalbab1| Se unió en junio de 2016 | Estado: Trader | 14 publicaciones
Citando a honestknave
Versión 1.24 Fecha de caducidad: 10 de agosto de 2016 (180 días) {archivo}
Regístrate sólo para decir gracias.
Cuanto más das, más recibes.
355
Cita
3 de junio de 2016, 4:04 a. m.
 dra.forex| Se unió en marzo de 2016 | Estado: Trader | 27 publicaciones
gracias .
356
Cita
3 de junio de 2016, 4:28 a. m.
 sameerbiz| Se unió en mayo de 2012 | Estado: Comerciante | 97 publicaciones
Gracias
357
Cita
3 de junio de 2016, 11:34 a. m.
 eje| Se unió en septiembre de 2009 | Estado: Comerciante | 42 publicaciones
Hola, ¿alguien podría aconsejarme? Cuando agregué el índice al gráfico, el TF predeterminado era diario. ¿Es esta la mejor configuración para el índice?
Por cierto, las alertas son bastante buenas.
Me preguntaba si hay alguna buena estrategia para usarlo con el TP y el SL de entrada.


¡Buen trabajo, Honestknave!
358
Cita
23 de junio de 2016, 5:56 a. m.
 Js3mwtRcSe unió en junio de 2016 | Estado: Compartiendo ideas y perspectivas sobre el EUR/USD | 14,892 publicaciones
Hola honestknave, uso mucho tu panel, quizás porque mi ordenador portátil no ocupa mucha memoria y es más ligero que otros paneles del foro. De todas formas, he configurado mi propia estrategia usando diferenciales de fuerza, pero mi estrategia también usa no solo la diferencia entre dos divisas individuales, sino también la fuerza de las divisas. Me alegra mucho que tu panel use alertas para las diferencias, pero no me gusta que no use alertas sonoras cuando se alcanza cierto umbral de una divisa. Si pudieras incluir en la próxima versión una opción con alertas sonoras cuando se alcance cierto umbral, como en el ejemplo: USD 6.0 ¡ALERTA SONORA! o AUD 7.5 ¡ALERTA SONORA! ¿Podrías hacerlo?
Otro problema es que no puedo crear un Asesor Experto a partir de un archivo ex. Quizás podrías agregar un búfer que use variables globales para poder obtener de ahí los datos que necesito para mi experto.

Espero que en la próxima versión consigas al menos la función de alerta sonora. ¡Que tengas un buen verano!
Buscando operaciones rentables a corto plazo...|
359
Cita
28 de junio de 2016, 1:02 a. m.
 Aguacate| Se unió en junio de 2016 | Estado: Trader | 4 publicaciones
Gracias por compartir este CSM útil y confiable.
360
Cita
5 de julio de 2016, 7:43 a. m.
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Me alegra que todos se lleven bien con csDash 

Versión 1.25
Fecha de vencimiento codificada para el 31 de diciembre de 2016 (180 días)

P19
Gracias por su contribución. ¡Excelente trabajo!
¿Podría explicarme la diferencia entre una barra verde llena y una barra vacía?
Imagen adjunta

367
Cita
27 de julio de 2016, 5:21 a. m.
 Js3mwtRcSe unió en junio de 2016 | Estado: Compartiendo ideas y perspectivas sobre el EUR/USD | 14,892 publicaciones
Citando a hirandom
Gracias por su contribución. ¡Excelente trabajo! ¿Podrían explicarme la diferencia entre una barra verde llena y una barra vacía? {imagen}
La respuesta está al final de este post: http://www.forexfactory.com/showthre...39#post8241439
Buscando operaciones rentables a corto plazo...|
368
Cita
9 de agosto de 2016, 10:46 a. m.
 cugir321| Se unió en julio de 2009 | Estado: Comerciante | 815 publicaciones
CSDash... ¡Ese es un medidor de fuerza increíble, amigo! Tuve un pequeño problema cuando el medidor estaba con el indicador MW... a veces se bloqueaba.

Facilita muchísimo encontrar los pares más fuertes... 10 segundos... ¡boom!... ¡Listo!

Cuando la diferencia es de 2 o 3, muchas veces el precio está a punto de salir del retroceso de la segunda pierna en algún tf.

Si sigue funcionando así, avísame qué debo hacer para conseguir uno que no se bloquee en diciembre de 2016. Este es el mejor indicador de fuerza que he visto.
369
Cita
11 de agosto de 2016, 7:25 a. m.
 nuevo comerciante| Se unió en enero de 2015 | Estado: Trader | 214 publicaciones
Citando a cugir321
CSDash... ¡Ese es un medidor de fuerza increíble, amigo! Tuve un pequeño problema cuando el medidor estaba con el indicador MW... a veces se bloqueaba. Facilita muchísimo encontrar los pares más fuertes... 10 segundos... ¡boom!... ¡Listo! Cuando la diferencia es de 2 o 3, muchas veces el precio está a punto de salir del retroceso de la segunda pierna en algún tf. Si sigue funcionando así, avísame qué debo hacer para conseguir uno que no se bloquee en diciembre de 2016. Este es el mejor indicador de fuerza que he visto.

Estoy de acuerdo. ¿Planean lanzar la versión sin vencimiento? Por favor, avísenme. Si pueden enviar su dirección de PayPal, haré mi contribución. Gracias.
nuevo comerciante
370
Cita
11 de agosto de 2016, 8:27 a. m.
 rickpilot601| Se unió en noviembre de 2011 | Estado: Comerciante | 10 publicaciones
Gracias por lo último. Estaría feliz de pagar por una versión sin vencimiento, el mejor de los muchos medidores de fortaleza de moneda que he probado.
371
Cita
15 de agosto de 2016, 13:06
 George K.| Se unió en febrero de 2014 | Estado: Trader | 1 publicación
Citando a honestknave
Tenga en cuenta: no estoy pensando en hacer demasiado desarrollo en esta versión porque mi enfoque principal está en una versión MTF (aún no está lista): {imagen}
Hola a todos, ¿

podría alguien ser tan amable de indicarme dónde puedo conseguir una copia de este medidor de fuerza MTF?

Muchas gracias, lo agradezco mucho.
372
Cita
15 de agosto de 2016, 13:39
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a George K.
Hola a todos, ¿podría alguien ser tan amable de indicarme dónde puedo conseguir una copia de este medidor de fuerza MTF? Muchas gracias, lo agradezco mucho.
http://www.forexfactory.com/showthre...32#post9014532
El único límite es el que tú mismo te pones - Felix Baumgartner
373
Cita
15 de agosto de 2016, 14:55
 Shahzadex| Se unió en junio de 2016 | Estado: Trader | 3 publicaciones
Error No Funciona ¿Cuál es el problema?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Image1.png Tamaño: 25 KB
374
Cita
15 de agosto de 2016, 19:41
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a Shahzadex
Error No Funciona ¿Cuál es el problema? {imagen}
Intente hacer clic derecho en MarketWatch y marque "Mostrar todos".

Si faltan pares, verifique la pestaña de expertos, deberían aparecer allí.
El único límite es el que tú mismo te pones - Felix Baumgartner
375
Cita
19 de agosto de 2016, 12:30 p. m.
 50d| Se unió en noviembre de 2009 | Estado: Puedo... | 374 publicaciones
Citando a honestknave
Me alegra que todos se lleven bien con csDash Versión 1.25 Fecha de vencimiento codificada para el 31 de diciembre de 2016 (180 días) {archivo}

Gracias por la actualización y por todo el buen trabajo que haces.

De verdad que lo aprecio mucho. Tu servicio desinteresado es muy loable.
Que Dios te bendiga.
376
Cita
19 de agosto de 2016, 13:03
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando 50d
{quote} Gracias por la actualización y por todo el buen trabajo que haces. De verdad que lo aprecio mucho. Tu servicio desinteresado es muy loable. Que Dios te bendiga.
Un gran amén de su parte.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
377
Cita
19 de agosto de 2016, 14:30
 50d| Se unió en noviembre de 2009 | Estado: Puedo... | 374 publicaciones
Citando a 919gilead
{quote} Un gran amén de su parte.
Eres otra persona que me parece muy interesante y útil.

Por tu enfoque y tu forma de responder a las personas y a los problemas. Que la ayuda siempre te llegue cuando la necesites... y que los Pips siempre te acompañen.

Saludos.
378
Cita
22 de agosto de 2016, 10:55 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando 50d
{quote} Eres otra persona que me parece muy interesante y útil. ... por tu enfoque y la forma en que respondes a las personas y a los problemas. Que la ayuda siempre te llegue cuando la necesites... y que los Pips siempre te acompañen. Saludos.
Hola, gracias 50d y un gran amén a tu oración, pues te deseo lo mismo. Saluda al presidente Buhari 

Shalom, amigo.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
379
Cita
22 de agosto de 2016, 23:16
 kisaragi7| Se unió en agosto de 2015 | Estado: Trader | 6 publicaciones
Hola　
Hay una sugerencia sobre un indicador　
para ordenar monedas　
Quiere ordenarse a su vez libremente　
Por ejemplo

aud cad chf eur gbp jpy nzd usd
↓　
usd eur gbp jpy chf cad nzd aud

Muchas gracias por tu ayuda
380
Cita
25 de agosto de 2016, 20:32
 nasz85| Se unió en enero de 2009 | Estado: Comerciante | 13 publicaciones
Gracias por el gran indicador.


P20
 sam68Usuario comercial | Se unió en octubre de 2015 | 281 publicaciones
Gracias por esta gran herramienta. ¿Alguien podría compartir su estrategia, que ha sido probada y utilizada?
Estoy pensando en adaptarme al cálculo mensual y seleccionar operaciones con base en dicho sesgo, aunque no estoy seguro de si funcionará. ¡

Todos los pips del nido y verdes para todos!
Lo que sube bajará...
384
Cita
28 de septiembre de 2016, 14:57
 Wex| Se unió en abril de 2016 | Estado: Trader | 3 publicaciones
Citando a honestknave
Me alegra que todos se lleven bien con csDash Versión 1.25 Fecha de vencimiento codificada para el 31 de diciembre de 2016 (180 días) {archivo}

Hola hk, espero que estés bien.

Actualmente tengo este problema con el csdash, el problema es que H4 muestra exactamente el mismo movimiento que H1. No estoy seguro de si esto es un error o no.

https://i.gyazo.com/68ab3a66962b370e...b32602d621.png
385
Cita
29 de septiembre de 2016, 6:29 a. m.
 Wex| Se unió en abril de 2016 | Estado: Trader | 3 publicaciones
Citando a wex
{quote} Hola hk, espero que estés bien. Actualmente tengo este problema con el csdash, el problema es que H4 muestra exactamente el mismo movimiento que H1. No estoy seguro de si esto es un error o no. https://i.gyazo.com/68ab3a66962b370e...b32602d621.png
Mejores capturas de pantalla aquí http://www.forexfactory.com/attachme...1&d=1475108078
386
Cita
29 de septiembre de 2016, 12:31 p. m.
 jarfx05Se unió en septiembre de 2014 | Estado: FF es una pérdida de tiempo | 1361 publicaciones
Hola,

esta es una herramienta excelente , csDash. ¡Funciona de maravilla!

¿Es posible usarla en Inedx, Gold y Silver?

Saludos.

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: idx1.png Tamaño: 44 KB
Si lo estás haciendo todos tenemos resultados con todo.
387
Cita
1 de octubre de 2016, 13:20
 zbyma| Se unió en febrero de 2015 | Estado: Trader | 79 publicaciones
Hola jarfx05,
¿podrías compartir los indicadores del TABLERO?
Gracias,

Zbma.
388
Cita
1 de octubre de 2016, 14:01
 amigos1000| Se unió en enero de 2013 | Estado: Comerciante | 32 publicaciones
Publicación 360
389
Cita
1 de octubre de 2016, 14:12
 zbyma| Se unió en febrero de 2015 | Estado: Trader | 79 publicaciones
Hola amigos 1000,

gracias CS Meter.
EA necesita un panel de control experto.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: DASH.png Tamaño: 44 KB
390
Cita
3 de octubre de 2016, 12:33 p. m.
 ychaim| Se unió en septiembre de 2016 | Estado: Trader | 13 publicaciones
Jefe, ¿podría compartir este panel, por favor?
Saludos.
ychaim
391
Cita
5 de octubre de 2016, 6:39 a. m.
 ychaim| Se unió en septiembre de 2016 | Estado: Trader | 13 publicaciones
Hola chicos, disculpen la molestia de nuevo... me pregunto si es posible obtener este tablero con Dax30, etc.

Cualquier ayuda será muy apreciada... ychaim
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: idx1.png Tamaño: 47 KB
ychaim
392
Cita
1 de noviembre de 2016, 14:36
 saranga| Membresía revocada | Se unió en marzo de 2016 | 1615 publicaciones
Cita
bribón honesto
gracias amigo
393
Cita
5 de noviembre de 2016, 15:28
 sueña en grande| Se unió en febrero de 2011 | Estado: Trader | 205 publicaciones
Citando a honestknave
Me alegra que todos se lleven bien con csDash Versión 1.25 Fecha de vencimiento codificada para el 31 de diciembre de 2016 (180 días) {archivo}
Gracias honestknave, gran trabajo.

db
394
Cita
16 de noviembre de 2016, 10:50 a. m.
 patrón13| Se unió en febrero de 2016 | Estado: Trader | 438 publicaciones
Muchas gracias por esta excelente herramienta.
Mis operaciones de hoy se realizaron con la configuración predeterminada y en una cuenta de dinero real
. ¡Genial! Seguiré probando y publicando los resultados.

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: FF-10.PNG Tamaño: 33 KB
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: FF-10.PNG Tamaño: 33 KB
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Captura de pantalla (35).png Tamaño: 430 KB
395
Cita
22 de noviembre de 2016, 9:23 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Una recopilación de publicaciones relevantes para describir la configuración y los cálculos de esta increíble herramienta.

Archivo(s) adjunto(s)
Tipo de archivo: pdf Honestknave C-Dash.pdf   562 KB | 2918 descargas
El único límite es el que tú mismo te pones - Felix Baumgartner
1
396
Cita
23 de noviembre de 2016, 9:49 a. m.
 Águila poderosa| Se unió en septiembre de 2012 | Estado: Trader | 4 publicaciones
Honestknave, ¿la opción "Abrir con clic y plantilla aplicada para cada par" funciona?

Si es así, por favor, ayúdanos a aplicarla en los gráficos.

Gracias por esta excelente herramienta.
397
Cita
29 de noviembre de 2016, 22:50
 gran jefe| Se unió en noviembre de 2006 | Estado: Comerciante | 200 publicaciones
Citando a honestknave
Me alegra que todos se lleven bien con csDash Versión 1.25 Fecha de vencimiento codificada para el 31 de diciembre de 2016 (180 días) {archivo}
Leyendo tu hilo, me han llamado la atención muchos buenos comentarios. ¡Felicidades!
¿Es este un indicador comercial? Porque tiene fecha de caducidad.
Saludos.
398
Cita
4 de diciembre de 2016, 8:33 a. m.
 Arte 5| Se unió en septiembre de 2014 | Estado: Trader | 169 publicaciones
Hola honestknave,

gracias por este indicador, pero tengo un problema:

cada vez que lo incluyo en un gráfico (1 csdash, 2 o 3 a veces), guardo la plantilla y cierro MT4, desaparece. Ni siquiera aparece en la plantilla.

¿Qué debo hacer?
399
Cita
4 de diciembre de 2016, 10:48 a. m.
 ruma29| Membresía revocada | Se unió en agosto de 2015 | 1243 publicaciones
Citando a honestknave
Me alegra que todos se lleven bien con csDash Versión 1.25 Fecha de vencimiento codificada para el 31 de diciembre de 2016 (180 días) {archivo}
¿Por qué el indicador tiene fecha de vencimiento?
400
Cita
4 de diciembre de 2016, 13:49
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a ruma29
{quote}¿Por qué el indicador tiene fecha de vencimiento?
http://www.forexfactory.com/showthre...76#post8252576

La última versión siempre está en la publicación n.° 1,
vencimiento el 31 de diciembre de 2016
El único límite es el que tú mismo te pones - Felix Baumgartner


P21
panameño| Se unió en enero de 2010 | Estado: Trader | 1448 publicaciones
Una herramienta fantástica para limitar la selección de pares negociables y reforzar las señales del sistema. ¡Excelente trabajo!


Algo que utilizo para ver qué tipo de día es y dónde nos encontramos, gracias a tu ratio de oferta, es mi ADR dinámico de 10 días. Uso un ADR de 10 días sin fines de semana, lo que me da una media móvil del rango diario promedio de las últimas dos semanas. Se traza en mi gráfico desde la apertura y luego se ajusta según el cálculo a partir del mínimo o el máximo, el precio actual más lejano. Es asombroso cómo cambia el mercado en este punto. Cuando se rompe el H o el L del ADR y el precio continúa, esto también es importante. Dejo de operar con cualquier par si el precio supera el 85 o 90 % del movimiento del ADR hacia el H o el L. Si rompe el H o el L y se expande más allá del 120 %, es un día de gran tendencia y volveré a operar con el par. Si el precio se estanca o se revierte en el ADR 10 D H o L, buscaré oportunidades en la dirección opuesta. Los niveles de expansión de FIB del ADR10 son buenos objetivos y áreas de interés en esos días de expansión. Solo mis 0.02.
1
402
Cita
10 de diciembre de 2016, 14:41
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Versión: 1.26.

Caducidad: 30 de junio de 2017.

Me alegra que algunas personas encuentren csDash útil.

El futuro de MT4 está en duda tras algunos comentarios en la prensa y la eliminación del instalador de MT4 del sitio web de MetaQuotes (el instalador de MT4, en realidad, instala MT5).

Por ello, no seguiré desarrollando proyectos de MT4. Aún no he decidido si migraré proyectos a la plataforma MT5.

No obstante, estoy lanzando la versión 1.26 de csDash con fecha de caducidad para mediados del próximo año (sin cambios respecto a la versión 1.25). ¡

Les deseo a todos un próspero 2017!
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   127 KB | 3137 descargas
6
403
Cita
10 de diciembre de 2016, 18:21
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a honestknave
Versión: 1.26 Caducidad: 30 de junio de 2017 Me alegra que algunas personas encuentren útil csDash.
Gracias
El único límite es el que tú mismo te pones - Felix Baumgartner
1
404
Cita
10 de diciembre de 2016, 18:28
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
Versión: 1.26. Caducidad: 30 de junio de 2017. Me alegra que csDash les resulte útil a algunas personas. El futuro de MT4 está en duda tras algunos comentarios en la prensa y la eliminación del instalador de MT4 del sitio web de MetaQuotes (el instalador de MT4 instala MT5). Por ello, no seguiré desarrollando proyectos de MT4. Aún no he decidido si migraré proyectos a la plataforma MT5. No obstante, estoy lanzando la versión 1.26 de csDash con fecha de caducidad para mediados del próximo año (sin cambios respecto a la versión 1.25). Espero...

Gracias como siempre Capitán.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
2
405
Cita
12 de diciembre de 2016, 16:48
 michelmichel| Se unió en octubre de 2015 | Estado: Trader | 15 publicaciones
¿Puede este indicador servir como PIN para el Dashboard EAX? De ser así, ¿con qué indicador de conector?
406
Cita
12 de diciembre de 2016, 23:16
 comerciante de asientos888| Se unió en febrero de 2014 | Estado: Trader | 142 publicaciones
Citando a honestknave
Versión: 1.26. Caducidad: 30 de junio de 2017. Me alegra que csDash les resulte útil a algunas personas. El futuro de MT4 está en duda tras algunos comentarios en la prensa y la eliminación del instalador de MT4 del sitio web de MetaQuotes (el instalador de MT4 instala MT5). Por ello, no seguiré desarrollando proyectos de MT4. Aún no he decidido si migraré proyectos a la plataforma MT5. No obstante, estoy lanzando la versión 1.26 de csDash con fecha de caducidad para mediados del próximo año (sin cambios respecto a la versión 1.25). Espero...
¡Gracias por la actualización, honestknave!

st888
407
Cita
13 de diciembre de 2016, 8:05 a. m.
 taipan99| Se unió en octubre de 2010 | Estado: Comerciante | 32 publicaciones
Gracias por la actualización. Es útil para el trading.
408
Cita
16 de diciembre de 2016, 11:51 a. m.
 zafarrafiq| Membresía revocada | Se unió en noviembre de 2013 | 7 publicaciones
Citando a honestknave
Versión: 1.26. Caducidad: 30 de junio de 2017. Me alegra que csDash les resulte útil a algunas personas. El futuro de MT4 está en duda tras algunos comentarios en la prensa y la eliminación del instalador de MT4 del sitio web de MetaQuotes (el instalador de MT4 instala MT5). Por ello, no seguiré desarrollando proyectos de MT4. Aún no he decidido si migraré proyectos a la plataforma MT5. No obstante, estoy lanzando la versión 1.26 de csDash con fecha de caducidad para mediados del próximo año (sin cambios respecto a la versión 1.25). Espero...
Señor, soy nuevo. Por favor, dígame si quiero ingresar esto. Dígame cómo puedo usarlo en mi Meta Trader 4 o 5.
409
Cita
16 de diciembre de 2016, 16:38
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a zafarrafiq
{quote} Señor, soy nuevo. Por favor, dígame si quiero ingresar esto. Dígame cómo puedo usarlo en mi Meta Trader 4 o 5.
Es un indicador exclusivo para MT4. Copie y pegue el indicador en su carpeta de indicadores a través de MT4. Menú Archivo > Abrir carpeta de datos > Carpeta MQL > Indicadores.

El indicador más reciente siempre está en la publicación n.° 1.

Configuración y funciones:
http://www.forexfactory.com/showthre...19#post9275919
El único límite es el que tú mismo te pones - Felix Baumgartner
410
Cita
17 de diciembre de 2016, 7:10 a. m.
 zafarrafiq| Membresía revocada | Se unió en noviembre de 2013 | 7 publicaciones
Gracias por esta buena ayuda
Ver publicación
Oculto por incumplimiento del Código de Conducta del Comerciante
zafarrafiq
412
Cita
5 de enero de 2017, 8:21 a. m.
 Ozzy1984| Se unió en enero de 2017 | Estado: Trader | 1 publicación
Hola, este indicador me ha ayudado mucho, por favor no lo quiten del mt4, desde que comencé a usar este indicador, mi sistema de trading ha cambiado y ahora me considero trader, así que asegúrense de que no caduque.
413
Cita
5 de enero de 2017, 18:02
 HenryOko| Se unió en septiembre de 2016 | Estado: Trader | 37 publicaciones
Citando a Ozzy1984
Hola, este indicador me ha ayudado mucho, por favor no lo quiten del mt4, desde que comencé a usar este indicador, mi sistema de trading ha cambiado y ahora me considero trader, así que asegúrense de que no caduque.
¿Es esto un EA o un indicador?
414
Cita
5 de enero de 2017, 18:56
 GorriónSe unió en mayo de 2014 | Estado: Trader | 4735 publicaciones
Citando a Henry Oko
{quote} ¿Es esto un EA o un indicador?
¿Vamos hombre?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot_1.jpg Tamaño: 165 KB
Toma lo que puedas y no des nada a cambio
415
Cita
6 de enero de 2017, 00:23
 HenryOko| Se unió en septiembre de 2016 | Estado: Trader | 37 publicaciones
Citando a Husky77
{quote} ¿Vamos hombre? {image}

¡Jajaja! Lo veo después de mi propia publicación.
416
Cita
8 de enero de 2017, 21:14
 nuevo comerciante| Se unió en enero de 2015 | Estado: Trader | 214 publicaciones
Citando a Ozzy1984
Hola, este indicador me ha ayudado mucho, por favor no lo quiten del mt4, desde que comencé a usar este indicador, mi sistema de trading ha cambiado y ahora me considero trader, así que asegúrense de que no caduque.

Estoy de acuerdo; esta es una herramienta excelente.

Si pudieras, por favor, crea también una para MT5. Si no tienes tiempo, puedo contribuir con mi tiempo al desarrollo para MT5 y enviarlo para tu revisión, para que podamos lanzarla para MT5.

Agradezco mucho tu tiempo y esfuerzo.

nzt
nuevo comerciante
417
Cita
9 de enero de 2017, 6:14 a. m.
 Js3mwtRcSe unió en junio de 2016 | Estado: Compartiendo ideas y perspectivas sobre el EUR/USD | 14,892 publicaciones
Citando a Ozzy1984
Hola, este indicador me ha ayudado mucho, por favor no lo quiten del mt4, desde que comencé a usar este indicador, mi sistema de trading ha cambiado y ahora me considero trader, así que asegúrense de que no caduque.



Metatrader no cerrará la plataforma MT4 tan pronto, así que no creo que no tengamos una actualización. Leí en alguna parte que hasta 2019 seguiremos pudiendo usar MT4. Además, el desarrollador debería empezar a trabajar en dos versiones del indicador (para MT4 y MT5) si quiere mantener este hilo activo.
Buscando operaciones rentables a corto plazo...|
418
Cita
12 de enero de 2017, 22:48
 Juan007Se unió en agosto de 2012 | Estado: Trader | 1275 publicaciones
muy agradable
gracias
honesto

gracias
419
Cita
1 de febrero de 2017, 8:16 a. m.
 fibo38Se unió en marzo de 2016 | Estado: Operador completo | 1378 publicaciones
Citando a honestknave
Versión: 1.26. Caducidad: 30 de junio de 2017. Me alegra que csDash les resulte útil a algunas personas. El futuro de MT4 está en duda tras algunos comentarios en la prensa y la eliminación del instalador de MT4 del sitio web de MetaQuotes (el instalador de MT4 instala MT5). Por ello, no seguiré desarrollando proyectos de MT4. Aún no he decidido si migraré proyectos a la plataforma MT5. No obstante, estoy lanzando la versión 1.26 de csDash con fecha de caducidad para mediados del próximo año (sin cambios respecto a la versión 1.25). Espero...
Gracias, honestknave.

¿Es posible comprar un indicador?
Por favor, avísame.
Saludos.
420
Cita
2 de febrero de 2017, 5:41 a. m.
 Akamaro| Se unió en enero de 2017 | Estado: Trader | 50 publicaciones
Citando a honestknave
Versión: 1.26. Caducidad: 30 de junio de 2017. Me alegra que csDash les resulte útil a algunas personas. El futuro de MT4 está en duda tras algunos comentarios en la prensa y la eliminación del instalador de MT4 del sitio web de MetaQuotes (el instalador de MT4 instala MT5). Por ello, no seguiré desarrollando proyectos de MT4. Aún no he decidido si migraré proyectos a la plataforma MT5. No obstante, estoy lanzando la versión 1.26 de csDash con fecha de caducidad para mediados del próximo año (sin cambios respecto a la versión 1.25). Espero...

Lo siento, pero si se me permite preguntar, ¿por qué hacerlo caducar?
Las estrategias comerciales son como una receta: ¡ingredientes adecuados y cocinas excelente!


P22
 ismael360| Se unió en agosto de 2011 | Estado: Comerciante | 59 publicaciones
En lugar de descontinuar el indicador, ¿por qué no comercializarlo y ofrecerlo en un sitio web independiente con una suscripción como la de Forex Early Warning?
Haces un trabajo excelente. Y mucha gente lo usa, incluyéndome a mí. Estoy seguro de que a la mayoría no le importaría pagar una suscripción razonable de entre 5 y 10 dólares al mes.

Todos entendemos el esfuerzo que dedicas a tu trabajo. Y deberías recibir una compensación por ello, lo cual no está nada mal. Así no tendrías que preocuparte por la migración a MQL5 y nosotros no tendríamos que preocuparnos por no tener acceso a tus excelentes herramientas después del verano

.
1
424
Cita
3 de febrero de 2017, 14:21
 Akamaro| Se unió en enero de 2017 | Estado: Trader | 50 publicaciones
Lo único que me molesta actualmente es que realmente estoy disfrutando de este medidor de moneda y me está ayudando, PERO no quiero acercarme demasiado a él porque, ¿qué pasa si nunca lo volverás a obtener una vez que el tiempo de vencimiento llega a su punto y nunca lo vuelves a obtener...? ¡

Realmente es un gran indicador, debo decirlo! ¡¡¡Y me encanta!!!
Las estrategias comerciales son como una receta: ¡ingredientes adecuados y cocinas excelente!
425
Cita
3 de febrero de 2017, 15:23
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a akamaro
Lo único que me molesta actualmente es que realmente estoy disfrutando de este medidor de moneda y me está ayudando, PERO no quiero acercarme demasiado a él porque, ¿qué pasa si nunca lo volverás a obtener una vez que el tiempo de vencimiento llega a su punto y nunca lo vuelves a obtener...? ¡Realmente es un gran indicador, debo decirlo! ¡¡¡Y me encanta!!!
No creo que tengas que preocuparte por eso. Esta es la PROMESA de Honestknave:

" He tenido algunas preguntas sobre la caducidad de MADdash (y csDash).

Cada versión tiene una fecha de caducidad predefinida. No se preocupen, no se debe a un plan nefasto para empezar a cobrar por ello. Todo lo contrario.

Hay una pequeña pero persistente minoría que recorre foros de trading robando indicadores y Asesores Expertos para venderlos a personas desprevenidas que no saben que es gratis. Tengo un gran problema con esto. 

Hasta que se descifre la Build 600+ (lo cual será un día triste), la fecha de caducidad es una última medida de seguridad contra este tipo de estafas, ya que limita su duración.

Por esta razón, no existen versiones de MADdash ni csDash sin fecha de caducidad, y el código fuente nunca se ha publicado para nadie. Ni siquiera para mi gato. En realidad no tengo gato, pero si lo tuviera, no lo tendría. Así que, por favor, no pidan el código fuente, ya que... No quiero ofender. 

Si alguna vez abandono MADdash (o csDash) por completo, publicaré una versión final sin fecha de caducidad . Pero por ahora, sigo desarrollando los paneles de forma activa (¡más o menos!) .

Shalom
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
2
426
Cita
3 de febrero de 2017, 15:58
 GorriónSe unió en mayo de 2014 | Estado: Trader | 4735 publicaciones
Estoy de acuerdo con Gil. Sería un desperdicio compartir el código de cualquiera de esas brillantes herramientas. Y eso es simple porque incluso si podemos tenerlas aquí gratis, algunos idiotas pueden venderlas y las personas buenas pueden ser engañadas para pagar por ellas, pero ocultas bajo nombres extraños antes de descubrir que, de hecho, todas son gratuitas aquí. Siempre que sea gratis es perfecto y envíe deseos de salud al codificador y felicitaciones por esto.
Para mí, cualquier persona aquí que pida el código fuente es sospechoso, lo siento, pero esta es mi opinión personal. Si sabe pedir código, entonces sabe lo que tener un código puede hacer por usted y qué hacer con él.

¡Salud!
Toma lo que puedas y no des nada a cambio
427
Cita
3 de febrero de 2017, 16:29
 Akamaro| Se unió en enero de 2017 | Estado: Trader | 50 publicaciones
Citando a 919gilead
{quote} No creo que tengas que preocuparte por eso. Esta es la PROMESA de Honestknave: "He tenido algunas preguntas sobre la expiración de MADdash (y csDash). Hay una fecha de expiración predefinida en cada lanzamiento. No te preocupes, esto no se debe a un plan nefasto para empezar a cobrar por ello. Todo lo contrario. Hay una pequeña pero persistente minoría que recorre foros de trading robando indicadores y Asesores Expertos para venderlos a personas desprevenidas que no...

WOW!!!!

gracias.....! ahora puedo seguir estando enamorado!
Las estrategias comerciales son como una receta: ¡ingredientes adecuados y cocinas excelente!
428
Cita
5 de febrero de 2017, 14:08
 Tirachinas1Se unió en febrero de 2012 | Estado: Trader | 1894 publicaciones
Citando a honestknave
Versión: 1.26. Caducidad: 30 de junio de 2017. Me alegra que csDash les resulte útil a algunas personas. El futuro de MT4 está en duda tras algunos comentarios en la prensa y la eliminación del instalador de MT4 del sitio web de MetaQuotes (el instalador de MT4 instala MT5). Por ello, no seguiré desarrollando proyectos de MT4. Aún no he decidido si migraré proyectos a la plataforma MT5. No obstante, estoy lanzando la versión 1.26 de csDash con fecha de caducidad para mediados del próximo año (sin cambios respecto a la versión 1.25). Espero...
Hola HK, gran material el que compartiste aquí. Solo quiero aclarar un problema que tengo. ¿Está bien si limito los pares a 6 por cuestiones de espacio? ¿Seguirá funcionando la alerta porque me encantan las alertas? Gracias.
429
Cita
5 de febrero de 2017, 14:12
 Akamaro| Se unió en enero de 2017 | Estado: Trader | 50 publicaciones
Citando a Slingshots1
{quote} Hola HK, muy buen material el que compartiste aquí. Solo quiero aclarar un problema que tengo. ¿Está bien si limito los pares a 6 por cuestiones de espacio? ¿Seguirá funcionando la alerta porque me encantan las alertas? Gracias.

Por cuestiones de espacio , 
establecí el tamaño de fuente a un valor más bajo, ¡así puedo ver 
todo 
! 
Las estrategias comerciales son como una receta: ¡ingredientes adecuados y cocinas excelente!
430
Cita
6 de febrero de 2017, 4:30 a. m.
 Akamaro| Se unió en enero de 2017 | Estado: Trader | 50 publicaciones
Citando a Slingshots1
{quote} Hola HK, muy buen material el que compartiste aquí. Solo quiero aclarar un problema que tengo. ¿Está bien si limito los pares a 6 por cuestiones de espacio? ¿Seguirá funcionando la alerta porque me encantan las alertas? Gracias.
Hola, no sé si has venido bien, pero aquí está mi configuración:
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot1.png Tamaño: 111 KB
Las estrategias comerciales son como una receta: ¡ingredientes adecuados y cocinas excelente!
431
Cita
25 de abril de 2017, 5:32 a. m.
 FXtraderPH| Se unió en abril de 2017 | Estado: Trader | 4 publicaciones
Buen día, operadores de divisas.

Soy nuevo en este foro y en el trading de divisas. He estado leyendo algunos hilos y estoy muy agradecido de haber descubierto este sitio.
Ahora mismo, descargué la última versión de CSDASH 1.26 (en {1}). Pero al cargarla en mi gráfico, me aparece el error "Pares no disponibles".
Al revisar la pestaña de experto, los siguientes pares no están disponibles en mi bróker:
NZDCHF ,
NZDCAD,
GBPCAD,
CHF, JPY
, CADCHF
, AUDCHF
, AUDCAD.

Así que edité la entrada y puse "false" en los pares mencionados. Sin embargo, el error persiste. ¿
Qué debo hacer?

Además, ¿qué PIN?

Muchas gracias.
432
Cita
25 de abril de 2017, 6:37 a. m.
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Cotización de FXtraderPH
Buen día, operadores de divisas. Soy nuevo en este foro y en el trading de divisas. He estado leyendo algunos hilos y estoy muy agradecido de haber conocido este sitio. Ahora mismo, descargué la última versión de CSDASH 1.26 (en {1}). Pero al cargarla en mi gráfico, me aparece el error "Pares no disponibles". Al revisar la pestaña de experto, los siguientes pares no están disponibles en mi bróker: NZDCHF, NZDCAD, GBPCAD, CHF, JPY, CADCHF, AUDCHF, AUDCAD. Así que edité la entrada y puse "false" en los pares mencionados. Sin embargo, el error es...
Intente hacer clic derecho en la lista de pares (Observación del mercado) > Mostrar todo...
Codificador de EA/Indicadores/Alertas MT4/MT5
433
Cita
25 de abril de 2017, 6:50 a. m.
 FXtraderPH| Se unió en abril de 2017 | Estado: Trader | 4 publicaciones
Cotización de FerruFx
{quote} Intente hacer clic derecho en la lista de pares (Observación del mercado) > Mostrar todo...
Gracias por la respuesta, señor FerruFX. La verdad es que no sé cómo hacerlo. Abrí Marketwatch (Ctrl+M). ¿Dónde hago clic derecho para ver "Mostrar todo"?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Sc.jpg Tamaño: 775 KB
434
Cita
25 de abril de 2017, 6:55 a. m.
 FXtraderPH| Se unió en abril de 2017 | Estado: Trader | 4 publicaciones
Lo siento, ya lo entiendo... después de eso, ¿qué hago? ¿Intentaré cargar el CSDash? Luego, pondré "false" en los pares que mi bróker no tiene.
Muchas gracias.
435
Cita
25 de abril de 2017, 7:28 a. m.
 FerruFxSe unió en mayo de 2007 | Estado: Programador de Asesores Expertos (EAs), Indicadores y Alertas MT4/MT5 | 6536 publicaciones
Cotización de FXtraderPH
{quote} Gracias por la respuesta, señor FerruFX. La verdad es que no sé cómo hacerlo. Abrí Marketwatch (Ctrl + M). ¿Dónde hago clic derecho para ver "Mostrar todo"? {image}
Haga clic derecho con el ratón...

Luego recargue el indicador.
Codificador de EA/Indicadores/Alertas MT4/MT5
436
Cita
26 de abril de 2017, 6:21 a. m.
 FXtraderPH| Se unió en abril de 2017 | Estado: Trader | 4 publicaciones
Cotización de FerruFx
{quote} Haga clic derecho con el mouse... Luego recargue el indicador.
Buen día, señor FerruFx.

Ya realicé el procedimiento. Presioné Ctrl + M (para mostrar el Marketwatch), luego hice clic derecho en los pares y luego en "Mostrar todo".
Después, recargué el indicador csdash (versión más reciente) y seleccioné "falso" en los siguientes pares, ya que mi bróker no los tiene:
NZDCHF,
NZDCAD,
GBPCAD
, CHF, JPY,
CADCHF,
AUDCHF,
AUDCAD.

Sin embargo, sigue ocurriendo el mismo error. ¿Qué puedo hacer, señor?
Gracias por la ayuda.
437
Cita
9 de mayo de 2017, 14:14
 Kimimax| Se unió en diciembre de 2010 | Estado: Trader | 46 publicaciones
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: 1231.png Tamaño: 89 KB
438
Cita
7 de junio de 2017, 3:43 a. m.
 Cliffy C| Se unió en febrero de 2015 | Estado: Trader | 48 publicaciones
Citando a honestknave
Versión: 1.26. Caducidad: 30 de junio de 2017. Me alegra que csDash les resulte útil a algunas personas. El futuro de MT4 está en duda tras algunos comentarios en la prensa y la eliminación del instalador de MT4 del sitio web de MetaQuotes (el instalador de MT4 instala MT5). Por ello, no seguiré desarrollando proyectos de MT4. Aún no he decidido si migraré proyectos a la plataforma MT5. No obstante, estoy lanzando la versión 1.26 de csDash con fecha de caducidad para mediados del próximo año (sin cambios respecto a la versión 1.25). Espero...

¡Gracias! Me encanta esta versión.
439
Cita
10 de junio de 2017, 14:30
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Versión: 1.27.

Caducidad: 31 de diciembre de 2017.

Hay estafadores que venden csDash (y MADdash), por lo que he añadido un mensaje de confirmación para advertir a las víctimas.

Solo debería ser necesario confirmar la cuenta una vez por cuenta. Por lo demás, esta versión no ha sufrido cambios desde la 1.26.

¡Les deseo éxito a todos!
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   141 KB | 3213 descargas
5
440
Cita
10 de junio de 2017, 17:16
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
Versión: 1.27. Caducidad: 31 de diciembre de 2017. Hay estafadores que venden csDash (y MADdash), por lo que he añadido un mensaje de confirmación para advertir a las víctimas. Solo debería ser necesario confirmar la cuenta una vez por cuenta. Por lo demás, esta versión no ha sufrido cambios desde la 1.26. ¡Les deseo éxito a todos! {file}
Gracias como siempre, Capitán, y me alegra saber de usted. 

Le deseo éxito también.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad


P23
deseo éxito a todos! {file}
¡Gracias! Hay otros paneles, pero Cdash es mejor porque es simple.
447
Cita
2 de julio de 2017, 17:29
 rustydavo| Se unió en julio de 2017 | Estado: Trader | 141 publicaciones
Cotización de FXtraderPH
{quote} Buen día, señor FerruFx. Ya realicé el procedimiento. Presioné Ctrl + M (para mostrar el Marketwatch), luego hice clic derecho en los pares y luego en "Mostrar todo". Después, recargué el indicador csdash (versión más reciente) y seleccioné "falso" en los siguientes pares, ya que mi bróker no los tiene: NZDCHF, NZDCAD, GBPCAD, CHF, JPY, CADCHF, AUDCHF, AUDCAD. Sin embargo, sigue ocurriendo el mismo error. ¿Qué debo hacer? Gracias por la ayuda.

¿Encontraste una solución? Tengo el mismo problema. Sufijo del corredor (£), pero no le gustan mis apuestas y no las muestra. ¡Me estoy volviendo loco!
448
Cita
3 de julio de 2017, 4:30 a. m.
 shahab24s| Se unió en abril de 2017 | Estado: Trader | 67 publicaciones
Hola a todos,
por favor ayúdenme. cDash2EAX no se carga en mi MT4
tanx.
449
Cita
3 de julio de 2017, 4:44 a. m.
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Citando a shahab24s
Hola a todos, por favor ayúdenme. cDash2EAX no se carga en mi MT4 tanx.
Shahab,

Honestknave no participa en la creación de pines para EAX. Por favor, ve aquí . Le pedí a HP que nos proporcionara el enlace a una versión actualizada de cDash2EAX.

Saludos, 

Lee.
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
450
Cita
17 de julio de 2017, 6:23 a. m.
 Tirachinas1Se unió en febrero de 2012 | Estado: Trader | 1894 publicaciones
Citando a 919gilead
Buenos días {imagen}
Hola 919, por favor necesito humildemente tu ayuda aquí. ¿Puedes ayudarme a hacer una plantilla de cdash como la que se muestra aquí, incluidos todos los demás efectos? Por favor, ayúdame. Saludos.
451
Cita
19 de julio de 2017, 5:44 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Slingshots1
{quote} Hola 919, por favor necesito humildemente tu ayuda aquí. ¿Puedes ayudarme a hacer una plantilla de cdash como la que se muestra aquí, incluidos todos los demás efectos? Por favor, ayúdame. Saludos.
Hola Slingshots,

me gustaría poder ayudarte, pero lamentablemente no puedo. Sin embargo, te guiaré en cómo configurar tu propio sistema. Sabes que los sistemas de trading evolucionan con la experiencia, y ya no uso el sistema de 2015 al que te refieres, así que no recuerdo el período de la media móvil. Si lees mis publicaciones de esa época, puede que encuentres las medias móviles

que tienes en el gráfico:
MA Ribbon se puede descargar aquí y puedes usar el MA de tu elección
El minigráfico se puede descargar aquí y, si las fuentes no se muestran correctamente, deberá descargar la fuente correcta.
El estocástico está en tu MT4
Puede descargar el histograma del CCI aquí y
Por supuesto, el MADdash actual está en este hilo. Lo único que hice para el panel fue configurar la opción "mostrar grupos de divisas" como "falso", mostrando así solo los grupos de divisas seleccionados (TF1, TF2, etc.).
La información de los datos (dispersión y rango) también se puede descargar aquí.
Puede buscar el indicador de noticias en FF y debería encontrar uno adecuado para su uso.
Espero que esto ayude y si me olvido de algo, háganmelo saber.

Saludos,

George.

Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
452
Cita
2 de agosto de 2017, 9:00 a. m.
 gogonkt| Se unió en julio de 2010 | Estado: Comerciante | 28 publicaciones
Citando a honestknave
Versión: 1.27. Caducidad: 31 de diciembre de 2017. Hay estafadores que venden csDash (y MADdash), por lo que he añadido un mensaje de confirmación para advertir a las víctimas. Solo debería ser necesario confirmar la cuenta una vez por cuenta. Por lo demás, esta versión no ha sufrido cambios desde la 1.26. ¡Les deseo éxito a todos! {file}
¡Señor! ¡
Gracias por su excelente trabajo!
453
Cita
19 de agosto de 2017, 19:21
 Vida de Kurt| Se unió en agosto de 2017 | Estado: Trader | 2 publicaciones
Hola George,

he estado intentando registrarme en el foro de Steve, pero no encuentro dónde hacerlo. ¿Están cerrados los nuevos registros?
454
Cita
23 de agosto de 2017, 20:13
 Gatillo feliz| Se unió en agosto de 2017 | Estado: Trader | 4 publicaciones
Vaya, @Honestknave, todo lo que puedo decir es que este es un trabajo brillante.

Me suscribí al hilo.
455
Cita
31 de agosto de 2017, 20:42
 EllenbrookSe unió en octubre de 2011 | Estado: Trader | 1026 publicaciones | En línea
Hola,
gracias de nuevo, el mejor tablero que mi santo grial no puede prescindir de ti, eres un maestro, un millón de gracias.
456
Cita
31 de agosto de 2017, 20:51
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Kurtlife
Hola George, he estado intentando registrarme en el foro de Steve, pero no encuentro dónde hacerlo. ¿Están cerrados los nuevos registros?
Hola Kurt, no sé por qué la gente tiene problemas para registrarse, ya que no soy administrador. Acabo de encontrar un programador/codificador que me ayude con mi proyecto y, por lo tanto, me vi obligado a publicar el panel de control. Sigue intentándolo, ya que creo que el registro no está cerrado.

Saludos,

George.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
457
Cita
1 de septiembre de 2017, 7:12 a. m.
 aindriu80| Se unió en enero de 2017 | Estado: Trader | 10 publicaciones
gracias por la cinta excelente!!
458
Cita
12 de septiembre de 2017, 00:12
 kalpavata| Se unió en agosto de 2009 | Estado: 300 pips | 13 publicaciones
Citando a 919gilead
{quote} Hola Kurt, no sé por qué la gente tiene problemas para registrarse, ya que no soy administrador. Acabo de encontrar un programador/codificador que me ayude con mi proyecto y, por lo tanto, me vi obligado a publicar el panel de control. Sigue intentándolo, ya que creo que el registro no está cerrado. Saludos, George.

Hola Gilead,

este es el indicador al que me refería.

Imagen adjunta

459
Cita
12 de septiembre de 2017, 00:42
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando el kalpavata
{quote} Hola Gilead, este es el indicador al que me refería. {imagen}
El indicador no funciona en el MT4 actual y no tengo la versión MQL, así que ahora uso la que te envié en el enlace.
Imagen adjunta

Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
460
Cita
12 de septiembre de 2017, 2:20 a. m.
 kalpavata| Se unió en agosto de 2009 | Estado: 300 pips | 13 publicaciones
Citando a 919gilead
{quote} El indicador no funciona en el MT4 actual y no tengo la versión MQL, así que ahora uso la que te envié en el enlace {image}


Gilead,

muchas gracias 

P24
 Ican2020| Se unió en agosto de 2014 | Estado: Trader | 457 publicaciones
¿Cómo puedo hacer que el Dashboard Ea tome todas las operaciones de 'Señales de alerta'?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: A1.png Tamaño: 139 KB
Imagen adjunta

463
Cita
4 de octubre de 2017, 14:25
 ilíquido| Se unió en mayo de 2016 | Estado: Trader | 43 publicaciones
Citando a Ican2020
¿Cómo puedo hacer que el Dashboard Ea tome todas las operaciones de 'Señales de alerta'? {image} {image}
Echa un vistazo a https://www.forexfactory.com/showthread.php?t=568595.

Puedes usar un panel de control para esto.

Saludos,
illiquid.
464
Cita
6 de octubre de 2017, 6:45 a. m.
 amigo para ti| Se unió en enero de 2011 | Estado: Comerciante | 126 publicaciones
Hola, he leído mucho aquí y muchas gracias, pero ¿podrías decirme cómo operas con csDash, especialmente en marcos temporales cortos? Si abro el par más fuerte, suele retroceder antes del movimiento más fuerte y entonces la tabla se ve completamente diferente.

Si configuro las opciones en 30 minutos, ¿por qué la lista sigue cambiando cada segundo, ya que una barra con nuevos cálculos solo termina cada 30 minutos en la configuración M30? Sí, puedo configurarlo en 30000 x 60 ms, pero ¿eso lo hace menos fiable, ya que es solo una instantánea después de 30 segundos?
Me gustaría poder cambiar más opciones y me gusta mucho csDash. El límite de tiempo de unos meses podría reemplazarse por una notificación con un enlace a este foro de vez en cuando, pero si el propietario tuviera un accidente (espero que no), todo el trabajo y el uso desaparecerían después del límite de tiempo (fecha de vencimiento). ¿No sería fantástico que tu trabajo pudiera ayudar a las próximas generaciones de traders? ¿

Qué influye en los cálculos: media móvil, RSI y estocástico? Por favor, aclaren un poco más el cuadro negro y cómo las diferentes configuraciones modifican el comportamiento. No quiero ganar dinero solo con la experiencia con un indicador, pero todos los usuarios podrían ayudarme a interpretar este excelente trabajo.
465
Cita
19 de octubre de 2017, 16:16
 aPhongSe unió en septiembre de 2017 | Estado: ... lo queremos más, pero lo usamos peor | 239 publicaciones
[quote=919gilead;10099983]{quote} Hola Slingshots, me gustaría poder ayudarte, pero lamentablemente no podré. Sin embargo, te guiaré en cómo configurar tu propio...

¡Hola 919gilead! ¡Gracias, Sr. Honestknave y a los demás, por esta gran herramienta gratuita!
Soy nuevo y no se me da bien el inglés. Me suscribí y leí las publicaciones, pero no entendí todas las buenas ideas de este hilo sobre csDash. ¿
Alguien podría explicarme la estrategia para operar con csDash y cómo configurar correctamente esta herramienta? ¿
O decirme dónde encontrar estas opciones? ¡

Muchas gracias a todos por este excelente hilo!
Saludos.
...¡lo quiero más pero lo uso peor!
466
Cita
8 de noviembre de 2017, 7:33 a. m.
 rebeldes| Se unió en julio de 2009 | Estado: Comerciante | 6 publicaciones
Citando a honestknave
Versión: 1.27. Caducidad: 31 de diciembre de 2017. Hay estafadores que venden csDash (y MADdash), por lo que he añadido un mensaje de confirmación para advertir a las víctimas. Solo debería ser necesario confirmar la cuenta una vez por cuenta. Por lo demás, esta versión no ha sufrido cambios desde la 1.26. ¡Les deseo éxito a todos! {file}
Hola honestknave, gracias por compartir este excelente indicador basado en la conocida hoja de cálculo de fortaleza de divisas. ¡Uno de los mejores paneles de fortaleza de divisas que he visto! De hecho, lo he usado a diario y ha sido una adición muy importante a mis operaciones.

Cuando tengas tiempo para revisar las nuevas incorporaciones, será interesante ver si podemos determinar cuándo comenzó la fortaleza de la divisa y no quedarnos atrapados al final del movimiento. Quizás como una ventana de gráfico de líneas móviles basada en un marco temporal específico (D1, H4, H1, M30, M15, M5 y M1), donde el eje Y representa la fortaleza de la divisa y el eje X el tiempo del bróker.

Saludos cordiales.
1
467
Cita
7 de diciembre de 2017, 5:43 a. m.
 Jonie| Se unió en febrero de 2016 | Estado: Trader | 7 publicaciones
Hola honestknave,
uso tus indicadores MADdash y csDash y estoy muy satisfecho. ¡Gracias!
Tengo una pregunta: ¿se puede crear un panel para fusionar ambos indicadores en uno solo? Creo que sería una herramienta útil. Disculpa mi mal inglés.
468
Cita
11 de diciembre de 2017, 18:31
 rustydavo| Se unió en julio de 2017 | Estado: Trader | 141 publicaciones
Excelente indicador. Muchas gracias. No siempre da pips (noticias, etc.), pero sin duda es representativo de lo que está sucediendo.
469
Cita
12 de diciembre de 2017, 2:23 a. m.
 hsoltan59| Se unió en mayo de 2015 | Estado: Trader | 53 publicaciones
Hola honestknave
Gracias por el gran trabajo.
¿Podrías compartir la configuración de la bestia para este tablero para usarlo mtf?
Gracias.
470
Cita
20 de diciembre de 2017, 5:59 a. m.
 johnsmith2do| Se unió en enero de 2017 | Estado: Trader | 530 publicaciones
Solo quería expresar mi gratitud por esta herramienta increíblemente útil, a la que recurro una y otra vez, independientemente de la estrategia que esté desarrollando.

¡Gracias!
471
Cita
25 de diciembre de 2017, 19:51
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Versión: 1.28

Caducidad: 31 de diciembre de 2018

¡Les deseamos éxito a todos!
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   141 KB | 4016 descargas
6
472
Cita
25 de diciembre de 2017, 20:49
 EllenbrookSe unió en octubre de 2011 | Estado: Trader | 1026 publicaciones | En línea
Hola,
muchas gracias.
473
Cita
25 de diciembre de 2017, 21:26
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
Versión: 1.28 Caducidad: 31 de diciembre de 2018 ¡Les deseamos éxito a todos! {file}
Gracias Andrew y todo lo mejor para el Año Nuevo.

Shalom 

George
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
474
Cita
26 de diciembre de 2017, 5:49 a. m.
 rosalieoneSe unió en septiembre de 2009 | Estado: Trader | 544 publicaciones
Citando a honestknave
Versión: 1.28 Caducidad: 31 de diciembre de 2018 ¡Les deseamos éxito a todos! {file}
¡¡¡Gracias!!! ¡¡¡
Feliz 2018!!!
475
Cita
26 de diciembre de 2017, 8:03 a. m.
 diana97| Se unió en abril de 2015 | Estado: Trader | 93 publicaciones
Citando a honestknave
Versión: 1.28 Caducidad: 31 de diciembre de 2018 ¡Les deseamos éxito a todos! {file}
¡Qué gran regalo de Navidad, muchas gracias por su generosidad!
476
Cita
26 de diciembre de 2017, 9:10 a. m.
 fotografiar| Se unió en noviembre de 2012 | Estado: Comerciante | 315 publicaciones
Citando a honestknave
Versión: 1.28 Caducidad: 31 de diciembre de 2018 ¡Les deseamos éxito a todos! {file}
Éxito en los próximos meses, saludos Pho
477
Cita
27 de diciembre de 2017, 13:02
 vip3644534| Membresía revocada | Se unió en noviembre de 2009 | 83 publicaciones
Citando a honestknave
Versión: 1.28 Caducidad: 31 de diciembre de 2018 ¡Les deseamos éxito a todos! {file}
Hola señor,

¿puede hacerlo funcionar con Axitrader pro? Gracias.

Feliz Navidad y Año Nuevo.
478
Cita
27 de diciembre de 2017, 20:40
 vip3644534| Membresía revocada | Se unió en noviembre de 2009 | 83 publicaciones
Esto es lo que tengo
Imagen adjunta

479
Cita
3 de enero de 2018, 6:31 a. m.
 Prava| Se unió en enero de 2018 | Estado: Trader | 5 publicaciones
Un indicador muy impresionante. Gracias por compartir.
¿Cuál es el mejor marco temporal que me recomiendas? ¿Debería esperar un rato hasta que la vela cierre, después de que aparezca la alerta de compra/venta, para asegurarme de que el movimiento sea válido?

Muchas gracias, P
Opere con seguridad y construya con pequeños pasos.
480
Cita
8 de enero de 2018, 1:33 a. m.
 Salizzan| Se unió en febrero de 2010 | Estado: Comerciante | 19 publicaciones
Citando a honestknave
Versión: 1.28 Caducidad: 31 de diciembre de 2018 ¡Les deseamos éxito a todos! {file}
Hola señor.
Gracias por la actualización.
Solo quería mencionar que las notificaciones push no funcionan.

Gracias.


P25
 FxMadnessSe unió en mayo de 2017 | Estado: Trader | 1564 publicaciones
cDash2EAX 2018
Archivo(s) adjunto(s)
Tipo de archivo: ex4 cDash2EAX.ex4   14 KB | 2503 descargas
Puedo calcular el movimiento de las estrellas, pero no la locura de los hombres. Isaac N.
2
482
Cita
9 de enero de 2018, 14:46
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Honestknave,

gracias por la última actualización, ¡te lo agradezco mucho! 


FxM,

¡Muchísimas gracias por cDash2EAX! Funciona perfectamente con la última versión. 

Para quienes no sepan qué es cDash2EAX: es el complemento (PIN) que integra csDash en el panel de control de EAX y que pueden encontrar aquí .

Saludos.
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
483
Cita
12 de enero de 2018, 16:31
 sdsn| Se unió en diciembre de 2015 | Estado: Trader | 107 publicaciones
Citando a honestknave
Versión: 1.28 Caducidad: 31 de diciembre de 2018 ¡Les deseamos éxito a todos! {file}
¿No entiendo por qué no está instalado en la terminal?
484
Cita
12 de enero de 2018, 18:47
 Foro de FX| Se unió en marzo de 2017 | Estado: Trader | 118 publicaciones
SDSN: olvídate de eso. Aquí hay uno que puedes usar siempre que mt4 lo permita.
Archivo(s) adjunto(s)
Tipo de archivo: rar smStrengthRange09_v2.2.rar   52 KB | 2182 descargas
1
485
Cita
13 de enero de 2018, 8:51 a. m.
 mtharwatSe unió en agosto de 2015 | Estado: Trader | 981 publicaciones
Citando a Fxforum
SDSN - olvídate de esas cosas. Aquí hay uno que puedes usar siempre que mt4 lo permita {archivo}
Hola Fxforum,

gracias por tu publicación. Estoy un poco indeciso sobre por dónde empezar. Estuve en el hilo de MAdashboard y ahora encontré este, donde también está el panel de EAX. Este fin de semana dedicaré mi tiempo a averiguar por dónde empezar.

Con el indicador que publicaste, es excelente. Me preguntaba si existe una versión MTF. Supongo que la que publicaste es diaria, ¿no?

Gracias de nuevo.
486
Cita
14 de enero de 2018, 00:05
 Foro de FX| Se unió en marzo de 2017 | Estado: Trader | 118 publicaciones
Citando a mtharwat
{quote} Hola Fxforum, gracias por tu publicación. Estoy pensando por dónde empezar. Estuve en el hilo de MAdashboard y encontré este, donde también está el panel de EAX. Este fin de semana dedicaré tiempo a averiguar por dónde empezar. Con el indicador que publicaste, es excelente. Me preguntaba si existe una versión MTF. Supongo que la que publicaste es diaria, ¿no? Gracias de nuevo.
De nada. Es un índice; por lo tanto, el MTF no importa, ya que todos los indicadores de fuerza reflejan los mismos datos en todos los intervalos de tiempo.
487
Cita
10 de febrero de 2018, 17:30
 MerkaSe unió en enero de 2016 | Estado: Trader | 2062 publicaciones
Citando a Fxforum
SDSN - olvídate de esas cosas. Aquí hay uno que puedes usar siempre que mt4 lo permita {archivo}
¿Cómo se usa? ¿
Se emparejan los fuertes con los débiles o se usan también las curvas gráficas?
¿Qué significan los círculos rojo y verde del medio?
Gracias.
488
Cita
10 de febrero de 2018, 22:41
 EllenbrookSe unió en octubre de 2011 | Estado: Trader | 1026 publicaciones | En línea
Hola,
chicos, probé todo el correlador cc dash, muy bueno, si saben cómo usarlo, ahora encontré otro más preciso, pueden cambiar la sesión, tengo 2 configuradas con Asia/sesión/Londres, otra con Bondon sesión/y EE. UU., así que 1 hora antes de que comience cualquier sesión, el correlador marca un cero, por lo que es muy preciso.
489
Cita
10 de febrero de 2018, 22:42
 EllenbrookSe unió en octubre de 2011 | Estado: Trader | 1026 publicaciones | En línea
Citando a Ellenbrook
Hola, chicos, probé todo el correlador cc dash, muy bueno, si saben cómo usarlo, ahora encontré otro más preciso, pueden cambiar la sesión, tengo 2 configuradas con Asia/sesión/Londres, otra con Bondon sesión/y EE. UU., así que 1 hora antes de que comience cualquier sesión, el correlador marca un cero, por lo que es muy preciso.
Archivo(s) adjunto(s)
Tipo de archivo: rar Session_Correlator1.rar   54 KB | 1444 descargas
1
490
Cita
12 de febrero de 2018, 18:23
 MerkaSe unió en enero de 2016 | Estado: Trader | 2062 publicaciones
Citando a Ellenbrook
{cita} {archivo}
¿Puedes mostrarnos cómo lo usas?
Gracias.
491
Cita
13 de febrero de 2018, 00:46
 Zorndyke| Se unió en junio de 2012 | Estado: Comerciante | 95 publicaciones
Todavía prefiero csdash (al menos 4 csdash en un gráfico) para mostrar toda la fuerza en todos los TF
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Untitled.png Tamaño: 50 KB
"Esperanza" es una palabra peligrosa en el trading. ¡Opera con lo que ves, no con lo que esperas!
1
492
Cita
13 de febrero de 2018, 21:48
 funyoda| Se unió en enero de 2015 | Estado: Trader | 2 publicaciones
@zorndyke

¿Podrías explicar cómo apilaste 5 indicadores csdash en un gráfico a la derecha? No puedo hacerlo con las opciones de diseño actuales en la entrada del indicador.

Gracias.
493
Cita
13 de febrero de 2018, 22:34
 funyoda| Se unió en enero de 2015 | Estado: Trader | 2 publicaciones
@zorndyke

Descubrí el diseño ajustando las coordenadas X e Y. Después de agregar 6 indicadores csdash en un gráfico, Mt4 se volvió muy lento, así que decidí quedarme con un solo csdash en modo expandido y eso es todo lo que necesito.
494
Cita
13 de marzo de 2018, 10:20 a. m.
 drdraco| Se unió en enero de 2017 | Estado: Trader | 4 publicaciones
Citando a FxMadness
cDash2EAX 2018 {archivo}
Hola,

mi bróker usa algunos símbolos después del par, como + o . o .., entonces EURUSD en mi gráfico es EURUSD.
¿Podrías ampliar este indicador para que uno pueda hacer coincidir los símbolos?
495
Cita
14 de marzo de 2018, 8:57 a. m.
 atrapapipas2| Se unió en marzo de 2011 | Estado: Comerciante | 33 publicaciones
Citando a honestknave
Tenga en cuenta: no estoy pensando en hacer demasiado desarrollo en esta versión porque mi enfoque principal está en una versión MTF (aún no está lista): {imagen}
https://www.forexfactory.com/attachm...9&d=1430045007


¿Podría ser tan amable de compartir conmigo el indicador en la captura de pantalla/imagen adjunta?

Saludos cordiales,

Saludos
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: #.png Tamaño: 151 KB
496
Cita
14 de marzo de 2018, 9:48 a. m.
 Zorndyke| Se unió en junio de 2012 | Estado: Comerciante | 95 publicaciones
Citando a pipcatcher2
{quote} https://www.forexfactory.com/attachm...9&d=1430045007 ¿Podría ser tan amable de compartir conmigo el indicador en la captura de pantalla/imagen adjunta? Saludos cordiales, Saludos {image}
¡Echa un vistazo a su perfil! y haz clic en el hilo que ha iniciado.
Imagen adjunta

"Esperanza" es una palabra peligrosa en el trading. ¡Opera con lo que ves, no con lo que esperas!
497
Cita
14 de marzo de 2018, 18:57
 atrapapipas2| Se unió en marzo de 2011 | Estado: Comerciante | 33 publicaciones
Citando a zorndyke
{quote} ¡Echa un vistazo a su perfil! y haz clic en el hilo que ha iniciado. {image}



Hola Zorndyke,


gracias por tu respuesta, pero no compartió la información en cuestión en ese hilo.

Consulta la captura de pantalla adjunta para obtener más información.

Gracias de nuevo.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot_7.jpg Tamaño: 116 KB
498
Cita
14 de marzo de 2018, 19:02
 atrapapipas2| Se unió en marzo de 2011 | Estado: Comerciante | 33 publicaciones
lo encontré, gracias
499
Cita
17 de marzo de 2018, 8:18 a. m.
 drdraco| Se unió en enero de 2017 | Estado: Trader | 4 publicaciones
Citando a honestknave
Última versión 1.28 --------------------------------------------------------- Existe una hoja de cálculo de Excel muy conocida que utiliza las capacidades DDE de MT4 para calcular la fortaleza de la moneda mediante una fórmula basada en el máximo, el mínimo y la oferta de D1: {image} Como consecuencia de otro proyecto en el que estoy trabajando, la he adaptado a MT4. Es un indicador EA simple que debería replicar los resultados de la hoja de cálculo de Excel. Incluye algunas mejoras adicionales (alertas,...)
Como mi bróker no tiene el par NZDCHF, el indicador no se inicia:

0 12:14:25.901 Indicador personalizado csDash CADJPY..,M5: cargado exitosamente
0 12:14:31.721 csDash CADJPY..,M5: NZDCHF.. no está disponible en su bróker
0 12:14:31.721 csDash CADJPY..,M5: Alerta: Pares no disponibles: vea la pestaña Expertos para más detalles
3 12:14:31.721 csDash CADJPY..,M5: error de inicialización (1)

¿Hay alguna forma de decirle al indicador que no se ocupe de este par faltante?
500
Cita
18 de marzo de 2018, 23:16
 tuanyerSe unió en julio de 2014 | Estado: Trader | 282 publicaciones
Realmente genial.......
https://charts.mql5.com/17/823/usdch...ivision1-2.png
Tuanyer

P26
501
Cita
18 de marzo de 2018, 23:29
 tuanyerSe unió en julio de 2014 | Estado: Trader | 282 publicaciones
Me gusta el método de clasificación de csdash.
Tuanyer
502
Cita
18 de marzo de 2018, 23:52
 Zorndyke| Se unió en junio de 2012 | Estado: Comerciante | 95 publicaciones
Citando a drdraco
{quote} Como mi bróker no tiene el par NZDCHF, el indicador no se inicia: 0 12:14:25.901 Indicador personalizado csDash CADJPY..,M5: cargado exitosamente 0 12:14:31.721 csDash CADJPY..,M5: NZDCHF.. no está disponible en su bróker 0 12:14:31.721 csDash CADJPY..,M5: Alerta: Pares no disponibles: vea la pestaña Expertos para más detalles 3 12:14:31.721 csDash CADJPY..,M5: error en la inicialización (1) ¿Hay alguna forma de decirle al indicador que no maneje este par faltante?
Imagen adjunta

"Esperanza" es una palabra peligrosa en el trading. ¡Opera con lo que ves, no con lo que esperas!
503
Cita
18 de marzo de 2018, 23:54
 EllenbrookSe unió en octubre de 2011 | Estado: Trader | 1026 publicaciones | En línea
Citando a Merka
{quote} ¿Puedes mostrarnos cómo lo usas? Gracias.
Lo siento por la respuesta tardía, bueno, es fácil cuando la moneda rompe el nivel, la línea negra se muestra en la imagen.

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot_1.png Tamaño: 197 KB
1
504
Cita
19 de marzo de 2018, 17:19
 MerkaSe unió en enero de 2016 | Estado: Trader | 2062 publicaciones
Citando a Ellenbrook
{quote} Lo siento por la respuesta tardía, pero es fácil cuando la moneda rompe el nivel, la línea negra se muestra en la imagen {imagen}
Gracias
505
Cita
19 de marzo de 2018, 17:50
 drdraco| Se unió en enero de 2017 | Estado: Trader | 4 publicaciones
Citando a zorndyke
{cita} {imagen}
No entiendo por qué resaltaste la línea NZDCHF=true en la página de consejos de configuración de csDash. Claro que probé con las versiones true y false, pero el indicador no se inicia. Sería bueno que pudieras sugerir una solución real.
506
Cita
23 de marzo de 2018, 6:56 a. m.
 drdraco| Se unió en enero de 2017 | Estado: Trader | 4 publicaciones
Han pasado 10 días desde que descargué csDash y sigo sin poder probar este indicador debido al mensaje de error " NZDCHF... no está disponible en su bróker ".
Intenté configurar este par como falso en el campo de entrada al adjuntar el indicador al gráfico, pero no funcionó. El mismo mensaje de error aparece en el registro del experto.
Por favor, sugiera una solución.
507
Cita
11 de abril de 2018, 1:41 a. m.
 ehabfraihat| Se unió en enero de 2014 | Estado: Trader | 5 publicaciones
Gracias querido @honestknave por extender el tiempo.
508
Cita
13 de abril de 2018, 16:14
 b6770| Se unió en octubre de 2016 | Estado: Trader | 8 publicaciones
Hola, ¿
cómo puedo usarlo como PIN en el tablero EAX?
509
Cita
23 de abril de 2018, 8:06 a. m.
 Seunboi4u| Se unió en agosto de 2016 | Estado: Trader | 65 publicaciones
No funciona en mi Broker...lqdfx ¿qué puedo hacer para que funcione? Gracias.
510
Cita
23 de abril de 2018, 10:38 a. m.
 Seunboi4u| Se unió en agosto de 2016 | Estado: Trader | 65 publicaciones
csDash (medidor de fuerza monetaria) por favor necesito ayuda esto no funciona en mi corredor ¿qué puedo hacer por favor que Dios los bendiga?
511
Cita
23 de abril de 2018, 11:34 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Seunboi4u
csDash (medidor de fuerza monetaria) por favor necesito ayuda esto no funciona en mi corredor ¿qué puedo hacer por favor que Dios los bendiga?
Hola Seun,

asegúrate de usar la versión 1.28 y, en Prefijo/Sufijo de Broker, asegúrate de que la opción "Detectar automáticamente" esté seleccionada. Cierra MT4 y vuelve a abrirla.

Shalom
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
512
Cita
23 de abril de 2018, 13:03
 Seunboi4u| Se unió en agosto de 2016 | Estado: Trader | 65 publicaciones
Por favor, ¿podemos hablar mejor, señor? 919gilead,
hablemos mejor. Tengo como dos desafíos aquí.
513
Cita
24 de abril de 2018, 10:51 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a Seunboi4u
Por favor, ¿podemos hablar mejor, señor? 919gilead, hablemos mejor. Tengo como dos desafíos aquí.
Hola Seun,

pregunta o envíame un mensaje privado. Con gusto te responderé, pero recuerda que estoy 8 horas por detrás de Londres y 3 horas por detrás de Nueva York, así que siempre puedo responder tarde, incluso cuando veas mis operaciones en el hilo de MADdash. Ya respondí a tu mensaje privado.

Cuídate y que Dios bendiga

a George.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
1
514
Cita
24 de abril de 2018, 11:14 a. m.
 Seunboi4u| Se unió en agosto de 2016 | Estado: Trader | 65 publicaciones
Citando a 919gilead
{quote} Hola Seun, pregunta o envíame un mensaje privado. Con gusto te responderé, pero recuerda que estoy 8 horas por detrás de Londres y 3 horas por detrás de Nueva York, así que siempre puedo responder tarde, incluso cuando veas mis operaciones en el hilo de MADdash. Ya respondí a tu mensaje privado. Cuídate y que Dios bendiga a George.


Gracias señor, tengo un mensaje. Revise su bandeja de entrada.
515
Cita
8 de junio de 2018, 4:48 a. m.
 diestro| Se unió en junio de 2011 | Estado: Comerciante | 214 publicaciones
Al instalar csdash me aparece un mensaje de error. Por favor, ayuda.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: IMG_20180608_094445.JPG Tamaño: 125 KB
516
Cita
8 de junio de 2018, 5:06 a. m.
 Zorndyke| Se unió en junio de 2012 | Estado: Comerciante | 95 publicaciones
Citando diestro
Al instalar el csdash, me aparece un mensaje de error. Por favor, necesito ayuda. {imagen}
Establezca manualmente el sufijo del corredor.
Parece que su mt4 usa símbolos de sufijo como USDCAD.c, AUDUSD.c, EURUSD.c, ....
"Esperanza" es una palabra peligrosa en el trading. ¡Opera con lo que ves, no con lo que esperas!
517
Cita
9 de junio de 2018, 3:29 a. m.
 diestro| Se unió en junio de 2011 | Estado: Comerciante | 214 publicaciones
Por favor, ¿cómo puedo hacer que mi gráfico se vea así? Intenté cambiar el número de tiradas de 1 a cualquier otro número, pero no funciona.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot_2018-06-09-08-26-09.png Tamaño: 217 KB
518
Cita
10 de junio de 2018, 7:59 a. m.
 diestro| Se unió en junio de 2011 | Estado: Comerciante | 214 publicaciones
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: IMG_20180610_125639.JPG Tamaño: 78 KB
519
Cita
10 de junio de 2018, 13:33
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Citando diestro
Por favor, ¿cómo puedo hacer que mi gráfico se vea así?
Aquí tienes, hermano.

Ahora puedes relajarte el resto del fin de semana. 

Saludos.

Archivo(s) adjunto(s)
Tipo de archivo: tpl dexterous_MTF-csDash.tpl   36 KB | 1393 descargas
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
1
520
Cita
10 de junio de 2018, 17:28
 diestro| Se unió en junio de 2011 | Estado: Comerciante | 214 publicaciones
Citando a LifeHunt3r
Aquí tienes, hermano. Ahora puedes relajarte el resto del fin de semana. Saludos.


P27
 petersuccess| Se unió en marzo de 2017 | Estado: Trader | 17 publicaciones
Hola, por favor. ¿Puede el indicador csdash dar señales de alerta en otros pares aparte de gbpusd, eurusd, nzdusd, audusd, usdcad, usdjpy y usdchf? Porque en mt4 no hay alerta en otros pares. Gracias.
522
Cita
17 de julio de 2018, 16:40
 hsoltan59| Se unió en mayo de 2015 | Estado: Trader | 53 publicaciones
Hola,
¿cuál es la configuración ideal para este indicador si usamos un marco temporal de 15 millones?
Gracias.
523
Cita
24 de noviembre de 2018, 9:21 a. m.
 mtharwatSe unió en agosto de 2015 | Estado: Trader | 981 publicaciones
@HonestKnave

Hola y gracias por abrir este hilo y compartirlo.

Tengo curiosidad por algo que me gustaría probar:

he notado algunos indicadores que combinan varios indicadores y que emiten una alerta al alcanzar una puntuación determinada. Por ejemplo, supongamos que tenemos un indicador que mide el MACD, el RSI y la variación del precio. Mostrará una señal al alcanzar una puntuación determinada, por ejemplo, el 70 %. La lógica es entrar antes de alcanzar el agotamiento. Ojalá

encontrara algo similar en los paneles. Si una divisa muestra tendencia alcista o bajista, quiero recibir una notificación al alcanzar el 70 %, no después. ¿

Has experimentado esta idea antes?

Gracias.
524
Cita
26 de diciembre de 2018, 19:20
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Versión: 1.29

Caducidad: 31 de diciembre de 2019

¡Les deseamos éxito a todos!
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   145 KB | 6153 descargas
20
525
Cita
26 de diciembre de 2018, 19:21
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Gracias, Andrew, y felicitaciones. Por favor, contáctame si puedes; es algo muy importante para compartir y debatir.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
526
Cita
26 de diciembre de 2018, 20:07
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Gracias de nuevo HK, todo lo mejor para el Año Nuevo.
El único límite es el que tú mismo te pones - Felix Baumgartner
527
Cita
26 de diciembre de 2018, 22:59
 4xu2| Se unió en agosto de 2016 | Estado: Trader | 179 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
¡Gracias de nuevo! ¡Mi medidor de fuerza favorito!
Negocie con lo que "es", no con lo que "si".
528
Cita
27 de diciembre de 2018, 2:02 a. m.
 leowang2013| Se unió en abril de 2013 | Estado: Comerciante | 1 publicación
Gracias por actualizar, este indicador es realmente útil~~
529
Cita
4 de enero de 2019, 19:35
 Woodie| Se unió en septiembre de 2018 | Estado: Trader | 1 publicación
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Gracias, honestknave, por el indicador csDash actualizado. Lo uso mucho y no sabía que tenía fecha de caducidad. Intenté averiguar por qué no cargaba después de pasar un tiempo sin operar durante las vacaciones. ¿Hay alguna forma de comprar o donar una versión sin caducidad en caso de que, por alguna razón, no puedan proporcionar actualizaciones en el futuro? Lamentaría perder el uso de su indicador. Gracias, agradezco mucho su generosidad.

Woodie
1
530
Cita
5 de enero de 2019, 18:53
 viento del norteSe unió en octubre de 2017 | Estado: Trader | 362 publicaciones
[quote=Woodie;11848104]{quote} Gracias, honestknave, por el indicador csDash actualizado. Lo uso mucho y no sabía que tenía fecha de caducidad. Intenté averiguar por qué no cargaba después de pasar un tiempo sin operar durante las vacaciones. ¿Hay alguna forma de comprar o donar una versión sin caducidad en caso de que, por alguna razón, no puedan proporcionar actualizaciones en el futuro? No me gustaría perder el uso de su indicador. Gracias, agradezco mucho su generosidad. Woodie[/quote

Hola, Woodie:
Consulta la publicación n.° 524, csdash con nueva fecha de caducidad, o haz clic en el clip para ver los archivos más recientes.
Pips pérfidos
531
Cita
6 de enero de 2019, 6:21 a. m.
 fluyendoUsuario comercial | Se unió en septiembre de 2015 | 38 publicaciones
Gracias al creador de este útil indicador. Lo estoy usando junto con MadDash para encontrar buenas configuraciones de trading.
Sin embargo, no encuentro información sobre qué valores específicos muestra exactamente. Publicaré una imagen y agradecería que alguien me explicara detalladamente a qué valores me refiero.

Por ejemplo, ¿qué nos muestra "Bid Radio"? ¿La relación entre el precio de apertura y el de cierre?
Imagen adjunta



Otra pregunta: ¿qué es el Umbral Diferencial (por defecto = 4)? Si un valor de Moneda es 4, ¿significa que está en rango (sin movimiento)?
Imagen adjunta



Y por último, ¿qué es la sensibilidad del disparador (por defecto = baja) y cuál es la diferencia entre "baja" y "alta"?
Imagen adjunta

Si no sabes dónde estás crea tu Eje
532
Cita
8 de enero de 2019, 13:16
 mirko2017| Se unió en noviembre de 2018 | Estado: Trader | 42 publicaciones
Citando flowin
Gracias al creador de este útil indicador. Lo estoy usando junto con MadDash para encontrar buenas configuraciones de trading. Sin embargo, no encuentro información sobre qué valores específicos muestran exactamente. Publicaré una imagen y agradecería que alguien me explicara detalladamente a qué valores me refiero. Por ejemplo, ¿qué nos muestra "Bid Radio"? ¿La relación entre el precio de apertura y el de cierre? {image} Otra pregunta: ¿qué es el Umbral Diferencial (por defecto = 4)? Si un valor de divisa es 4, ¿significa que está en rango (sin movimiento)? {image} Y por último, ¿cuál es la sensibilidad del disparador?
Hola flowin,
¿sabes dónde puedo encontrar el PIN de csDash? Lo necesito para EAX.
Tengo este cDash2EAX, pero ya no funciona. Probablemente haya caducado.
533
Cita
8 de enero de 2019, 15:41
 fluyendoUsuario comercial | Se unió en septiembre de 2015 | 38 publicaciones
Citando a mirko2017
Hola flowin, ¿sabes dónde puedo encontrar el PIN de csDash? Lo necesito para EAX. Tengo este cDash2EAX, pero ya no funciona. Probablemente haya caducado.
https://www.forexfactory.com/showthr...3#post11824753
Si no sabes dónde estás crea tu Eje
534
Cita
13 de enero de 2019, 7:15 a. m.
 mirko2017| Se unió en noviembre de 2018 | Estado: Trader | 42 publicaciones
Citando flowin
{cita} https://www.forexfactory.com/showthr...3#post11824753
Hola, flowin. Gracias.
Ya descargué el archivo csDash y funciona correctamente.
Pero el archivo cDash2EAX ya no me funciona. Estas son las conexiones entre las señales de csDash y el panel EAX.
535
Cita
22 de enero de 2019, 12:45 p. m.
 Gentlepips| Se unió en febrero de 2018 | Estado: Trader | 31 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
@honestknave, ¡Dios te bendiga! Te deseo un 2019 lleno de éxitos.
536
Cita
22 de enero de 2019, 14:35
 Rolando| Se unió en noviembre de 2018 | Estado: Trader | 42 publicaciones
¿Existe alguna configuración especial para hacer scalping con este indicador?
537
Cita
30 de enero de 2019, 00:39
 hendri83| Se unió en enero de 2019 | Estado: Trader | 3 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Gracias Maestro

538
Cita
30 de enero de 2019, 00:50
 hendri83| Se unió en enero de 2019 | Estado: Trader | 3 publicaciones
Citando a mirko2017
{quote} Hola, Flowin. Gracias. Ya descargué el archivo csDash y funciona correctamente. Pero el archivo cDash2EAX ya no me funciona. Estas son las conexiones entre las señales de csDash y el panel EAX.
https://www.forexfactory.com/showthread.php?t=568595
539
Cita
6 de febrero de 2019, 7:26 a. m.
 FxMadnessSe unió en mayo de 2017 | Estado: Trader | 1564 publicaciones
cDash2EAX 2019 ~ hasta que el mundo llegue a su fin.
Archivo(s) adjunto(s)
Tipo de archivo: ex4 cDash2EAX.ex4   13 KB | 3027 descargas
Puedo calcular el movimiento de las estrellas, pero no la locura de los hombres. Isaac N.
6
540
Cita
6 de febrero de 2019, 16:25
 salimc| Se unió en enero de 2012 | Estado: Trader | 1329 publicaciones
Citando a FxMadness
cDash2EAX 2019 ~ hasta que el mundo llegue a su fin. {archivo}
Gracias


P28 
mirko2017| Se unió en noviembre de 2018 | Estado: Trader | 42 publicaciones
Citando a FxMadness
cDash2EAX 2019 ~ hasta que el mundo llegue a su fin. {archivo}
Muchas gracias, amigo. Eres un gran hombre.
Ahora empezaré a probarlo junto con ###CMSMIndV17.01.
542
Cita
7 de febrero de 2019, 5:12 a. m.
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Citando a FxMadness
cDash2EAX 2019 ~ hasta que el mundo llegue a su fin. {archivo}
Jajajaja... ¡Ojalá no sea demasiado pronto!

¡Gracias, FxMadness!
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
543
Cita
7 de febrero de 2019, 16:26
 salimc| Se unió en enero de 2012 | Estado: Trader | 1329 publicaciones
Citando a LifeHunt3r
{quote} ¡Jajajajaja! ¡Ojalá no sea demasiado pronto! ¡Gracias, FxMadness!

544
Cita
13 de febrero de 2019, 10:18 a. m.
 Rolando| Se unió en noviembre de 2018 | Estado: Trader | 42 publicaciones
Chicos, ¿sería posible crear una alerta en este EA cuando esté siempre en un porcentaje determinado? Sería perfecto,

o si me pueden pasar el archivo abierto para que lo revise y luego lo comparta.

Estén atentos.

Saludos .
545
Cita
8 de marzo de 2019, 3:15 a. m.
 ctnie2143| Se unió en diciembre de 2007 | Estado: Comerciante | 119 publicaciones
Citando a FxMadness
cDash2EAX 2019 ~ hasta que el mundo llegue a su fin. {archivo}


Estimado FxMadness, supuse que era un indicador. Sin embargo, intenté instalarlo y no se mostró nada en mi gráfico. ¿Se requiere alguna configuración?
546
Cita
8 de marzo de 2019, 4:25 a. m. | Editado a las 4:50 p. m.
 Señor Pablo| Se unió en diciembre de 2016 | Estado: Trader | 39 publicaciones
Hola Honestknave,

si tienes algo de tiempo libre, podrías considerar implementar el envío de una alerta/señal por "color" en lugar de por "umbral predeterminado".
Así recibirás una alerta cuando dos pares sean de colores opuestos.

Saludos cordiales.
547
Cita
8 de marzo de 2019, 16:44
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Citando a ctnie2143
Estimado FxMadness, supuse que era un indicador. Sin embargo, intenté instalarlo y no se mostró nada en mi gráfico. ¿Se requiere alguna configuración?
Es el complemento (PIN) que envía las señales de csDash al panel de EAX. Se arrastra al mismo gráfico donde se encuentra csDash. Consulta el hilo de EAX para obtener las instrucciones de instalación (y las carpetas).
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
548
Cita
8 de marzo de 2019, 16:48
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Citando a Sir Paul
Tengo un CsDash semanal, diario y H4 abierto en el mismo gráfico. Cuando el JPY está en verde en todos ellos, quiero una señal, y viceversa, cuando una divisa está en rojo en todos ellos. O bien, si el JPY está en verde en todos los gráficos de TF y la GBP está en rojo en todos los gráficos de TF, quiero una señal para vender GBPJPY.
Señor Paul,

todo esto es posible con csDash, pero solo si se usa con el panel EAX. Ver publicación anterior.

Saludos,

Lee.
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
549
Cita
8 de marzo de 2019, 16:54
 Señor Pablo| Se unió en diciembre de 2016 | Estado: Trader | 39 publicaciones
Citando a LifeHunt3r
{quote} Sir Paul, todo esto es posible con csDash, pero solo si se usa con el panel EAX. Ver publicación anterior. Saludos, Lee.
Gracias, ya estaba experimentando con EAX y avancé un poco más, por eso edité mi publicación hace un momento.
¿Sabes si los pines de EAX también envían alertas/notificaciones push cuando los pines 1, 2 y 3 se alinean, por ejemplo?
Al usar EAX, no quiero operar automáticamente, solo recibir una notificación cuando todos los pines coincidan para poder abrir mi gráfico y revisarlo.
No lo he encontrado ahora mismo, pero con tantas opciones, quizás lo pasé por alto.

Gracias
. Saludos.
1
550
Cita
8 de marzo de 2019, 17:22
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Citando a Sir Paul
{quote} Gracias, ya estaba jugando con EAX... ¿Sabes si EAX...? Al usar EAX...
Señor Paul,

si no le molesta, he citado (y respondido) su pregunta en el hilo de EAX, ya que este es un hilo de csDash y no quiero discutir EAX aquí.
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
551
Cita
25 de marzo de 2019, 00:43
 Pagar por adelantadoSe unió en febrero de 2015 | Estado: Paciencia | 1331 publicaciones
¿Alguien con experiencia puede arrojar algo de luz sobre esto... D1 y W1 tienen exactamente la misma fuerza... no parece correcto?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: EAX_CsDash2EAX_D1W1Identical.png Tamaño: 253 KB
Cuando tengas éxito quizás debas pensar en los demás... Kiva dot org
552
Cita
25 de marzo de 2019, 1:24 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Cotización de PayItForward
¿Alguien con experiencia puede arrojar algo de luz sobre esto... D1 y W1 tienen exactamente la misma fuerza... no parece correcto? {imagen}
Dado que es el comienzo de la semana y ambos se mueven al mismo ritmo hasta mañana, cuando entramos en el segundo día, cuando el Semanal tendrá dos días y el Diario comenzará de nuevo.

Al comienzo de cada día, observarán que D1, H4, H1, M30, etc., tendrán la misma intensidad hasta después de los primeros 30 minutos. D1 y H4 también tendrán la misma intensidad hasta después de las primeras 4 horas.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
3
553
Cita
25 de marzo de 2019, 2:05 a. m.
 Pagar por adelantadoSe unió en febrero de 2015 | Estado: Paciencia | 1331 publicaciones
Citando a 919gilead
{quote} Porque es el comienzo de la semana y ambos se mueven al mismo ritmo hasta mañana, cuando entramos en el segundo día, cuando el Semanal tendrá dos días y el Diario comenzará de nuevo. Al comienzo de cada día, observarán que D1, H4, H1, M30, etc., tendrán la misma intensidad hasta después de los primeros 30 minutos. D1 y H4 también tendrán la misma intensidad hasta después de las primeras 4 horas.
Claramente necesito "ejercitar el cerebro"... bueno, es lunes... gracias, se agradece.
Cuando tengas éxito quizás debas pensar en los demás... Kiva dot org
554
Cita
25 de marzo de 2019, 15:15
 aleqsei| Se unió en marzo de 2019 | Estado: Trader | 3 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Muchas gracias, Honestknave. Uno de los mejores paneles de indicadores de fortaleza de divisas disponibles. Sin engaños.
Me costó mucho encontrar este tipo de indicador. La información del panel es muy útil y directa.
Una vez seleccionados los pares en tendencia, me da una idea de las reversiones de tendencia y cuándo ejecutar mis operaciones.
555
Cita
1 de abril de 2019, 16:16
 ronbautSe unió en agosto de 2010 | Estado: Trader | 510 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Hola Honestknave,

¿es posible que tu indicador tenga la opción de filtrar el par por fortaleza o debilidad POR DIVISA ? Por ejemplo, si configuro el indicador así:

Umbral inferior (fuerza del tipo de cambio constante) = 2
Umbral superior (fuerza del tipo de cambio constante) = 7

En cuanto obtengamos una divisa con esos valores, se activará el par. Por ejemplo, si GBP >= 7, USD <= 2, se activará la compra de GBPUSD.

Quiero tener otra opción como "filtrar solo el tipo de cambio constante".

Si GBP >= 7, GBP activará la compra >>> compra de GBPAUD, GBPCAD, GBPCHF, GBPJPY, GBPNZD, GBPUSD y venta de EURGBP. Si USD <= 2, USD activará la venta >>> venta de USDCAD, USDCHF, USDJPY y compra de AUDUSD, EURUSD, GBPUSD, NZDUSD.

556
Cita
8 de abril de 2019, 10:23 a. m.
 geceler001| Se unió en abril de 2019 | Estado: Trader profesional | 24 publicaciones
XAUUSD, DE30, Brent, petróleo crudo vs. ¿Podemos tener la oportunidad de sumar?
Puedes perder tu dinero y posiblemente perder. Así que opera con inteligencia.
557
Cita
6 de mayo de 2019, 3:40 a. m.
 Jessica| Se unió en mayo de 2019 | Estado: Trader | 2 publicaciones
Hola honestknave , realmente tu indicador es bueno, también tengo una duda. ¿Cómo se comportará este indicador cuando el mercado tenga picos o noticias de última hora o sea muy volátil?





558
Cita
19 de mayo de 2019, 23:57
 dios del dinero| Se unió en junio de 2018 | Estado: Trader | 42 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
muchas gracias por compartir que Dios te bendiga
559
Cita
21 de mayo de 2019, 8:33 a. m.
 Preecha2022| Se unió en mayo de 2019 | Estado: Trader | 5 publicaciones
Citando a honestknave
Esta actualización no soluciona nada. Solo permite seleccionar cuál de los 28 pares se desea mostrar: {image} Nota: Es necesario configurar un par para que se muestre para recibir alertas. Los 28 pares siguen siendo necesarios para los cálculos (por lo que los números deberían ser exactamente los mismos, ya sea que se visualicen 1 o 28 pares). Es posible que vea esta pantalla y se pregunte por qué no se han realizado los cálculos. Esto se debe a que csDash aún espera la actualización de otros pares que no aparecen en la lista. {image} Por favor, informe cualquier error.
No puedo agregarlo al gráfico
560
Cita
21 de mayo de 2019, 9:00 a. m.
 Preecha2022| Se unió en mayo de 2019 | Estado: Trader | 5 publicaciones
¿Por qué no puedo arrastrar este csdash al gráfico?


P29
563
Cita
21 de mayo de 2019, 12:24 p. m.
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Citando a Preecha2022
¿Por qué no puedo arrastrar este csdash al gráfico?
Es un indicador, no un asesor experto
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
564
Cita
21 de mayo de 2019, 12:52 p. m.
 Preecha2022| Se unió en mayo de 2019 | Estado: Trader | 5 publicaciones
LifeHunt3r Puedo encontrarlo como tu consejo, gracias por tu amable ayuda.
565
Cita
21 de mayo de 2019, 12:56 p. m.
 Preecha2022| Se unió en mayo de 2019 | Estado: Trader | 5 publicaciones
He visto a alguien usar la versión 1.30
566
Cita
29 de mayo de 2019, 23:08
 Simba111| Se unió en mayo de 2019 | Estado: Trader | 1 publicación
Hola, ¿hay alguna forma de ver los datos históricos del indicador? Quiero hacer una prueba retrospectiva del rendimiento del indicador en ciertos escenarios. ¿Hay alguna forma de reproducir los datos históricos? Muchas gracias.
567
Cita
14 de junio de 2019, 5:22 a. m.
 Tom Chandler| Se unió en diciembre de 2018 | Estado: Trader | 1 publicación
¿Puedo usar este indicador de fortaleza de divisas para operar en el intervalo de tiempo de 1 minuto? Normalmente opero en ese intervalo. Por lo tanto, me gustaría saber si este indicador podrá generar señales precisas en ese intervalo. Espero respuesta...
568
Cita
25 de junio de 2019, 8:52 a. m.
 Juan 7| Se unió en noviembre de 2017 | Estado: Trader | 310 publicaciones
Cotización de PayItForward
¿Alguien con experiencia puede arrojar algo de luz sobre esto... D1 y W1 tienen exactamente la misma fuerza... no parece correcto? {imagen}
¿Alguien podría ayudarme?
Tengo csDash en la carpeta de indicadores y cargado en el gráfico EAX, y funciona correctamente.
Instalé csDash2EAX en la carpeta PIN, con el PIN 2 asignado, pero no aparece.
¿Cuál podría ser el problema?
He instalado otros PIN antes y todos funcionan.
569
Cita
25 de junio de 2019, 10:32 a. m.
 Caza de vida3rSe unió en noviembre de 2016 | Estado: Trader | 233 publicaciones
Citando a Johannes7
{quote} ¿Alguien podría ayudarme? Tengo csDash en la carpeta de indicadores y cargado en el gráfico EAX, y funciona correctamente. Instalé csDash2EAX en la carpeta PIN, con el PIN 2 asignado, pero no se muestra. ¿Cuál podría ser el problema? He instalado otros PIN antes y todos funcionan.
Respondido en el hilo EAX.
Fijad vuestros pensamientos en todo lo que es verdadero, todo lo honesto, todo lo justo y todo lo puro...
570
Cita
17 de julio de 2019, 21:34
 ronbautSe unió en agosto de 2010 | Estado: Trader | 510 publicaciones
Hola honestknave

¿Es posible obtener variables globales externas con su indicador?
571
Cita
17 de julio de 2019, 22:55 | Editado a las 23:29
 ronbautSe unió en agosto de 2010 | Estado: Trader | 510 publicaciones
Hola FxMadness.

En tu indicador cDash2EAX, ¿podrías habilitar la opción para identificar los pares con filtro FUERTE o DÉBIL, y no ambos, como ocurre ahora?

A ver:

Si configuramos FUERTE 7 vs. DÉBIL 2 en D1, al aparecer EUR 7 y CAD <= 2, se activarán los siguientes pares: EURCAD.

Si la opción solicitada se activará, se activarán los siguientes pares:

EURAUD, EURCAD, EURCHF, EURGBP, EURJPY, EURNZD, EURUSD, AUDCAD, GBPCAD, NZDCAD, USDCAD,

CADCHF, CADJPY.

Si dos divisas son FUERTES o DÉBILES simultáneamente, los pares no se activarán; por ejemplo, si

AUD 7, CAD 8, AUDCAD NO se activa,

AUD 2, CAD 1, AUDCAD NO se activa.
572
Cita
19 de agosto de 2019, 7:49 a. m.
 brianmfxt254| Se unió en julio de 2019 | Estado: Trader | 2 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Hola honestdave, ¿alguien puede comprar el archivo cdash para usarlo de por vida?
573
Cita
27 de agosto de 2019, 9:28 a. m.
 patel879| Se unió en agosto de 2016 | Estado: Trader | 53 publicaciones
Citando a honestknave
Última versión: 1.29 --------------------------------------------------------- Existe una hoja de cálculo de Excel muy conocida que utiliza las funciones DDE de MT4 para calcular la fortaleza de la moneda mediante una fórmula basada en el máximo, el mínimo y la oferta de D1: {image} Como consecuencia de otro proyecto en el que estoy trabajando, la he adaptado a MT4. Es un indicador de EA simple que debería replicar los resultados de la hoja de cálculo de Excel. Incluye algunas mejoras adicionales (alertas,...)
Hola honestknave,

tengo un EA en csDash.
¿Puedo crear un hilo nuevo y compartirlo públicamente?

Gracias.
574
Cita
27 de agosto de 2019, 10:04 a. m.
 4x4x| Se unió en septiembre de 2017 | Estado: Trader | 1 publicación
Hola a todos,

antes que nada, felicidades por este fabuloso indicador. Una adición bienvenida a las medias móviles, les aseguro.

Mi pregunta es la siguiente, y creo que ya se ha hecho antes, pero no he encontrado la respuesta, así que disculpas si ya se ha hecho... ¿

Por qué csdash y madash tienen que actualizarse cada 1 de enero? ¿

Sería mala idea mantener una versión anterior? ¿Qué pasaría si no actualizo?

Tres preguntas, ya sé, pero las otras dos me acaban de venir a la cabeza.

Gracias de nuevo,

4x4x.
575
Cita
27 de agosto de 2019, 11:19 a. m. | Editado a las 3:42 p. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando 4x4x
Hola a todos, antes que nada, felicidades por este fabuloso indicador. Una adición bienvenida a las medias móviles, les aseguro. Mi pregunta es la siguiente, y creo que ya se ha hecho antes, pero no he encontrado la respuesta, así que disculpas si ya se ha hecho... ¿Por qué csdash y madash tienen que actualizarse cada 1 de enero? ¿Sería mala idea mantener una versión anterior? ¿Qué pasaría si no actualizo? Tres preguntas, ya sé, pero las otras dos me acaban de venir a la cabeza. Gracias de nuevo, 4x4x.
Respondí en 2017:

No creo que tengas que preocuparte por eso. Esta es la PROMESA de Honestknave:

" He tenido algunas preguntas sobre la caducidad de MADdash (y csDash).

Cada versión tiene una fecha de caducidad predefinida. No se preocupen, no se debe a un plan nefasto para empezar a cobrar por ello. Todo lo contrario.

Hay una pequeña pero persistente minoría que recorre foros de trading robando indicadores y Asesores Expertos para venderlos a personas desprevenidas que no saben que es gratis. Tengo un gran problema con esto. 

Hasta que se descifre la Build 600+ (lo cual será un día triste), la fecha de caducidad es una última medida de seguridad contra este tipo de estafas, ya que limita su duración.

Por esta razón, no existen versiones de MADdash ni csDash sin fecha de caducidad, y el código fuente nunca se ha publicado para nadie. Ni siquiera para mi gato. En realidad no tengo gato, pero si lo tuviera, no lo tendría. Así que, por favor, no pidan el código fuente, ya que... No quiero ofender. 

Si alguna vez abandono MADdash (o csDash) por completo, publicaré una versión final sin fecha de caducidad . Pero por ahora, sigo desarrollando los paneles de control de forma activa (¡casi!) . ¿

Sería mala idea mantener una versión anterior? ¿Qué pasaría si no la actualizara?
La caducidad significa que la versión anterior dejará de funcionar... ¿es obvio, no?
El único límite es el que tú mismo te pones - Felix Baumgartner
3
576
Cita
28 de agosto de 2019, 2:34 a. m.
 GorriónSe unió en mayo de 2014 | Estado: Trader | 4735 publicaciones
Citando a patel879
Hola, honestknave. Tengo un EA en csDash. ¿Puedo crear un hilo nuevo y compartirlo públicamente? Gracias.
Ya publicaste ese hilo sospechoso y lo promocionaste en otros hilos. ¡Qué grosero, la verdad! ¿Qué sentido tiene preguntar después? Jajaja.
Toma lo que puedas y no des nada a cambio
3
577
Cita
13 de septiembre de 2019, 00:51
 criptografía electrónica| Se unió en junio de 2019 | Estado: Trader | 140 publicaciones
Hola,

intento cargar la última versión de ccDash pero recibo muchos errores.
He seleccionado los 28 pares. También ejecuté ForceLoadHistoricalData(ASM).ex4 4 veces (la espera de finalización lleva algo de tiempo, esto está dentro de los requisitos previos de un nuevo setup.zip )
cierro y reinicio mt4 cuando cargo la última versión de Dashboard EAX
(no hay errores allí) solo cuando intento cargar ccDash tengo los siguientes errores, el corredor es xtb.com (demo) ¿puedes ayudarme?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: error load ccDash.png Tamaño: 239 KB
Todo fluye. Aprende a Ganar.
578
Cita
14 de septiembre de 2019, 12:02 p. m.
 GauerUsuario comercial | Se unió en octubre de 2017 | 654 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Gracias por esta información. ¿Podrías responder algunas preguntas? He hecho algunas anotaciones en una captura de pantalla. Quería saber qué significa la tasa de oferta. ¿Qué significa que las barras estén llenas o vacías? ¿Qué significa el spread y cómo usar esta información para operar?

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: csdashquestions.png Tamaño: 107 KB
579
Cita
14 de septiembre de 2019, 14:04 | Editado a las 14:40
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a Gauer
{quote} Gracias por esta información. ¿Podrías responder algunas preguntas? He hecho algunas anotaciones en una captura de pantalla. Quería saber qué significa la tasa de oferta. ¿Qué significa que las barras estén llenas o vacías? ¿Qué significa el spread y cómo usar esta información para operar? {image}
Bid Ratio - ¿Qué es?

https://www.forexfactory.com/showthr...64#post8223664

https://www.forexfactory.com/showthr...38#post8229938

El final de esta publicación explica qué significan las columnas sólidas y huecas:

https://www.forexfactory.com/showthr...39#post8241439


Visualización de la proporción de oferta modificada
¿Por qué? No era particularmente intuitivo
¿Qué significa esto? La proporción de oferta es donde el precio de oferta actual es relativo al máximo y al mínimo.

El inicio de la barra es 50%.
Si la barra es de color rojo , significa que la proporción de oferta está por debajo del 50% . Cuanto más larga sea la barra, más cerca del 0%. Por debajo del 25% es un rojo sólido. Entre el 25 y el 50% es un rojo hueco.
Si la barra es de color verde , significa que la proporción de oferta está por encima del 50% . Cuanto más larga sea la barra, más cerca del 100%.
Por encima del 75% es un verde sólido. Entre el 50% y el 75% es verde hueco.
Por debajo del 25% es rojo sólido. Entre el 50% y el 25% es rojo hueco.
El único límite es el que tú mismo te pones - Felix Baumgartner
2
580
Cita
14 de septiembre de 2019, 14:29
 GauerUsuario comercial | Se unió en octubre de 2017 | 654 publicaciones
Citando a Shabs19
{quote} Bid Ratio - ¿Qué es? https://www.forexfactory.com/showthr...64#post8223664 https://www.forexfactory.com/showthr...38#post8229938 Al final de esta publicación se explica el significado de las columnas sólidas y huecas: https://www.forexfactory.com/showthr...39#post8241439 Se modificó la visualización del Bid Ratio. ¿Por qué? No era muy intuitivo. ¿Qué significa esto? El Bid Ratio indica la relación entre el precio de oferta actual y el máximo y el mínimo. El inicio de la barra es del 50 %. Si la barra está en rojo, significa...
Gracias, amigo.

Vaya, eso es muy confuso, bueno, al menos para mí, no aporta ninguna ventaja ni información útil a mi análisis. Espero que honestknave añada una opción para ocultar las columnas. Me gustaría ver solo la columna de pares de divisas; el resto es pura información.

Bueno, y el spread que veo es el mismo término que el spread de oferta/demanda; son los valores de Market Watch, ¿no? Pensé que era otra cosa.

P30
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Aquí hay un indicador útil que da la relación de ofertas para todos los períodos de tiempo:

Archivo(s) adjunto(s)
Tipo de archivo: ex4 Indicador de relación precio-oferta de Forex.ex4   11 KB | 1279 descargas


Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Bid Ratio.png Tamaño: 57 KB
El único límite es el que tú mismo te pones - Felix Baumgartner
3
582
Cita
5 de octubre de 2019, 10:31 a. m.
 MtinifxSe unió en febrero de 2011 | Estado: Trader | 6018 publicaciones
Citando ecryptom
Hola, intento cargar la última versión de ccDash pero recibo muchos errores. He seleccionado los 28 pares. También ejecuté ForceLoadHistoricalData(ASM).ex4 4 veces (la espera de finalización lleva algo de tiempo, esto está dentro de los requisitos previos de un nuevo setup.zip ) cierro y reinicio mt4 cuando cargo la última versión de Dashboard EAX (no hay errores allí) solo cuando intento cargar ccDash tengo los siguientes errores,,, el...
Hola, tengo exactamente el mismo problema.

"Pares no disponibles - ver la pestaña de experto para más detalles".

¿Alguien sabe cuál es el problema? Gracias (el bróker es FPMarkets - prefijo .r).
583
Cita
5 de octubre de 2019, 11:05 a. m. | Editado a las 11:15 a. m.
 MtinifxSe unió en febrero de 2011 | Estado: Trader | 6018 publicaciones
Cotización de Mtinifx
{quote} ¡Hola! Tengo exactamente el mismo problema. "Pares no disponibles - ver la pestaña de experto para más detalles". ¿Alguien sabe cuál es el problema? Gracias (el bróker es FPMarkets - prefijo .r).
¡Actualización!

Funciona correctamente en la cuenta demo de este bróker, que no tiene el sufijo (.r) después del nombre del par, así que supongo que el problema es el sufijo. ¿Alguien sabe cómo solucionarlo? Obviamente, el indicador no detecta el sufijo automáticamente.


ACTUALIZACIÓN FINAL.

Todo arreglado: cambié el indicador a "manual" e ingresé el sufijo del bróker. ¡Ahora funciona correctamente en la cuenta real!
584
Cita
6 de octubre de 2019, 13:58
 cero| Se unió en mayo de 2017 | Estado: Trader | 18 publicaciones
Felicidades por otro indicador fabuloso. Honest Knave, gracias. Que Dios te bendiga.
585
Cita
8 de octubre de 2019, 7:07 a. m.
 fotiosUsuario comercial | Se unió en noviembre de 2014 | 12 publicaciones
Dejé de creer en el Indigator después de probar 1000 de EA e Indi, pero este Indigator es increíble y gratuito. Gracias al tipo que lo creó.
1
586
Cita
27 de octubre de 2019, 8:10 a. m.
 Tripl3333| Se unió en septiembre de 2019 | Estado: Trader | 30 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Gracias.
587
Cita
12 de noviembre de 2019, 9:14 a. m.
 rustydavo| Se unió en julio de 2017 | Estado: Trader | 141 publicaciones
Citando a FxMadness
cDash2EAX 2019 ~ hasta que el mundo llegue a su fin. {archivo}
Gracias. ¿Hay algún archivo de preajustes incluido? No consigo que se cargue en la última versión de EAX Dash.
588
Cita
9 de diciembre de 2019, 14:01
 Tirachinas1Se unió en febrero de 2012 | Estado: Trader | 1894 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Hola HK, por favor, ayúdenme con un problema: ¿cuándo es el momento adecuado para operar cuando un par se ha alineado? Actualmente, lo que suelo hacer es abrir gráficos semanales y diarios y colocar el guión en ellos. Si hay coincidencia en ambos marcos temporales, compruebo si puedo operar en 4 horas. Gracias.
589
Cita
15 de diciembre de 2019, 18:59
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Versión: 1.30

Caducidad: 31 de diciembre de 2020

¡Les deseamos éxito a todos!
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash.ex4   143 KB | 5035 descargas
22
590
Cita
15 de diciembre de 2019, 20:21
 IrfanlodhiSe unió en junio de 2016 | Estado: Trader | 39 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Gracias señor
1
591
Cita
16 de diciembre de 2019, 5:34 a. m.
 919galaadSe unió en julio de 2010 | Estado: Las grandes esperanzas hacen grandes hombres | 2042 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Gracias Andrew y te deseo lo mejor para el Año Nuevo.

Shalom.
Operaciones de bajo riesgo, bajo estrés, alta recompensa y alta probabilidad
2
592
Cita
16 de diciembre de 2019, 7:20 a. m.
 fotografiar| Se unió en noviembre de 2012 | Estado: Comerciante | 315 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
FELICES FIESTAS MUCHAS GRACIAS
pHO O querido keybd lol
1
593
Cita
16 de diciembre de 2019, 11:36 a. m.
 SamalinSe unió en abril de 2017 | Estado: Trader | 1106 publicaciones
Gracias señor que Dios siga bendiciéndole a usted y a su familia.
1
594
Cita
2 de enero de 2020, 10:24 a. m.
 benjamin89| Se unió en enero de 2017 | Estado: Trader | 112 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
muchas gracias !!
595
Cita
2 de enero de 2020, 13:01
 disbelljSe unió en agosto de 2008 | Estado: Comerciante | 772 publicaciones
¡Gracias, honestknave!

Saludos cordiales,

Don
596
Cita
3 de enero de 2020, 3:16 a. m.
 fotiosUsuario comercial | Se unió en noviembre de 2014 | 12 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Gracias, me encanta tu indicador. Creo que es uno de los mejores mapas de calor de divisas. ¡Genial! Gracias de nuevo y feliz año nuevo.
597
Cita
4 de enero de 2020, 11:00 a. m.
 husham.madhi| Se unió en enero de 2020 | Estado: Trader | 1 publicación
Citando a honestknave
Última versión: 1.30 --------------------------------------------------------- Existe una hoja de cálculo de Excel muy conocida que utiliza las funciones DDE de MT4 para calcular la fortaleza de la moneda mediante una fórmula basada en el máximo, el mínimo y la oferta de D1: {image}. Como consecuencia de otro proyecto en el que estoy trabajando, la he adaptado a MT4. Es un indicador EA sencillo que debería replicar los resultados de la hoja de cálculo de Excel. Incluye algunas mejoras adicionales (alertas,...)
El archivo no funciona. Recibí un mensaje que dice que puedo instalar la aplicación porque debería haber archivos asociados para configurar.
598
Cita
5 de enero de 2020, 14:00
 Tripl3333| Se unió en septiembre de 2019 | Estado: Trader | 30 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
gracias...….
599
Cita
7 de enero de 2020, 14:03
 Jennyt| Se unió en octubre de 2019 | Estado: Trader | 1 publicación
Gracias.
600
Cita
9 de enero de 2020, 11:52 a. m.
 Wolfsch| Se unió en noviembre de 2012 | Estado: Trader | 215 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Hola Honesrknive. ¿Existe la posibilidad de conseguir una versión más nueva, por favor?
Saludos, Wolf.


P31
 benjamin89| Se unió en enero de 2017 | Estado: Trader | 112 publicaciones
Citando a Wolfsch
{quote} Hola Honesrknive. ¿Existe la posibilidad de obtener una versión más nueva, por favor? Saludos, Wolf.
https://www.forexfactory.com/showthr...3#post12663663
publicación 589
602
Cita
12 de enero de 2020, 6:47 a. m.
 LiovannixUsuario comercial | Se unió en septiembre de 2015 | 433 publicaciones
Citando a benjamin89
{cita} https://www.forexfactory.com/showthr...3#post12663663 publicación 589
csDash.ex4
603
Cita
12 de enero de 2020, 8:45 a. m.
 Chico maloSe unió en noviembre de 2006 | Estado: Comerciante | 457 publicaciones
¿Por qué no utilizar un clip en la esquina superior derecha? :-)

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot1.png Tamaño: 7 KB


Citando a Wolfsch
{quote} Hola Honesrknive. ¿Existe la posibilidad de obtener una versión más nueva, por favor? Saludos, Wolf.
604
Cita
16 de enero de 2020, 8:37 a. m.
 rustydavo| Se unió en julio de 2017 | Estado: Trader | 141 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Gracias amigo, te lo agradezco mucho.
605
Cita
27 de enero de 2020, 11:21 a. m.
 Alesiosc| Se unió en febrero de 2019 | Estado: Trader | 387 publicaciones
Hola a todos. ¿Se ha actualizado CSDash? El mío ya no aparece... saludos.
Si al principio no tienes éxito, inténtalo una y otra vez.
606
Cita
27 de enero de 2020, 16:02
 Jolly Roger| Se unió en diciembre de 2008 | Estado: Comerciante | 182 publicaciones
Podrías dedicar un rato a revisar las publicaciones anteriores del hilo. Quizás la página anterior si no te quita mucho tiempo.
607
Cita
6 de febrero de 2020, 8:54 a. m.
 Chico maloSe unió en noviembre de 2006 | Estado: Comerciante | 457 publicaciones
Hola Andrew,

¿sería posible activar o desactivar el sonido de las alertas emergentes?
Para mí, las ventanas emergentes son suficientes .

Imagen adjunta




Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
1
608
Cita
7 de febrero de 2020, 6:17 a. m.
 EeZeeTrader| Se unió en abril de 2016 | Estado: Trader | 103 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Hola HonestKnave,

descargué e instalé la versión 1.30 (es la primera vez que uso tu dash).
Mi bróker no tiene el par NZDCHF e incluso después de seleccionar FALSO para la notificación, sigue sin cargar.
¿Hay alguna solución para solucionar este problema?
Pregunta y parecerás estúpido por 5 minutos. No preguntes y seguirás siendo estúpido para siempre.
609
Cita
13 de febrero de 2020, 8:23 a. m.
 Wolfsch| Se unió en noviembre de 2012 | Estado: Trader | 215 publicaciones
¡Muchas gracias, hermano!
Por favor, revisa mi siguiente deseo: Quiero crear un Asesor Experto (EA) con el indicador adjunto, que está dando buenos resultados con una alta tasa de victorias y pequeñas pérdidas, especialmente al combinarlo con una Mediana Operativa (MA) para la derivación. La señal se da al cruzar la línea cero y salir.
Gracias por tu ayuda.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: USDJPYM15 Graal signals.png Tamaño: 65 KB
Archivo(s) adjunto(s)
Tipo de archivo: ex4 Alertas GRAALUn.ex4   14 KB | 1082 descargas
610
Cita
18 de marzo de 2020, 18:40
 Cerugo| Se unió en mayo de 2012 | Estado: Comerciante | 66 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Muchas gracias por esta excelente herramienta, eres una gran persona por compartir tus conocimientos.
611
Cita
25 de marzo de 2020, 3:03 a. m.
 JayPeBe| Se unió en abril de 2019 | Estado: Trader | 47 publicaciones
Por favor ignore esta publicación
612
Cita
6 de abril de 2020, 12:17 p. m.
 Godwin IgiliSe unió en mayo de 2011 | Estado: Trader | 559 publicaciones
Citando a FxMadness
cDash2EAX 2019 ~ hasta que el mundo llegue a su fin. {archivo}
Hola day traders.
El PIN de csdash no funciona con el panel de EAX.
¿Cómo puedo hacerlo funcionar?
613
Cita
23 de abril de 2020, 20:28
 MoMo5| Se unió en abril de 2020 | Estado: Trader | 1 publicación
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Hola honestknave ,
primero quiero agradecerte tu excelente trabajo. ¡Un tablero increíble!
Pero me gustaría preguntarte si hay otra manera de conectar tu csdash al panel eax de Aeseme .

El csdash2 eax de fxMadness no funciona.
¿Podrías ayudarme?
¿O quizás sería mejor usarlo en el manual?

Gracias por la ayuda, señor.
614
Cita
26 de mayo de 2020, 1:27 a. m.
 Sukhjit| Se unió en junio de 2019 | Estado: Trader | 6 publicaciones
Hola,
me gustaría usar esta herramienta. Lamentablemente, no funciona en mi sistema.
Uso VantageFX como bróker.
¿Alguien podría ayudarme, por favor?
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Screenshot1.png Tamaño: 36 KB
615
Cita
26 de mayo de 2020, 3:57 a. m.
 LiovannixUsuario comercial | Se unió en septiembre de 2015 | 433 publicaciones
Citando a Sukhjit
Hola, me gustaría usar esta herramienta. Lamentablemente, no funciona en mi sistema. Estoy usando VantageFX como bróker. ¿Alguien podría ayudarme, por favor? {image}
Detectar automáticamente el prefijo/sufijo del bróker debería haber solucionado el problema. Si no es así, asegúrese de tener los 28 pares de divisas y configure el prefijo/sufijo manualmente. Ingrese el prefijo o el sufijo usted mismo.
Si tiene AUDUSD.ecn, significa que tiene ecn como sufijo,
mientras que ecn.AUDUSD significa que ecn es el prefijo
.
Imagen adjunta

616
Cita
26 de mayo de 2020, 12:00 p. m.
 Sukhjit| Se unió en junio de 2019 | Estado: Trader | 6 publicaciones
Citando a Liovannix
{quote} Detectar automáticamente el prefijo/sufijo del broker debería haber solucionado tu problema, pero si no es así, asegúrate de tener los 28 pares de divisas y configura el prefijo/sufijo para que detecte manualmente. Introduce el prefijo o el sufijo tú mismo. Si tienes AUDUSD.ecn, significa que tienes ecn como sufijo, mientras que ecn.AUDUSD, significa que ecn es el prefijo. {image}
Muchas gracias, Liovannix. Configuré el sufijo como se sugirió y ya funciona. Muchas gracias por tu ayuda.
1
617
Cita
26 de mayo de 2020, 12:57 p. m.
 Sukhjit| Se unió en junio de 2019 | Estado: Trader | 6 publicaciones
Tengo el indicador instalado en mi sistema y funciona.
Así es como entiendo cómo usarlo:
- USDCAD y EURCAD resaltados en rojo: debería buscar una oportunidad para vender aquí.
- CADJPY, NZDUSD y AUDUSD resaltados en verde: debería buscar una oportunidad para comprar.

¿Es correcto?
Por favor, corríjame si no lo entiendo bien.

Muchas gracias.
Imagen adjunta

618
Cita
28 de mayo de 2020, 2:58 a. m.
 Sukhjit| Se unió en junio de 2019 | Estado: Trader | 6 publicaciones
Citando a Liovannix
{quote} Detectar automáticamente el prefijo/sufijo del broker debería haber solucionado tu problema, pero si no es así, asegúrate de tener los 28 pares de divisas y configura el prefijo/sufijo para que detecte manualmente. Introduce el prefijo o el sufijo tú mismo. Si tienes AUDUSD.ecn, significa que tienes ecn como sufijo, mientras que ecn.AUDUSD, significa que ecn es el prefijo. {image}
Esta herramienta es increíble. Pude ganar más de 100 pips en un día.
Muchas gracias por crearla y compartirla.
Que Dios te bendiga.
619
Cita
6 de junio de 2020, 8:18 a. m.
 howa61Se unió en julio de 2013 | Estado: Trader | 551 publicaciones
Citando a Wolfsch
¡Muchas gracias, hermano! Por favor, revisa mi siguiente deseo: Quiero crear un Asesor Experto (EA) con el indicador adjunto, que está dando buenos resultados con una alta tasa de victorias y pequeñas pérdidas, especialmente al combinarlo con una Media Móvil (MA) para la descripción. La señal se da al cruzar la línea cero y salir. Gracias por tu ayuda. {archivo} {imagen}

Hola Wolfsch.

Gracias por la información.

¿Tienes una plantilla con toda la información de Indi y me podrías dar más información?

Gracias de antemano.
620
Cita
9 de junio de 2020, 12:37 p. m.
 sinohe6| Se unió en mayo de 2020 | Estado: Trader | 69 publicaciones
Citando a Sukhjit
{quote} Muchas gracias, Liovannix. Configuré el sufijo como se sugirió y ya funciona. Muchas gracias por tu ayuda.
Hola, yo también tengo el mismo problema para cargar, ¿podrías explicarme detalladamente cómo solucionarlo? Soy un usuario principiante.

P32
 Chandana47| Se unió en septiembre de 2018 | Estado: Trader | 232 publicaciones
¡Gracias compañero!
¡Nadar con tiburones!
622
Cita
15 de julio de 2020, 14:54
 JacemSe unió en enero de 2014 | Estado: Trader | 58 publicaciones
¡Muchas gracias por tu trabajo!

Citando a honestknave
Última versión: 1.30 --------------------------------------------------------- Existe una hoja de cálculo de Excel muy conocida que utiliza las funciones DDE de MT4 para calcular la fortaleza de la moneda mediante una fórmula basada en el máximo, el mínimo y la oferta de D1: {image}. Como consecuencia de otro proyecto en el que estoy trabajando, la he adaptado a MT4. Es un indicador EA sencillo que debería replicar los resultados de la hoja de cálculo de Excel. Incluye algunas mejoras adicionales (alertas,...)
623
Cita
17 de julio de 2020, 22:54
 Depósito de petróleo| Se unió en julio de 2020 | Estado: Trader | 2 publicaciones
¡Gracias por esta información tan genial! Admiro su pasión y generosidad. ¡Espero aprender más de ustedes!
624
Cita
26 de julio de 2020, 2:59 a. m.
 mdt244| Se unió en marzo de 2014 | Estado: Comerciante | 19 publicaciones
Citando a honestknave
Versión: 1.29 Caducidad: 31 de diciembre de 2019 ¡Les deseamos éxito a todos! {file}
Hola querido
¿puedes borrar el límite del indicador para que pueda usarlo?
625
Cita
26 de julio de 2020, 3:52 a. m.
 aquí2alláSe unió en diciembre de 2019 | Estado: Trader | 5585 publicaciones
Citando a mdt244
{quote} Hola querido, ¿puedes borrar el límite del indicador para que pueda usarlo?
Tener fecha de caducidad es problemático. Prefiero comprar un indicador que haga lo mismo que usar uno gratis con fecha de caducidad.

Dicho esto, puedes encontrar la versión más reciente aquí (con fecha de caducidad, por supuesto).
Aprende de tus errores y sigue adelante.
626
Cita
6 de agosto de 2020, 23:21
 Fayelfx| Se unió en mayo de 2019 | Estado: Trader | 16 publicaciones
Hola, ¿alguien tiene el archivo mq4 de este indicador?
Imagen adjunta

627
Cita
8 de agosto de 2020, 11:58 a. m.
 howa61Se unió en julio de 2013 | Estado: Trader | 551 publicaciones
Citando a Fayelfx
Hola, ¿alguien tiene el archivo mq4 de este indicador? {imagen}

Similar no sé si está bien para ti
Archivo(s) adjunto(s)
Tipo de archivo: mq4 Cambiador de símbolos - vspat 1.2.mq4 (   10 KB | 806 descargas)
Saludos
2
628
Cita
8 de agosto de 2020, 21:14
 Fayelfx| Se unió en mayo de 2019 | Estado: Trader | 16 publicaciones
Citando a howa61
{quote}Similar no sé si está bien para ti {file}Saludos

¡Gracias! ¡Eres el mejor! ¿Pero qué tal el cambio de horario?
629
Cita
11 de septiembre de 2020, 4:30 a. m.
 RoyNZ| Se unió en septiembre de 2020 | Estado: Trader | 1 publicación
Hola Honestknave,

he usado tu indicador csDash versión 1.30. Me gusta. ¿Sería posible añadir una pequeña función a la interfaz gráfica y eliminar la limitación de tiempo, si la hubiera? Estoy dispuesto a pagar una tarifa, dentro de un límite razonable. Gracias. RoyNZ
630
Cita
11 de septiembre de 2020, 6:04 a. m.
 howa61Se unió en julio de 2013 | Estado: Trader | 551 publicaciones
Citando a Fayelfx
{quote} ¡Gracias! ¡Eres el mejor! ¿Pero qué tal el cambio de horario?
Hola y gracias.

Disculpen que no lo tenga.

Saludos.
631
Cita
19 de septiembre de 2020, 6:17 a. m. | Editado a las 9:32 a. m.
 lechugas| Se unió en marzo de 2016 | Estado: Trader | 36 publicaciones
Citando a honestknave
Última versión: 1.30 --------------------------------------------------------- Existe una hoja de cálculo de Excel muy conocida que utiliza las funciones DDE de MT4 para calcular la fortaleza de la moneda mediante una fórmula basada en el máximo, el mínimo y la oferta de D1: {image}. Como consecuencia de otro proyecto en el que estoy trabajando, la he adaptado a MT4. Es un indicador EA sencillo que debería replicar los resultados de la hoja de cálculo de Excel. Incluye algunas mejoras adicionales (alertas,...)
¿Puedo solicitar que CsDash muestre valores históricos? Por ejemplo, los valores del día anterior o de la semana anterior. Podría ser un indicador con muchas líneas, como algunos indicadores de fortaleza de divisas, como un oscilador. Actualmente, solo muestra lo que está sucediendo. Lo solicito para realizar pruebas retrospectivas. Gracias. ¿Dónde puedo contactarlos personalmente?
Operador de SMA múltiple
632
Cita
18 de octubre de 2020, 10:58 a. m.
 Teoría de RoninSe unió en abril de 2020 | Estado: aprendiendo a ser mariposa | 741 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Tu trabajo es muy interesante

, gracias.
633
Cita
18 de octubre de 2020, 12:23 p. m.
 Vinna| Se unió en mayo de 2020 | Estado: Trader | 71 publicaciones
Citando a Fayelfx
Hola, ¿alguien tiene el archivo mq4 de este indicador? {imagen}
Un archivo .ex4..........

https://www.forexfactory.com/thread/...6#post13095506

Espero que esto ayude.........
Todos los créditos a cja.......
634
Cita
26 de diciembre de 2020, 00:35
 bribón honestoSe unió en noviembre de 2014 | Estado: Trader | 1300 publicaciones
Version: 1.31

Expiry: N/A (or technically somewhere around 68 years from now...)

Wishing success to all!
Attached File(s)
Tipo de archivo: ex4 csDash.ex4   140 KB | 4,869 downloads
22
635
Quote
Dec 26, 2020 1:32am
 919gileadJoined Jul 2010 | Status: Great hopes make great men | 2,042 Posts
Quoting honestknave
Version: 1.31 Expiry: N/A (or technically somewhere around 68 years from now...) Wishing success to all! {file}
Thank you Andrew and Merry Christmas to you and the family.

Shalom
Low Risk Low Stress High Reward High Probability Trades
636
Quote
Dec 27, 2020 10:54am
 micah119| Joined Dec 2011 | Status: Trader | 91 Posts
Thank you Andrew.
637
Quote
Dec 31, 2020 7:24pm
 Gabosky007| Joined Nov 2018 | Status: Trader | 3 Posts
Quoting honestknave
Version: 1.31 Expiry: N/A (or technically somewhere around 68 years from now...) Wishing success to all! {file}
just wanted to ask if you can create the expert advisor [ea] version of the csdash?
638
Quote
Jan 3, 2021 10:07am
 dbenie| Joined Jan 2021 | Status: Trader | 2 Posts
Quoting honestknave
Version: 1.30 Expiry: 31 December 2020 Wishing success to all! {file}
Hi Honestknave, Would you be able to you extend the expiration date of your CsDash for 2021?
639
Quote
Jan 3, 2021 2:40pm
 Vinna| Joined May 2020 | Status: Trader | 71 Posts
[quote=dbenie;13339867]{quote} Hi Honestknave, Would you be able to you extend the expiration date of your CsDash for 2021
go to post 634 problem solved................
honours....to honestKnave.....
640
Quote
Jan 3, 2021 6:57pm
 dbenie| Joined Jan 2021 | Status: Trader | 2 Posts
[cita=Vinna;13340053]
Citando a dbenie
{quote} Hola Honestknave, ¿Podrías extender la fecha de vencimiento de tu CsDash para 2021? Ve a la publicación 634. Problema resuelto. Honores... a honestKnave.
Me lo perdí por completo, mi culpa. Gracias, Vinna y HonestKnave.
Intentemos hacer algunas pips.


P33
 dariuske| Se unió en octubre de 2005 | Estado: Solo un miembro | 237 publicaciones
Citando a honestknave
Versión: 1.31 Caducidad: N/D (o técnicamente, dentro de unos 68 años...) ¡Les deseo éxito a todos! {archivo}
¡Gracias! ¡

El mejor impulso de fortaleza monetaria que existe!
642
Cita
7 de enero de 2021, 6:19 a. m.
 Tharnge| Se unió en enero de 2021 | Estado: Trader | 4 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
¿Cómo configurar ccDash.ex4??????????
Archivo(s) adjunto(s)
Tipo de archivo: ex4 csDash .ex4   143 KB | 1100 descargas
643
Cita
7 de enero de 2021, 13:42
 Tharnge| Se unió en enero de 2021 | Estado: Trader | 4 publicaciones
Citando a honestknave
Última versión: 1.31 --------------------------------------------------------- Existe una hoja de cálculo de Excel muy conocida que utiliza las funciones DDE de MT4 para calcular la fortaleza de la moneda mediante una fórmula basada en el máximo, el mínimo y la oferta de D1. Como consecuencia de otro proyecto en el que estoy trabajando, la he adaptado a MT4. Es un indicador EA sencillo que debería replicar los resultados de la hoja de cálculo de Excel. Incluye algunas mejoras adicionales (alertas, posibilidad de seleccionar...)
Puedo usar este csDash.ex4 desde mi país (Myanmar).
¿Podría haber un error en la hora del corredor y del mercado?
644
Cita
13 de enero de 2021, 9:51 a. m.
 Chica acuática| Se unió en noviembre de 2012 | Estado: Comerciante | 11 publicaciones
Citando a honestknave
Versión: 1.31 Caducidad: N/D (o técnicamente, dentro de unos 68 años...) ¡Les deseo éxito a todos! {archivo}
Gracias por su generosidad al compartir un indicador de advertencia (¡para mí!) muy inteligente y útil :-)
645
Cita
15 de enero de 2021, 18:11
 Tirachinas1Se unió en febrero de 2012 | Estado: Trader | 1894 publicaciones
Citando a honestknave
Versión: 1.31 Caducidad: N/D (o técnicamente, dentro de unos 68 años...) ¡Les deseo éxito a todos! {archivo}
Hola honestknave, te deseo un muy feliz año nuevo y lo mejor para el 2021. Por favor, necesito tu guía sobre cómo ingresar pares con sufijo como el de la captura de pantalla adjunta. ¿Habrá una coma o un punto después de cada par? Lo intenté, pero no está activado en el csdash. Gracias.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: HonestKnaveCSDASH.PNG2.PNG Tamaño: 24 KB
Imagen adjunta

646
Cita
16 de enero de 2021, 7:47 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Deje esa entrada en blanco y pruebe la opción "Detectar automáticamente" que aparece encima.
Si no funciona, introduzca solo la letra del sufijo "z".
El único límite es el que tú mismo te pones - Felix Baumgartner
647
Cita
20 de enero de 2021, 4:23 a. m.
 Tharnge| Se unió en enero de 2021 | Estado: Trader | 4 publicaciones
Citando a honestknave
Versión: 1.30 Caducidad: 31 de diciembre de 2020 ¡Les deseamos éxito a todos! {file}
Hola señor...
Quiero operar en el marco temporal H1. ¿Cuál es la configuración básica para mí?
img-1 es la opción TF IndexBack (si opero en el marco temporal H1, ¿cuál es la configuración básica para mí)?
img-2 es el índice (¿puedo cambiarlo a 0? ¿Qué significa?)

<<<Disculpen mi mal inglés>>>
Imagen(es) adjunta(s) (haga clic para ampliar)
Haga clic para ampliar Nombre: ff ask.png Tamaño: 123 KB
Haga clic para ampliar Nombre: ff ask1.png Tamaño: 123 KB
648
Cita
20 de enero de 2021, 5:51 a. m.
 Tharnge| Se unió en enero de 2021 | Estado: Trader | 4 publicaciones
Hola,
quiero operar en el marco temporal H1. ¿Cuál es la configuración básica para mí?
img-1 es la opción TF IndexBack (si opero en el marco temporal H1, ¿qué opción es básica para mí)?
img-2 es el índice (¿puedo cambiarlo a 0? ¿Qué significa?

<<<Disculpen por mi mal inglés>>>
Imagen(es) adjunta(s) (haga clic para ampliar)
Haga clic para ampliar Nombre: ff ask.png Tamaño: 123 KB
Haga clic para ampliar Nombre: ff ask1.png Tamaño: 123 KB
649
Cita
1 de febrero de 2021, 20:27
 método alfa| Se unió en febrero de 2021 | Estado: Trader | 3 publicaciones
Muchas gracias honestknave, ¡saludos!
650
Cita
1 de febrero de 2021, 20:47
 método alfa| Se unió en febrero de 2021 | Estado: Trader | 3 publicaciones
Hola Honestknave, muchas gracias por compartir tu csdash, saludos, probé csdash, el diario fue increíble, tu indicador realmente me ayudó con mis ganancias comerciales, también intenté usarlo en un marco de tiempo más pequeño para el cálculo de h4 y h1, pero noté una preocupación: a veces, h4 y h1 muestran el mismo cálculo, también para el diario y h4, espero saber de ti pronto, gracias y mantente a salvo
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: e67370b6de0c6859c2b363973955e528.png Tamaño: 269 KB
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: 68a4d4e82703c4b5e8f9900f548fe7b2.png Tamaño: 278 KB
651
Cita
6 de febrero de 2021, 11:46 a. m.
 vasal| Se unió en noviembre de 2020 | Estado: Trader | 67 publicaciones
Citando alphamethod
Hola Honestknave, muchas gracias por compartir tu csdash, saludos, probé csdash, el diario fue increíble, tu indicador realmente me ayudó con mis ganancias comerciales, también intenté usarlo en un marco de tiempo más pequeño para el cálculo de h4 y h1, pero noté una preocupación: a veces, h4 y h1 muestran el mismo cálculo, también para el diario y h4, espero saber de ti pronto, gracias y mantente a salvo {image}{image}
Esto se debe a que, al iniciarse el período H4, la primera hora de este H4 coincide: de 8:00 a 12:00, se muestra una barra de 4H, y de 8:00 a 9:00, la barra H1 coincide con la H4 para este período. Lo mismo ocurre con H4 y D1: en las primeras 4 horas del día, de 00:00 a 04:00, H4 y D1 mostrarán los mismos resultados.
652
Cita
10 de febrero de 2021, 4:49 a. m.
 ctnie2143| Se unió en diciembre de 2007 | Estado: Comerciante | 119 publicaciones
Estimado Shabs19,

gracias por el excelente indicador. Esta versión fue corregida y no había opción para agregar la TF necesaria. ¿Tiene la versión con M1, M5, M15 hasta MN?
Si tiene el enlace al codificador,

gracias por su amable ayuda,

Citi.

Citando a Shabs19
Aquí hay un indicador útil que da la relación de oferta para todos los períodos de tiempo: {archivo} {imagen}
653
Cita
10 de febrero de 2021, 6:17 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a ctnie2143
Estimado Shabs19, gracias por el excelente indicador. Esta versión fue corregida y no había opción para agregar la TF necesaria. ¿Tiene la versión con M1, M5, M15 hasta MN? Si tiene el enlace al codificador, gracias por su amable ayuda, Citi. {quote}
Lo siento, no puedo ayudarte, solo encontré la versión ex4, por lo que no puedo editar el archivo.
El único límite es el que tú mismo te pones - Felix Baumgartner
654
Cita
15 de febrero de 2021, 9:14 a. m.
 rustydavo| Se unió en julio de 2017 | Estado: Trader | 141 publicaciones
Citando a honestknave
Versión: 1.31 Caducidad: N/D (o técnicamente, dentro de unos 68 años...) ¡Les deseo éxito a todos! {archivo}
Gracias, amigo, te lo agradezco mucho. Cuídate.
655
Cita
18 de febrero de 2021, 8:46 a. m.
 método alfa| Se unió en febrero de 2021 | Estado: Trader | 3 publicaciones
Citando a Vasal
{quote} Esto se debe a que, al iniciarse el período H4, la primera hora de este H4 coincide: de 8:00 a 12:00, se muestra una barra de 4H, y de 8:00 a 9:00, la barra H1 coincide con la de H4 para este período. Lo mismo ocurre con H4 y D1: en las primeras 4 horas del día, de 00:00 a 04:00, H4 y D1 mostrarán los mismos resultados.
Vaya, gracias por la aclaración, Vasal. Te lo agradezco. ¡Saludos!
656
Cita
22 de marzo de 2021, 14:58
 vasal| Se unió en noviembre de 2020 | Estado: Trader | 67 publicaciones
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Window-2021-03-22 19_55_19.png Tamaño: 22 KB
657
Cita
22 de marzo de 2021, 20:52
 Tinieblas EternasSe unió en julio de 2011 | Estado: Oro nuevamente | 10,031 publicaciones | En línea ahora
Citando a dariuske
{quote} ¡Gracias! ¡El mejor dash de fortaleza monetaria que existe!
Los CSM son como los médicos, lo mejor es obtener una segunda opinión, o una tercera opinión, tal vez incluso 4.



Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: 2021-03-23_9-50-17.jpg Tamaño: 653 KB
Me cuesta mucho IGNORARTE, pero puedes intentarlo.
Nunca vuelva a perder. Retorno histórico: 2,4 %
4
658
Cita
23 de marzo de 2021, 2:17 a. m. | Editado a las 7:16 p. m.
 Tinieblas EternasSe unió en julio de 2011 | Estado: Oro nuevamente | 10,031 publicaciones | En línea ahora
En caso de que no lo hayas notado, el NZD está siendo golpeado hoy, no estoy seguro por qué, no leí ninguna noticia, probablemente me lo perdí, de todos modos,

el NZD es el Conor McGregor de la moneda, pequeño, descarado y necesita ser eliminado de vez en cuando.

Imagen adjunta



ACTUALIZACIÓN , cierre del día, ¿es "whacked" un término lo suficientemente fuerte?

Imagen adjunta

Me cuesta mucho IGNORARTE, pero puedes intentarlo.
Nunca vuelva a perder. Retorno histórico: 2,4 %
659
Cita
8 de abril de 2021, 5:34 a. m.
 jones026| Se unió en abril de 2021 | Estado: Trader | 1 publicación
Por favor, dame una versión del tablero de cs. ¿Alguien me puede ayudar? Es una versión para mt4 y ya la descargué. Por favor, ayúdenme por completo.
660
Cita
21 de abril de 2021, 6:12 a. m.
 PetroPol| Se unió en enero de 2021 | Estado: Trader | 48 publicaciones
Citando a honestknave
Versión: 1.31 Caducidad: N/D (o técnicamente, dentro de unos 68 años...) ¡Les deseo éxito a todos! {archivo}
¡Hola! ¿Tienes el MQL4? Así podemos crear un EA con el indi.
¡Gracias!


P34
661
Cita
30 de abril de 2021, 8:05 a. m.
 Alesiosc| Se unió en febrero de 2019 | Estado: Trader | 387 publicaciones
Citando a honestknave
Versión: 1.31 Caducidad: N/D (o técnicamente, dentro de unos 68 años...) ¡Les deseo éxito a todos! {archivo}
Hola, honestknave. Me preguntaba si podrías echar un vistazo a una valiosa adición a CSDash. Al menos en mi humilde opinión... La usé hace un tiempo cuando tuvimos que retomar el hilo para renovarla. Agradezco que la hayas eliminado. La he estado usando junto con otros indicadores y he descubierto que, al combinarlo con estocásticos simples y RSI + Bandas de Bollinger como parte de mi plantilla de "Gráfico Abierto", me da un buen punto de partida para decidir si abro una operación. Por ejemplo, cuando hago clic en un par resaltado en verde en CSDash y el estocástico está en el extremo de sobreventa y el RSI también, con la Banda de Bollinger inferior en el extremo de sobreventa, pero por encima del RSI, luego, con un par de indicadores de confirmación adicionales, abro la operación una vez que el RSI cruza la primera Banda de Bollinger por encima. Me ha ido muy bien con este enfoque, haciendo scalping de 5 a 20 pips por operación. Pero usar entre 0,5 y 1,0 lotes resulta bastante lucrativo. Mi humilde sugerencia es: ¿se podrían añadir los criterios extremos del estocástico y el RSI + Banda de Bollinger a CSDash, con un interruptor, para usar todos los criterios normales de fuerza, pero al activarlo, permitir que la información del estocástico y el RSI solo muestre los pares resaltados que cumplen estos criterios, además de los de fuerza? Esto significaría que, al hacer clic en un par resaltado en CSDash, obtendría un gráfico listo para operar, salvo que revise rápidamente mis otros indicadores de confirmación... Espero no ser impertinente, pero funciona de maravilla... Espero que lo consideren. Saludos desde Manchester.
Si al principio no tienes éxito, inténtalo una y otra vez.
2
662
Cita
9 de junio de 2021, 22:06
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Ha pasado tiempo desde que publiqué aquí. También soy un ferviente seguidor de MADDash, como pueden ver aquí .

Pero quizás prefiero CSDash a MADDash por razones complejas.

Sí, a ver cómo crece esta operación...

Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: using csdash as gauge.png Tamaño: 61 KB
663
Cita
9 de junio de 2021, 22:08
 se casó de nuevoSe unió en agosto de 2013 | Estado: Trader | 387 publicaciones
Tras analizar tu sugerencia, puedo concluir lo siguiente:

define la tendencia con CSDash y busca el retroceso que la sigue con el RSI/BB.

Citando a Alesiosc
{quote} Hola, honestknave. Me preguntaba si podrías echarle un vistazo a una valiosa adición a CSDash. Al menos en mi humilde opinión... La usé hace un tiempo cuando tuvimos que volver al hilo para renovarla. Agradezco que la hayas eliminado. La he estado usando junto con otros indicadores y he descubierto que usarla con estocásticos simples y RSI + Bandas de Bollinger como parte de mi plantilla de "Gráfico Abierto" me da un excelente punto de partida para decidir si abro una operación o no. Así que, cuando hago clic en un par resaltado en verde...
1
664
Cita
12 de junio de 2021, 13:25
 Nod32Se unió en agosto de 2020 | Estado: Trader | 297 publicaciones
https://www.mql5.com/es/market/produ....google.com%2F
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: aq-currencyexplorer-screen-5214.png Tamaño: 102 KB
2
665
Cita
15 de junio de 2021, 13:01
 Judas 3| Se unió en octubre de 2018 | Estado: Trader | 9 publicaciones
¿Alguien puede explicar cómo funciona el filtro AQ? Llevo un tiempo usándolo, pero sigo malinterpretándolo. Parece cambiar de dirección al iniciar una operación. ¿Alguien tiene el AQ que proporciona ideas para operar? Gracias.
666
Cita
28 de agosto de 2021, 13:47
 Campco| Se unió en julio de 2009 | Estado: Comerciante | 173 publicaciones
Citando a Alesiosc
{quote} Hola, honestknave. Me preguntaba si podrías echarle un vistazo a una valiosa adición a CSDash. Al menos en mi humilde opinión... La usé hace un tiempo cuando tuvimos que volver al hilo para renovarla. Agradezco que la hayas eliminado. La he estado usando junto con otros indicadores y he descubierto que usarla con estocásticos simples y RSI + Bandas de Bollinger como parte de mi plantilla de "Gráfico Abierto" me da un excelente punto de partida para decidir si abro una operación o no. Así que, cuando hago clic en un par resaltado en verde...
Hola,
soy Ben. Agradezco todo el trabajo realizado por Honestknave.
Muchas gracias.

Gracias por tu pregunta, Alesiosc. Pienso lo mismo.
Sería fantástico que csDash se pudiera combinar con lo que describiste.

Saludos cordiales,
Ben .
2
667
Cita
16 de septiembre de 2021, 2:11 a. m.
 apestoso| Se unió en marzo de 2016 | Estado: Trader | 23 publicaciones
¿Soy solo yo o csDash se ha vuelto invisible de repente en mi MT4? No lo veo, aunque MT4 dice que se ha cargado correctamente. Lo he eliminado y vuelto a descargar, pero sigue sin estar visible.
668
Cita
16 de septiembre de 2021, 8:56 a. m.
 Judas 3| Se unió en octubre de 2018 | Estado: Trader | 9 publicaciones
¿El indicador tiene fecha de caducidad? No he revisado la mía.
669
Cita
17 de septiembre de 2021, 5:10 a. m.
 apestoso| Se unió en marzo de 2016 | Estado: Trader | 23 publicaciones
Citando a Judas 3
¿El indicador tiene fecha de caducidad? No he revisado la mía.
Tomé el último que dice que no tiene fecha de vencimiento.
670
Cita
11 de octubre de 2021, 20:16
 roma777| Se unió en octubre de 2009 | Estado: Comerciante | 112 publicaciones
Citando a honestknave
Tenga en cuenta: no estoy pensando en hacer demasiado desarrollo en esta versión porque mi enfoque principal está en una versión MTF (aún no está lista): {imagen}
¿Puedo encontrar en algún lugar dicha versión MTF, por favor?
671
Cita
11 de octubre de 2021, 20:21
 roma777| Se unió en octubre de 2009 | Estado: Comerciante | 112 publicaciones
Citando a Shabs19
Aquí hay un indicador útil que da la relación de oferta para todos los períodos de tiempo: {archivo} {imagen}
¿Cómo se usa este indicador? Intento vincularlo al gráfico, pero no funciona.
672
Cita
12 de octubre de 2021, 9:14 a. m. | Editado a las 10:10 a. m.
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a rome777
{quote} ¿Cómo se usa este indicador? Intento vincularlo al gráfico, pero no funciona.
¿Seleccionó "Verdadero" para "Relación de puja activada"?
En la pestaña Entradas.

Explicación de la relación de puja aquí.
El único límite es el que tú mismo te pones - Felix Baumgartner
673
Cita
5 de enero de 2022, 11:23 a. m.
 thchai2005| Se unió en mayo de 2015 | Estado: Trader | 1 publicación
Citando a Tharnge
{quote} ¿Cómo configurar ccDash.ex4??????????{archivo}
Alguna actualización para el 2022. por favor.
1
674
Cita
23 de enero de 2022, 17:28
 aquí2alláSe unió en diciembre de 2019 | Estado: Trader | 5585 publicaciones
¡Este es un medidor de fuerza de moneda fantástico! ¡Gracias!
Aprende de tus errores y sigue adelante.
1
675
Cita
27 de marzo de 2022, 15:28
 francisakz| Se unió en marzo de 2013 | Estado: Comerciante | 252 publicaciones
Por favor, ¿existe una versión GOLD del medidor de fuerza de la moneda cdash? para operar con oro.
1
676
Cita
23 de julio de 2022, 15:30
 fred01| Se unió en octubre de 2007 | Estado: Comerciante | 31 publicaciones
Citando a honestknave
Esta actualización no soluciona nada. Solo permite seleccionar cuál de los 28 pares se desea mostrar: {image} Nota: Es necesario configurar un par para que se muestre para recibir alertas. Los 28 pares siguen siendo necesarios para los cálculos (por lo que los números deberían ser exactamente los mismos, ya sea que se visualicen 1 o 28 pares). Es posible que vea esta pantalla y se pregunte por qué no se han realizado los cálculos. Esto se debe a que csDash aún espera la actualización de otros pares que no aparecen en la lista. {image} Por favor, informe cualquier error.
Bien organizado, amigo. ¿Se puede añadir XAUUSD? Muchas gracias.
Los mejores indicadores son el conocimiento y el estado mental del trader.
677
Cita
23 de julio de 2022, 17:48
 Tinieblas EternasSe unió en julio de 2011 | Estado: Oro nuevamente | 10,031 publicaciones | En línea ahora
Citando a fred01
{quote} Bien escrito, amigo. ¿Se puede añadir XAUUSD? Muchas gracias.
Lea esto dos veces y contáctenos, gracias

https://www.forexfactory.com/thread/...86#post8335286
Me cuesta mucho IGNORARTE, pero puedes intentarlo.
Nunca vuelva a perder. Retorno histórico: 2,4 %
678
Cita
23 de julio de 2022, 17:48
 Tinieblas EternasSe unió en julio de 2011 | Estado: Oro nuevamente | 10,031 publicaciones | En línea ahora
Citando a francisakz
Por favor, ¿existe una versión GOLD del medidor de fuerza de la moneda cdash? para operar con oro.
Lea esto dos veces y contáctenos, gracias

https://www.forexfactory.com/thread/...86#post8335286
Me cuesta mucho IGNORARTE, pero puedes intentarlo.
Nunca vuelva a perder. Retorno histórico: 2,4 %
679
Cita
3 de diciembre de 2022, 21:26
 LivingCovers| Se unió en diciembre de 2018 | Estado: Trader | 202 publicaciones
Citando a honestknave
{quote} De nada, Pax. Disculpen la ambigüedad del nombre... con "ordenado" me refiero a "ordenar por fuerza". "Sin ordenar" significa alfabéticamente. Para los pares, la ordenación se realiza por diferencial (es decir, compra-venta = diferencial). Si la moneda base es muy fuerte mientras que la moneda cotizada es muy débil, se observará un diferencial grande. Lo mismo ocurre a la inversa.

Hola chicos,
solo una pregunta. Con todo lo que se ha discutido sobre esta herramienta en este hilo, ¿cómo se usa para operar? Si alguien ya lo ha mencionado y tiene la respuesta, por favor, indíqueme dónde está. Gracias al desarrollador por esta herramienta tan genial.
680
Cita
10 de septiembre de 2023, 6:07 a. m.
 DevontraderSe unió en febrero de 2013 | Estado: Trader | 1456 publicaciones
Honestknave,


sé que ha pasado mucho tiempo desde que te uniste a este proyecto. Espero que esto te llegue y que estés bien. ¿

Hay alguna opción para añadir índices a este excelente indicador o para mostrar lo que tengas en tu lista de símbolos?

Por favor, envíame un mensaje directo si es necesario.

Muchas gracias de antemano.


P35
681
Cita
19 de marzo de 2025, 9:36 a. m.
 benjamin89| Se unió en enero de 2017 | Estado: Trader | 112 publicaciones
Citando a honestknave
Versión: 1.31 Caducidad: N/D (o técnicamente, dentro de unos 68 años...) ¡Les deseo éxito a todos! {archivo}
Hola honestknave, tengo un problema con el último csdash publicado, lo he estado usando desde entonces, cada vez que cambio de par, el indicador muestra el mismo mensaje de advertencia.
Imagen adjunta (haga clic para ampliar)
Haga clic para ampliar Nombre: Untitled.png Tamaño: 41 KB
682
Cita
3 de septiembre de 2025, 11:53 a. m.
 Tirachinas1Se unió en febrero de 2012 | Estado: Trader | 1894 publicaciones
Citando a Shabs19
Aquí hay un indicador útil que da la relación de oferta para todos los períodos de tiempo: {archivo} {imagen}
Hola, hermano, ¿podrías ayudarme con tu plantilla para la proporción de pujas? La descargué y me gusta mucho, pero quiero que se vea pequeña en mi gráfico, como la tuya, pero no encuentro dónde ajustar el tamaño ni la captura de pantalla. Por favor, ayúdame. Gracias.
683
Cita
Última publicación : 3 de septiembre de 2025, 13:47
 Shabs19Se unió en agosto de 2006 | Estado: Trader | 5301 publicaciones
Citando a Slingshots1
{quote} Hola, hermano, ¿podrías ayudarme con tu plantilla para la proporción de pujas? La descargué y me gusta mucho, pero quiero que se vea pequeña en mi gráfico, como la tuya, pero no encuentro dónde ajustar el tamaño ni la captura de pantalla. Por favor, ayúdame. Gracias.
Simplemente cambie los ajustes X e Y en la entrada para la ubicación.

El tamaño de fuente se configura en el indicador; al ser un archivo ex4, no es posible ajustarlo.
El único límite es el que tú mismo te pones - Felix Baumgartner

FIN FORO  csDash (medidor de fortaleza monetaria) ------ 35 Paginas de Conversación
********************************************************************************************** 
Te sugiero,  revisa cuidadosamente este documento  de texto, y haz un resumen con subtitulos ana lizando los siguientes temas:
1. Resumen de la información mas importante, sobre la base teórica del indicador y el algoritmo detrás de su codificación. 

2.- Además reúne toda la información posible en base a las estrategias con las que se utiliza que el propio programador o algunos trader  refieran que se mejoran los resultados. 

3.- Si hay información sobre complementación, diferencias, u otra informaion importante que lo comparae con el indicador MaDash del mismo autor, registarala al igual que las conclusiuones importantes relacionadas

4.- Indicadores probados y recomendados para utilizar para validadar o descartar las señales, o que se complementen con csDash para mejorar la rentabilidad.

5.- Cualquier recomendación hecha por el autor, otros programadores o  trader que se hagan con intención de mejorar la estrategia o al propio indicador.

6.- Detalla la estrategia que propones cuando mencionas "Uso Complementario (Estrategia Potente):"
     MADdash para identificar la dinámica del momentum y el inicio potencial de un movimiento (¿qué par se está moviendo?). y csDash para confirmar la dirección y la solidez subyacente del movimiento (¿tiene respaldo de la fuerza estructural de las divisas?)

7.- POr ultimo cual es exactamente lo propuesto e integrado en el codigo cuando dices: "el autor introduce una mejora crucial: "Timeframe Rolling Count".

8.- Terminado el analisis revisa cuidadosamente entes de entregar el informe, y recupera cualquier detalle pequeño pero importante y lo agregas al informe. Te doy una pista en algun lugar del foro se menciona que cuando la distancia es de 3 pips o menos significa, algo que nunca mencionaste en los intentos anteriores.

9.- Agrega cualquier información que consideres necesario en relación a las conclusiones  que saques de esta revisión, ideas para mejorar el incador, ideas de uso y cualquier otra que consideres necesario dejar registro.
