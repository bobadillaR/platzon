# platzom

Platzom es una libreria para el curso de [platzi](platzi.com)

## Descripcion del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

## Instalacion

```
npm install platzom
```

## Uso

import platzom from 'platzom'

platzom('programar') // program

## Creditos

- Felipe Bobadilla

## Licencia

[MIT](https://opensource.org/licenses/MIT)
