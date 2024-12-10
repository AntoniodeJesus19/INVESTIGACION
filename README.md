# INVESTIGACION
Tarjeta de Adquisición de Datos, HMI, Sensores.
## CONTENIDO
- Tarjeta de Adquisición de Datos
- HMI
- Sensores y Tipos de Sensores
- Acondicionador de Señal
- bibliografia


## TARJETA DE ADQUISICIÓN DE DATOS
Las tarjetas de adquisición de datos son dispositivos diseñados para la adquisición y medición de señales que consiste en la toma de muestras de variables físicas del mundo real (sistema analógico por lo general), para generar datos que pueden ser manipulados por un programa diseñado en un ordenador. El dispositivo de adquisición de datos o USB-6009 es un dispositivo de bajo costo ideal para realizar mediciones de entradas analógicas (ocho canales) y con funcionalidad para generar niveles de voltaje de salida (dos canales), dispone de un contador y dos puertos con 8 líneas de entradas y salidas digitales. Esta funcionalidad se puede realizar simultáneamente para solucionar aplicaciones que van desde registros de datos, adquisición analógica con alarmas, conteo de eventos, hasta control de lazo cerrado. Al usar la interfaz de programación LabVIEW se puede lograr desarrollar este tipo de aplicaciones de manera más sencilla y además permite la flexibilidad de expandir la funcionalidad (Francisco J. Enríquez, 2016).

Las tarjetas de adquisición de datos (hardware) actúan como la interfaz entre una computadora y señales físicas, es decir, la información recaudada por el sensor se pasa al DAQ, el cual se encarga de transformar los códigos del mundo real a los códigos digitales, como si se tratara de un intérprete que traduce de un lenguaje a otro, con el fin de que el sistema digital (es decir, cualquier computadora o dispositivo electrónico) sea capaz de comprender los signos del analógico. Las tarjetas de adquisición de datos consisten en tres partes principales: por un lado está el circuito de acondicionamiento de señales, después está el convertidor analógico-digital (ADC por sus siglas en inglés) y, finalmente, el bus del ordenador. (JMIndustrial, s.f.)


## HMI
Un sistema HMI es una interfaz de usuario o panel de control que conecta a una persona con una máquina, sistema o dispositivo. Aunque el término puede aplicarse técnicamente a cualquier pantalla que permita al usuario interactuar con un dispositivo, la HMI se utiliza más comúnmente en el contexto de los procesos industriales que controlan y monitorean máquinas de producción.

Por otro lado, HMI es la abreviatura de Human Machine Interface. De igual manera, entre profesionales se suele emplear su traducción al castellano Interfaz Humano-Máquina para denominar a este tipo de paneles de operador.

Un ejemplo común es el de un cajero automático que todos utilizamos en la vida cotidiana. En este caso, la pantalla y los botones pulsadores le permiten a la máquina dispensar billetes, ingresar dinero, entre otras operaciones.

Los sistemas de interfaz humano-máquina (HMI) permiten operaciones confiables de tecnología en cada aplicación, incluyendo trenes de alta velocidad, centros de mecanizado CNC, equipos de producción de semiconductores y equipos médicos de diagnóstico o laboratorio.

En resumen, la interfaz HMI abarca todos los elementos que una persona tocará, verá, escuchará o utilizará para realizar funciones de control y recibir respuesta sobre esas acciones.

Así pues, un operario o personal de mantenimiento puede controlar o monitorear la maquinaria desde la HMI, puede incluir información como temperatura, presión, pasos de proceso productivo, cálculo de materiales necesarios, posiciones exactas de las líneas de producción, control de los niveles de los tanques con materias primas entre otras muchas más funciones.

Además, estos paneles de control pueden conectarse a los PLC y mostrar su comportamiento para resolver problemas a los técnicos de mantenimiento, lo que supone un ahorro muy valioso (Industria, s.f.).


## ELEMENTOS DE UN SISTEMA DE ADQUISICIÓN
Cuando hablamos de adquisición de datos, comúnmente abreviado como DAQ o DAS, nos referimos al proceso de realizar mediciones de fenómenos físicos y registrarlos de alguna manera para analizarlos.
En general, se acepta que la adquisición de datos es distinta de las formas anteriores de grabación en cinta o gráficos de papel.
A diferencia de esos métodos, las señales se convierten del dominio analógico al dominio digital y luego se graban en un medio digital como ROM, medios flash o unidades de disco duro.
Los sistemas modernos de adquisición de datos digitales constan de cuatro componentes esenciales que forman toda la cadena de medición de los fenómenos físicos:
-Sensores
-Acondicionamiento de Señal
-Convertidores Analógico-Digital
-Computadora con software DAQ para registro y análisis de señales (Smith, 2024)

![](https://github.com/AntoniodeJesus19/INVESTIGACION/blob/main/Captura%20de%20pantalla%202024-12-07%20002041.png?raw=true)

## SENSORES Y TIPOS DE SENSORES
Los sensores son herramientas que detectan y responden a algún tipo de información del entorno físico.     
Existe una amplia gama de sensores utilizados en la vida diaria, que se clasifican según las cantidades y características que detectan.

Algunos ejemplos incluyen sensores de corriente eléctrica, magnéticos o de radio, sensores de humedad, sensores de velocidad o flujo de fluidos, sensores de presión, sensores térmicos o de temperatura, sensores ópticos, sensores de posición, sensores ambientales y sensores químicos (NIH, 2022).

La medición de un fenómeno físico, como la temperatura, el nivel de una fuente de sonido o la vibración que se produce por el movimiento constante, comienza con un sensor. Un sensor también se llama transductor. Un sensor convierte un fenómeno físico en una señal eléctrica medible.

Los sensores se utilizan en nuestra vida diaria. Por ejemplo, el termómetro de mercurio común es un tipo de sensor muy antiguo que se usa para medir la temperatura. Al usar mercurio coloreado en un tubo cerrado, se basa en el hecho de que este químico tiene una reacción constante y lineal a los cambios de temperatura. Al marcar el tubo con valores de temperatura, podemos mirar el termómetro y ver cuál es la temperatura con precisión limitada. Por supuesto, no hay otra salida analógica que la visual. Este tipo de termómetro primitivo, aunque es útil en el horno o fuera de la ventana de la cocina, no es particularmente útil para aplicaciones de adquisición de datos.

Por eso se han inventado otros tipos de sensores para medir temperaturas, como termopares, termistores, RTD (Detectores de temperatura de resistencia) e incluso detectores de temperatura por infrarrojos. Millones de estos sensores funcionan todos los días en todo tipo de aplicaciones, desde la temperatura del motor que se muestra en el tablero de nuestro automóvil, hasta las temperaturas medidas en la fabricación farmacéutica. Prácticamente todas las industrias utilizan la medición de temperatura de alguna manera.

Sensores de temperatura: termopar, termistores, sensor RTD.
Por supuesto, hay muchos otros tipos de sensores que se han inventado para medir otro fenómeno físico:
Celdas de carga: para medir peso y carga
Sensores LVDT: los LVDT se utilizan para medir el desplazamiento en la distancia
Acelerómetros: medición de vibraciones y golpes
Micrófonos: para medir el sonido,
Medidores de deformación: para medir la deformación de un objeto, p. Ej. medir fuerza, presión, tensión, peso, etc.,
Transductores de corriente: para medir corriente CA o CC (Smith, 2024).


## ACONDICIONADOR DE SEÑAL
El objetivo del acondicionador de señal es generar, a partir de lo obtenido por los sensores, una señal que sea aceptable por las tarjetas de adquisición de datos. Las tarjetas de adquisición de datos suelen admitir niveles de tensión que van entre unos márgenes determinados: -10V a 10V, 0 a 10V, 0 a 5V, etc., ... Las funciones principales que va a tener que realizar el acondicionador de señal son las siguientes: 

- Transformación 
- Amplificación 
- Conversión por medio de optoacopladores 
- Filtrado 
- Excitación 
- Linealización
   
- Transformación: Los sensores pueden proporcionar una diferencia de potencial, o una variable de intensidad. Normalmente las tarjetas de adquisición de datos admiten diferencias de potencial, por lo que si el sensor proporciona una variación de intensidad, esta debe ser convertida en una diferencia de potencial proporcional.
  
- Amplificación: La señal proporcionada por los sensores suele ser de un valor muy pequeño, por lo que debe ser amplificada con el fin de que pueda ser detectada correctamente por la tarjeta de adquisición de datos. La amplificación debe ser tal que las variaciones de la señal recorran todo el margen de la tarjeta de adquisición de datos. La amplificación de las señales, en su origen, reduce el ruido que les puede afectar en su transmisión hasta el computador.
  
- Conversión por medio de optoacopladores: Consiste en la conversión de una señal eléctrica en una señal óptica, de luz. El principal objetivo de esta conversión consiste en aislar los sistemas eléctricos de los sensores de los sistemas eléctricos de la tarjeta de adquisición para que de esta forma, se evite tener que usar masas comunes, que en algunos casos producen problemas de derivación de corrientes. Conviene que los sensores de calidad realicen esta conversión por medio de optoacopladores.
  
- Filtrado: Con el filtrado se pretende eliminar ruidos de alta frecuencia que pueden hacer perder exactitud al sistema de adquisición de datos. Lo ideal es transportar la señal del sensor lo más limpia posible a la tarjeta de adquisición.
  
- Excitación: Hay muchos sensores que necesitan de una excitación, bien en corriente, bien en tensión, para producir la variación proporcional a la magnitud a medir.
  
- Linealización: No todos los sensores tienen una variación lineal con respecto a las variaciones de la magnitud que se miden; a veces es necesario realizar unos cálculos para convertir la respuesta del sensor en lineal (rua).

## Bibliografía
Francisco J. Enríquez, E. S. (2016). Sistema Embebido para Validar el Funcionamiento de la Tarjeta de Adquisición de Datos USB-6009 de National Instruments. Scielo.

Industria, C. d. (s.f.). aula21. Obtenido de https://www.cursosaula21.com/que-es-un-hmi/#:~:text=Un%20ejemplo%20com%C3%BAn%20es%20el,supone%20un%20ahorro%20muy%20valioso.

JMIndustrial. (s.f.). Obtenido de https://www.jmi.com.mx/tarjetas-de-adquisicion-de-datos/#:~:text=Las%20tarjetas%20de%20adquisici%C3%B3n%20de%20datos%20(hardware)%20act%C3%BAan%20como%20la,int%C3%A9rprete%20que%20traduce%20de%20un

NIH. (04 de 2022). Obtenido de https://www.nibib.nih.gov/espanol/temas-cientificos/sensores#:~:text=la%20atenci%C3%B3n%20m%C3%A9dica%3F-,%C2%BFQu%C3%A9%20son%20los%20sensores%3F,cantidades%20y%20caracter%C3%ADsticas%20que%20detectan

rua. (s.f.). Obtenido de https://rua.ua.es/dspace/bitstream/10045/19119/1/Sistemas%20de%20adquisici%C3%B3n%20y%20Procesamiento%20de%20datos.pdf

Smith, G. M. (05 de 02 de 2024). dewesoft. Obtenido de https://dewesoft.com/es/blog/que-es-adquisicion-de-datos


### Elaborado por:
Antonio de Jesús Mentado Huerta
[Github](https://github.com/AntoniodeJesus19)
