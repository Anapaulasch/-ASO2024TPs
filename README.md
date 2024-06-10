1.A) 
Conhilos.py tiempos de ejecución: 4.16s – 4.14s – 4.11s – 4.08s – 4.14s
Sinhilos.py tiempos de ejecución: 7.18s – 7.40s – 7.11s – 7.39s – 7.43s

El tiempo de ejecución de conhilos.py es menor al de sinhilos.py, los dos no tienen mucha variación entre cada una de sus ejecuciones. 
El tiempo de ejecución es y no es predecible, por un lado, podemos ver que el tiempo de ejecución de conhilos.py no varían de cuatro segundos, 
pero los números después de la coma no siguen ningún patrón, lo mismo sucede con sinhilos.py.

B) Con mi compañero encontramos que hay menos variación de tiempo de ejecución en nuestros resultados de conhilos.py, que en los resultados de sinhilos.py, 
ya que, a él, sinhilos.py se le ejecutaba 1.s más rápido que a mí.

C) Sumaresta.py valor final: 0
- 0.16s
- 0.16s
- 0.16s
- 0.16s
- 0.15s
- 0.16s
- 0.18s
- 0.16s
- 0.14s
- 0.13s

Sumaresta.py descomentado
-Tomó 37.089s, valor final es -499500
-Tomó 37.018s, valor final es -459080
-Tomó 42.769s, valor final es 500000
-Tomó 37.076s, valor final es 442625
-Tomó 37.450s, valor final es -257890
-Tomó 36.713s, valor final es -449640
-Tomó 38.327s, valor final es -499540
-Tomó 35.972s, valor final es -500000
-Tomó 36.130s, valor final es -385660
Al descomentar el código sumayresta.py, se volvió más lento el tiempo de ejecución, más impredecible y el valor final varía en cada resultado. 
Esto sucede ya que al descomentar el código, se introducen bucles adicionales que no hacen nada, esto aumenta el tiempo de ejecución,
y el valor final varía porque los dos hilos van entrando a “acumulador” y cambiando su resultado simultáneamente sin sincronizarse.
