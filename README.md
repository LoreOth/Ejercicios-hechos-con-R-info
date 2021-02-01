# Ejercicios-hechos-con-R-info
Ejercicios concurrentes, resuletos en plataforma R-info
Practica 3 del modulo concurrente y ejercicios adicionales.-

1- Realice un programa con 2 robots recolectores de flores (floreros) y 2 robots recolectores de
papeles (papeleros).
Los floreros comparten área y tienen 5 intentos para juntar las flores de una esquina, dentro de
dicha área, elegida al azar. Del mismo modo, los papeleros comparten área y tienen 3 intentos
para juntar los papeles. En cada intento cada robot va a la esquina al azar, junta todos los
elementos (flores o papeles según le corresponda) y vuelve a su esquina original. Al finalizar
sus intentos cada robot debe acceder a la esquina (10, 10) y depositar los elementos recogidos
de a uno.
- Área de floreros: (1,1) a (5, 10)
- Área de papeleros: (6, 1) a (10, 9)
- Esquinas de inicio de floreros: (6,10) y (7,10)
- Esquinas de inicio de papeleros: (8,10) y (9,10)

3- Realice un programa donde 4 robots colaboren para recoger todas las flores de una esquina
indicada por un robot jefe, seleccionada de manera aleatoria dentro del cuadrante (2,2) y
(10,10). Para ello el jefe determina inicialmente una esquina y los robots deben accederla,
tomar de a una las flores y volver a su posición inicial. Cuando los robots terminan el jefe
deberá informar cuál de ellos logró recoger más flores.
Las esquinas de inicio de los robots deberán ser jefe (1,1) y robots (2,1), (3, 1), (4,1), (5,1) y
(6,1)

4- Realice un programa en el que 4 robots mueven de a una todas las flores de la esquina
(10,10) a la esquina (11,11). Cada robot que finaliza (o, sea, que detecta que la esquina
(10,10) se ha vaciado) deberá avisar al robot coordinador que ha finalizado. Cuando todos los
robots finalizaron, el robot coordinador deberá informar qué robot finalizó último y a
continuación deberá recolectar todas las flores de la esquina (11,11).
El robot coordinador inicia en la esquina (1,1).
Los robots inician en las esquinas (9,9) (9,10) (9,11) y (9,12).

5- Realice un programa en el que 4 robots juegan una carrera por avenidas diferentes: 4, 6, 8 y
10 respectivamente. Todos los robots inician en la calle 1.
Para poder avanzar, cada robot debe juntar un papel de una fuente de papeles localizada en la
esquina (11,11), colocarlo en la esquina actual de su avenida y avanzar un paso. Cuando la
esquina fuente ya no tiene más papeles, o cuando se haya completado la avenida, deberán
avisar al robot coordinador y este determinará el robot que llegó más lejos


Ejercicio adicional 1
Realice un programa formado por 2 equipos de robots. Cada equipo está conformado por 1 robot
recolector de flores y 1 robot depositador de papeles. A cada equipo se le asigna un área de
trabajo.
Cada robot recolector de flores tiene 3 intentos para recoger todas las flores de esquinas de su
área, escogidas al azar. En cada intento debe ir a la esquina, recoger las flores y volver a su
esquina de inicio. Cuando finaliza sus 3 intentos debe avisar al robot jefe.
Cada robot depositador de papeles tiene 5 intentos para depositar un papel en 5 esquinas de su
área, elegidas al azar. En cada intento, los robots deben ir a las esquinas, depositar un papel
tomado de una fuente de papeles en la esquina (13, 13) y volver a su esquina original. Al finalizar
sus 5 intentos debe avisar al robot jefe.
Finalmente, el jefe debe determinar qué equipo terminó primero.
El robot jefe inicia en la esquina (1,1)
El robot recolector de flores del equipo 1 inicia en la esquina (2,1) y su área está comprendida
por las esquina (2,2) y (12, 12).
El robot depositador de papeles 1 inicia en la esquina (3,1) y su área está comprendida por las
esquina (2,2) y (12, 12).
El robot recolector de flores 2 inicia en la esquina (14,1) y su área está comprendida por las
esquina (14,2) y (24,12).
El robot depositador de papeles 2 inicia en la esquina (15,1) y su área está comprendida por las
esquina (14,2) y (24,12).


Ejercicio adicional 2
Realice un programa con 2 equipos de 2 robots y un fiscalizador.
Cada equipo debe hacer el recorrido de L de (10x15) . En cada equipo un robot recorre la arista
vertical juntando flores, y el otro la horizontal juntando papeles.
El fiscalizador debe indicar qué equipo ganó. El equipo ganador es el que termina primero su
recorrido.
El equipo1 inicia su recorrido en la esquina (5, 5) y el equipo2 inicia el recorrido en la esquina (25,
5).
Los robots inician en las esquinas
Fiscalizador: (1,1), R1_1 (2,1), R2_1(3,1), R1_2(4,1), R2_2(5,1)
