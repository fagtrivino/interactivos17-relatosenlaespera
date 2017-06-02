
- [0. Interactivos17-Relatos en la Espera](#interactivos17-relatos-en-la-espera)
- [1. Idea](#1-idea)
- [2. Implementación](#2-implementación)
- [2.1 Caso-a-estudiar](#2-2-caso-a-estudiar) 
- [3. Desarrollo de los relatos](#3-desarrollo-de-los-relatos) 
- [4. Tecnología](#4-tecnología)
- [5. Experiencia de usuario](#5-experiencia-de-usuario)
- [6. Diseño de producto](#6-diseño-de-producto) 
- [Promotores y colaboradores](#promotores-y-colaboradores)
- [Instrucciones](#instrucciones)
- [Diario del proceso](#diario-del-proceso)



# Interactivos17-Relatos en la Espera  
Antes de empezar a movernos con el transporte público vivimos en la ‘espera’, en un tiempo muerto e insignificante. ¿Qué objeto, suceso o acontecimiento nos puede despertar del letargo de esa espera?
![](LOGOFINAL.jpg)
- [Video presentación del proyecto](https://mega.nz/#!fMIxWAbI)



## 1-Idea
Hoy en día los usuarios del transporte público suelen recibir información del tiempo de espera. Un tiempo que hasta ahora está ocupado, principalmente, por el teléfono móvil y la publicidad de las paradas. El proyecto aprovecha ese tiempo de una forma alternativa, involucra al viajero en una experiencia extraña pero enriquecedora que sirve para contextualizar la ciudad que le envuelve. La audición de un relato que dura el tiempo de espera previsto se convierte en el detonante para viajar con la imaginación sin moverse de la parada.

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/1-idea/Relatos-de-espera_low.jpg)

## 2-Implementación

### 2-1 Estado del Arte 
Se ha hecho un rastreo de otros proyectos que se han desarrollado en torno al transporte público. Proyectos que unas veces se han centrado en la lectura de un libro, en los anuncios que suelen estar en estas paradas o en lo que ocurre durante el viaje. Para localizar la propuesta de "Relatos en la Espera" en este entorno de referencias, se ha llevado a cabo un "Mapa de usuario" que permite reconocer todas las referencias estudiadas bajo dos parámetros: nivel de relación con el factor tiempo de espera y nivel de importancia de la oralidad. Ambos factores han sido elegidos por su fuerte vinculación con el transporte; el primero por su funcionalidad, el segundo por la capacidad de despertar la imaginación y por favorecer el alejamiento del teléfono móvil o de la publicidad de una ciudadanía volcada exclusivamente en lo visual.  

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/2-1Estado%20del%20Arte/MAPADEUSUARIO.jpg?raw=true)

+ 01 Axe, pantalla interactiva (https://www.youtube.com/watch?v=UIHwHqaY3SY)
+ 02 Expendedora de libros (http://www.lamasbella.es/bellamatic/) 
+ 03 Máquina expendedora de micro-relatos (http://lapiedradesisifo.com/2015/11/14/la-maquina-expendedora-de-relatos-cortos)
+ 04 Cuentos por teléfono (http://maguared.gov.co/project/cuentos-por-telefono-libro-de-gianni-rodari-para-ninos/)
+ 05 Cocacola, pantalla interactiva (https://www.youtube.com/watch?v=ctdYwo55pPA)
+ 06 Apotek, pantalla interactiva. (https://www.youtube.com/watch?v=tdQgsmYKxLM)
+ 07 Best Bus Ever (https://www.youtube.com/watch?v=zpdcUakdQVA)
+ 08 Billetes impresos en libros (https://www.youtube.com/watch?v=1PAkrApvkac) 
+ 09 Kulturbus (https://www.youtube.com/watch?v=W20u8qJWv2M)
+ 10 Viraphone (http://danielperlin.net/#viraphone-with-vito-acconci)
+ 11 Portadas de libros comprometidas (https://www.youtube.com/watch?v=2LyVVbhvStk)
+ 12 Photoshop en la pantalla (https://www.youtube.com/watch?v=jpRmQo1_4Es) 

### 2-2 Caso a estudiar 
De los modos de transporte donde se lleva a cabo la espera, autobús, tren o metro, se decide estudiar el autobús por tener menos elementos de distracción. Actualmente en Madrid, lugar donde se lleva a cabo el prototipo, todas las paradas de metro disponen de pantallas que indican el tiempo de espera, así como en muchas ocasiones televisiones o anuncios que juegan con la presencia del viajero en la parada. Mientras que en autobús, la presencia de pantallas que indican el tiempo de espera es más escaso y los anuncios en las marquesinas suelen ser más genéricos.

De todas las líneas de autobuses que existen en Madrid, se decide la línea 6. Esta línea no es de suministro, es decir no sirve para llevar a los usuarios a centros productivos de la ciudad, sino que es una línea de barrio que alimenta al barrio de Orcasitas y que puntualmente pasa por la ciudad. 

De todas las paradas que tiene la línea 6, se ha elegido la que está en la plaza Tirso de Molina. Una parada que está en una plaza con bastante vida, cerca de centro Medialab Prado, y que tiene árboles cercanos que dan sombra a la parada. Algo que ayuda al prototipo pues no hay reflejos en la pantalla.

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/2-2%20Caso%20a%20estudiar/prueba.jpg)

Para conocer los hábitos de los usuarios de dicha parada se ha llevado a cabo una recogida de datos tanto de forma cuantitativa, basadas en la observación, como de forma cualitativa. Esta segunda ha permitido conocer las características habituales de los usuarios de dicha parada, cuáles son sus hábitos, qué ven desde ella, cómo la habitan. Respecto a la recogida de datos de forma cuantitativa estos son los datos recogidos: 
Hora de llegada/salida, hombre/mujer/otro, solo/acompañado, edad (joven/mediano/mayor), actividad (móvil/libro/bolso/conversación), si está sentado o no lo está.

Así mismo se ha llevado a cabo un cuestionario a pie de parada de autobús que ha permitido reconocer el perfil  del usuario mayoritario de dicha parada: mujer, principalmente sola y de edad avanzada. 
![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/2-2%20Caso%20a%20estudiar/Resumen%20de%20datos%20observados%20(1).jpg)

A parte de esta recogida de datos hemos llevado a cabo una encuesta a través de las redes sociales para saber la reacción ante un posible dispositivo que cuente un relato durante las esperas. En esta ocasión la distribución de edad es mucho más repartida y las actividades que se realizan en general son más variadas. 
![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/2-2%20Caso%20a%20estudiar/Resumen-Sobre-el-tiempo-de-espera-(6).jpg) 

El resultado de estos documentos nos informa que hay un usuario en las paradas principalmente mujer de mediana o avanzada edad que no usa teléfono móvil. Así mismo se destaca en los cuestionarios el escaso interés de que suceda una actividad en las paradas, sin embargo el alto interés ante que la actividad sea un relato escuchado que permita saber más sobre la ciudad inmediata en torno a ella.

## 3 Desarrollo de los relatos 
A través de redes de contacto se ha localizado a escritores a los que se les ha dado una serie de recomendaciones a seguir: la claridad en la redacción del relato, la simplicidad y sobretodo el objetivo de que las historias sirvan para ampliar la lectura de la ciudad inmediata. Los relatos sirven para construir y para saber más de la ciudad que envuelve a la parada. Se adjunta el mail de invitación que se envió a los autores. En él se especifican la importancia del tiempo del relato, imágenes de lo que se ve desde la parada y una lista de detonantes generales que tienen el objetivo de ayudar a inventar los relatos.

Así mismo, gracias a la colaboración de actores, los textos han sido interpretados para que el contenido tuviera más incidencia en el oyente y realismo.

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Interpretes.jpg) 

Estas son las historias elegidas junto a los relatos producidos. 
Título / Autor / Intérprete / Duranción:

+ 1 Se busca poeta / Paloma Diez Temprano /	Manuel Cruz López ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Se%20Busca%20Poeta.mp3)
+ 2 Besos en la parada /	Paloma Diez Temprano /	Manuel Cruz López ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Besos%20en%20la%20Parada.mp3)
+ 3 Chofer /	Marta Felipe Soria /	Manuel Cruz López ![Audio](https://github.com/fagtrivino/interactivos17-relatosenlaespera/blob/master/3%20Desarrollo%20de%20los%20relatos/Chofer.mp3)
+ 4 Tarde de Domingo /	Paloma Diez Temprano /	Gonzalo Pendolema ![Audio](https://github.com/fagtrivino/interactivos17-relatosenlaespera/blob/master/3%20Desarrollo%20de%20los%20relatos/Tarde%20de%20domingo.mp3)
+ 5 Un, dos, tres, cuatro vamos a divertirnos un rato /	Fran Carrillo /	Raquel Sánchez ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Un%20dos%20tres%20cuatro%20vamos%20a%20divertirnos%20un%20rato%20(9.17).mp3)
+ 6 La muerte y la doncella /	Bernardo Gómez /	Mónica Montoro ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/La%20muerte%20y%20la%20doncella.mp3)
+ 7 El flautista /	Julia Livaditi /	Mónica Montoro ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/El%20flautista.mp3)
+ 8 Chocolate con churros /	Marta Felipe Soria /	Marta Felipe Soria ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Chocololate%20con%20churros.mp3)
+ 9 El tapicero /	Marta Felipe Soria /	Manuel Cruz López (hombre), Elena Peña Parrilla (mujer), Marta Felipe Soria (tapicero)![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/El%20tapicero.mp3)
+ 10 Ocupación para desocupados /	Ángel Muñoz Jiménez,	Manuel Cruz López ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Ocupaci%C3%B3n%20para%20desocupados.mp3)
+ 11 Como no bailar salsa /	Katerina Psegiannaki /	Monica Montoro ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Como%20no%20bailar%20salsa.mp3)
+ 12 En un minuto /	Bernardo Gómez ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/En%20un%20minuto.mp3)
+ 13 Bolsa para la compra /	Isabel Martín Ruiz / Isabel Martín Ruiz, Damiana Ruiz ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Bolsa%20para%20la%20compra.mp3)
+ 14 Dos minutos /	MaxCooper /	Monica Montoro ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Dos%20Minutos.mp3)
+ 15 Un fantasma en Zingarella /	Osvaldo Michelón / Osvaldo Michelón ![AudioXXXXX](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Un%20Fantasma%20en%20Zingarella.mp3)
+ 16  

## 4 Tecnología 
Se han barajado distintas tecnologías para llevar a cabo el dispositivo. Desde una App hasta un teléfono analógico que pudiera servir para escuchar los relatos. Dada la vinculación de la espera con el lugar donde se desarrolla, la tecnología del prototipo tendría que dar salida a este requisito. Por lo tanto la solución de una App no ha sido factible por la deslocalización del lugar y por el necesario consumo de datos que supondría trabajar con ella. A priori el uso de la tecnología "nearby" parecía la más óptima: una vibración del móvil personal cuando el viajero se acerca a la parada sería una buena solución para llevarlo a cabo, salgo que para el desarrollo del prototipo es excesivamente complejo.

Por facilidad de ejecución se decide desarrollar una tecnología mixta. Un dispositivo que con apariencia de teléfono permitiera narrar las historias y junto a él una pantalla con la que interaccionar para especificar el tiempo de espera que el usuario estima que va tardar el t5 Experiencia de usuarioransporte.

El producto final ha necesitado de los siguientes requerimiento técnicos: 
+ Tableta android de 18 pulgadas, en donde se ha desarrollado un interfaz. 
+ Sensor de distancia. [Sensor de ultrasonido](http://www.micropik.com/PDF/HCSR04.pdf)
+ Arduino Uno
+ Batería
+ Micro switch swap
+ Cable OTG

### 4.2 Lets code
#### 4.2.1 [Android App](https://github.com/fagtrivino/relatosEnLaEspera) 
#### 4.2.2 [Arduino y Sensores](https://github.com/fagtrivino/interactivos17-relatosenlaespera/blob/master/4-Tecnologia/sensor2.inoX)
##### Diagrama esquemático
![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/4-Tecnologia/relatosEsquematico.png)

## 5 Experiencia de usuario
Dado el diseño del prototipo, la experiencia de usuario se ha basado en dos puntos importantes: en el diseño de un interface en la pantalla del dispositivo y en la primera experiencia auditiva que recibe el usuario.

En el diseño del interface, para una mayor credibilidad, se ha hecho uso del color oficial de la EMT. Así mismo también se ha diseñado un entorno simple y sobrio, con un tamaño de fuente pensado para un usuario de edad avanzada. La primera pantalla es la más importante, la cual invita al usuario a usar el dispositivo, el pictograma de una persona mayor busca empatizar con el usuario habitual. 

Por otro lado la primera experiencia auditiva se vuelve muy importante para empatizar con el usuario. Por ello se ha trabajado con la frase "Hola soy Leo, estoy aquí para hacer tu espera más amena, lo único que necesito de ti es que me selecciones cuánto tiempo vas a esperar". Se ha elegido el nombre de Leo por la ambigüedad de género, así como una frase natural que intente alejarse de las respuestas automatizadas de los servicios telefónicos habituales.

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/5-Experiencia%20de%20usuario/Interface.jpg)

## 6 Diseño de producto 
El diseño del dispositivo se basa en la integración de una tablet de 18", un sensor de distancia, un arduino, una batería y el cuelgue del mango del teléfono. Un solo elemento que actúa como cabina telefónica, colgado a través de unas cinchas a la altura de una persona sentada. Dado que el dispositivo estará en la parada y que en ocasiones el sol puede llegar generar un brillo que dificulte la lectura en la pantalla, el diseño incluye una pequeña visera que se integra en el diseño final.

El material usado para el dispositivo principal es madera DM cortada a laser, de 5 mm de espesor. El diseño del mango telefónico es de madera pero de 3mm de espesor. La madera tanto del manguito como del dispositivo se resuelve con ensambles en L.

El modelo desarrollado no es impermeable, pero sería necesario su planteamiento en el caso de que se llevara a cabo en otra escala.

Para el modelado se ha utilizado el sowftware Solidwords, y para el corte láser DraftSight-3DS. Se adjuntan en la carpeta correspondiente. 

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/6-Dise-o%20de%20producto/atlas.jpg)

# Promotores y colaboradores: 
### Equipo: 
+ Katerina Psegiannaki (www.kuneoffice.com/)
+ Francisco García Triviño (http://www.kuneoffice.com/)
+ José Manuel López Ujaque (http://www.kuneoffice.com/)
### Colaboradores
+ Sandra Vivar Maestre (www.sandramind.design/)
+ Katalina Soto Rivera (https://www.behance.net/katakatasoto)
+ Mario Alejandro Alzate López (www.marioalzatelopez.com)
+ Inmanulada Marruecos Payán (www.behance.net/inmarru)
+ Marta Felipe Soria 
+ Jonathan Ros 
### Autores e Interpretadores de los textos
+ Manuel de la Cruz (interprete)
+ Gonzalo Pendolema (interprete)
+ Raquel Sánchez (interprete)
+ Monica Montoro (interprete)
+ Marta Felipe Soria (autora e interprete)
+ Elena Peña Parrilla (interprete)
+ Ángel Muñoz Jimenez (autor)
+ Bernardo Gómez (autor e interprete)
+ Esther Iorfida (autor)
+ Fran Carrillo (autor)
+ Julia Livaditi (autor)
+ Osvaldo Michelón (autor e interprete)
+ Paloma Díez (autor)


# Instrucciones
### Instrucciones de montaje y desmontaje
+ Qué material se necesita
+ Cómo se ensambla todo
+ En qué puntos hay que tener cuidado
### Instrucciones de funcionamiento
+ ¿Cómo se enciende? ¿Cómo se apaga?
Para apagar y encender la batería portátil es necesario es delcolgar el teléfono y acceder al botón de encendido y apagado, a través del agujero superior de dónde cualga el teléfono. Previo a esto para poder acceder más fácilmente al botón retirar el USB conectado a la misma batería. También cabe mencionar que el altavoz que está dentro del teléfono puede estar apagado o encendido. Para acceder al mismo habría que levantar la tapa superior del teléfono y pulsar de encendido/apagado, que está en la parte anterior del altavoz. Se puede comprobar que el altavoz está encendido porque puede verse una luz roja (encendido y cargando) o azul (encendido y no cargando).
En caso de que la pantalla de la tablet estuviese bloqueada habría que acceder al botón de desbloqueo por el agujero superior de dónde cuelga el teléfono. Y posteriormente desbloquear la pantalla.
+ ¿Qué hace exactamente? ¿Cómo interactuar con el dispositivo? (pensar que la gente que lo ve no ha estado en el taller). 

### Instrucciones de mantenimiento
+ ¿Tiene batería? ¿Cómo cargarla? ¿Cada cuánto?
Sí. La primera batería a tener en cuenta es la batería portátil que ya se indica anteriormente cómo encender y apagar.
Para cargar esta batería es necesario acceder al puerto por el agujero superior de donde cuelaga el teléfono. Este puerto tiene denominación IN. El cable necesario es microUSB/enchufe o USB/enchufe.
La batería tiene una duración aproximada de 5 horas. 
Hay que cargarla todos los días; y se recomienda hacer el período de carga cuando no esté en uso y al final de cada día.
Hay que tener el cuenta que esta batería suministra energía a tanto a la tablet como al altavoz del teléfono por tanto hay que tener en cuenta que la batería es vital para el correcto funcionamiento del dispositivo. Los cables necesarios para la carga de la tablet es miniUSB(tablet)/USB(batería portátil). Y para el altavoz del teléfono microUSB(altavoz)/USB(batería portátil)

+ ¿Utiliza materiales desechables? ¿tintas? ¿papel?
Para la exposición se ha considerado pegar cinta adhesiva azul: 
- suelo: delimita el espacio donde ocurrirá la experiencia simulando una marquesina que ocupa 1m2. En caso de que se moviese la exposición sería necesario volver a pegar la cinta en el suelo tal y como se ha descrito. Además se 

- expositor: con la cinta adhesiva se colocarán dos franjas, una colocada al final de la parte vertical del expositor y otra colocada al final de la parte inclinada del mismo expositor. 
En la exposición se ha creado un panel simulado del recorrido de una línea de autobús. El formato de este documento es 18x41,1cm. En caso de que se dañase el panel debería volver a imprirse y pegarse sobre un panel de cartón pluma que tendrá las mismas medidas. Se colocará en el lugar que ese indica en el gráfico.
+ Si deja de funcionar cuál sería la lista de errores más corrientes: de los más comunes a los más raros. ¿Cómo arreglar cada uno?

# Diario del proceso
### Semana 1
En esta semana se hizo una presentación de la idea, los colaboradores expusieron sus perfiles y se comenzó con una definición del estado del arte que nos supuso una búsqueda de referencias para definirnos y diferenciarnos.
Durante la primera semana, el cuestionamiento y la viabilidad del prototipo ha tomado el máximo protagonismo. Se analizó la viabilidad técnica y se cuestió el formato del prototipo: si era vía móvil/tablet, si era una app o si lo adaptábamos a un antiguo walkman con auriculares. Las mentorías han cuestionado las distintas áreas que forman el proyecto y nos han invitado a concentrarnos en las historias para que el dispositivo sea lo más sencillo posible.  
### Semana 2
El desarrollo de las historias ha sido lo más importante así como la búsqueda de escritores y actores que locuten e interpreten los textos. Se ha creado un texto, enviado a los autores, con pautas sobre cómo hemos definido que deben ser los relatos. Algunas de estas pautas por ejemplo son: que el relato se localice en la plaza de de Tirso de Molina y en concreto en la parada del autobús; que el tiempo de la historia sea el presente y sin saltos al pasado; o que tengan un lenguaje sencillo y directo puesto que van a ser relatos escuchados. Se ha realizado también la grabación de los audios con actores y locutores y hemos decidido mantener los diversos acentos de nuestros intérpretes porque hemos querido representar el abanico de nacionalidades de una ciudad como Madrid y en concreto de los usuarios de dicha plaza. 
Asimismo esta semana hemos desarrollado el dispotivo básico así como la interfaz y los colores que la caracterizan (colores que hemos decidido que sean similares a los de la EMT para vincular nuestro prototipo con los tiempos de la espera de los autobuses); sin embargo a pesar de la sencillez, hemos necesitado mucho más tiempo del esperado. Han empezado a surgir errores tecnológicos fundamentalmente debidos a la interactuación entre el arduino y la tablet.
### Semana 3
La última semana ha sido en la que más situaciones de tensión han surgido porque hemos detectado también errores de diseño.  Se ha salido a la parada del bus para hacer el testeo del producto y hemos constatado errores de funcionamiento. Hasta el último día no funcionó, y los ensayos se realizaron sin el dispositivo a pleno rendimiento.
También en esta semana se ha compilado toda la información recogida, se ha llevado a cabo toda la producción de la narrativa y se ha hecho el planteamiento de la exposición. Se ha creado un panel informativo con unas aparentes paradas del autobús que refleja el recorrido del proyecto (origen Medialab, destino Relatos en la espera) y cuyas paradas son los títulos de todos los relatos.
Los últimos días son de cierre y perfeccionamiento de los errores detectados. Y de preparativos de la exposición.


