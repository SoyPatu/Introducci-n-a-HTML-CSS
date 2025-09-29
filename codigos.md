# Ejemplos de códigos

### 1. Esctructura básica en HTML
```  bash
<!DOCTYPE html>
<html lang="es">
<head>
      <title>Título de la página</title>
</head>
<body>
      <h1>Encabezado principal</h1>
      <p>Este es un párrafo.</p>
</body>
</html>
``` 

### 2. Etiquetas
```  bash
<h1> - <h6> : Encabezados 
<p>: Párrafos.
<a> : Enlaces.
<img>  : Imágenes.
<li> : Listas.
<div> y <span> : Contenedores genéricos.
``` 

### 3. Atributos

- lang
```  bash
<html lang="es">
``` 

- href
```  bash
<a href="https://google.com">Ir a Google</a
``` 

- scr y alt
```  bash
<img src="cars.jpg" alt="Cars" width="200">
``` 

- style
```  bash
<!<p style="color:red;">Texto en rojo</p>
``` 

### 4. Listado de etiquetas mas utilizadas
```  bash
Texto: <h1>...<h6>, <p>, <span>, <strong>, <em>.
Estructura: <div>, <section>, <header>, <footer>, <nav>.
Listas: <ul>, <ol>, <li>.
Enlaces: <a href="...">.
Multimedia: <img>, <video>, <audio>.
Tablas: <table>, <tr>, <td>, <th>.
Formularios: <form>, <input>, <textarea>, <button>.
``` 

### 5. Etiquetas Lineales
```  bash
<span>(estilo)
<a> (enlace)
<img> (imagen)
<strong> (negrita)
<em> (cursiva)
``` 

### 5. Etiquetas en Bloques
```  bash
<div> (dividir)
<p> (párrafo)
<h1> ... <h6> (títulos)
<section> (seccion)
<article> (Contenido independiente)
<header> (Encabezado)
 <footer> (Pie de pagina)
``` 

### 6. Modelo de Caja
```  bash
<p style="
    background: lightblue;
    padding: 20px;
    border: 5px solid blue;
    margin: 15px;">
 ¡Hola, soy un párrafo dentro de una caja!
</p>
``` 

### 7. Unidades absolutas

```  bash
p { font-size: 16px; margin: 10mm;}
``` 

### 8. Unidades relativas
```  bash
div 
{
  width: 50%;      /* ocupa la mitad del contenedor */
  font-size: 1.2em; /* 20% más grande que la fuente padre */
  margin: 2vh;      /* depende del alto de la ventana */
  padding: 10px;    /* tamaño fijo en píxeles */
}
```

### 9. Propiedades básicas en CSS: Color, Tipografía, Alineación y Caja

- Color
```  bash
p { color: red; }
```
```  bash
div { background-color: lightblue; }
```

- Tipografía
```  bash
- font-family: define la fuente (Arial, Times, etc.).

- font-size: tamaño de la letra.

- font-weight: grosor (normal, bold, 100–900).

- font-style: estilo (normal, italic).

- line-height: altura de línea.
```

- Alineación de texto
```  bash
- text-align: alineación horizontal (left, right, center, justify).

- vertical-align: alineación vertical (middle, top, bottom en elementos en línea o celdas de tabla).
```

- Caja (Box Model)
```  bash
- margin: espacio externo alrededor del elemento.

- padding: espacio interno entre el contenido y el borde.

- border: borde del elemento.

- width y height: dimensiones del elemento.
```

### 10. Propiedad display

- Inline
```  bash
span { display: none; }
```
- Block
```  bash
div { display: flex; }
```
- Inline-block
```  bash
div { display: flex; }
```

### 11. Responsive Design

- Unidades relativas
```  bash
%, em, rem, vw, vh → tamaños que dependen de la pantalla o del contenedor.

```
- Media Queries
```  bash
@media (max-width: 600px) 
{
  body { background-color: lightgreen; }
}
```


- Layouts flexibles

```  bash
img { max-width: 100%; height: auto; }
``` 





