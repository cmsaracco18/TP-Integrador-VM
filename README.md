Nombres: Camila Saracco y Jonathan Chavez

/proc y archivo particion:
   - Debido a que `/proc` es un sistema efímero, se generó el archivo `particion` con:
	cat /proc/partitions > particion
   - Este archivo se incluyó dentro del `.tar.gz` correspondiente a `/proc`.

