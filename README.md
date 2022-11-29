# Proyecto-Primer-Parcial
Integrantes:
- Alomoto Pilamunga Oscar Alexander
- Ordóñez Quiroz Fernando Gabriel
- Pilataxi Constante Luis Jairo

# LED NOCTURNO AUTOMÁTICO

## 1. OBJETIVOS

***General***

*- Conocer las principales características de un led nocturno automático, con la ayuda de la ingenieria inversa para conocer caracteristicas, funcionamiento  y que aporta cada elemento usado para el correcto funcionamiento del circuito.*

***Especificos***

*- Analizar las propiedades, funciones y operaciones que realiza cada componte usado para armar el circuito.*

*- Comparar dicho proyecto con otros sitemas mecatrónicos parecidos.*

*- Determinar los difrentes usos de este proyecto a mayor escala.*

## 2. MARCO TEÓRICO

***COMPONENTES***

![image](https://user-images.githubusercontent.com/104925648/204429031-61807b92-9371-434d-a160-59de2d740bd8.png)

![image](https://user-images.githubusercontent.com/104925648/204429089-e5b9f609-6f53-4935-9f86-b957d73d1aae.png)

***INGENIERÍA INVERSA***

![Esquema Mapa Conceptual Doodle Multicolor](https://user-images.githubusercontent.com/116774906/204401919-aa56e4f7-b145-453e-b05d-bdcaa7369a73.png)

***INGENIERÍA INVERSA PRESENTE EN EL CIRCUITO***

![image](https://user-images.githubusercontent.com/116705680/204545196-19ece777-cf5a-4bb5-992d-0301ac051b62.png)

## 3. EXPLICACIÓN DEL PROCEDIMIENTO

***CIRCUITO ARMADO***

![1](https://user-images.githubusercontent.com/116774906/204432646-084ceb57-db4e-4525-9180-a1be6c119993.jpg)

***CIRCUITO FUNCIONANDO***

![2](https://user-images.githubusercontent.com/116774906/204432694-a51a9332-3bf8-4cf4-9300-369c2c491553.jpg)

***PROCEDIMIENTO DE LA INGENIERÍA INVERSA***

*1. Colocamos nuestro protoboard que es el instrumento que nos permite probar un diseño del circuito sin la necesidad de soldar componentes, y los componentes forman un circuito temporal.*

*2. Ubicamos el transistor en el protoboard que es el elemento semiconductor que permite el paso de una señal en respuesta a otra. Este se compone de un colector, base y emisor.*

*3. Conectamos los diodos LED en serie al emisor del transistor que es la terminal por el cual salen los portadores de carga.*

*4. Se conecta la resistencia de 10k ohm en serie, esto se lo hace para que haya un ajuste máximo en el brillo de los diodos LED, que dicho brillo es independiente a cada diodo.*

*5. Seguimos en serie la conexión de la resistencia de 10k ohm hasta conectarlo al potenciómetro, que es similar a las resistencias, pero lo que es diferente es su valor de resistencia que en vez de ser fijo es variable, permitiendo controlar la intensidad de corriente a lo largo de un circuito conectándolo en paralelo o la caída de tensión al conectarlo en serie.*

*6. Este potenciómetro se compone de terminales, Terminal fija, Terminal Variable, Terminal fija. La resistencia de 10k ohm se la coloca en serie a la primera terminal fija del potenciómetro.*

*7. Realizamos una conexión por medio de un alambre conductor desde la terminal variable del potenciómetro hasta la terminal base del transistor. Esto nos permitirá controlar la intensidad de corriente que se dirige hacia los diodos.*

*8. En cuanto a la fotorresistencia que es una resistencia que varía en función de la luz que incide sobre su superficie, cuanto mayor sea la intensidad de la luz menor será su resistencia y cuanta menos luz incida mayor será su resistencia, la conectamos su terminal positiva al terminal colector del transistor y su terminal negativa a la terminal negativa del protoboard.*

*9. Finalmente conectamos la batería de 9V al circuito, esta será nuestra fuente de voltaje que ayudara a que el circuito funcione adecuadamente, los terminales de la batería van conectados de la siguiente manera, polo positivo de la batería al polo positivo del protoboard y así mismo con el polo negativo.*

## 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

***1.- ¿Cuál es la importancia de usar la Ingeniería Inversa?***

Este proceso de ingeniería inversa conlleva una serie de beneficios respecto al proceso tradicional de creación y modificación de piezas:
      
- Permite modificar características de la pieza original de forma digital, mejorando su funcionalidad sobre todo sin perder la base de la propia pieza.
        
- Permite que la creación de nuevas piezas sea un proceso más sencillo, al haber podido extraer toda la información sobre la pieza actual.
      
![image](https://user-images.githubusercontent.com/104925648/204437046-10e24a87-6b90-4a18-af04-e8c856996f5c.png)

- 2.- ¿El potenciómetro es una resistencia variable?

El potenciómetro (también conocido como pot) es un dispositivo electrónico con un valor de resistencia variable y generalmente ajustable manualmente que se puede usar para medir posición angular. Los potenciómetros tienen tres terminales y se suelen utilizar en circuitos de corriente baja, para circuitos de mayor corriente se utilizan los reóstatos. En muchos dispositivos eléctricos los potenciómetros son los que establecen el nivel de salida. Por ejemplo, en un altavoz, el potenciómetro ajusta el volumen; en un televisor o un monitor de ordenador se puede utilizar para controlar el brillo.

- 3.- ¿Cuáles con las ventajas de un circuito en serie?

La mayor ventaja de un circuito en serie es que puede agregar dispositivos de potencia adicionales, generalmente con baterías. 
Los circuitos en serie son fáciles de aprender y de hacer. Su diseño simple es fácil de entender, y esto significa que es simple realizar reparaciones sin la ayuda de un profesional. Esto también te ayudará a calcular el voltaje de tu circuito fácilmente.
Los circuitos de la serie tampoco se sobrecalientan fácilmente. Esto los hace muy útiles en el caso de algo que podría estar cerca de una fuente potencialmente inflamable, como plantas secas o tela. Esta ventaja es también una de las principales razones por las que los circuitos en serie se usan con luces navideñas. 

- 4.- ¿Cómo funciona la fotorresistencia?

La base del funcionamiento de una fotorresistencia radica en su componente principal, el sulfuro de cadmio (CdS). Este componente químico es un semiconductor que tiene la capacidad de variar su resistencia según la cantidad de luz que en él incida.

- 5.- ¿Cuáles son las aplicaciones del transistor NPN 2N3904?

los Aplicaciones del transistor NPN 2N3904 Incluya lo siguiente.

- Este transistor se utiliza en módulos de controlador como controlador de LED, controlador de relé, etc.
- Se utiliza en módulos amplificadores como amplificador de señal, amplificador de audio, etc.
- Los voltajes como VBE y VCB son altos, por lo que se pueden usar para controlar cargas de voltaje de hasta 40 V.
- Por lo general, se usa en televisores y otros electrodomésticos.
- Cuando funciona como un interruptor, controla cargas pesadas debido a la alta ganancia y al menor voltaje de saturación.
- Este transistor también se puede utilizar en aplicaciones de conmutación rápida como PWM (modulación de ancho de pulso) debido a su rápida velocidad de conmutación.
- Se utiliza en amplificadores de sonido, ya que incluye una alta ganancia de corriente, por lo que se utiliza como amplificador.

## 5. VIDEO

*LINK DEL VIDEO*

## 6. CONCLUSIONES

*-Se pudo analizar las propiedades, funciones y operaciones que realiza cada componente al momento de armar el circuito, y se pudo deducir la importancia que tenía cada elemento y el rol que cumplía cada uno, así mismo bajo el mismo principio de análisis, cuando el componente no cumpla con las características indicadas o no funcione se lo puede mejorar, ya sea modificándolo o reemplazándolo por un elemento mejor, que cumpla con los requerimientos y especificaciones del circuito.*

*-Una comparación muy importante relacionado a nuestro proyecto, lo encontramos en el alumbrado público, ya que se basa en el mismo principio de nuestro proyecto, ya que, si nosotros evitamos que ingrese luz por la fotorresistencia, los diodos LEDS se encenderán. El alumbrado público en el día cuando la luz del sol está presente, mantiene sus focos apagados, hasta que oscurezca y la luz sea mínima ahí puede encender las bombillas o focos de luz.* 

*- Este proyecto se lo puede usar a mayor escala en la automatización y dogmática de casas o de centros comerciales, que buscan principalmente el ahorro de energía eléctrica, mediante circuitos automatizados que cumplan los mismos funcionamientos que se presentó en el proyecto.*

## 7. BIBLIOGRAFÍA

- Floyd, T. L. (2007). Principios de circuitos electricos. (8.a ed.). México. Pearson Educación
- Xtrategics. (s/f). Beneficios, utilidad y características de la ingeniería inver. Beneficios, utilidad y características de la ingeniería inver. Recuperado el 29 de noviembre de 2022, de https://www.dibtec3d.com/actualidad/usos-y-beneficios-de-la-ingeniera-inversa/
- Latam, M. (2020, February 21). Potenciómetro. Mecatrónica LATAM. https://www.mecatronicalatam.com/es/tutoriales/electronica/componentes-electronicos/potenciometro/
- 3 ventajas de un circuito de serie. (n.d.). nrelectricidad - Información de mejoras para el hogar. Retrieved November 29, 2022, from https://es.nrelectricidad.com/articles/electrical-electronics/wiring-projects/3-advantages-of-a-series-circuit.html
- R., J. L. (2017, November 24). FOTORRESISTENCIA (LDR). ComoFunciona | Explicaremos hasta cosas que NO existen!; ComoFunciona. https://como-funciona.co/una-fotorresistencia/
- (N.d.). Electrositio.com. Retrieved November 29, 2022, from https://electrositio.com/transistor-npn-2n3904-configuracion-de-pines-y-sus-aplicaciones/








