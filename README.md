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

***COMPONENETES***

![image](https://user-images.githubusercontent.com/104925648/204429031-61807b92-9371-434d-a160-59de2d740bd8.png)

![image](https://user-images.githubusercontent.com/104925648/204429089-e5b9f609-6f53-4935-9f86-b957d73d1aae.png)

***INGENIERÍA INVERSA***

![Esquema Mapa Conceptual Doodle Multicolor](https://user-images.githubusercontent.com/116774906/204401919-aa56e4f7-b145-453e-b05d-bdcaa7369a73.png)

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
- 3.- ¿Porqué se usan en mayor cantidad circuitos en serie?
- 4.- ¿Cómo funciona la fotoresistencia?
- 5.- ¿Cuáles son las aplicaciones del transistor NPN 2N3904?

## 5. VIDEO

Link del video en YouTube:


## 6. CONCLUSIONES

*-Con la realizacion del proyecto se pudo analizar y comprender de gran medida las propiedades, funciones y operaciones de cada elemento que compone el circuito que presentamos, cada componente tiene un rol muy importante en el buen desempeño del circuito, y mediante esos analisis se pudo deducir si algun elemento no funciona o no corresponde con las caractetisticas que se dispone, y asi poder cambiar o mejorar el elemento para que funcione de la manera correcta.*

*-Se pudo encontrar que este proyecto a verdad de ser  muy simple, es muy empleado en la automatizacion y dogmotica de casas, ya que con multiples sensores, conexiones y focos se puede replicar exactamente el proyecto expuesto, ya que se usan otros elementos pero que basicamente cumplen la misma funcion, y claro esta su desempeño y rango es mucho mejor a los que nosotros dispusimos para armar nuestro circuito.* 

*-Se determino que el uso que se le dio a este proyecto a una escala mucho mayor se ve reflejado en el alumbrado publico, ya que nuestro proyecto si tapamos la fotoresistencia (evitar el ingreso de luz) el led se encendia, este principio usa el alumbrado publico, que en las mañanas cuando hay mucha luz los focos se mantienen apagados, pero cuando llega la noche o hay poca luz, las luces se encienden.*

## 7. BIBLIOGRAFÍA

- Floyd, T. L. (2007). Principios de circuitos electricos. (8.a ed.). México. Pearson Educación
- Xtrategics. (s/f). Beneficios, utilidad y características de la ingeniería inver. Beneficios, utilidad y características de la ingeniería inver. Recuperado el 29 de noviembre de 2022, de https://www.dibtec3d.com/actualidad/usos-y-beneficios-de-la-ingeniera-inversa/



