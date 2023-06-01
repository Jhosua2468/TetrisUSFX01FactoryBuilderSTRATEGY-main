 # TetrisUSFX01FactoryBuilderSTRATEGY
 Implementacion del patron Strategy en el juego Tetris

## Resumen...
Se creo tres tipos de estrategias relacionados con el spawneo de piezas:
Uno que es el normal, osea que aparece en el lugar de origen, otro que aparece las piezas más arriba y más a la derecha, el otro es  practicamente lo mismo solo que en vez de aparecer la pieza en la derecha, lo hace en la izquierda .  Se crearon clases  en las cuales se definieron las estrategi, se creo una interface en la que se definio una  funcion que  posiciona la pieza que devuelve valores, las banderas son restricciones que evitan poder mover las piezas mientras estan fuera del board estas funciones  funcionan cada  tick 
