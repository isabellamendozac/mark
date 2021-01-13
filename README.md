<!-- HEADINGS , esto en un comentario y los de abajo son los tipos de encabezado-->

# my title (h1)
## my second title (h2)
### my title h3
#### my title h4
##### my title h5
###### my title h6
<!-- Para generar un texto en italica se escibre el texto entre asteriscos *texto*-->

this is an *italic* text
<!-- Para generar un texto en negrita (strong) se escibre el texto entre dos asteriscos **texto**-->

this is an **strong** text
<!-- Para generar un texto tachado (strikethrough) se escribe el texto entre dos ~~ ~~texto~~-->
esto es ~~un texto tachado~~

## Listas
<!-- Lista desordenada-->
* manzana
    * otro item
* naranja
* etc
<!-- Lista ordenada-->

1. manzana
    1. manzana dos
2. naranja
3. etc

## Enlaces
<!-- Pagina web como hipertexto [nombre pagina](enlace)-->
[faztweb.com](https://www.faztweb.com)

<!-- Para no mostrar el enlace hipertexto [nombre pagina](enlace "lo que quiero que diga")-->

[faztweb.com](https://www.faztweb.com "lo que quiero mostrar")

## Citas
<!-- Como generar citas > cita-->
> this is a quote
## Separaciones
---
___

## Para  escribir lineas de  código
`console.log('hello world') `

## Para  escribir bloques  de  código
<!-- Se abre y cierra el bloque con tres tildes ``` y seguido se especifica el lenguaje d eprogramación-->

```c
void bubbleSort(int vector_entrada[], int n){
    int i,j;
    for(i=0; i<n; i++){
        for(j=0; j<n-i-1; j++){
            if(vector_entrada[j]<vector_entrada[j+1])
                cambiar_pos(&vector_entrada[j],&vector_entrada[j+1]);
        }
    }
}
```

```python
print("hello world")
``` 

## Tablas
| Tables | Are  | Cool      |
|--------|:----- | ----      | 
|1  |2    |      2|
|Esta es|una|tabla|


## Imagenes
![visual studio code logo](https://user-images.githubusercontent.com/674621/71187801-14e60a80-2280-11ea-94c9-e56576f76baf.png "vscode logo")

<!-- GITHUB MARDOWN-->
### To do List
* [x] Task 1
* [] Task 1
* [x]









