<!-- Encabezado -->
# **Encabezado**    
`# Mi titulo`   
# Mi titulo h1
## Mi titulo h2
### Mi titulo h3
#### Mi titulo h4
##### Mi titulo h5
###### Mi titulo h6

<!-- Italic -->
# **Cursiva**   
` *italic* `    
this is an *italic* text

`_italic_`    
this is an _italic_ text

<!-- Strong -->
# **Negrita**  
`**strong**`  
this is an **strong** text

`__strong__`  
this is an __strong__ text 

<!-- Italic and Strong -->
# **Negrita y Cursiva**
`**_negrita y cursiva_**`  
**_negrita y cursiva_**

`***negrita y cursiva***`  
***negrita y cursiva***

<!-- Strikethrough -->
# **Tache**  
`~~~strikethrough~~~`  
this is a ~~striketrough~~ text

<!-- List -->
# **Lista**
<!-- Unordered list -->
### **Lista desordenada**
`* apple/- orange/+ etc`
* apple
    * apple
- orange
    - orange
+ etc
    + etc

<!-- Sorted list -->       
### **Lista ordenada**
1. apple
    1. apple

2. orange 

    2. orange 

3. etc
    
    3. etc 
 
<!-- Enlaces -->
# **Enlaces**
`[aqui va el nombre del sitio web](aqui va el enlace "aqui va el nombre que quieras que aparezca en el enlace")`  
[faztweb.com](https://www.faztweb.com "hello xd")


`<Aqui pones tu correo>`  
<antonellapozo23@gmail.com>


```
[Enlace 1][1], [Enlace 2][2], [Enlace 3][3]  

[1]: link
[2]: link
[3]: link
```

[Enlace 1][1], [Enlace 2][2], [Enlace 3][3]

 [1]: http://joedicastro.com/consejos
 [2]: http://joedicastro.com/consejos "Consejos"
 [3]: http://joedicastro.com/

<!-- Citas -->
# **Citas**
`> This is quote`
> This is quote

`>>> This is other quote`  
>>> This is other quote 


<!-- Lineas -->
# **Lineas**  
---
___


<!-- Codigo -->
# **Código**
Para poner código lo ponemos entre tildes graves (Alt+96):   
`console.log('hello world')`


### **Cuadros negros**
Aqui podemos poner varias lineas de codigo, poniendo tres acentos graves al incio y final:   

``` 
const mongoose = require('mongoose');
```
y si queremos que la linea de codigo salga con colores le ponemos el nombre del codigo que pertenece:

```python
print("hello world")
```

```HTML
<h1>hello world</h1>
```

<!-- Tablas -->
# **Tablas**
| Nombre | Pais | Edad |
| ------ | ---- | ---- |
| Anna   | Peru | 16   |
| Pepe   | Peru | 18   |


<!-- GITHUB MARKDOWN -->
# **Tareas**  
```
* [x] Task 1
* [ ] Task 2
* [ ] Task 3
```  

* [x] Task 1
* [ ] Task 2
* [ ] Task 3

<!-- Imagen -->
# **Imagen**
La primera forma de poner una imagen es:   
`![aqui va el nombre](aqui va la direccion de la imagen)`
![visual studio code logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png)

La segunda forma es:  
`![aqui va el nombre](aqui va el nombre de como lo guardaste en la carpeta de markdown + png)`

![visual studio code logo](vscode.png "vscode logo")

<!-- Badges -->
### **Badges**  
Los links de los badges se encuentran en [Badges](https://dev.to/envoy_/150-badges-for-github-pnk "badges")

![twitch](https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white "twitch")

![youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white "youtube")

![Github](https://img.shields.io/github/followers/adripozo?style=social "Mis seguidores")

<!-- Emojis -->
# **Emojis**  
`:cry:`  
:cry:  :smile:  :angry:  

<!-- Video -->
# **Video**
- En markdown no se puede insertar un video, sin embargo podemos disimular uno.

[![](aqui va la imagen de la miniatura del video https://img.youtube.com/vi/***aqui se pone el ID del video***/maxresdefault.jpg ***o si lo quieres más pequeño la img ponemos:*** /hqdefault.jpg)](aqui va el link del video)

[![ve aqui el video](https://img.youtube.com/vi/1BzzckYqT9w/hqdefault.jpg)](https://www.youtube.com/watch?v=1BzzckYqT9w)


<!-- Diagramas de flujo -->
# **Diagramas de flujo**
- Podemos utilizar mermaid

[![](https://mermaid.ink/img/pako:eNpVkTFuwzAMRa9CaI4v4CGD4XrrVKSTFkJiWiI2lVJykCLIqXqEXqyUGwOOoIHQIz_Fz5sLKZJrXaavmSRQz_ihOHkBO14wlKRwAMxwyKRevJxRCwc-oxQYKhg0Wfgi8Zl1lXUYThXBM-sfMBNEu1hSrtJeDtDs9ybbWtGF04YOC-mMvOPIEQP__siGdwvvlwRSPrLNAyMCXTkXm4wRagNLaFahvlZCSKoU1h7No7uqzU1SFS6bfm7nJtIJOZpnt-qSd-WTJvKutTCinrzzcrc8nEt6-5bg2qIz7dx8tp-u_rr2iGO2V4psDr_-L2HZxf0PZBGIGQ)](https://mermaid.live/edit#pako:eNpVkTFuwzAMRa9CaI4v4CGD4XrrVKSTFkJiWiI2lVJykCLIqXqEXqyUGwOOoIHQIz_Fz5sLKZJrXaavmSRQz_ihOHkBO14wlKRwAMxwyKRevJxRCwc-oxQYKhg0Wfgi8Zl1lXUYThXBM-sfMBNEu1hSrtJeDtDs9ybbWtGF04YOC-mMvOPIEQP__siGdwvvlwRSPrLNAyMCXTkXm4wRagNLaFahvlZCSKoU1h7No7uqzU1SFS6bfm7nJtIJOZpnt-qSd-WTJvKutTCinrzzcrc8nEt6-5bg2qIz7dx8tp-u_rr2iGO2V4psDr_-L2HZxf0PZBGIGQ)


<!-- Md y HTML -->
# **Combinación de Markdown y HTML**
### **Imagen**
- Debido a que en markdown no se puede modificar el tamaño de la imagen vamos a usar html en un archivo md. Aunque esto funciona, es recomendable usar solo md para archivos md.

`<img src="Aqui va el link" width=N°px height=N°px>`  

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png" width=50px height=50px>

### **Subrayado**
`<ins>Aqui va el texto</ins>`  
<ins>texto subrayado</ins> 

### **Alineado al centro**
`<center>Aqui va el texto</center>`  
<center>texto al centro</center>

### **Subrayado y al centro**
`<center><ins>Aqui va el texto</ins></center>`   
<center><ins>texto subrayado y al centro</ins></center>


### **Color**
`<p style="color:color que deseas">Aqui va el texto</p>`  
<p style="color:orange">texto de color</p>


