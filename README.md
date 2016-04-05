# personalmarkdown-reference
_______________________________________
Personal referencia al lenguaje Markdown para uso personal o para alguien que no lo encuentre por internet.

_____________________________________
### Headings

```
# Esto es un H1
## Esto es un H2
### Esto es un H3
#### Esto es un H4
##### Esto es un H5
###### This is an H6

Esto tambien es un H1
==================

Esto tambien es un H2
------------------

```
# Esto es un H1
## Esto es un H2
### Esto es un H3
#### Esto es un H4
##### Esto es un H5
###### This is an H6

Esto tambien es un H1
==================

Esto tambien es un H2
------------------

_____________________________________

### Énfasis


```
*Enfatizar* _Enfatizar_
**Negrita** __Negrita__
~~Tachado~~
```

*Enfatizar* _Enfatizar_
**Negrita** __Negrita__
~~Tachado~~

_____________________________________

### Lista

```
* Item
* Item
- Item
- Item
```

* Item
* Item
- Item
- Item

### Lista numerada

```
1. Item
2. Item
```

1. Item
2. Item

### Lista Mixta

```
1. Item
2. Item
   * Mixed
   * Mixed  
3. Item
```

1. Item
2. Item
   * Mixed
   * Mixed  
3. Item

### Bloques

```
> Bloque de texto.
> > Bloque dentro de bloque.

> * Lista en bloque 1 
> * Lista en bloque 2
```

> Bloque de texto.
> > Bloque dentro de bloque.

> * Lista en bloque 1 
> * Lista en bloque 2

### Codigo

```
Referencia a codigo `Start()`.
`Esto es codigo`
```

Referencia a codigo `Start()`.

`Esto es codigo`

### Bloque de codigo

```
~~~~
Esto es una parte 
bloque de
codigo.
~~~~
```

```
```
Esto es una parte 
bloque de
codigo.
```
```

~~~~
Esto es una parte 
bloque de
codigo.
~~~~

```
Esto es una parte 
bloque de
codigo.
```

### Especificar codigo

```
```C#
void Start()
{
    //Esto es un comentario en C#
}

```
```

```C#
void Start()
{
    //Esto es un comentario en C#
}

```

### Link

```
Un [link](https://github.com "GitHub") a github.

https://github.com "GitHub

[GitHub](https://github.com "GitHub")
```

Un [link](https://github.com "GitHub") a github.

https://github.com "GitHub

[GitHub](https://github.com "GitHub")

### Referenciar links

```
Aqui referneciamos [un link][1] y
aqui otro [link][2].

[1]: https://github.com "GitHub"
[2]: https://github.io "GitHub io"
```

Aqui referneciamos [un link][1] y
aqui otro [link][2].

[1]: https://github.com "GitHub"
[2]: https://github.io "GitHub io"

### Imagenes

```
![Img](https://github.com/lPinchol/personalmarkdown-reference/LogPreview.jpg "Img")
![Img](/LogPreview.jpg)
[![Img](/LogPreview.jpg)](http://www.pixiv.net/member_illust.php?mode=medium&illust_id=54719529 "サメヤマ次郎")
![Img][1]

[1]: https://github.com/lPinchol/personalmarkdown-reference/LogPreview.jpg "Img"
```

![Img](https://github.com/lPinchol/personalmarkdown-reference/LogPreview.jpg "Img")
![Img](/LogPreview.jpg)
[![Img](/LogPreview.jpg)](http://www.pixiv.net/member_illust.php?mode=medium&illust_id=54719529 "サメヤマ次郎")
![Img][1]

[1]: https://github.com/lPinchol/personalmarkdown-reference/LogPreview.jpg "Img"

### Tablas

```
| Version     | Estado    | Bugs |
| --------|---------|-------|
| 1.0.0  | Estable   | 0 bugs    |
| 2.0.0 | No Estable | 12 bugs    |

| Version | Estado    | Bugs   |
| --------|-----------|--------|
| 1.0.0   | Estable   | 0 bugs |
| 2.0.0   | No Estable| 12 bugs|
```

| Version     | Estado    | Bugs |
| --------|---------|-------|
| 1.0.0  | Estable   | 0 bugs    |
| 2.0.0 | No Estable | 12 bugs    |

| Version | Estado    | Bugs   |
| --------|-----------|--------|
| 1.0.0   | Estable   | 0 bugs |
| 2.0.0   | No Estable| 12 bugs|

### 