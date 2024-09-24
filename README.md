# _Etiquetas Básicas de Markdown_  


## Encabezados  
# Esto es un encabezado h1
## Esto es un encabezado h2
### Esto es un encabezado h3
#### Esto es un encabezado h4
##### Esto es un encabezado h5
###### Esto es un encabezado h6  

## Negrita y cursiva
**Texto en negrita**  
_Texto en cursiva_  

## Resaltar un comando
`ls -la`  

## Bloques de código
```
sudo systemctl start apache2
```

```bash
#!/bin/bash
echo "Hola mundo"
```

```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```

```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```

## Enlaces
[Enlace a la página web del IES Celia Viñas](https://iescelia.org)

Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

[1]: https://iescelia.org
[2]: https://github.com  

## Imágenes
![](https://iescelia.org/web/wp-content/uploads/2012/05/iescelia_1950.jpg)  


## Listas
### Desordenadas
* Item 1
* Item 2
* Item 3
* Item 4
### Desordenadas anidadas
* Item 1
  * Item 1.1
  * Item 1.2
* Item 2
  * Item 2.1
* Item 3
* Item 4
### Ordenadas
1. Item 1
2. Item 2
3. Item 3
4. Item 4
### Ordenadas anidadas
1. Item 1  
  1.1 Item 1.1  
  1.2 Item 1.2  
2. Item 2  
  2.1 Item 2.1  
3. Item 3  
4. Item 4

## Tablas
| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| --- | --- | --- |
| Fila 1.1 | Fila 1.2 | Fila 1.3 |
| Fila 2.1 | Fila 2.2 | Fila 2.3 |
| Fila 3.1 | Fila 3.2 | Fila 3.3 |

## Forzar salto de linea
Por ejemplo, en esta frase  
hemos forzado un salto de linea.

## Citar textos
Este texto no es una cita.
> Este texto daría como resultado una cita.

## Comentarios
Párrafo 1.

<!-- Este texto es un comentario y no será renderizado -->

Párrafo 2.  


# _Ejercicios extra_
Imágen externa:  
![](https://pbs.twimg.com/media/FnuBEI9XkAAW4n9.png)

Imágen carpeta _images_:
![](images\gatofumon.png)

Enlace al nuevo [documento][3]

[3]: Documento.md
