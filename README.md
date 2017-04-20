# ModulosPD
ModulosPD by Diego Molina Quintero Estudiante de artes de la grabación y producción musical.

ModulosPD es una serie de modelos ya programados en puré data para enseñar 
y facilitar la labor de aprendizaje de síntesis simple, esta herramienta es útil para 
docentes de audio y/o música digital ya que permite mostrar a los alumnos de manera 
rápida y fácil que pasa en los diferentes procesos de la síntesis de audio, cuales 
son los parámetros a tener en cuenta y como se pueden modificar. también es útil
para las personas que se están acercando a puré data o al audio digital porque 
podrán comprender términosy conceptos de audio digital de manera sencilla.

Para usar los modelos de forma fácil, crea tu nuevo parche en la carpeta ModulosPD así podrás llamar los modelos sin ningún problema.

ModulosPD contiene :

controlenvolvente.pd
controlfreq.pd
modulodac.pd
moduloenv.pd
modulofm.pd
moduloonda.pd
moduloring.pd
pruebamodulos.pd


controlenvolvente.pd
En este modulo de pd podras encontrar todos los parámetros de una envolvente tradicional ADSR (Ataque, Decay, Sustain, Release), 
estos parámetros están acompañados por unos sliders o faders que modifican a estos; 
cabe aclarar que esto solo es un modulo de control envía datos en ningún momento envía señales
y mucho menos es la envolvente, solo son los parámetros que se modificaran de la envolvente.


controlfreq.pd
Este modulo es una imitación de una octava de un piano con unos [Bangs] cada uno de ellos 
envía el valor de una frecuencia hacia el oscilador que desees, cada frecuencia esta cuantizada en valores MIDI
es decir la frecuencia que se envía al oscilador será la mas acertada a las notas musical de la posición del piano.

modulodac.pd
Este modulo contiene un medidor de señal por si en algún momento estamos  saturando alguna señal,
una entrada de audio y una entrada para envolventes y esto ya sincronizado al sonido de tu computadora.

moduloenv.pd
posee 8 entradas de datos para modificar todos los componentes de una envolvente en el siguiente orden
nivel del ataque, nivel del decay, nivel del sustain, nivel del release, tiempo de ataque, tiempo de decay, 
tiempo de sustain, tiempo de release.

modulofm.pd
Es un modulo para hacer síntesis fm , el cual posee la entrada un carrier, de un modulador y de un indice de modulación, puedes 
crear síntesis mas complejas ya que puedes incluir 3 carriles, 3 moduladores y 3 indices de modulación.

moduloonda.pd
Este modulo es muy simple puedes seleccionar un sonido senosoidal o diente de sierra o un ruido, 
en la actualidad solo están integrados estos 3 sonidos, en futuras versiones tendrás mas opciones, por el momento
puedes explicar la onda usar la onda he ingresar los parámetros de frecuencia de la onda que necesitas.

moduloring.pd
Modulo para crear sonidos apartir de modulación de anillo, puedes multiplicar hasta 6 señales para crear tus propios
sonidos, debes usar mínimo dos máximo 6 señales para poder utilizarlo sin problemas.

pruebamodulos.pd
Es un ejemplo donde están abierto todos los modelos y tiene una configuración básica para que hagas sinteis en el.
es una forma de conocer todos los modelos.
