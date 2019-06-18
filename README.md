# graficos_vectoriales
Un pequeño repositorio para poder documentar todo lo aprendido acerca de las animaciones en javascript con svg

#sitios de interes para leer

Web de Sara Soueidan

Web de CSS Tricks (Chris Coyier)

Compendio de artículos de SVG en CSS Tricks

Libro de Chris Coyier sobre SVG

Web de Val Head

Web de Rachel Nabors

Portafolio de Chris Gannon

Portafolio de Dan Klammer

Web de Jorge Aznar

Libro sobre SVG de Jorge Aznar

Libro online sobre SVG (SVG Pocket Guide)

Contenidos sobre SVG de Mozilla Developer Network

## Etiquetas y aributos básicos

```html
//Por de fecto la etiqueta svg tiene un widht y un height, siempre hay que ponerle por css una
<svg width="600" height="400">
    //Etiquetas
    //Etiqueta rectangulo
    <rect x="50" y="100"
        width="200" height="80" fill="blue" />
    
    // Etiqueta circulo
    <circle cx="50" cy="100" r="100" fill="yellow" />

     // Etiqueta ellipce
    <ellipce cx="50" cy="100" rx="50" ry="100" fill="yellow" />
</svg>
```
## Estilos en svg
```css
//
Propiedades como:
**stroke** : Color del borde
**stroke-width** : grueso del borde
**stroke-linejoin** 
//esto tambien funciona con estilos en css
```
## Etiqueta de línea polilinea y poligono


<------------------------>
## 


Foobar is a Python library for dealing with word pluralization.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)