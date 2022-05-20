# 2022-MicroTaller-FPGA-URJC-jornadas-abiertas
Micro taller de FPGAs libres para las Jornadas de puertas abiertas de la ETSI Telecomunicación URJC

## Descripción

* Fecha: Viernes, 20-Mayo-2022
* Hora: 18:30
* Duración: 15 minutos
* Capacidad: 10 asistentes en grupos de 2
* Placas: 5 x Alhambra-II
* Versión de Icestudio: icestudio-0.9.2w202205140705


## Guión

* Arranca Icestudio
* Abre el diseño plantilla: **Archivo/Abrir**. Fichero: `Circuito-plantilla.ice`

### Circuito 1: Encender LEDs

* Concepto de Bit
* Salida de bits: Puerto/pin de salida
* Los LEDs nos permite "ver" los bits
  * Bit a 1: Led encendido
  * Bit a 0: Led apagado

#### Ejemplo 1

* Cable de unión entre el bit y el pin de salida
* El bit a 1 causa que el LED7 se encienda

#### Ejemplo 2

* Los bits son voltajes: Se DUPLICAN con las bifurcaciones

### Circuito 2: Sirena luminosa (Auto)

* El bit a 1 es un bit constante... que nunca cambia
* ¿Cómo hacemos que parpadee un LED? (Encendido/Apagado/Encendido...)
* Bombeo de bits: corazon

#### Ejemplo 3

* Demo de bombeo
* Cambiar la frecuencia
* Volver a 1Hz

#### Ejemplo 4

* Manipulación de bits: NOT
* El not siempre está enfadado: Hace lo contrario de lo que se le pide
* Estructura sencilla que provoca un "movimento de LEDs"

### Circuito 3: Sirena luminosa (Manual)

* Puertos de entrada: Introducir datos desde el exterior
* Botón: elemento mínimo de entrada de bits:
  -Pulsado: Bit a 1
  -No pulsado: Bit a 0

#### Ejemplo 5

* Vemos el estado del pulsador: lo conectamos al LED1

#### Ejemplo 6

### Circuito 4: Actuación: Limpiaparabrisas

#### Ejemplo 7 (Manual)

#### RETO: Limpiaparabrisas (Automático)

