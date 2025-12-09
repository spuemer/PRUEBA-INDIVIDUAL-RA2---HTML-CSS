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

### 3B

