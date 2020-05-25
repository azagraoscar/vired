---
title: Documento de Diseño
layout: page
menubar: menu
---
## PROYECTO FINAL TECNOLOGÍA DE VIDEOJUEGOS

Nombre: Vired-Co

Género: Shooter, Juego de oleadas

Estilo artístico: Retro/Pixelado

### Tema del juego

Un doctor/anticuerpo se alza de valor y con una jeringuilla decide salir a combatir los virus para salvar la raza humana.

#### Características del protagonista: 

Se trata de un médico/anticuerpo que ataca a distancia con una jeringuilla y que más tarde desbloqueará un arma cuerpo a cuerpo, el bisturí. 

Su objetivo es eliminar a todos los virus que han entrado en el cuerpo en el que vive, y descubrir quién está detrás de todo esto.

#### Música:

* Intro
* Tema de batalla
* Tema de victoria
* Tema de Game Over
* Tema de la tienda
* Tema del boss final

#### Efectos:

*	Disparo (Sonido de gotita de la jeringuilla)
*	Pasos (Sonido de caminar tanto del personaje principal como de los enemigos)
*	Daño (Recibido por los enemigos o por el personaje principal)
*	Daño letal del personaje principal
*	Daño cuerpo a cuerpo

#### Sprites:

* Protagonista
* Armas
*	Enemigos
*	Terreno:
 *	Suelo de varios tipos
 *	Muros de varios tipos
 *	Zona de tienda
*	Tendero
*	Proyectiles
*	PowerUps
*	Objetos
*	Interfaz:
 *	Vida
 *	Numero de vidas
 *	Dinero

### Máquina de estados:

![](/images/fms.png)

### Objetos por definir y relación entre ellos:

![](/images/obj.png)
### Planificacion temporal

|Semana	| Programación | Música | Diseño |
|-------|--------------|--------|--------|
| 1 |Definir clases básicas (No es necesario incluir la tienda ni powerUps por ahora) | Empezar música de batalla y efectos de sonido | Sprite del protagonista, del primer tipo de enemigo, suelo 1 y muro 1. Diseñar un mapa en TileMap (lo más simple posible, un cuadrado con 2 muros y una zona en la que aparezcan enemigos) Página Web |
| 2 | Primer mapa para testear las clases y posibles errores | Terminar efectos de sonido y hacer música de victoria/derrota | Añadir sprites al protagonista y los enemigos para animarlos. Empezar a hacer Sprites diferentes de terreno y enemigos. Terminar página web |
| 4 | Pulir posibles fallos | Pulir posibles fallos | Pulir posibles fallos |
