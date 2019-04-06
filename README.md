# GuerraDeMonstruos
Proyecto de practica donde se verá TDD, POO y SOCKETS


--GUERRA DE MONSTRUOS--
Se requiere realizar un mini-juego donde existan dos jugadores
los cuales cada uno tendran 3 diferentes mounstros.
REGLAS
1.- Cada jugador cuenta con tres monstruos
Troll de hielo 
	- vida = 70  
	- fuerza = 7  
	// poder especial
	- Congelar()
Minotauro      
	- vida = 130 
	- fuerza = 13 
	// poder especial
	- Arremeter()
Dragon         
	- vida = 185 
	- fuerza = 20 
	// poder especial
	- Escupe fuego()
	- Volar()
- Debe contar con una pantalla la cual solicite ingresar el nombre del jugador y un botón el cual de acceso al sistema
- El nombre del jugador no debe ser vacio.
- El nombre del jugador por lo menos debe tener 3 caracteres.
- Antes de iniciar la partida cada jugador lanzara un dado, quien obtenga el número mas alto inica, en
    caso de empate se vuelven a lanzar los dados.
- Una vez dentro del sistema debe de mostrar el nombre del jugador tanto jugador como oponente.
- Mostrará los tres monstruos con sus caracteristicas
8.- Cada jugador podrá atacar solo cuando sea su turno de atacar.
2.- Cada jugador tendrá un turno para atacar.
3.- Solo se puede atacar a un monstruo a la vez.
// ataque normal
4.- El daño causado es aleatoreo entre cero y su fuerza.
	4.1.- El contador de vida del monstruo oponente se verá afectado por el
	      ataque recibido.
	4.2.- En caso que la vida restante sea menor al ataque recibido esta pasara a cero.
// poder especial
5.- Los poderes especiales no serán ejecutados por el usuario, sino que 
estan condicionados a ciertos eventos:
	5.1.- El dragon cada vez que el daño que obtenga sea cero escupira fuego y su
		  daño sera entre 1 y un 30% de su ataque.
	5.2.- El dragon podra volar si es atacado en un turno que sea 
	      divisible entre 3 y no recibirá daño alguno.
	5.3.- El minotauro cada vez que su ataque cause un daño igual a cero el siguiente 
	      turno arremetera causando un daño entre 5 y 10
	5.4.- El troll de hielo cuando ataque a su oponente con su maximo de fuerza, en su mismo turno
	      congelara a su oponente impidiendo que lo pueda utilizar en el siguiente turno.
          Una vez terminado el turno que estuvo congelado este se descongelará.		  
6.- El ganador será le quede por lo menos un monstruo con vida.
