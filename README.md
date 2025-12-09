# PRUEBA-INDIVIDUAL-RA2---HTML-CSS
## Ejercicio 1
### 1A
Porque el "text-aling: center" solo centra el texto dentro del h1, no el elemento "h1" como tal.
### 1B
FlexBox:
Simplemente he cambiado el "justify-content: space-between" por "center" para que deje de haber espacio entre el h1 y el nav.
.site-header {
  display: flex;
  justify-content: center;
  align-items: center;
}

h1 {
  text-align: center;
}

CSS Grid:
Lo mismo pero con el Grid.
.site-header {
  display: grid;
  justify-content: center;
  align-items: center;
}

h1 {
  text-align: center;
}
### 1C
Le he puesto la separación indicada, he añadido texto plano para poder ver que está alineado y está todo perfectamente alineado.
.site-header {
  display: grid;
  justify-items: center;
  align-items: center;
  gap: 30px;
}

h1 {
  text-align: center;
}
### 1D
He creado una caja con su color de fondo, su padding para que no quede pegado a los bordes, su borde por abajo y su sombra.
.site-header {
  display: grid;
  justify-items: center;
  align-items: center;
  gap: 30px;
  background-color: #f46464;                
  padding: 20px 40px;                      
  border-bottom: 1px solid rgba(0, 183, 255, 0.1); 
  box-shadow: 0 10px 8px rgba(33, 4, 255, 0.1);  
}

h1 {
  text-align: center;
}

## Ejercicio 2
Todo el botón de Hamburguesa y el menú lateral lo introducí en el Header simplemente conrtando el boton y el menú y copiandolo en el header.
En el CSS, he añadido "flex: 1; text-align: center;" en el ".site-header h1" para poder conseguir que se ocupa el espacio central y centra su texto.

## Ejercicio 3
### 3A
Simplemente he añadido que cuando hagas click a la imagen de alguna habilidad, te mande a esa habilidad.
### 3B
Ya lo tenía en mi página pero he cambiado el "transform:scale".
### 3C
Ya lo tenia.

## Ejercicio 4
### 4.1
Mi web trata sobre un personaje (Volibear) de un juego llamado League of Leyends, donde intento enseñar las mejores estrategias con ese personaje.
En esta he includo un video donde introduce un poco al personaje como por ejemplo sus habilidades, los itemes que recomiendo que te compres (build) y runas, las mejores rutas de la jungla y consejos y combos.
Mi idea era un diseño bonito pero sencillo, para que todo el mundo pueda ver la web de forma muy sencilla pero elegante y creo que lo he conseguido.
### 4.2
**Header:** Contiene el logo, menú principal y botón hamburguesa.
<img width="719" height="619" alt="image" src="https://github.com/user-attachments/assets/fb291db7-2ff5-489d-82f3-7b16c5b11c92" />

**Main:** Agrupa todo el contenido central.
<img width="1009" height="816" alt="image" src="https://github.com/user-attachments/assets/07aea0f3-4283-4a24-88fb-191ea82365a9" />

**Section:** Divide el contenido en temas claros.
<img width="995" height="810" alt="image" src="https://github.com/user-attachments/assets/93d4f4ca-78ab-4090-8bdc-e6b1d35171b9" />

**Footer:** Cierra con enlace de regreso al principio.
<img width="663" height="106" alt="image" src="https://github.com/user-attachments/assets/af5eff56-7988-45b9-b00d-7eda4718b322" />

**El menú superior:** Permite moverse a través de la página de forma rápida y sencilla.
<img width="532" height="299" alt="image" src="https://github.com/user-attachments/assets/1a605f90-7a74-4e08-9617-7b23fc065b03" />

**El menú lateral:** Lo mismo que el menú superior.
<img width="694" height="324" alt="image" src="https://github.com/user-attachments/assets/74580218-666b-4104-9b50-daf91dc869db" />

**La sección hero:** Una sección para introducir al personaje con una foto que tiene un enlace a un video.
<img width="998" height="157" alt="image" src="https://github.com/user-attachments/assets/b0eed91f-cf40-4cfe-b0d8-45ff2c9efa10" />

**La tabla:** Una tabla con 2 columnas en la que tenemos los items recomendados y lo que te aportan. Utiliza "thead" para encabezados y "tbody" para el contenido.
<img width="983" height="330" alt="image" src="https://github.com/user-attachments/assets/8a0b798a-5842-401c-9896-8845ab19e4d0" />

**La galería de imágenes:** Imágenes de las habilidades del personaje y cada habilidad te manda a la foto ampliada.
<img width="988" height="813" alt="image" src="https://github.com/user-attachments/assets/35afe501-474a-490d-aaeb-61990c282eaa" />

**Enlaces internos y externos:** Enlaces internos hay bastantes para poder navegar en la página como por ejemlpo los menús y como enlace externo tengo el video de youtube explicando un poco el personaje.
<img width="981" height="553" alt="image" src="https://github.com/user-attachments/assets/fcc2c991-e7f7-4830-bca2-90631e614b1a" />

### 4.3
**Selector de tipo:** 

body {
  font-family: system-ui, -apple-system, "Segoe UI", sans-serif;
  line-height: 1.5;
  background: #0f1720;
  color: #e6eef6;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 12px;
}

**Selector de clase:**

.site-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 20px;
  background: #111c2c;
  position: sticky;
  top: 0;
  z-index: 10;
}

.main-nav a {
  text-decoration: none;
  color: #9aa6b2;
  padding: 6px 10px;
  border-radius: 6px;
}

**Selector de ID:**

#hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  margin-bottom: 30px;
}

#hero img {
  max-width: 100%;
  border-radius: 12px;
  margin-top: 12px;
}

**Selector descendente:**

.site-header h1 {
  color: #f59e0b;
  font-size: 1.6rem;
  margin: 0 50px;
  flex: 1;
  text-align: center;
}

.main-nav ul {
  list-style: none;
  display: flex;
  gap: 12px;
}

.habilidades {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 12px;
}

**Pseudoclases:**

.main-nav a:hover {
  color: #fff;
  background: rgba(255, 255, 255, 0.05);
}

figure img:hover {
  transform: scale(1.1);
  box-shadow: 0 4px 20px rgba(5, 150, 200, 0.6);
}

#hero img:hover {
  transform: scale(1.05);
  cursor: pointer;
}

.side-menu a:hover {
  color: #fff;
  background: rgba(255, 255, 255, 0.05);
}

.open-menu.active {
  background: #f59e0b;
  color: #0f1720;
}

*::before, *::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

**Flexbox y Grid:**

.site-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 20px;
}

.main-nav ul {
  list-style: none;
  display: flex;
  gap: 12px;
}

#hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.habilidades {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 12px;
  margin-top: 12px;
}

**Sombras:**

figure img:hover {
  transform: scale(1.1);
  box-shadow: 0 4px 20px rgba(5, 150, 200, 0.6);
}

**Estilos de menús:**

.main-nav a {
  text-decoration: none;
  color: #9aa6b2;
  padding: 6px 10px;
  border-radius: 6px;
}

.main-nav a:hover {
  color: #fff;
  background: rgba(255, 255, 255, 0.05);
}

.side-menu {
  position: fixed;
  top: 0;
  left: -230px;
  width: 230px;
  height: 100%;
  background: #111c2c;
  padding-top: 60px;
  transition: left 0.3s ease;
  z-index: 15;
}

.side-menu.active {
  left: 0;
}

**Objetivo:** Con este diseño he intentado conseguir un diseño interactivo, entretendido y nada monótomo. Con las interacciones cuando pasas el ratón por encima o los vídeos. Hacer un diseño tanto para ordenadores como para dispositivos móviles.

### 4.4
No he utilizado ninguna fuente porque sinceramente no me he dado cuenta de que había que utilizar una diferente.

### 4.5
Cuando pulsas el botón, se ejecuta la función y se añade la clase "active" lo que hace que se despliegue el menú y el boton de hamburguesa cambie a una cruz.
Así sería el CSS:

.side-menu {
  position: fixed;
  left: -230px;
  transition: left 0.3s ease;
}

.side-menu.active {
  left: 0;
}

### 4.6
He aprendido mucho sobre los menús y detalles que hacen que la página poco a poco vaya quedando mucho más profesional.
Me gustaría mejorar sobre todo mi imaginación ya que me cuesta mucho saber que más añadir para que quede más bonita.
Lo que más me ha costado ha sido la parte de las habilidades.
También ha sido la parte que más me ha gustado ya que creo que es a la que más tiempo le he dedicado, la que más bonita está y con la que más he aprendido.
