Enbabezados

    # esto es lo quivalente a un h1 ojo  hay que dejar espacio despues del #
    ## este es un equivalente a un h2
    ### este es el quivalente a un h3 y asi consecutivamente

# esto es lo quivalente a un h1 
## este es un equivalente a un h2
### este es el quivalente a un h3 y asi consecutivamente

Poner untexto en italica

    esto es un txto en *italica va entre*

 *esto es un txto en italica*

Texto en Negrita

    **Texto en negrita** 

Texto tachado

     ~~Texto tachado~~ 

 ~~tachado va entre~~ 

Listas Desordenadas

    * jonan
    * este es un subiten se se hace con una tabulacion y *
    * Jwssica
    *  estella

* jonan
  * este es un subiten se se hace con una tabulacion y *
* Jwssica
*  estella
  
Listas Ordenadas

      1. johan
         1. este es un subitem ordenado
      2. jessica
      3. estella

1. johan
   1. este es un subitem ordenado
2. jessica
3. estella


De la siguiente maneta es como se hace links:

     [texto del link ]seguido entre pa url donde apunta(https://github.com/perez28?tab=repositories "aqui puede  ir un texto que salga cuado posiciono el curso en el link")
[Mi github](https://github.com/perez28?tab=repositories "este es un titulo que aparece al poner el cursor en el link ")


para hacer citas se hace de la siguiente forma

    >este simbolo y seguido el texto de la cita
>esta es una cita

Para hacer una linea divisoria:

    Se pone --- ó ___

---

Para insertar una linea de codigo:

    `aqui va el codigo`

`console.log('hello word')`
Para poner un  bloque de codigo:

    ```aqui va el tipo de lenguaje que se esta utilizando. para qued aparezca con colores.
    Aqui va el bloque de codigo
    mas codigo
    ```
```javascript
function draw() {
  ctx.clearRect(0,0,WIDTH,HEIGHT);
  for (var i = 0; i < 100; i++) {
    ctx.beginPath();
    ctx.fillStyle = 'rgba(255,0,0,0.5)';
    ctx.arc(random(WIDTH), random(HEIGHT), random(50), 0, 2 * Math.PI);
    ctx.fill();
  }
}
```
Generacion de Tablas
    
    |:------:| centrado
    |-------:| alinenado a la Izquierda
    |`Jessi`   |resaltado
    |**papá**  | negrita

    |COLUMNA1|COLUMNA2|
    |--------|--------|
    |joan    |Jessi   |
    |mamá    |papá    |

|COLUMNA1|COLUMNA2|
|--------|--------|
|joan    |`Jessi`   |
|mamá    |**papá**  |

Generacion de Imagenes Remotas:

    ![Texto enlace ](Enlace donde esta la Imagen "Texta que aparece cuando posiciono el cursor en el texto enlace")

![Logo demi empresa](https://labarta.es/wp-content/uploads/2019/11/vscode-450x450.png "CosasInWeb")

Generacion de Imagenes Locales:

    ![Texto enlace ](Enlace local "Texta que aparece cuando posiciono el cursor en el texto enlace")

![Seguridad](seguridad.svg "CosasInWeb")


Reglas Github en Markdown

      * [x] Task 1
      * [ ] tarea 2
      * [ ] tarea3

* [x] Task 1
* [ ] tarea 2
* [ ] tarea3

Laforma para mencional a un usuario dentro de github

@emilio28 es mi colaborador :snowman:

Adicionar emojis
Para Adicionar emojis debemos ingresar aqui estan la lista de los emojis

    *[ emojisgithub ](https://gist.github.com/rxaviers/7360908)*

*[Lista emojisgithub ](https://gist.github.com/rxaviers/7360908)*







