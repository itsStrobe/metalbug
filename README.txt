Antes de hacer un cambio, avisen en Facebook cuando inicien a trabajar
y cuando hagan el commit.

1er Log -- Pepe
>Creacion del proyecto

2do Log -- Gallo
>Test

3er Log -- Pepe
>agregue sonido "bobby_taunt"
>obj_bobby: evento q -> taunt

3er Log -- Pepe
>agregue 	sprites [goku/superman/darthvader/stone]
		sonidos [stone]
>obj_stone	evento	colision con "bobby" ->	sonido "snd_stone" y desaparecer

4to Log -- Seiji
>agregue objeto "floor_inv" y sprite de "invisible floor"
>ajuste los sprites de bobby a un mismo tamaño (para, segun yo, evitar problemas)
>separe el sprite "bobby_jump" en "bobby_jump" y "bobby_fall"
>implemente algunas cosas en obj_bobby para agregar gravedad y brinco, pero todavia no jala bien.

5to Log -- Seiji
>agregue sprite "bobby_mask" y se le asigno al objeto "obj_bobby".
>se corrigio problema de movimiento y gravedad en objeto bobby.