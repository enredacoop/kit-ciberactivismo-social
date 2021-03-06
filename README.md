KIT DE CIBERACTIVISMO SOCIAL
============================

# Marco del proyecto

Proyecto formativo titulado **ACTIVISMO DIGITAL. Cómo mejorar el impacto de las acciones comunicativas**. Fue desarrollado presencialmente en Sevilla en febrero de 2017.

## Formación y dinamización
[![Logo de Enreda Cooperativa](enreda.png)](http://enreda.coop)

## Organización
[![Logo de Intermón Oxfam](intermon-oxfam.png)](http://www.oxfamintermon.org/)

## Financiación
[![Logo de la Agencia Andaluza de Cooperación Internacional para el Desarrollo (AACID)](aacid.jpg)](http://www.juntadeandalucia.es/aacid/)


# Índice

* [Técnicas de recolección de información](https://enredacoop.github.io/kit-ciberactivismo-social#Tcnicas-de-recoleccin-de-informacin)
* [Cómo construir infografías](https://enredacoop.github.io/kit-ciberactivismo-social#como-construir-infografas) 
* [Ciberactivismo con Facebook y Twitter](https://enredacoop.github.io/kit-ciberactivismo-social#ciberactivismo-con-facebook-y-twitter) 
* [Organizando una campaña en las redes sociales](https://enredacoop.github.io/kit-ciberactivismo-social#organizando-una-campaña-en-las-redes-sociales) 
* [Bibliografía](https://enredacoop.github.io/kit-ciberactivismo-social#bibliografía) 

# Técnicas de recolección de información

## Tipi Ciudadano

![Logo de Tipi Ciudadano](http://tipiciudadano.es/images/tipigold.png)

[Tipi Ciudadano](http://tipiciudadano.es/) es una herramienta de incidencia política que hace uso de datos públicos para ofrecérselo a la sociedad civil de una forma más organizada y directa. Se basa en la recolección de toda la actividad parlamentaria del Congreso de los Diputados de España y la catalogación de dichas iniciativas en torno a [21 diccionarios temáticos](http://tipiciudadano.es/temas) relacionados con la pobreza y la explusión social.

Para ofrecer todos estos datos, Tipi cuenta con un [escáner o buscador avanzado](http://tipiciudadano.es/escaner) en el que se permiten un número importante de criterios de búsqueda con el objetivo de poder llegar hasta el nivel de detalle que cada usuario requiera. Todos los datos que el escaner ofrece se pueden descargar en formato reutilizable para ser trabajados de manera offline.

Además [el sistema dispone de una API](http://tipiciudadano.es/api-doc) (interfaz de programación de aplicaciones) para que los datos puedan ser integrados con otras aplicaciones de forma casi directa.

## Google Alerts

Las Alertas de Google es un servicio de supervisión de los contenidos, que ofrece el motor de búsqueda de la compañía Google, que automáticamente notifica al usuario cuando el nuevo contenido coincide con un conjunto de términos de búsqueda seleccionados por el usuario. (Wikipedia)

### Posibles usos

* Monitorizar cualquier mención a nuestra organización
* Buscar referencias a una campaña que hayamos lanzado
* Medir la difusión de nuestros contenidos
* Recibir las novedades sobre un tématica de sitios webs de referencia
* Monitorizar la actividad en Redes Sociales 


### Configuración básica

* La frecuencia con la que recibes notificaciones
* Las fuentes donde realizará las busquedas (Noticias, Web, Blogs, vídeos, libros o foros)
* El idioma
* La zona del mundo de la que quieres recibir información (por paises)
* El número de resultados que quieres ver (Todos, o solo los más destacados)
* Las cuentas que reciben la alerta: Puedes rebirlo en tu mail o en un lector RSS

### Comandos para afinar nuestras busquedas

* " ": Para buscar una algo literalmente > "economia social" "la transicionera" (los artículos son exluidos de la búsqueda sino están entre comillas)

* -: Para excluír de la busqueda los resultados que incluyan un término concreto> cooperativo -deporte

* OR (ó |): Permite agrupar busquedas, incluyendo páginas que contengan un término u otro> Manifestación TTIP Málaga OR Sevilla OR Granada


* *: Comodín. Utilizado para sustituir una palabra en las busquedas de frases exactas (las que usan "")> 

* Site: busca en webs especificas> pobreza site:pp.es OR site:psoe.es  OR site:podemos.info OR site:ciudadanos.es

* intitle: limita las busquedas de las palabras al titulo de la página > site:eldiario.es OR site:publico.es intitle:tercer sector

Tienes todos los comandos en las [páginas de ayuda de Google](https://support.google.com/websearch/answer/2466433?hl=es)

# Como construir infografías

## Por qué infografías

Vivimos en la era de los datos, rodeados de ellos y cada va a más. Por otro no solemos sacarle valor a los mismos, ni de forma interna en las organizaciones para medir evoluciones o proyectos ni de forma externa para comunicar mejor. Y es que las infografías son un gran recurso comunicativo (o pieza comunicativa) cuando se desea hacer resúmenes o agregados de cierta información.

Se trabajarán las visualizaciones desde una perspectiva eminentemente práctica con el objetivo de poder usarlas mañana mismo, aunque con ello se pierda la introducción téorica a veces necesarioa.

## El trabajo de preparación de los datos

Existen diferentes formas de trabajar con los datos con el objetivo de prepararlos para la visualización. Eso si, las tareas están bien definidas: limpieza, unificar criterios, ordenación, agrupamientos, etc. Este tipo de tareas para personas con conocimientos técnicos medios se las facilita mucho as hojas de cálculo.

Las hojas de cálculo son un tipo de documento que nos permiten manipular datos numéricos y/o alfanuméricos.
* La representación de los datos se realiza en forma de filas y columnas (formato tabular) lo que hacer que cada dato esté dispuesto en una celda (conexión entre fila y columna).
Cada celda puede contener un valor numérico, alfanumérico o una fórmula que opere con los valores de otras celdas.
Debido a estas cuestiones, el uso de las hojas de cálculo está muy extendido en todas las áreas ya que permiten un trabajo simple/medio/complejo con los datos para obtener resultados de forma rápida y automatizada.
Existen ciertos formatos (ods, xls, ...) propios de los diferentes tipos de software de gestión de hojas de cálculo  pero se recomienda el uso del formato CSV (valores separados por comas) para la exportación de los mismos una vez que se ha realizado el trabajo con ellos.
Dado el formato tabular de las hojas de cálculo es automático transformar un documento en su análogo CSV, el cual perderá todo el estilo y solo conservará los datos.
En un formato CSV cada fila representa una fila de la hoja de cálculo y cada columna se representa por su valor más una coma indicando que termina una columna y empieza otra.

Para la tabla

| Paises    | Población | Área (km2) | Capital |
|---|-------|-----------|------------|---------|
| España    | 46704314  | 504645     | Madrid  |
| Portugal  | 10427301  | 92212      | Lisboa  |
| Italia    | 60782668  | 301338     | Roma    |

su correspondencia CSV sería

<pre>
Paises, Población, Área (km2), Capital
España, 46704314, 504645, Madrid
Portugal, 10427301, 92212, Lisboa
Italia, 60782668, 301338, Roma    |
</pre>

Todo software de hojas de cálculo puede abrir sin problemas los ficheros CSV y presentarlos en formato tabular para su posterior procesamiento.
Para obtener un fichero CSV de una hoja de cálculo basta con abrir dicha hoja de cálculo con el software que se use y guardarla como “CSV” en la opción determinada del programa. Con ello se obtiene una copia estandarizada de los datos en un formato abierto.
Nuestro objetivo no es indagar en el funcionamiento de las hojas de cálculo pero sí se valoró como necesario el presentarlas dado el amplio uso que de ellas se realiza en diferentes ámbitos como forma de mostrar y operar con conjuntos de datos.


## De los datos a las visualizaciones

Para la inmensa mayoría de los seres humanos la comprensión de los datos se simplifica aplicando sobre ellos diversas técnicas de visualización de los mismos, tanto para facilitar su entendimiento como para destacar alguna característica o elemento diferenciador oculto en cierto conjunto de datos.
de la estadística en particular y desde la ciencia matemática en general siempre se ha tendido a realizar representaciones gráficas de conceptos abstractos difícilmente entendibles sin dichas gráficas.
Es por ello que el campo de las representaciones gráficas de números (datos) siempre ha tenido una gran importancia tanto en su uso como en su investigación.
Con la irrupción de la Era del Dato en la que actualmente nos encontramos dentro de la Sociedad de la Información, en donde toda entidad del sistema genera datos sin cesar, el estudio de las representaciones gráficas de los datos ha experimentado un tremendo auge y no son pocas las posibilidades con las que se cuenta.
A continuación se verán algunas posibilidades, desde las clásicas hasta las más actuales en la red.

* Gráfico de barras (bar chart): Consta de dos ejes y representa en en Y los elementos a medir (agrupados o no) y en el eje X el valor medido.
* Gráfico de columnas (column chart): Consta de dos ejes y representa en en X los elementos a medir (agrupados o no) y en el eje Y el valor medido.
* Gráfico de tarta o donut (pie/donut chart): Representa de forma circular los porcentajes del elemento a medir en torno al total que es la tarta/donut completo.
* Gráfica de dispersión (scatter plot/chart): Basado en el sistema cartesiano, permite representar los valores de dos variables para un conjunto de datos. Los datos se muestran como una colección de puntos tomando valores en el eje vertical (variable1) como en el horizontal (variable2).
* Circle packing: Círculos anidados que permiten representar jerarquías y comparar los valores. Esta visualización es particularmente eficaz para mostrar la proporción entre los elementos a través de sus áreas y su posición dentro de una estructura jerárquica.
* Treemap: Permite representar las jerarquías de datos y la proporción entre los elementos. Los diferentes niveles jerárquicos crean agrupaciones visuales a través de la subdivisión en rectángulos en proporción al valor de cada elemento. Estas visualizaciones son útiles para representar las diferente proporciones de estructuras de datos jerárquicos anidados.
* Gráfico de barras apiladas (stacked bars graph): Similar a los gráficos de columnas pero en el eje Y se muestran valores de una variable agrupados en torno a una categoría. El objetivo de la visualización es intenta comparar las partes de un todo.
* Gráfico de flujo (stream graph): Visualización muy recomendable para datos continuos tales como series temporales.

Para la creación de las visualizaciones se usarán dos aplicaciones web, por lo que no serán necesario instalar ningún software en los equipos personales.

Las aplicaciones web son:

* [DataWrapper](http://datawrapper.de)
* [Raw Graphs](http://rawgraphs.io)

Antes de empezar con algunos ejemplos de uso de las herramientas comentadas sería conveniente identificar algunos aspectos comunes de toda herramienta de creación de visualizaciones.
Básicamente siempre se pueden diferenciar 3 apartados fundamentales: inserción de datos, configuración y adaptación, y exportación de la visualización.

**Inserción de datos**

Se trata de introducir los datos que servirán de materia prima al sistema para la creación de la visualización.
Pueden existir diversas formas de inserción de datos pero las más comunes son mediante texto (formato CSV) o mediante la subida de un fichero (CSV, ODS, XLS, etc).

**Configuración y adaptación**

Una vez cargados los datos se deberá elegir la gráfica que mejor represente el conjunto de datos con el que se trabaja. Además de ello hay que definir las variables a mostrar, los colores en los que se visualizarán, los textos y algunas cuestiones más.

**Exportación**

Finalizada la visualización es tiempo de exportarla para usarla en otros entornos, ya sea obteniendo la imagen resultante u obteniendo su código embebido (código HTML) para ser integrada en otras webs.

Vistas estas tres secciones de trabajo bastante común en este tipo de herramientas pasamos a mostrar, mediante ejemplos, cada una de las aplicaciones webs comentadas previamente para realizar las visualizaciones de los datos.


### Data Wrapper

Data Wrapper es una herramienta web libre y gratuita desarrollada por ABZV (Instituto alemán de formación en periodismo) para realizar visualizaciones de datos. Estas visualizaciones cuentan además con ciertas interacciones qe se pueden definir en la herramienta.
Al igual que RAW, el ser libre la convierte en una herramienta altamente configurable y modifcable.

**Inserción de datos**

![Insertar datos en data Wrapper](dw1.png)

Esta sección está preparada para que copies el contenido de un fichero CSV o directamente de una hoja de cálculo en la caja de texto que aparece en la interfaz.
Además permitirá subir directamente un fichero CSV de datos para operar con él.

**Configuración y adaptación**

![Configuración y adaptación en Data Wrapper (1)](dw2.png)

Con los datos ya cargados es hora de revisar que todo se subió correctamente. Para ello tenemos un visualizador en modo tabla de los mismos.
Además podremos describir los datos indicando si éstos cuentan como cabecera de información en la primera fila o añadiendo nuevas columnas.

![Configuración y adaptación en Data Wrapper (2)](dw3.png)

En el siguiente paso podremos seleccionar que tipo de gráfica y estilos para los datos queremos aplicar.
Junto a la selección de la gráfica podremos además afinar el resultado de la visualización y añadir campos que nos permitan contar una historia en torno a los datos que se visualizan como es añadir textos y marcar elementos como destacados (entre otras muchas opciones).

**Exportación**

![Exportación en Data Wrapper](dw4.png)

En este paso final se nos permite enlazar directamente a la visualización en el sistema compartiendo en enlace que se muestra. También nos permite copiar el código HTML que genera la visualización para pegarlo directamente en otra web o blog.
Por último permite crear otra visualización duplicando la actual, facilitando así el trabajo al usuario.


### Raw Graphs

RAW Graphs es una herramienta web libre y gratuita desarrollada por Density Design Research Lab (Politécnica de Milán) para servir de puente entre hojas de cálculo y gráficas vectoriales.
Está construído usando como base D3js, una de las librerías gráficas más potentes y extendidas en el mundo web. Además el ser libre la convierte en una herramienta altamente configurable y modifcable.

**Inserción de datos**

![Insertar datos en Raw](raw1.png)

Esta sección está preparada para que copies el contenido de un fichero CSV o directamente de una hoja de cálculo en la caja de texto que aparece en la interfaz.
Tiene dos tipos de visualización una vez copiados los datos: en modo texto y en modo tabla. Además el sistema indicará si la importación se realizó correctamente.

**Configuración y adaptación**

![Configuración y adaptación en Raw (1)](raw2.png)

En el siguiente paso podremos seleccionar que tipo de gráfica o layout para los datos queremos aplicar.
El sistema nos proporciona una pequeña miniatura de ejemplo del gráfico, un texto explicativo y un enlace para ahondar en el tipo de gráfica.

![Configuración y adaptación en Raw (2)](raw3.png)

Una vez marcada que tipo de gráfica se va a usar es necesario asociar algunas variables del conjunto de datos a los parámetros de la gráfica para su construcción (serie, jerarquía, tamaño, color, etiqueta, tamaño, ...)

![Configuración y adaptación en Raw (3)](raw4.png)

Además se indicarán algunos parámetros de estilo adicionales tales como tamaños del gráfico y colores de los elementos a mostrar.

**Exportación**

![Exportación en Raw](raw5.png)

Este es el paso final antes de poder compartir la visualización. RAW, una vez realizado el trabajo, nos permite descargarlos como imagen, como gráfico vectorial o como modelo de datos en JSON para usarlo en otra aplicación.
Además nos permite copiar el código HTML que genera la visualización para pegarlo directamente en otra web o blog.


## Insertar visualizaciones en otras web

Una vez realizado todo el trabajo será necesario publicarlo. Se pueden considerar dos tipos de formatos según lo que hemos visto:

**Imagen**

Son relativamente fáciles de integrar en una web con independencia de su formato de fichero (JPG, PNG, SVG, ...). Dependiendo del sistema que estemos usando para publicar la noticia en la que se incluirá dicha visualización puede modificarse la nomenclatura pero buscando una opción de “añadir imagen” o similar tendríamos el trabajo finalizado.

**Código embebido**

El código embebido siempre se encuentra en formato HTML (lenguaje básico de la Web). La mayoría de los sistemas de gestión de contenidos o de blogs (Drupal, Wordpress, Mezzanine, etc.) nos permiten integrar dicho código embebido como parte de la página que estemos editando por lo que copiando el código embebido y pegándolo en el cuerpo de pagina se tendría el trabajo finalizado.

# Ciberactivismo con Facebook y Twitter

## El papel de las redes sociales en nuestra estrategia comunicativa online

El papel protagónico que en los últimos años han alcanzado las redes sociales ha provocado que muchas organizaciones se centren exclusivamente en ellas, olvidándose de que ni todas las personas son usuarias de las RRSS, ni estas son el mejor medio para alcanzar algunos de los objetivos que puede plantearse un organización.

Es por ello que, antes de lanzarnos a planear una campaña en RRSS, debemos plantear el rol que jugaran las mismas dentro de todo nuestra estrategia comunicativa online.

![embudo de conversión](embudo.jpg)
(Fuente de la imagen [Wingu](http://www.winguweb.org/sitio2012/wp-content/uploads/2014/05/ComunicacionOnlineentuONG.pdf)


En la imagen de arriba vemos una versión (adaptada los objetivos clásicos de un colectivo u organización) del llamado [“embudo de conversión”](https://es.wikipedia.org/wiki/Embudo_de_ventas) que suele usarse en marketing online. 

Dependiendo de los objetivos de nuestra campaña, seleccionaremos cual es el público en el que debemos centrarnos, lo que determinará cuál son los medios más adecuado para llegar al mismo y , por tanto, el papel que deben jugar las redes sociales en la misma.

### Un esquema clásico

![esquema de campaña online](esquema.jpg)
(Fuente de la imagen [Wingu](http://www.winguweb.org/sitio2012/wp-content/uploads/2014/05/ComunicacionOnlineentuONG.pdf)


El esquema de arriba muestra un ejemplo de campaña online clásica de una ONG, cuyos objetivos están centrados en conseguir donaciones y voluntarios. En una campaña de este tipo la centralidad está ocupada por la web, y sus mecanismos para conseguir suscripciones que profundicen la relación con la organización, relegando a las redes sociales a uno de las medio a través de los que conseguir visitantes.

Dependiendo de la campaña que estemos realizando el papel de las redes sociales puede ser muy diferentes, y actualmente muchas campañas tienen su centralidad en ellas, una tendencia lógica dado el inmenso crecimiento en usuarios activos que siguen teniendo, y las nuevas funcionalidades que día a día se les van añadiendo, con el objetivo de poder hacer casi cualquier cosa (desde trasmitir eventos a recibir donaciones) sin salir de ellas.

## El papel de Facebook y Twitter en el universo de las Redes Sociales 

Aunque este taller está centrado en el uso de Facebook y Twitter, es importante conocer el resto de grandes redes sociales existentes actualmente en España, y qué uso podrían tener:

### Facebook, la red de amigos
* ¿Quien la usa? 1.550 millones de usuarios activos, 21 en España.  
* ¿Cuanto se usa? 4:23 h semanales de uso medio
* ¿Para qué podría usarse desde el activismo?  Es la red social con mayor número de usuarios y con más funcionalidades, por lo que tiene infinidad de posibles usos en los que profundizaremos en la sección de Facebook.

### Twitter, la inmediatez
* ¿Quien la usa?  320 millones de usuarios activos,  11 en España 
* ¿Cuanto se usa?  2:40 semanales de uso medio
* ¿Para qué podría usarse desde el activismo? Movimientos como occupy wall street, 15m o las primaveras árabes hicieron que twitter fuese considerado en los inicios de esta decada como un [“vehículo de revoluciones”](http://www.huffingtonpost.es/2016/03/20/twitter-movilizacion-social_n_9496078.html) su simplicidad, ligereza, apertura y arquitectura la hace una herramienta ideal para canilizar momentos. Profundizaremos más en la sección de twitter

### Instagram, la centralidad de la imagen
* ¿Quien la usa? 400 millones de usuarios activos, 8 en España,
* ¿Cuanto se usa? 32 horas semanales de uso medio
* ¿Para qué podría usarse desde el activismo? A pesar de que ya ha superado a twitter en usuarios diarios, todavía poco usada por organizaciones. La centralidad que tienen las imágenes en esta red social obligan a tener bien trabajado este aspecto para tener repercusión. Tienes más información  [aquí](http://www.socialco.es/como-puede-tu-ong-sacar-partido-de-instagram/)

### Snapchap, la red de los millennials 
* ¿Quien la usa? 150 millones de usuarios diarios
* ¿Cuanto se usa? 30 horas semanales de uso medio
* ¿Para qué podría usarse desde el activismo? Esta red ha sido poco usada por el activismo, ya que desde sus inicios su funcionamiento se ha caracterizado más por ser un red de mensajería instantánea que una red social. La progresiva ampliación de características y su amplísima difusión entre la más jóvenes (el 50% tiene menos de 24 años) hace que deba tenerse en cuenta para acciones dirigidas a este público. Tienes más información [aquí](http://www.socialco.es/para-que-puede-servir-snapchat-a-tu-ong-e-ideas-para-inspirarte/)

### Pinterest, la red social feminizada
* ¿Quien la usa? 150 millones de usuarios activos
* ¿Cuanto se usa? 1:49 horas semanales de uso medio
* ¿Para qué podría usarse desde el activismo? Esta red tiene un perfil bastante definido: el 80% de sus usuarios son mujeres, y el 80% es mayor de 25 años. La fuerza de esta red reside en su facilidad para compartir, recopilar y organizar imágenes de diversas fuentes, por lo que es de utilidad para campañas visuales para este sector, con el valor añadido de que es un buen generador de tráfico a nuestra web, ya que enlaza a la fuente original de la imagen. Tienes algunas herramientas [aquí]( http://www.afundacion.org/es/socialia/noticia/como_explotar_pinterest_para_tu_ong._15_herramientas_utiles)

### Google +, posicionando nuestros artículos en google
* ¿Quien la usa?  540 millones de usuarios 
* ¿Cuanto se usa? 1:43 horas semanales de uso medio
* ¿Para qué podría usarse desde el activismo? El alto número de usuarios oficiales de esta red está provocado por el hecho de que la cuenta en g+ viene en “de regalo” cuando abres una cuenta en alguno de los populares servicios de google (gmail, youtube...). Su uso real sigue siendo marginal (fuera de algunos sectores profesionales muy concretos), aún así esta red puede ser de gran utilidad para nuestra organización por su capacidad SEO, es decir, de posicionar los artículos que en ella colgamos en el buscador de google.  

### Whatsapp/telegram

Aunque es discutible si es estos servicios de mensajería son técnicamente una red, durante este taller quisimos preguntar a las organizaciones asistentes el uso que le daban:

* Organización “interna”: La mayoría de organizaciones usan estos canales como método de organización o comunicación interna, ya sea con grupos genéricos o grupos específicos para alguna tarea o campaña concreta.
* Mensajes virales: También es relativamente habitual preparar mensajes específicos para whatsapp con el objetivo de ser viralizados, como versiones modernas del “pásalo”.
* Canales de telegram como newsletter: Hay organizaciones, como [greempeace]( http://www.telegram.me/greenpeace_esp) que han creado su propio canal (público y unidireccional) para enviar noticias.
* Bots de telegram: A pesar de las ilimitadas posibilidades que abre esta función avanzada de Telegram, todavía no parece muy explotada por el activismo en España.

### Menéame

Menéame es el mayor agregador de noticias de España, con nueve millones de usuarios únicos al mes. Su funcionamiento general es sencillo: cualquier usuario puede enviar una noticia, y el resto de usuarios la votan, siendo las más votadas la “portada” de la web.

Además de esta portada general, existen “subs” temáticos , que cualquier usuario puede crear, que tienen su propia portada especializada.

Dadas estas funciones, parece clara la utilidad que pueden tener meneame para el activismo:
* Dar gran difusión a noticias o artículos que elaboremos que sean de interés general.
* Encontrar público interesado en temáticas que trabajamos a través de los subs
* En caso de que no exista, siempre podemos plantearnos crear un “sub” sobre la temática que trabajamos, dando una herramienta a su amplia comunidad para encontrar y difundir  información sobre la misma.

Como en el resto de redes sociales que hemos visto, es importante leer con detenimientos las [normas del sitio]( https://meneame.wikispaces.com/Comenzando) antes de empezar a trabajar en el.

### La imaginación al poder

Aunque hemos hecho un repaso de las principales redes sociales con un uso claro por parte del activismo social, cualquier red puede servir como plataforma si conseguimos echarle un poquito de imaginación...esde [Tinder](http://www.eldiario.es/catalunya/barcelona/Vecinos-Barcelona-ocupan-turistico-Ayuntamiento_0_560994279.html) a [AirBnB](http://verne.elpais.com/verne/2015/05/21/articulo/1432198673_037211.html) 

Fuente: La mayoría de los datos sobre uso de redes sociales están basados en los [estudios de IAB](http://iabspain.es/investigacion/busca-tu-estudio/) 

# Usar Facebook en nuestra estrategia comunicativa

## Conceptos básicos

Empezamos repasando algunos conceptos básicos sobre esta red:

### Cuenta

Las personas usan facebook creando una “cuenta”. Esta cuenta debe tener el nombre real de la persona que se registra (aunque facebook todavía es bastante flexible en este aspecto).  

Es importante resaltar que solo las personas pueden abrir una cuenta: los colectivos, asociaciones, empresas, etc deben abrir una página. Aunque en sus inicios Facebook era flexible con está política, desde hace unos años tiene poca permisividad, por lo que es imprescindible que si tu colectivo todavía usa facebook como “cuenta” convertirlo en una página, a riesgo de que esta sea eliminada. En la ayuda de Facebook te explican [como hacerlo](https://www.facebook.com/help/175644189234902?helpref=page_content)

[+info sobre cuentas en facebook](https://www.facebook.com/help/112146705538576?helpref=faq_content)

### Página

Las páginas son la forma desde que las organizaciones y “celebridades” (ya que las cuentas tienen un límite de 5.000 amigos) gestionan su presencia en Facebook. Cualquier persona puede crear una página desde su cuenta. [Como crear una página](https://www.facebook.com/help/104002523024878?helpref=popular_topics&ref=popular)

Para seguir a la actividad de una  página, no tiene que  “hacerte amigo” sino indicar que “te gusta”, este hecho limita información que proporcionas a los gestores de las páginas que sigues.

Una página tiene muchas más ventajas que una cuenta, ya que mejora las formas de publicación, de personalización y da acceso a  multitud de estadísticas sobre tus acciones en Facebook, etc. Profundizaremos en estos aspectos en la sección “gestionar una página”.

### Grupo

Los grupos ofrecen un espacio para intercambiar opiniones acerca de intereses comunes con determinadas personas. Existen multitud de tipos de grupos, empezando por la privacidad de con la que se configure: 

* *Abierto:* Cualquiera puede  unirse. Los miembros  y el contenido del grupo pueden ser vistos por cualquier persona e incluso  ser indexada por buscadores externos como google.

* *Privado*: Cualquiera puede encontrar el grupo y ver quienes son sus miembros, pero no las publicaciones, que sólo están accesibles para los miembros del grupo. Para poder entrar tenemos que hacer una solicitud, que debe ser aprobada por los administradores. 

* *Secreto:* El grupo sólo es accesible a través de una invitación de uno de sus miembros.

Las funciones que se le pueden dar a los grupos desde el activismo son muy variadas, desde crear un pequeño grupo secreto entre los miembros de nuestra organización, a usar los grupos públicos como forma de difusión. En este sentido, cabe destacar que existen grandes grupos con decenas de miles de miembros sobre todo tipo temáticas, por lo que es interesante hacer un “mapeo” de los grupos que existen sobre los temas que trabajamos antes de iniciar una campaña, y ver el papel que pueden jugar en la misma.

[+info sobre grupos](https://www.facebook.com/help/1629740080681586/?helpref=hc_fnav)


## Gestionar una página

Como ya hemos visto, la página es el espacio adecuado para gestionar la presencia de nuestra organización en Facebook. Veamos las principales herramientas para su gestión:

### Roles y permisos

Las páginas se gestionan desde cuentas personales. El creador de una página puede otorgar a otros usuarios diferentes tipos de permisos para gestionar la página. Veamos los más interesantes para páginas de movimientos sociales:

![Tipo de roles en Facebook](roles.jpg)

* *Administrador*: Es el único que puede otorgar y quitar permisos de gestión de la página. Es preferible que este rol no sea otorgado a un gran número de personas, ya que sus funciones únicas se usan muy pocas veces, y además así se limita los famosos problemas de [“robo de páginas”](http://www.elmundo.es/elmundo/2012/04/23/madrid/1335191371.html) en caso de disputas internas.
* *Editor:* Puede realizar publicaciones en nombre de la página, por lo que solo es necesario asignarlo a las personas que vayan a realizar esta función
* *Moderador*: En página con gran repercusión puede ser útil crear la figura del moderador, para ayudar a limpiar la página de comentarios inapropiados y contestar mensajes
* *Colaborador en vivo:* La nueva función recientemente añadida a Facebook para poder emitir vídeos en streaming ha venido acompañada de este nuevo rol, que únicamente permite realizar esta tarea. Puede ser útil para  nombrar “corresponsales” en algún evento concreto. 


## Personalización

### Perfil y cabecera

Los principales elementos de identidad visual de nuestra organización le Facebook se hace a través de las fotos de perfil y cabecera. Veamos los principales problemas que encontramos.

![Malas prácticas en fotos de perfil de Facebook](perfil.jpg)

**Perfil:** La foto de perfil es pequeña y cuadrada (170 x 170 px), eso supone un problema para muchas organizaciones cuya imagen corporativa no se adapta bien a este formato, por ser rectangulares o contener demasiados elementos para un tamaño tan pequeño. Es habitual encontrar “soluciones” como las de la imagen de arriba, tratando de encajar una imagen rectangular en un espacio cuadrado a base de reducirla o cortarla. 

Para evitar estas situaciones, lo ideal es realizar una trabajo gráfico de nuestra organización para dotándolo de [isotipos o imagotipos](http://www.brandemia.org/hablemos-con-propiedad-logotipo-isotipo-imagotipo-isologo-imagen-corporativa-identidad) que puedan adaptarse a estos formatos.

![Buena práctica en cabecera de facebook](cabecera.jpg)

**Cabecera:** El principal problema que nos encontramos en el diseño de las cabeceras es que su tamaño “cambia” según visitemos la página desde un ordenador (donde se muestra con un ancho de 820 px) o desde el móvil (donde se recortan los laterales de la imagen dejándola en 640 px). 

La solución a esto es la que vemos que realiza Greenpeace en la imagen de arriba: hacer un diseño con “el ancho” adaptado al ordenado, pero con toda la información esencial situada en el centro, para que no se recorte al verla desde el móvil.

[Toda la información sobre formatos de imágenes en facebook](https://www.facebook.com/help/mobile-touch/125379114252045?rdrhc)

### Botones de “llamadas a la acción”

![Botones en la página de OI](boton.jpg)

Una práctica útil de personalización es  la de poner botones de “llamada a la acción” en nuestra página. Estos botones aparecen justo debajo de la cabecera y pueden enlazar a diferentes funciones como llamar, enviar un mensaje o enlazar a una web, como el ejemplo de la imagen de la página de Oxfam Intermón, donde el botón “hacer una donación” nos lleva al apartado de donaciones de su web.
[Toda la información sobre como añadir estos botones](https://www.facebook.com/business/help/312169205649942)

### Pestañas

Una práctica todavía no muy extendida es la de personalizar el orden en el que aparecen las diferentes  “pestañas” de nuestra página. Estas pestañas no son otra cosa que los diferentes “bloques” de elementos que conforman nuestra página (publicaciones, fotos, videos, eventos, notas, me gustas...)

Facebook tiene algunos plantillas para organizar estos elementos, aunque también permite ordenarlas manualmente, lo cual es de gran utilidad, ya que la mayoría de plantillas predefinidas destacan en la cabecera elementos (como videos o eventos) que la mayoría de organizaciones no suelen actualizar con demasiada asiduidad.

Las pestañas se organizan en Configuración>Editar página. [Aquí lo explican detalladamente](https://www.facebook.com/help/371634529571035/?helpref=hc_fnav)


### Destacar publicaciones

![Destacar publicaciones](destacar.jpg)

Esta función permite fijar en la parte superior de nuestra página una publicación concreta que queramos destacar. La publicación permanecerá fijada hasta que decidamos destacar otra o la quitemos de allí. Para hacer esto solo que abrir el menú de cualquier publicación y pulsar sobre el botón “ fijar en la parte superior de la página” (como en la imagen).

## Herramientas básicas para comunicar con nuestro público: 

![botones de publicación](publicar.jpg)

En la imagen de arriba vemos la nueva y mejorada interfaz de publicación para páginas, en la que se destacan las funciones que no existen en las publicaciones de las cuentas. 
Veamos las herramientas básicas que ofrece

### Enlaces

Empezamos por esta simple función de “colgar” en Facebook publicaciones de otra web, ya que esta ha sido “ocultada” de los botones de publicación (probablemente por la obsesión de Facebook de impedir que los usuarios salgan de su red). 

Hay que destacar que cuando colgamos un enlace desde nuestra página tenemos acceso a opciones que no existen en las cuentas personales:
* Editar el titular, el texto o la url de la previsualización
* Añadir una foto (o un video) diferente a la previsualización
* Crear un pequeño “carrusel” añadiendo diferente fotos a la publicación.


[+ info](https://www.facebook.com/help/www/668969529866328?helpref=search
)

### Eventos

Crear un evento es la mejor forma de dar a conocer en Facebook los distintos actos que organizamos. La ventaja de crear un evento, respecto a simplemente colgar la información en tu página, es su potencial “viralización targetizada”: La datos muestran que los eventos son bastante más compartidos que los “posts”, además esa la forma de compartirlo se hace de manera más targetizada, es decir, se comparte con las personas que realmente podrían estar interesadas en asistir. 

Los eventos además tiene otras ventajas:
* Recordatorio automático que hace facebook a los asistentes cuando se acerca la hora del mismo
* Posibilidad de ir actualizando los detalles del evento 
* El potencial de creación de comunidad al permitir que los asistentes comenten, cuelguen fotos, o incluso creen grupos con amigos que han asistido al mismo, etc
[+ info](https://www.facebook.com/help/www/1076296042409786/?helpref=hc_fnav
)

### Vídeos/fotos 

Las posibilidades que tenemos al subir videos o fotos desde un página aumentan. Veamos algunas de ellas:
* **Crear videos automáticamente con nuestras fotos:** Una de las opciones que nos da el botón “compartir una foto o video” es la de “crear una presentación”, se trata de un pequeño video que crea facebook  simplemente dándole de 3 a 10 fotos.
* **Canvas:** Es una publicación optimizada para teléfonos móviles, donde se muestra a pantalla completa, que puede combinar fotos, textos, enlaces y videos, y permite al usuario “navegar” dentro de ella. [+ info](https://www.facebook.com/business/help/www/183469315334462)

### Video en directo

La gran novedad de facebook en 2016 fue el lanzamiento de “FB live”, una herramienta para transmitir en streaming desde los teléfonos móviles. Para hacerlo solo hay que pulsar el botón “transmitir” desde la aplicación de facebook instalada en el teléfono. 

Los videos en directo son promocionados de una forma importante por facebook, ya que cuando se inician se le envía una notificación a todos los seguidores de la página que estén conectados en ese momento. Por ello es importante preparar cuidadosamente y con antelación estas transmisiones, ya que es frustrante “molestar” a tus seguidores con la notificación de un vídeo en directo, y que cuando entren se corte, sea inaudible, se esté enfocando a otra parte, etc…

Facebook recomienda que la duración de un video en directo sea de al menos cinco minutos, ya que la gente se va incorporando poco a poco. la duración máxima que se permite actualmente es de 90 minutos. 

[+ info](https://www.facebook.com/help/1636872026560015)

### Notas

La función de notas fue totalmente rediseñada a finales de 2015, con el objetivo de facilitar que Facebook pudiera ser usada plataforma de publicación alternativa a los blogs (un poco como el servicio medium pensado para twitter, pero internalizado). 

Las notas ahora presentan una estética muy cuidada (y bastante alejada del resto de lugares de facebook), integran mejor las fotos a modo de cabecera, se destacan aún más del resto de publicaciones y permiten una perfecta integración en otras webs.

[+ info](https://www.facebook.com/help/www/488014787881885)

## Estadísticas 

Una de las grandes ventajas de las páginas es que   nos proporciona un sinfín de estadísticas que pueden ayudarnos a gestionar mejor la forma en que las usamos. Entre los datos más interesantes encontramos:
* Evolución del número de “me gusta” que ha recibido la página
* Cuántos de nuestros seguidores están conectados a cada una de las horas del día (y diferenciando según día de la semana). Estos datos nos ayudarán a decidir cuales son las mejores horas y días para publicar.
* El alcance que ha obtenido cada una de nuestras publicaciones, diferenciando qué número de ellos son seguidores y cuáles no. Además nos indica el número y tipo de reacciones (clicks, me gustas, comentarios) que ha provocado.
* Los datos sociodemográficos (sexo, edad y ciudad) de nuestros seguidores o de las personas a la que han alcanzado nuestras publicaciones.

## Usar Twitter en nuestra estrategia comunicativa

### Conceptos básicos

#### Perfil

A diferencia de lo que veíamos en Facebook, en Twitter no existen diferencias entre personas y organizaciones: todos tenemos un “simple” perfil, que (salvo contadas excepciones) es público a cualquier internauta (aunque no esté registrado en twitter) 
a través de la URL www.twitter.com/nombredeusuario.

Los perfiles tienen pocas opciones de personalización: en todos podemos encontrar   nombre, foto de perfil, cabecera, una breve biografía , número de tuits, número de seguidores y cuentas a las que sigue el usuario, listas y un timeline que recoge todos los tuits publicados por el usuario de manera cronológica.

Para añadir imágenes de perfil y cabecera, igual que veíamos en facebook, es imprescindible saber las medidas de cada una. Tienes toda la información [aquí](https://support.twitter.com/articles/166743)

#### Tuit

Es la única forma que ha tenido siempre twitter para publicar (aunque en el apartado de “nuevas funcionalidades de twitter” veremos algunas novedades). Se trata un simple mensaje de 140 caracteres en los que se puede añadir un enlace o imágenes.

#### Hashtag (HT)

Un hashtag es una etiqueta que se añade a cualquier tuit. Para hacerlo basta con añadir el símbolo # al principio de una palabra o frase (sin espacios ni puntos). Al hacer esto la palabra se convierte en un enlace, que al pulsarlo nos lleva a todos los tuits que hayan usado el mismo HT.

Esta simplísima herramienta es una de las grandes armas de twitter, ya que permite encontrar a “todas las personas del mundo” que están hablando sobre un tema concreto, y unirte a la conversación.

Durante el taller hicimos un pequeño recorrido sobre los diferente usos que se le dan al HT desde las organizaciones participantes. Estas fueron las respuestas:

* Etiquetar los tuits sobre determinada temática para que puedan encontrarlo las personas que buscan información sobre ella, dándole así más repercusión #Ciberacivismo #Transparencia #Pobreza
* “Transmitir” un evento determinado: facilitando así su difusión por la red y  permitir las intervenciones de personas que no han asistido. Para este taller usamos  el HT #DaTacticAND
* Nominar campañas: una tendencia creciente es usar como nombre o slogan de determinadas campañas directamente con un HT, facilitando así las sinergias online-offline #StopDesahucios #WelcomeRefugees #PaguenLoJusto #VíasLegalesYA
* Agrupar tuits para demostrar fuerza, y así aparecer entre los temas más comentados del momento en twitter (TT)
* Reforzar palabras, aprovechan que los HT aparecen en un color diferente al resto del mensaje es habitual usarlo con el único objetivo de dar más fuerza a determinadas palabras o frases #Basta #Nunca #LoHaremos
* Como “dialecto” tuitero: el limitado espacio que ofrece twitter, unido a la necesidad de crear herramientas lingüísticas de cercanía para hablar entre desconocidos, ha creado diversas variaciones lingüísticas exclusivas de esta red basada en gran parte en el uso de HT concretos (#EsBien #MatameCamión) sobre la que ya existen [estudios lingüísticos](https://www.academia.edu/10138878/HOLI_EN_TUITER_HABLAMOS_RARO_UN_BESI_La_variaci%C3%B3n_ling%C3%BC%C3%ADstica_en_Twitter) 

#### Trending Topic (TT)

Los TT son los temas (palabras, o HT) más comentados en twitter en un determinado momento. Los temas son destacados en un espacio propio de la web y es habitual que los medios de comunicación se hagan eco de los temas que han hecho “arder twitter”.

El algoritmo que usa twitter para determinar qué temas llegan a TT no se conoce en su totalidad, aunque si son de sobra conocidos sus aspectos más relevantes:
* Es importante señalar que los TT´s no son las palabras más usadas, sino las que han experimentado un mayor aumento en su uso durante un determinado periodo de tiempo. Por tanto, una palabra muy usada (por ejemplo Madrid) necesitará ser usada infinidad de veces más para llegar a ser TT que una que no se haya usado nunca (por ejemplo #Vamos28F). Este es el motivo por el que cuando se planea alcanzar un TT se pone una hora de inicio,asegurando que nadie la use anteriormente. 
* No solo es importante el número de tuits, también se contabilizan los Retuits 
* El número de seguidores que tienen las cuentas que usan la palabra también tiene una influencia decisiva.

#### Mensaje directo (MD)

Los mensajes directos son la forma con la que establecer un contacto privado entre usuarios. Su funcionamiento es similar a un chat, en el que también se pueden crear pequeños grupos.

Los usos más habituales en movimientos sociales son:
* Como forma de organización de los tuiteros de la organización (este es el único uso que le daban las organizaciones asistentes al taller). Se crea un grupo con los miembros de confianza y desde allí se coordina su actividad
* Para recibir mensajes y preguntas de personas interesadas. Aunque la configuración estándar limita la recepción de MD a personas a las que sigues, es posible reconfigurarla para aceptar MD de cualquier usuario de Twitter. Las cuentas que tiene esta configuración aparecen destacadas en el buscador con la etiqueta “proporciona asistencia”, pudiéndose configurar también un horario de asistencia (que aparecerá en tu perfil)
* Para enviar mensajes masivos a tus seguidores: Dado a fugacidad que tienen los tuits, es posible que queramos dar a determinados en determinado mensaje una difusión mayor, enviándolo a todos nuestros seguidores. Esto puede hacerse de manera manual, aunque habitualmente se usan herramientas externas que automatizan esta tediosa tarea, como por ejemplo http://botize.com/

#### Me gusta

Al igual que en Facebook, en Twitter también es posible dar a “me gusta” a los mensajes de otros usuarios. Esta acción puede usarse de forma literal (para marcar que te gusta un comentario), aunque también es usada habitualmente como forma de “guardar” determinados tuits, ya que todos tus “me gustas” se guardan (y son públicos). Esta segunda función se ha potenciado con la aparición de la funcionalidad “momentos”, que veremos en el siguiente apartado 

#### Mención

La mención es la forma de nombrar a cualquier usuario (lo estemos siguiendo o no). Para hacerlo basta con escribir su nombre con la @ delante(v.g. @OxfamIntermon). Cuando te nombran en twitter, te llega una notificación.  

Esta funcionalidad suele usarse para responder a un usuario y/o conversar con él (a través del botón reply). Aunque hay que advertir que haciendo este uso (que hace aparecer el nombre del usuario al principio del tuit de respuesta), provoca que el hilo de la conversación solo le aparezca a las personas que siguen ambas cuentas. Es por ello que es habitual añadir un punto (“.”) al comienzo del tuit, haciendo así que se visible para todos tus seguidores. (.@OxfamIntermon)

### Gestionar una cuenta colectiva

#### Gestionar permisos (Tweetdeck)

Uno de los problemas de gestionar una cuenta colectiva de Twitter, es que no se pueden asignar permisos y roles de gestión de forma directa (del modo que veíamos en Facebook), lo que obligaría a compartir la contraseña de nuestra cuenta con todas las personas que quieran colaborar en ella, con los consiguientes problemas de seguridad.
Para solucionar este problema existe una herramienta oficial de twitter https://tweetdeck.twitter.com/ que permite asignar permisos de publicación en nuestra cuenta  sin necesidad de proporcionar la contraseña.

El gran déficit de Tweetdeck es que todavía no tiene una aplicación oficial para teléfonos móviles, limitando así sus posibilidades de uso.

#### Listas

Esta funcionalidad permite crear grupos personalizados de usuarios a los que queremos hacer un especial seguimiento. Esta funcionalidad es de gran utilidad para cuentas colectivas, ya que permiten “monitorizar” la actividad en twitter de determinadas cuentas y poder actuar sobre ellas.

Los usos de estas listas pueden ser muy variados: pueden hacerse listas de “miembros de mi organización” o “colectivos cercanos” que me ayuden a difundir sus contenidos; o bien listas del tipo “diputados que votaron aquella cosa tan chunga”, para  buscar oportunidades de confrontar en el campo de las ideas. 

#### Destacados

Una de las pocas formas que tenemos de personalizar nuestro timeliner es destacando un tuit concreto. Este tuit destacado aparecerá en la parte superior hasta que destaquemos otro (o le quitemos la categoría de destacado).

### Nuevas funcionalidades de twitter

#### Momentos

"Momentos" ha sido la gran novedad de Twitter en 2017. Es una funcionalidad que permite agrupar diferentes tuits (propios y ajenos) y presentarlos con un diseño algo más cuidado de lo que Twitter nos tiene acostumbrados (puedes añadir una portada, un título y una breve descripción).

Para este taller [creamos un “momento”](https://twitter.com/i/moments/827156471259480064)  en el que agrupamos algunos de los tuits que se hicieron durante el mismo. 

Tienes toda la información sobre cómo crear y configurar los momentos [aquí](https://support.twitter.com/articles/20174549?lang=es)


#### Gifs

El botón “gifs” fue una de las principales novedades de twitter en 2016. Se trata de un botón que aparece en la caja de publicación y que facilita la navegación por la web http://giphy.com/ para buscar un gif concreto e integrarlo en nuestro tuit.

#### Encuestas

Las encuestas fueron la novedad de Twitter en 2015.  Se trata un botón que aparece en la caja de publicación y que abre un pequeño menú con la que crear una encuesta con las siguientes características: 

* Puedes usar hasta 140 caracteres en la pregunta de la encuesta.
* La encuesta puede tener hasta cuatro opciones. Puedes usar hasta 25 caracteres para cada opción.
* La cantidad mínima de tiempo para una encuesta es de cinco minutos y la máxima es de siete días.
[+ info](https://support.twitter.com/articles/20174534?lang=es)

### Herramientas de automatización

Una práctica cada vez más habitual entre las organizaciones es la de automatizar ciertas funciones de Twitter. Algunas de las más habituales son:

#### Programar tuits con Twitdeck 

La automatización más básica es la “programación” de tuits, de esta manera podemos idear decenas de tuits para una campaña y programar que vayan publicándose durante un periodo determinado.

Esta función puede hacerse directamente desde la palicación oficial de Twitter [Twitdeck ](https://tweetdeck.twitter.com/)
 
#### Automatización avanzada con IFTT

[IFTT](https://ifttt.com/discover) iniciales de If This, Then That (Si ocurre esto, Haz esto otro) es una completa herramienta de automatización, no solo para Twitter, sino para prácticamente cualquier servicio de internet. 

Su uso es bastante intuitivo, y la función para la que se suele usar en Twitter es la automatizar publicaciones recurrentes (al estilo Twitdeck), usando recetas del tipo “si es martes y son las 12:00, haz este tuit”. 

Pero IFTT permite otro tipo de automatizaciones interesantes en twitter, como por ejemplo publicar automáticamente nuevas noticias de una web determinada: “si está web publica una nueva noticia, tuiteala con este mensaje, o incluso “Si este medio de comunicación publica alguna noticia en cuyo título esté esta palabra, tuiteala”.

### Analítica 

Twitter ofrece también una analitica bastante completa de nuestra actividad. Las estadísticas de  una cuenta pueden consultarse accediendo a [https://analytics.twitter.com/](https://analytics.twitter.com/)

Entre los datos disponibles están:
* El número de impresiones e interacciones de cada uno de nuestros tuits
* La evolución de nuestra comunidad
* Los intereses de nuestros seguidores
* El sexo y el operador telefónico de nuestros seguidores

## Organizando una campaña en las redes sociales

### Los 11 pasos para desarrollar una campaña

* Elige objetivos
* Mide fuerzas
* Busca aliados
* Prioriza públicos
* Selecciona los canales
* Elige tu narrativa (Storytelling)
* Construye las herramientas adecuadas
* Planifica tu campaña
* Reparte tareas
* Actúa
* Evalúa los resultados

### Los pads como herramienta de coordinación

Para desarrollar las prácticas en grupo usamos como herramienta de coordinación http://titanpad.com , una herramienta para elaborar documentos colaborativos que tiene las siguientes ventajas:

* No hace falta registrarse ni instalar nada para empezar a trabajar. Se crea el documento, se envía el link y cualquiera al que le llegue el enlace puede empezar a editar.
* Permite la edición de varias personas en tiempo real, diferenciando por colores quien ha realizado cada edición
* Guarda cada una de las versiones del documento, por lo que si se borra algo por accidente se puede recuperar en cualquier momento.
* A pesar de ser un documento público en la web, es muy difícil que cualquier “intruso” se cuele en nuestro pad, ya que este no está indexado en buscadores, por lo que tendría que conocer la dirección exacta.
* Incorpora un chat para que las personas que están editando el documento puedan hablar.
* Ofrece la opción de importar o exportar varios formatos: Word, ODT, PDF, texto plano, web.

### Prácticas en grupo

Como final del taller se hizo una práctica, dividiendo a los asistentes en tres grupos. Estos fueron los resultados

* [La pobreza perjudica seriamente la -tu- salud.](https://titanpad.com/DatacticAND3)

* [Conseguir una Sevilla más verde y más fresca](https://titanpad.com/DatacticAND1)

* [Prevenir la construcción de estereotipos asociados a la población gitana.](https://titanpad.com/DatacticAND2)

## Bibliografía

Además de las diferentes fuentes específicas que hemos ido señalando en cada sección, para la elaboración general de este kit nos ha sido de gran ayuda 

* [Radical community manager](https://nocionescomunes.wordpress.com/2011/10/10/radical-community-manager-breves-nociones-para-aprender-a-comunicarse-organizarse-y-luchar-en-las-redes-2-0/)

* [Tecnopolítica, internet y R- Evoluciones](http://www.icariaeditorial.com/pdf_libros/Tecnopolitica,%20internet%20y%20r-evoluciones.pdf/)


* [Manual de comunicación para organizaciones sociales](http://antezanacc.com/docs/Manual_de_comunicacion_para_organizaciones_sociales.pdf)

* [Comunicación Online y Redes Sociales en tu ONG]( http://www.winguweb.org/sitio2012/wp-content/uploads/2014/05/ComunicacionOnlineentuONG.pdf) 

* [Nonprofits on Facebook](https://nonprofits.fb.com/) (en ingles)


