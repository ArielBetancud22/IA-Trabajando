# Clase 1

> Resumen

La inteligencia artificial (IA) ha transformado completamente la creación audiovisual, permitiendo que cualquier persona convierta sus ideas en impactantes escenas visuales. Antes, construir una batalla épica entre kaijus o producir secuencias con estilo anime requería de amplios recursos técnicos. Hoy, la IA pone esta capacidad al alcance de cualquier individuo, sin importar sus conocimientos previos o herramientas tecnológicas disponibles.<br>

## ¿Qué puedes crear utilizando inteligencia artificial?

La IA abre un panorama nuevo para quienes desean realizar proyectos visuales llamativos:<br>

Escenas cinematográficas: imagina dos kaijus gigantes combatiendo entre edificios derrumbados con calidad profesional.<br>
Secuencias animadas estilo anime: utilizando plataformas como Pixverse, Udio y Zuno, puedes añadir música original a tus propias creaciones.<br>
Comerciales visualmente atractivos con Sora: ideales para presentaciones empresariales o campañas en redes sociales.<br>
Personajes interactivos: crea videos donde los protagonistas hablan, reaccionan y se mueven fluidamente, todo sin complicados programas de animación.<br>
### ¿Necesitas experiencia técnica para empezar?

La gran ventaja del uso de inteligencia artificial es que cualquier persona puede hacerlo. Esto implica que:<br>

*No es necesario contar con conocimientos previos de animación o edición.
*No hace falta saber programar o utilizar software complejo.
*No requieres equipos sofisticados ni costosos. Solo basta con tener una idea clara.

### ¿Cómo beneficia a los creadores este tipo de tecnología?

Gracias a estas herramientas, los creadores pueden realizar trabajos que antes eran impensables por el requerimiento de tiempo, esfuerzo y recursos técnicos. Con IA, es posible:<br>

*Dar vida fácilmente a historias imaginativas.
*Construir portafolios sorprendentes que atraigan oportunidades profesionales.
*Lanzar proyectos personales o comerciales con resultados visuales emocionantes.

La IA ya no es solo un concepto futurista lejano. Actualmente, está transformando el panorama creativo y otorgando poder a quien tenga una visión clara para llevarla a cabo. ¿Listo para dar el primer paso y comenzar a transformar tus ideas en visualizaciones poderosas?<br>

# Clase 2

> Comandos para comenzar este proyecto desde GitHub:

Comenzamos entrando en nuestro perfil de GitHub, creamos un nuevo repositorio llamado en este caso IA-Trabajando, copiamos el enlace ssh y venimos a abrir la terminal de Git Bash, como administrador:

```sh
git clone enlace-ssh
cd ia-trabajando
touch README.md
code . #Abrimos VSC y escribimos en el la primera clase
ctrl + s
git fetch #Es lo primero que debemos hacer antes de un push
git pull origin main
git status
git add .
git commit -m"El primer paso, agregar el README.md con la introducción"
git push origin main
```

Continuamos con la creación de diferentes ramas primarias y secundarias:<br>

```sh
git tag -a v-01-01 -m"La primera clase"
git push --tag origin main
git branch
git branch second #Rama primaria junto con main
git branch ariel22 #Rama secundaria junto a profe
git branch profe
git branch #Vemos todas las ramas construidas
git checkout ariel22
git status #Escribimos esto en el README.md
ctrl + s
git status
git commit -am"Comienzo de la segunda clase"
git push origin ariel22
git checkout second
git merge ariel22
git push origin second
git checkout main #Vamos a GitHub y hacemos un pull requests
git pull origin main
git checkout profe
git merge main
git push origin profe
git checkout ariel22 #Terminamos por hoy
```