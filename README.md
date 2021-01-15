# Laboratorio 3
1. OBJETIVOS
- Objetivo General:
   
   - Comprender el método de superposición para analizar circuitos y declarar cada aporte de la fuente independiente.
   
- Objetivos Específicos:
 
   - Utilizar el método de superposición en el circuito descrito para observar como cada fuente tiene su propia corriente y se suma con la otra.
   - Verificar que al analizar el circuito haciendo corto una fuente, y luego haciendo corto la otra, al sumarse se obtiene la corriente Ix.
   - Verificar que al analizar el circuito haciendo corto una fuente, y luego haciendo corto la otra, al sumarse se obtiene el voltaje Va.
   
2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/75439689/104661918-a26c7780-5697-11eb-81ee-3b699ec3a20c.png)

3. DIAGRAMAS

 - Modelo del Circuito
    
  ![image](https://user-images.githubusercontent.com/75439689/104652571-4c8fd380-5687-11eb-8394-6e6009093cf3.png)
  
  *Figura 3.1*
  
   - Circuito Simulado
   
   ![image](https://user-images.githubusercontent.com/75439689/104652607-574a6880-5687-11eb-8320-058ee7ef98fe.png)
   
   *Figura 3.2*

   - Amperímetro y Voltímetro conectados
   
   ![image](https://user-images.githubusercontent.com/75439689/104652699-852fad00-5687-11eb-8bb8-5ab4133e0e9f.png)
   
   *Figura 3.3*
   
   - Amperímetro y Voltímetro conectados, con la fuente de 12v en corto
   
   ![image](https://user-images.githubusercontent.com/75439689/104652765-9f698b00-5687-11eb-9b6f-9a86e35e6904.png)
   
   *Figrua 3.4*
   
   - Amperímetro y Voltímetro conectados, con la fuente de 20v en corto
   
   ![image](https://user-images.githubusercontent.com/75439689/104652798-a85a5c80-5687-11eb-8762-1c5289e499a6.png)
   
   *Figura 3.5*
   
4. LISTA DE COMPONENTES
   
![image](https://user-images.githubusercontent.com/75439689/104658443-ca0c1180-5690-11eb-9258-a51448fed16d.png)

*Figura 4.1*

5. EXPLICACIÓN

 5.1. Procedimiento

   - Ingresar a la plataforma *Tinkercad* y crear un nuevo circuito, en el cual se escogen los componentes listados anteriormente.
   - Conectar el primer suministro de energía de 20 voltios a un extremo de la placa de pruebas (*protoboard*) uniendo respectivamente los polos positivos y negativos deL suministro y la placa; y de la misma manera, se conecta la otra fuente de voltaje de 12 voltios pero al otro extremo de la placa.
   - A continuación se conecta en escalera las cuatro resistencias (cada una de ellas tiene diferente resistencia).
   - Para finalizar la creación del circuito planteado, se conecta los suministros de energía a cada lado del circuito en escalera con sus respectivas terminales, generándose así un circuito de tres mallas: la primera malla consta de la fuente de 20 voltios y dos resistencias (de 1 y 2.2 kOhmios); la segundda malla se compone de tres esistencias (de 2.2, 0.82 y 0.47 kOmhios); y por último la tercera malla compuesta por la resistencia de 0.47 kOmhios y la fuente de 12 voltios.
 

 5.2. Análisis de Superposición
      
   - 5.2.1. Voltaje de Va y Corriente de Ix
      
   Para el análisis del voltaje Va y la corriente Ix, se colocó: un voltímetro en la resistencia de 820 Ω en paralelo, y un amperímetro se conectó en serie a la resistencia de 470 Ω, los resultados fueron anotados en la tabla 5-1 y la tabla 5-2; además se calcularon manualmente los resultados del voltaje Va y la corriente Ix; como se puede observar los resultados varian en una proporción muy pequeña pero aun así estos son diferentes.
   
   - 5.2.2. Voltaje de Va y Corriente de Ix cuando fuente de 12v es cero
   
   En la primera parte para la superposición se volvió a la fuente de 12v como una resistencia de 0 Ω, cambiando así el resultado del voltímetro de Va y del amperímetro de Ix, como se puede notar en las tablas 5-1 y 5-2. 
   
   - 5.2.3. Voltaje de Va y Corriente de Ix cuando fuente de 20v es cero
   
   Para la última parte del análisis del laboratorio se muestra que la fuente de 20v se convierte en una resistencia de 0 Ω, por lo que el circuito se analiza sin esta fuente de voltaje, en el simulador el voltímetro tiene un resultado negativo ya que este está conectado al contrario de la polaridad dada, los resultados fueron anotados en las tablas 5-1 y 5-2.
   
   ![image](https://user-images.githubusercontent.com/75439689/104662290-81585680-5698-11eb-9fca-9b22162f64e5.png)
   
   *Tabla 5-1*
   
   ![image](https://user-images.githubusercontent.com/75439689/104662305-8ddcaf00-5698-11eb-927a-27f801871eab.png)
   
   *Tabla 5-2*
   
   - 5.2.4. Análisis de Resultados y Comparaciones
   
   Como se puede observar en las tablas 5-1 y 5-2 el método de superposición se cumple ya que al sumar los voltajes Va dados por cada fuente de manera independiente de la otra, se obtiene el resultado de la primera medición del voltímetro. Además, no solo por parte del voltaje Va, también, por parte de la corriente Ix se cumple el método de superposición, ya que como se puede observar, la corriente Ix por parte de la fuente de 20v da 0 A y la corriente Ix por parte de la fuente de 12v da 25,5 mA, sumando estas nos da el resultado del amperímetro de la primera medición. Por otra parte, los resultados dados por el cálculo manual se creen que son más exactos ya que ellos no se saltan decimales, no obstante, los resultados calculados y los medidos son aproximados, por lo que se puede concluir que el circuito y los cálculos fueron bien tomados.
   
   - Porcentajes de Errores de las tablas 5-1 y 5-2
   
   ![image](https://user-images.githubusercontent.com/75439689/104663691-88cd2f00-569b-11eb-89bb-c727b8e75b18.png)
   
6. CONCLUSIONESS

   - El Teorema de Superposición resulta efectivo al analizar un circuito que se compone de dos o más fuentes de voltaje y/o corriente. Ya que puede causar cierta confusión al momento de resolver el circuito con los métodos de análisis básicos, por ello es práctico utilizar dicho método.
   
   - Después de haber hecho las respectivas mediciones en cada caso (analizando una fuente y poniendo la otra en cortocircuito) y sumando algebraicamente los valores obtenidos; se obtiene las mediciones iniciales que se realizó con ambas fuentes de voltaje, demostrándose así el método de análisis de circuitos que aplica el teorema de supreposición. 
   
   - Cabe destacar que en los cálculos es necesario determinar correctamente los signos tanto para la corriente como para los voltajes; ya que si se toma un sentido erróneo de una corriente o una polaridad errada de las caídas de voltaje, se obtienen resultados completamente desacertados. 
 
7. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).

   
      
      

