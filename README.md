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

## Resumen

Imagina poder desarrollar universos visuales completos y consistentes sin necesidad de saber dibujar, utilizando únicamente tus palabras. ChatGPT te permite generar imágenes realistas o estilizadas, crear personajes detallados y gestionar proyectos visuales usando únicamente prompts bien estructurados y específicos.<br>

> ¿Cómo crear imágenes precisas con ChatGPT?

ChatGPT facilita la generación directa de imágenes con capacidades similares a Dalí. Al escribir un prompt claro y detallado en español, puedes obtener resultados precisos con características visuales específicas. Por ejemplo:<br>

Descripción clara del sujeto: "Un lobo blanco de ojos dorados sobre una colina nevada".<br>
Detalles del entorno: "Aurora boreal en el cielo y templo en ruinas al fondo".<br>
Estilo visual deseado: óleo digital con iluminación suave.
Formato de la imagen: horizontal en ratio 16:9.<br>
Estas imágenes generadas en ChatGPT pueden servir como punto de partida en otras herramientas visuales especializadas como Runway,Hailu AI,Midjourney, Pixverse, Leonardo AI .<br>

> ¿Qué ventajas tiene un proyecto persistente en ChatGPT?

Crear un proyecto persistente en ChatGPT permite desarrollar un concepto visual unificado y cohesivo. Este procedimiento posibilita:<br>

Establecer estilos visuales coherentes para proyectos narrativos o visuales.<br>
Dar instrucciones permanentes sobre características como época, estética o contenido visual. Por ejemplo, especificar un universo medieval con estética gótica.<br>
Crear tablas de estilos, paletas de colores, ideas de ambientación y referencias artísticas o cinematográficas.<br>
Un proyecto persistente garantiza que cada prompt futuro automáticamente siga el estilo definido inicialmente.<br>

> ¿Cómo desarrollar personajes coherentes para animaciones o vídeos?

La creación de personajes consistentes puede ser compleja. Sin embargo, ChatGPT facilita este trabajo al proporcionar descripciones precisas y replicables. Elementos clave para incluir en tu prompt son:<br>

* Nombre y edad.
* Raza y características visibles, como color de cabello u ojos.
* Detalles específicos, como cicatrices o elementos distintivos.
* Descripción detallada de ropa y equipamiento.
* Rasgos de personalidad y comportamiento.

Ejemplo práctico:

* Nombre: Kael.
* Edad: 22 años.
* Raza: humano con sangre de dragón.
* Apariencia: cabello blanco largo; ojos rojo fuego; cicatriz en la ceja izquierda.
* Vestimenta: armadura negra con runas azules brillantes.
* Personalidad: silencioso, protector, impulsivo en combate.

Estos personajes generados en ChatGPT pueden posteriormente visualizarse en Dalí, Leonardo o Mid Journey, y usarse como referencias en diversas plataformas visuales.<br>

> ¿Qué posibilidades ofrecen los GPT especializados en prompts visuales?

Los GPT personalizados son herramientas que facilitan la generación de prompts adaptados específicamente para plataformas visuales, tales como:<br>

* GPT para prompts cinematográficos adaptados a Runway.
* GPT especializados en narrativas estilo Studio Ghibli para Pixverse.
* GPT enfocados en ideas para arte conceptual.

Estos GPT especializados pueden almacenarse, editarse y utilizarse directamente desde tu espacio de trabajo personal en ChatGPT.<br>

Te invito a experimentar creando tu propio universo visual y personajes completos utilizando prompts creativos.

### Práctica

Lo primero que vamos a hacer es generar imagenes en ChatGPT, en ChatGPT tenemos capacidades de imagen como Dali, te permite crear imagenes directamente. Ahora creamos un Prompt en español como:

```sh
    Genera una imagen de un lobo blanco de ojos dorados parado sobre una colina nevada, con la aurora boreal en el cielo y un templo en ruinas detrás. Iluminación suave, estilo óleo digital, formato horizontal 16:9
```

En DeepSeek generé otro prompt para otra imagen:

```sh
    Quiero una imagen de programación, un profesor frente a su ordenador, de fondo un sistema avanzado computacional de ciberseguridad, con un estilo futurista, bien iluminado y prolijo, en las pantallas hay diferentes códigos de diferentes lenguajes de programación

    Pregunta DeepSeek: 
    ¿Te gustaría ajustar algún detalle? Por ejemplo, ¿prefieres que el profesor sea más joven, o que haya algún elemento específico en el código?

    Respondo:
    si, el profesor de pelo blanco, largo y atado, con barba bien prolija, en el código que hayan diferentes ejecuciones

    Me responde:
    Prompt para IA (DALL·E/MidJourney):
    "Wise old programming professor with long white tied hair and neat beard, wearing a high-tech shirt, teaching in a futuristic cybersecurity lab. Multiple screens show Python code executing a neural network, a Linux terminal blocking cyber attacks, and JavaScript animations. Holograms of code float in the air, neon blue/green lighting, ultra-detailed, 8K, cyberpunk academia style, digital art."
```

Lo utilice en Leonardo AI y generó una de las siguientes imagenes:

![IA-Trabajando](https://github.com/ArielBetancud22/IA-Trabajando/issues/4#issuecomment-2963812591)

> Hay muchas más información en enlace de PDF

[prompts-chatgpt](https://static.platzi.com/media/public/uploads/prompts_chatgpt_900aea47-2e04-43d5-bb52-e4340029b388.pdf)<br>
[instrucción-como-hacer-un-buen-prompt](https://static.platzi.com/media/public/uploads/instructivo_como-hacer-un-buen-prompt_7929ce7e-3bfb-495e-b780-58bbcc443c92.pdf)<br>
[instructivo-formatos-de-video](https://static.platzi.com/media/public/uploads/instructivo_formatos-de-video_3985677a-9020-458c-8d22-1354a0270f21.pdf)<br>

### Comandos para terminar

```sh
git tag -a v-01-02
git push --tag origin ariel22
```

Después de esto solo a mergear<br>

# Clase 3

## Resumen

Imagina crear emocionantes escenas cinematográficas usando inteligencia artificial. Con iLuo AI es posible generar videos espectaculares a partir de simples imágenes y texto. Esta innovadora plataforma permite controlar meticulosamente la cámara, emociones faciales, efectos especiales y más, adaptándose a tus necesidades creativas.<br>

## ¿Qué es iLuo AI y por qué destaca?

iLuo AI es una plataforma china que utiliza inteligencia artificial para generar videos. Su popularidad crece debido al realismo cinematográfico, avanzada gestión de movimientos de cámara y la habilidad para crear emociones convincentes en personajes virtuales. Se usa especialmente en:<br>

* Cortometrajes narrativos.
* Generación de clips emocionales de personajes.
* Animación de ilustraciones o fotos antiguas.
* Producción de efectos visuales, como explosiones o plantas creciendo.
<sub>
Accesible desde iLuoAI.video, facilita trabajos desde texto o imágenes hacia video, permitiéndote transformar ideas en escenas emocionantes y visualmente cautivantes.</sub>

> ¿Cómo empezar con iLuo AI?

## ¿Cómo crear una imagen base eficaz?

Tu proyecto comienza seleccionando AI Create, y luego Create Image en el menú de iLuo. Un buen prompt describe claramente la escena inicial. Por ejemplo:<br>

Un P.O.V. de alta velocidad corre a través de una ciudad futurística de Warthorne, viajando a través de torres y bosques colapsantes, dentro una suite de cajas colosal con magma naranja, armadura negra de core, iluminación cinemática y explosiones de caos.<br>

Es importante elegir una imagen que represente fielmente la visión creativa original.<br>

## ¿Qué es el Director Mode para crear videos?

El siguiente paso usa el modelo Director para videos. Aquí seleccionas movimientos de cámara esenciales para tu narrativa:<br>

* Tracking Shot: sigue personas u objetos en movimiento.
* Shake: simula vibraciones o tensión.
* Pedestal Up: movimiento vertical ascendente desde la ubicación fija.

Mantener el Refining desactivado brinda control total del resultado.<br>

## ¿Cómo controlar personajes y emociones?

Sube una imagen del personaje al modo Image to Video y escribe un prompt específico según la emoción deseada. Por ejemplo, para expresar terror:<br>

Make this character look terrified, eyes wide open, mouth trembling, subtle head movement.<br>

Para emociones más tranquilas o suaves, utiliza:

<sub>Make him look nostalgic, blinking slowly, faint smile, soft lighting.</sub>

Puedes ajustar la refinación para variar la precisión del resultado.<br>

## ¿Qué movimientos de cámara puedes utilizar?

Cada movimiento tiene efectos específicos:<br>

- Static shot: ideal para emociones intensas sin distracciones.
- Zoom: acerca la atención sin desplazar físicamente la cámara.
- Push (Dolly): movimiento inmersivo hacia adelante o atrás.
- Panning: movimiento horizontal de izquierda a derecha.
- Tilt: movimiento vertical arriba o abajo.
- Crane: revelación desde arriba, vertical desplazado del eje.
- Tracking: seguimiento activo que ayuda en las persecuciones o acción.
- Shake: añade sensación de tensión o acción.

Al separar los movimientos con comas y espacios, se ejecutan secuencialmente; si no, suceden simultáneamente.<br>

## ¿Cómo mantener coherentes referencias de personaje?

Para mantener consistencia visual usa el modelo S2V-D01 en la sección de subject reference. Sube una imagen del personaje y especifica detalles concretos en el prompt, como:<br>

<sub>Young Asian man with spiky black hair, cybernetic eye implant, wearing a long black trench coat.</sub>

Esta imagen puede reutilizarse múltiple veces.<br>

## ¿Cómo integrar efectos visuales creativos?

Usa comandos específicos. Algunos ejemplos prácticos:<br>

* Explosiones:

<sub>A futuristic street erupts in flames, debris flying everywhere, shockwave blowing out windows.</sub>

* Insertar texto en la escena:

<sub>Add the phrase "K2 Rising" in glowing red letters in the center of the screen.</sub>

* Crecimiento acelerado de plantas:

<sub>Lush tropical plants grow out of a coach in time lapse.</sub>

## ¿De qué manera extender la duración de tus videos?

Para crear videos más largos, exporta el último frame del video finalizado en software como CapCut o Premiere. Luego usa este frame como base en iLuo AI, creando así extensiones naturales y visuales continuas.<br>

### Enlaces con más información

[prompts-hailuo](https://static.platzi.com/media/public/uploads/prompts_hailuo_8d987aa0-e905-4889-becd-28f8bd0ea5a7.pdf)<br>
[instructivo-movimientos-camara](https://static.platzi.com/media/public/uploads/instructivo_movimientos-de-camara_664eac5f-a7cb-4382-aac2-3b2ea10c99fe.pdf)<br>

### Lecturas recomendadas

[chatGPT-Hailuo Minimax Prompt Creator](https://chatgpt.com/g/g-l1gfQRwo5-hailuo-minimax-prompt-creator)<br>
[Media-Google Drive](https://drive.google.com/drive/folders/1U9r-wTTYMFJc9tAeen6NS5hpo-lPQKTy?usp=sharing)<br>

