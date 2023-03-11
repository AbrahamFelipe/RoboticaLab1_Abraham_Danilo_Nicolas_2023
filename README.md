## Laboratorio 1 Robótica
### Integrantes: 
- Danilo Enrique Insuasty Delgado.
- Abraham Másmela Ramirez
- Nicolás Prieto Solano
## Descripción de la solución planteada
## Diseño de la herramienta:
Para el diseño de la herramienta porta marcador se tuvo en cuenta que, esta no se encontrará alineada con la articulación No. 6.


Se planteó hacer la herramienta a través de diferentes piezas de MDF cortadas con láser, por lo que se procedió a diseñar el modelo en inventor para obtener los planos y el modelo STL que se exportó a Robot Studio.

<div>
<p style = 'text-align:center;'>
<img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/Herramienta/herramientaInventor.PNG" width="300px">
</p>
</div>

Después del corte láser se pegaron las piezas y se colocó un tubo de PVC que sostiene el marcador y en el fondo tiene un resorte para darle flexibilidad al momento de escribir.

<div>
<p style = 'text-align:center;'>
<img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/Herramienta/image_2023-03-10_141452888.png" width="300px">
</p>
</div>


## Generación de trayectorias
Para realizar las trayectorias primero se realizó en inventor el modelo de las letras a escribir.

<div>
<p style = 'text-align:center;'>
<img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/OtrasImagenes/DAN_Letras.png" width="300px">
</p>
</div>

El modelo se importo al RobotStudio y desde ahi se realizaron puntos sobre el contorno de las letras para posteriormete crear las trayectorias correspondientes. Cabe recalcar que en la rutina tambien se incluyo el movimiento desde el "home" del robot hacia las letras.


<div>
<p style = 'text-align:center;'>
<img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/OtrasImagenes/TrayectoriaLetras.PNG" width="300px">
</p>
</div>


El código RAPID utilizado para los dos ejercicios de escritura se encuentran dentro del repositorio, [plano sin inclinar]() y [plano inclinado](https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/tree/main/Paths-CodigoRAPID/Codigo%20RAPID%20plano%20inclinado).

## Obtencion del nuevo WorkObject del plano inclinado
Para poder inclinar la escritura de las letras con el fin de realizar la segunda parte del laboratorio es necesario redefinir el objeto de trabajo sobre el que se va a escribir, este es definido dentro de la propia interfaz del robot tocando 3 de las esquinas del trablero con la punta de la herramienta para que se calibrara la nueva superficia ha tabajar, el sistema requiere de defini 2 puntos X y 1 punto Y. 


## Video, simulación e implementación

1)Video de la simulación de la escritura en el piso (dar click en la imagen)

<a href="https://youtu.be/egIbVox9zpI" target="_blank"><img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/OtrasImagenes/simulacion%20piso.PNG" 
alt="IMAGE ALT TEXT HERE" width="299" height="315" border="10" /></a>


2)Video de la simulacion de la escritura en la superficie inclinada (dar click en la imagen)

<a href="https://youtu.be/Ptg3gcHkAj4" target="_blank"><img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/OtrasImagenes/simulacion%20Inclinada.PNG" 
alt="IMAGE ALT TEXT HERE" width="299" height="290" border="10" /></a>




3)Video de la implementacion de la escritura en el piso (dar click en la imagen)


<a href="https://youtube.com/shorts/9Qv1UK5hy0I" target="_blank"><img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/OtrasImagenes/LetrasPiso.PNG" 
alt="IMAGE ALT TEXT HERE" width="173" height="319.5" border="10" /></a>


4Videos de la implementacion de la escritura inclinada (dar click en las imagenes)


<a href="https://youtu.be/Ex8J-IRUotk" target="_blank"><img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/OtrasImagenes/LetrasInclinadaP1.PNG" 
alt="IMAGE ALT TEXT HERE" width="379" height="246" border="10" /></a>


<a href="https://youtu.be/gcav8XIhltA" target="_blank"><img src="https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/main/OtrasImagenes/LetrasInclinadaP2.PNG" 
alt="IMAGE ALT TEXT HERE" width="379" height="246" border="10" /></a>

## Conclusiones






























[Plano] (https://github.com/AbrahamFelipe/RoboticaLab1_Abraham_Danilo_Nicolas_2023/blob/cdf70a5ca54b7efc3ba971d285862cd2c907d776/Herramienta/PlanosCorteLaser.pdf)
