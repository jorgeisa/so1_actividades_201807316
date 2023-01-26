# ACTIVIDAD 1 - 201807316

<p align="center"><img src="../img/actividad1/actividad1.jpg" width="300" height="300"/></p>


Tipos de Kernel y sus Diferencias
=======

Hay cinco tipos "principales" de núcleos o arquitectura de sistema operativo son los siguientes.

## 1. Kernel Monolítico

<p align="center"><img src="../img/actividad1/monolitico.png" width="300" height="300"/></p>

Es el tipo de kernel mas simple y comun. Incluyen la funcionalidad central del sistema operativo y admiten todos los disòsitivos conectados a él. Los servicios de usuario y kernel se implementan en el mismo espacio de memoria. Por esto el tamaño del nucleo aumenta y por ende el tamaño del sistema operativo támbien. Su principal beneeficio es que en ejecucion el proceso es mas rapìdo ya que no hay espacio de memoria separado para el usuario y el kernel. 
## 2. Microkernel

<p align="center"><img src="../img/actividad1/microkernel.png" width="300" height="300"/></p>

Desarrollo mas "nuevo" y no son tan comunes como los monoliticos. Incluyen solamente servicios y dispositivos esenciales necesarios para que el sistema funcione. Esto da como resultado un kernel pequeño y compacto que usa menos memoria. El usuario y kernel se implementan en espacios distintos. Esto como consecuencia reduce el tamaño del kernel y da como resultado la reduccion del tamaño del sistema operativo.

## 3. Kernel Hibrido

<p align="center"><img src="../img/actividad1/kernelhibrido.png" width="300" height="300"/></p>

Estos combinan monoliticos y microkernels. Incluyen mas servicios que microkernels pero menos que nucleos monoliticos. Esto permite tener beneficios de ambos tipos de kernels. La combinacion toma la velocidad de los monoliticos y modularidad de los microkernels.

## 4. Nano Kernel

<p align="center"><img src="../img/actividad1/nanokernel.png" width="300" height="300"/></p>

Tipo mas pequeño de kernel. Consta soamente de miles de lineas de codigo (pequeña para ser de este campo). Esto implica que el codigo ejecutado en el hardware se ejecuta con el minimo. Se utilizan recursos limitados.

## 5. Exo Kernel

<p align="center"><img src="../img/actividad1/exokernel.jpg" width="300" height="300"/></p>

Tiene proteccion y gestion de recursos por separado. Es adecuado para cuando se hace un personalizacion en una aplicacion. Se usan mas en ambitos como dispositivos moviles. Es como un microkernel pero con caracteristicas especificamente para dispositivos moviles.