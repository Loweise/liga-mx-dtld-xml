# liga-mx-dtld-xml
1 ¿Cuál debería ser el elemento raíz? Partido 
2 ¿Una jornada puede contener varios partidos? Si
3 ¿Cada partido debe contener exactamente dos equipos? Si
4 ¿Cómo distinguirían al equipo local del visitante? Primero va siempre el local y al final el visitante aunque se le podria dar una propiedad para especificarlo
5 ¿El marcador debe representarse como un solo dato o separar los goles? separarlos
6 ¿Las estadísticas pertenecen al partido o a cada equipo? Cada equipo
7 ¿Qué datos son obligatorios? Equipos competencia marcador y fecha
8 ¿Cuáles podrían ser opcionales? Temporada, estadio, estado, posesion, tiros, tiros a puerta, faltas, tarjetas y tiros de esquina

Información	Elemento/Atributo	Justificación
Jornada		Elemento		Porque es un dato bastante importante al quese 					deberia poder acceder y hacer sort a traves de 					el

Fecha		Elemento		Porque es una de las cosas en la que la gente 					se fija mas a la hora de querer ver el partido 					o estar informado asi que para a futuro 					agregarlo asimismo debe estar individual

ID del partido	Atributo		Porque los usuarios no interactuaran con el

Equipo local	Atributo		Porque lo principal sera equipo y este solo 					sera otro dato	
Equipo visitante Atributo		Misma razon que el anterior

Goles		Elemento		Porque es un elemento que se usa en multiples 					lugares

Estadio		Elemento		Porque es de los primeros datos que aparecen 					por ej cuando se fijan en las tablas de un 					equipo
 
Estado del partido	Atributo	Porque puede ir vinculado al estadio ya que 					son dependientes uno del otro
	
Posesión	Elemento		Porque es dependiente de cada equipo pero son 					datos que al final se pueden usar para 
					promedios

Tarjetas	Elemento		Porque van vinculadas a varias cosas como 					equipos y jugadores
