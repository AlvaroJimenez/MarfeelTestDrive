### 1. CSS Selectors

* Select an __IMG__ element
```  
img{
}
``` 
* Select all __H2__ elements
```
h2 
{ 
}
```
* Select all __A__ elements that have the attribute _title_
```
A[title] {

}

```
* Select only the __IMG__ elements that are inside an __A__ element
```
A img{
}
```
* Select all elements with class _lv24noticia_
```
._lv24noticia_
{ 

}
```
* Select all _l24noticia_ from the middle and right column, but not from the left column
```
._lv24noticia colA last right+colAB2 last

```
* Select the 4th and 5th _lv24noticia_ from the left column
```
.lv24noticia colAB2
```
* Select the logo of the website
```
a[title="La Vanguardia.com"] {   

}
```
* Select all __IMG__ elements whose _SRC_ attribute is a _GIF_ file
img[src$=".gif"]{
}
* Select all elements that are __NOT__ inside the three columns
```
#pub_ist_layer{
}
```


### 2. Pick any __IMG__ and __A__ element and replace them for any other element of your choice
```
a.foto{
  
  background: url(http://...) ;

}
```

### 3. What is CSS minification?
  Is the process of removing all unnecessary characters from source code without changing its functionality

### 4. What is CSS compression?
Optimize the source code

### 5. Explain the difference between position static, relative, absolute and fixed
*static: Los elementos se van colocando uno a continuación del otro
*absolute: Los elementos se colocan sin influencia de los otros. Son colocados mediantes coordenadas.
*relative: Son colocados con relación a su posicion natural.
*fixed: Son colacodos relativamente a la ventana del navegador.

### 6. What are data URIs? When would you use them?

### 7. Using jQuery...

* Add a 10px red border around all __IMG__ elements 
* Fade out all __IMG__ elements
* Add a 10px red border around all __IMG__ and fade out the images after 3 seconds
