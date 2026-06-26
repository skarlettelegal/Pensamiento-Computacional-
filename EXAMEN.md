# Juego de la Identidad “femenina” - Skarlette Legal
## Problemática
La problemática que quiero representar en P5.js son los estándares impuestos en las sociedad y cómo afectan directamente la salud mental de las mujeres.

## Ideal de una Mujer socialemente

- TradWife
- Viralización
- Cirugías estéticas
- Influencer
- Filtros
- Cirugías
- Likes
- Aprobación

## Salud Mental

- Comparación
- Falta de autoestima
- Dismorfia
- Presión social
- Trastorno alimenticio

## Referencias Bibliográficas de la Problemática

https://repositoriobiblioteca.uniacc.cl/items/2c7a2552-71b4-4488-9996-13ca616dcf9f

> Según el estudio “Uso del tiempo (hombres y mujeres)” realizado por La Rebelión del cuerpo en el año 2018, las mujeres participantes manifestaron pensar en su cuerpo 3,6 horas diarias en promedio respecto de los hombres del estudio quienes manifestaron que lo hacen 1,8 horas.

https://revistafacso.ucentral.cl/index.php/liminales/article/view/845

> De acuerdo con una investigación realizada por The Wall Street Journal, el 32 % de las mujeres afirma sentirse mal con su cuerpo y que la plataforma Instagram les hace sentir peor (Castaño, 2021).


## ¿Qué es el proyecto?
El proyecto consiste en un juego interactivo compuesto por tres pantallas con una estética pixelada que hace referencia a los videojuegos. Se eligió este formato porque permite representar una problemática cotidiana desde un lenguaje visual cercano e interesante para el usuario. Aunque muchas personas no perciben esta problemática en su vida diaria, los videojuegos forman parte de la vida de muchas personas y suelen asociarse con el entretenimiento. Por ello, se utiliza este formato para invitar al usuario a reflexionar sobre el tema de una manera diferente.
A lo largo de la interacción aparecen críticas y comentarios que muchas mujeres reciben durante distintas etapas de su vida. Estas frases buscan representar cómo la constante presión social puede afectar la construcción de la identidad y, en algunos casos, contribuir al desarrollo de problemas de salud mental. Finalmente, el juego presenta una reflexión y permite volver al inicio, simbolizando que estas experiencias pueden repetirse en cualquier momento de la vida.

## ¿Qué se ve en pantalla?

En la primera pantalla se observa un fondo negro con el título del proyecto, las instrucciones de uso y un botón para comenzar la experiencia.
Al continuar, aparece la segunda pantalla, donde se activa la cámara del usuario con un efecto de pixelado. Con cada clic del mouse surgen textos en color rojo que representan comentarios y críticas que muchas mujeres reciben a lo largo de su vida. Junto a estas frases aparece un símbolo de advertencia, representando que algunos comentarios pueden tener un mayor impacto emocional dependiendo de la experiencia de cada persona.
Después de realizar la cantidad de clics necesaria, la pantalla se vuelve completamente roja, simbolizando el daño provocado por la acumulación de estas presiones y comentarios. Finalmente, se muestra la tercera pantalla, correspondiente al estado de reflexión, donde aparece una imagen tranquila acompañada de preguntas que invitan al usuario a reflexionar sobre su identidad y sobre el impacto que pueden tener las palabras en la vida de las personas.

## ¿Qué elementos visuales aparecen?

En el proyecto aparecen botones interactivos, textos con tipografía pixel, imágenes con estética pixel art, un cursor personalizado, la cámara del usuario con un efecto de pixelado, un marco decorativo, frases en movimiento acompañadas de símbolos de advertencia, un GIF de transición y una imagen final con preguntas que invitan a la reflexión. 

Además, se integra texto repetitivo con frases asociadas a la presión estética y social. La interacción del usuario modifica la visualidad mediante el mouse, generando el cambio entre las distintas pantallas, la aparición progresiva de frases y símbolos de advertencia, el desplazamiento de estos elementos por la pantalla y, finalmente, la aparición de preguntas de reflexión. Además, el cursor cambia al pasar sobre el botón, indicando que es un elemento interactivo. 


# Descripción Conceptual

Como tu proyecto cambió bastante (ahora funciona con clics, estados, cámara pixelada y reflexiones finales), ese texto ya no representa lo que hace realmente el sistema. Te propongo una versión adaptada a tu proyecto.

##¿Cuál es la regla de oro del sistema?
La regla de oro del sistema es:
Mientras mayor sea la interacción del usuario, mayor será la acumulación de críticas y presión visual, hasta llegar a un momento de reflexión sobre la identidad.
Esta regla representa cómo los comentarios y exigencias pueden acumularse con el tiempo, afectando la percepción que una persona tiene de sí misma.
##¿Cómo se relaciona esta lógica con la problemática de género elegida?
La lógica del proyecto se relaciona con la presión social y las expectativas impuestas sobre las mujeres.
Durante la interacción, cada clic genera nuevas frases y comentarios que simbolizan las críticas que muchas mujeres reciben a lo largo de su vida. A medida que estos mensajes aumentan, la pantalla se satura de información, representando cómo la acumulación de estas opiniones puede afectar la construcción de la identidad.
Finalmente, el proyecto cambia a una pantalla de reflexión que invita al usuario a cuestionarse quién es y cómo las palabras pueden influir en su bienestar emocional.

##Input / Output y Sistema
### ¿Qué datos entran? (INPUT)
Los datos que ingresan al sistema son:
Posición del mouse (mouseX, mouseY).
Clic del mouse (mousePressed()).
Tiempo de ejecución mediante frameCount.
Valores aleatorios generados con random() para la posición, velocidad y tamaño de los elementos.

### ¿Cómo se procesan y transforman?
El sistema procesa estos datos mediante distintas condiciones y funciones:
Las estructuras if, else if y else controlan el cambio entre las tres pantallas del proyecto.
Cada clic del usuario genera nuevos elementos visuales compuestos por imágenes y textos.
La función random() asigna posiciones, velocidades y tamaños diferentes a cada elemento, haciendo que cada interacción sea distinta.
Los bucles for recorren todos los elementos para actualizar su movimiento y dibujarlos continuamente en pantalla.
frameCount controla la duración del GIF antes de mostrar la reflexión final.

### ¿Qué respuesta visual producen? (OUTPUT)
Como resultado, el sistema genera distintas respuestas visuales:
Cambio entre las tres pantallas del proyecto.
Activación de la cámara con un efecto de pixelado.
Aparición progresiva de frases e imágenes de advertencia.
Movimiento continuo de los elementos por la pantalla.
Reproducción de un GIF como transición hacia la reflexión final.
Aparición progresiva de preguntas de reflexión mediante los clics del usuario.
Activación del botón para volver al inicio una vez finalizada la experiencia.
Todo esto busca representar el impacto que pueden tener las críticas constantes sobre la identidad y promover una reflexión en el usuario.
## Pensamiento Computacional
### Reglas que gobiernan el sistema
La experiencia se basa en la interacción constante del usuario mediante el mouse. Cada clic provoca un cambio en el sistema, generando nuevas imágenes y comentarios que aumentan progresivamente la saturación visual.
La interacción está organizada en tres estados: una pantalla inicial con instrucciones, una experiencia interactiva donde se acumulan las críticas y una pantalla final de reflexión. El sistema responde a las acciones del usuario mediante condiciones, contadores de clics y variables de estado que determinan cuándo avanzar de una etapa a otra.
De esta forma, la lógica del programa representa cómo la repetición de comentarios y expectativas sociales puede influir en la construcción de la identidad y generar un espacio para cuestionar esas experiencias.

# Referentes

## Jenny Holzer

Artista conocida por usar texto proyectado en espacios públicos.
Su trabajo influye en el proyecto por el uso de frases directas y repetitivas que generan impacto emocional y crítica social.

<img width="600" height="341" alt="image" src="https://github.com/user-attachments/assets/9201690f-bdc7-4454-b854-108adee0ce02" />

## Barbara Kruger

Su obra combina imágenes en blanco y negro con texto crítico sobre:

- El cuerpo
- El consumo
- Los estereotipos de género
<img width="300" height="302" alt="image" src="https://github.com/user-attachments/assets/aedbb586-95e0-429b-9371-66077f7b51b3" />


## Judith Butler – Teoría de la Performatividad de Género
Plantea que el género se construye mediante repetición de normas sociales. Esto se conecta con la repetición de textos y mensajes que refuerzan la presión sobre el cuerpo femenino.



# Diagrama de Flujo
<img width="2059" height="1052" alt="EXAMEN" src="https://github.com/user-attachments/assets/72981c0b-7701-43c9-84f7-52468a38cd33" />




# Link al Sketch Editable en P5.js
https://editor.p5js.org/Skarlettelegal/sketches/0B88Nxv8n 


# Código para Repositorio
```javascript
//VARIABLES
let estado = 1; // Variable para el estado de cada pantalla
let camara; // Variable para colocar la camara
let miFuente; // Variable para cargar la fuente que quiero, en este caso una de pixel
let miGif; // Variable para agregar el GIF
let frameInicioGif = 1; // Variable para guarda el frame en que empezó el gif
let boton = { x: 0, y: 0, ancho: 400, alto: 350 }; // Variable que determina la posicion x,y con el tamaño del boton
let marcoCamera; // Variable para la imagen que estara como marco
let imagenBoton; // variable para cargar la imagen de los botones
let cursorMano; // Variable para cargar la imagen del cursor
let imagenFinal; // Variable para cargar la imagen de reflexion
let elementos = []; // Array para elementos de la pantalla experienica
let bloqueado = true; // Variable para bloquear clicks en el tercer estado
const CLICS_NECESARIOS = 40; // variable para determinar los click que se haran para avanzar al tercer estado
let clicsPantalla = 0; // Variable que cuenta clics en cualquier parte
let clicsActuales = 0; //Variable que cuenta los clics ya hechos

// funcion para cargar los archivos antes de ocuparlos
function preload() {
  imagenBoton = loadImage("IMAGEN/text.png"); //  Cargo la imagen del boton
  marcoCamera = loadImage("IMAGEN/marco.png"); // Cargo la imagen del marco
  cursorMano = loadImage("IMAGEN/click.png"); //  Cargo la imagen del cursor
  miFuente = loadFont("FONT/pixel.ttf"); // Cargo la fuente de pixel
  imagenTexto = loadImage("IMAGEN/stop.png"); // Cargo imagen para el elemento
  imagenFinal = loadImage("IMAGEN/atardecer.jpg"); // Cargo imagen final de la interaccion
  miGif = loadImage("IMAGEN/ROJO.gif"); // Cargo el gif que usare en el ultimo estado
}

function setup() {
  pixelDensity(1); // Asigno el valor de la densidad del pixel
  createCanvas(windowWidth, windowHeight); // Crea un canvas del tamaño de la pantalla o ventana
  textAlign(CENTER, CENTER); // Agrego funcion para que los textos esten al centro
  noCursor(); // oculto el cursor normal para usar uno personalizado
  camara = createCapture(VIDEO); // Funcion para inicia la camara
  camara.hide(); // funcion para ocultar el elemento por defecto, la dibujamos nosotros
  posicionarBoton(); // Funcion para posicionar el boton que usaremos para pasar la pantalla
  actualizarBoton(); // Funcion para actualizar cada boton segun el estado
}

function cursorPersonalizado() {
  // Funcion para hacer mi cursor personalizado
  image(cursorMano, mouseX, mouseY, 50, 50); // Dibujo la mano pixeleada siguiendo la posición del mouse en tiempo real
}

function draw() {
  background(0); // Asigno el fondo negro
  switch (
    estado // Determino los estados y ocupo switch para que el programa dibuje segun su valor
  ) {
    case 1: // Para la primera pantalla seria el estado 1
      pantallaInicio(); // con la pantalla de inicio
      break;
    case 2: // Segundo estado
      pantallaExperiencia(); // Pantalla para la mayoria de interaccion
      break;
    case 3: // Tercer estado
      pantallaFinal(); // Para finalizar con la interaccion y volver al inicio
      break;
  }
  if (estado !== 2) {
    // si el estado es diferente al estado 2, se dibujo el boton, ya que en el estado 2 se utiliza la camara y para pasar al siguent estado lo haremos con clics
    dibujarBoton(); // dibuja el boton al cambiar de estado excepto el 2
  }
  cursorPersonalizado(); // Se dibuja el cursor personalizado en este caso una mano pixel
}

function posicionarBoton() {
  // funcion para ubicar el boton en el lienzo
  boton.x = width / 2 - boton.ancho / 2; // Calculo la posición x del botón para centrarlo horizontalmente, tomo el ancho total del canvas (width), lo divido en 2 para encontrar el centro,y se resto la mitad del ancho del botón para que quede justo en el medio
  boton.y = height / 2 - boton.alto / 2; // Se hace lo mismo en vertical
}

function dibujarBoton() {
  // funcion para mostrar el boton dibujado
  if (mouseEstaSobreBoton()) {
    // si el mouse esta sobre el boton
    tint(180); // se oscurece la imagen
  } else {
    // Si no esta encima del boton
    noTint(); //no se tinta y esta en su estado original
  }
  image(imagenBoton, boton.x, boton.y, boton.ancho, boton.alto); // dibuja la imagen escalada al tamaño del botón
  noTint(); // siempre resetear el oscurecer el boton
  // texto encima de la imagen
  fill(0); // Le asigno color negro al texto
  textSize(constrain(width * 0.025, 14, 20)); // Asigno el tamaño del texto responsivo, mínimo 14 y máximo 20
  text(boton.texto, boton.x + boton.ancho / 2, boton.y + boton.alto / 2); // Asigno el texto en el centro del botón
}

function mouseEstaSobreBoton() {
  // Función para comprobar si el cursor del mouse se encuentra sobre el botón
  return (
    mouseX > boton.x && // El mouse está a la derecha del borde izquierdo del botón
    mouseX < boton.x + boton.ancho && // El mouse está a la izquierda del borde derecho del botón
    mouseY > boton.y && // El mouse está debajo del borde superior del botón
    mouseY < boton.y + boton.alto // El mouse está sobre el borde inferior del botón
  );
}

//PANTALLAS

function pantallaInicio() {
  // Aplicamos el primer estado que seria el incio
  background(0); // Fondo de color negro
  fill(255); // Asigno el color Blanco para el texto
  textFont(miFuente); // Asigno mi fuente que carge anteriormente
  // TITULO
  textSize(constrain(width * 0.06, 16, 40)); // Funcion para adaptar el texto al diseño repsonsivo
  text("JUEGO DE LA IDENTIDAD", width / 2, height * 0.1); // Escribo el titulo del juego y su posicion en x,y
  //SUBTITULO
  fill(255, 192, 203); // Asigno el color rosado para el subtitulo como algo que se espera de lo femenino
  textSize(constrain(width * 0.06, 16, 40)); // Funcion para adaptar el texto al diseño repsonsivo
  text("´´femenina´´", width / 2, height * 0.15); // Escribo el subtitulo del juego y su posicion en x,y

  // INSTRUCCIONES
  fill(255); // Asigno el color blanco para el texto
  textSize(constrain(width * 0.04, 12, 22)); //Funcion para adaptar el texto al diseño repsonsivo
  text("PASOS:", width / 2, height * 0.28); // Escribo las instrucciones del juego y su posicion en x,y
  text("1. Haz clic en continuar", width / 2, height * 0.32); //Escribo el paso 1 del juego y su posicion en x,y
  text("2. Haz clic en la pantalla", width / 2, height * 0.39); // Escribo el paso 2 del juego y su posicion en x,y
}

//INTERACCION
function pantallaExperiencia() {
  // Colocamos el segundo estado que es donde se lleva a cabo la mayor interaccion
  background(0); // Asigno el fondo negro
  image(camara, 0, 0, width, height); // Coloco la camara en el lienzo
  aplicarPixelado(); // Aplico el efecto pixeleado para crear esta imagen distorsionada
  image(marcoCamera, 0, 0, width, height); //

  for (let e of elementos) {
    // funcion para recorrer cada elemento, actualizar su movimiento, dibujar la imagen y el texto en pantalla.
    e.x += e.velX; // Actualiza la posicion del texto sumando su velocidad en x,y ,lo que genera el efecto de movimiento en la pantalla
    e.y += e.velY;
    e.imgX += e.velX; // Actualiza la posicion del elemento sumando su velocidad en x,y para el movimiento en la pantalla
    e.imgY += e.velY;

    if (e.x < 0 || e.x > width) e.velX *= -1; // Si el elemento llega a un borde, invierte su dirección de movimiento, si ocurre, multiplica la velocidad por -1 para invertir la dirección y producir un efecto de rebote.
    if (e.y < 0 || e.y > height) e.velY *= -1;

    image(imagenTexto, e.imgX, e.imgY, e.imgTam, e.imgTam); // Dibuja la imagen del elemento en su posición actual utilizando el tamaño definido al momento de crear el elemento
    fill(255, 0, 0); // Asigno el color del texto en color rojo como presion
    textFont(miFuente); // Asigno mi fuente cargada previamente
    textSize(e.tam); // define el tamaño del texto según la propiedad tamaño de cada elemento
    noStroke(); // Elimino el contorno del elemnto
    text(e.palabra, e.x, e.y); // dibuja la palabra del elemento en la posición x,y
  }
}
//PIXELEADO
function aplicarPixelado() {
  let tamPixel = 150; // variable que determina la cantidad de pixeles

  image(camara, 0, 0, tamPixel, tamPixel); // dibuja la imagen de la cámara en un tamaño reducido definido por la variable tamPixel.
  copy(0, 0, tamPixel, tamPixel, 0, 0, width, height); // copia la imagen reducida y la agranda al tamaño completo del lienzo, generando el efecto de pixelado
}

// FINAL
function pantallaFinal() {
  image(imagenFinal, 0, 0, width, height); // Coloco la imagen final como fondo del ultimo estado

  // Compruebo si el GIF aún debe mostrarse
  if (frameCount - frameInicioGif < 100) {
    image(miGif, 0, 0, width, height); // Dibujo el GIF ocupando todo el lienzo
  } else {
    fill(255); // Asigno el color blanco al texto
    textFont(miFuente); // Asigno la fuente cargada anteriormente
    textSize(constrain(width * 0.06, 16, 56)); // Ajusto el tamaño del texto al tamaño de la ventana

    // srimer clic: aparece la primera reflexión
    if (clicsPantalla >= 1) {
      text("¿Qué tengo que hacer?", width / 2, height * 0.35);
    }

    // segundo clic: aparece la segunda reflexión sin borrar la primera
    if (clicsPantalla >= 2) {
      text("¿Quién soy?", width / 2, height * 0.15);
    }

    // tercer clic: aparece la tercera reflexión manteniendo las anteriores
    if (clicsPantalla >= 3) {
      text("¿Tanto cuesta ser feliz?", width / 2, height * 0.65);
    }
  }
}
// CAMBIAR DE ESTADO
function cambiarEstado() {
  // Compruebo si el usuario se encuentra en el estado de interacción
  if (estado === 2) {
    clicsActuales++; // Aumento el contador de clics realizados

    // Agrego un nuevo elemento al arreglo para que aparezca en la pantalla
    elementos.push({
      palabra: random([
        "Eso no te queda",
        "Haz esto",
        "Vas a terminar sola",
        "Debes casarte",
        "Para ser bella debes ver estrellas",
        "Debes bajar de peso",
        "Come esto",
        "Debes ser responsable",
        "Te verías bien si...",
        "Hace cosas de mujer",
        "Feminazi",
        "Para que provocas",
        "Aprende a cocinar",
        "Te recomiendo tomar pastillas",
        "",
      ]),

      x: random(width), // Asigno una posición aleatoria en X
      y: random(height), // Asigno una posición aleatoria en Y
      tam: random(0, 50), // Asigno un tamaño aleatorio para el texto

      imgX: random(width), // Asigno una posición aleatoria en X para la imagen
      imgY: random(height), // Asigno una posición aleatoria en Y para la imagen
      imgTam: random(50, 100), // Asigno un tamaño aleatorio para la imagen

      velX: random(-4, 4), // Asigno una velocidad horizontal aleatoria
      velY: random(-4, 4), // Asigno una velocidad vertical aleatoria
    });

    if (clicsActuales < CLICS_NECESARIOS) {
      // Compruebo si aún no se alcanza la cantidad de clics necesaria
      actualizarBoton();
      return; // Mantengo el estado actual hasta completar los clics
    }
    clicsActuales = 0; // Reinicio los contadores y elimino los elementos antes de pasar al siguiente estado
    elementos = [];
  }
  estado++; // Cambio al siguiente estado
  if (estado > 3) {
    estado = 1; // Si el estado supera el último, vuelve al primero
  }
  if (estado === 1) {
    // Al volver al inicio elimino los elementos restantes
    elementos = [];
  }

  if (estado === 3) {
    // Al entrar al estado final reinicio las variables necesarias
    bloqueado = true;
    clicsPantalla = 0;
    frameInicioGif = frameCount; // Guardo el fotograma en que comenzó el gif
  }

  // Actualizo el botón y su posición
  actualizarBoton();
  posicionarBoton();
}

// ACTUALIZAR BOTÓN
function actualizarBoton() {
  if (estado === 1) {
    // Compruebo el estado actual para cambiar el texto del botón
    boton.texto = "Continuar"; // En el estado inicial el botón permite comenzar la interacción
  } else if (estado === 2) {
    boton.texto = 0; // Oculto el texto del botón, ya que en este estado el usuario interactúa haciendo clic en la pantalla
  } else if (estado === 3) {
    boton.texto = "Volver al inicio"; // En el estado final el botón permite volver al inicio de la experiencia
  }
}

// DETECTAR CLIC
function mousePressed() {
  if (estado === 2) {
    cambiarEstado(); // Cada clic agrega un nuevo elemento y aumenta el contador de clics
  } else if (estado === 3 && bloqueado) {
    // Compruebo si el usuario se encuentra en el estado final y la reflexión aún está bloqueada

    clicsPantalla++; // Aumento el contador de clics realizados en la pantalla
    if (clicsPantalla >= 4) {
      // Al realizar cuatro clics se desbloquea el botón para volver al inicio
      bloqueado = false; // queda desbloqueado el boton
    }
  } else {
    // En cualquier otro caso, compruebo si el usuario hizo clic sobre el botón
    if (mouseEstaSobreBoton()) {
      cambiarEstado(); // Si el clic fue sobre el boton cambia al siguiente estado
    }
  }
}

// AJUSTAR EL LIENZO AL CAMBIAR EL TAMAÑO DE LA VENTANA
function windowResized() {
  resizeCanvas(windowWidth, windowHeight); // Ajusta el tamaño del lienzo al tamaño de la ventana
  posicionarBoton(); // Recalcula la posición del botón para mantenerlo centrado
}
``` 
