# ProyectoIADeepArt
Proyecto del curso Inteligencia Artificial.
<!-- PROJECT LOGO -->
<br />
<p align="center">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Proyecto DeepArt utilizando la red VGG19</h3>

  <p align="center">
    Kevin Díaz Torres
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Índice</h2></summary>
  <ol>
    <li>
      <a href="#Sobre-el-proyecto">Sobre el proyecto</a>
      <ul>
        <li><a href="#run">Como hacerlo funcionar</a></li>
      </ul>
    </li>
    <li>
      <a href="#Como-empezar">Como empezar</a>
      <ul>
        <li><a href="#prerequisitos">Prerequisitos</a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- SOBRE EL PROYECTO -->
## Sobre el proyecto

Es un proyecto en el cual se transfiere el estilo de imágenes (principalmente obras de arte impresionistas) 
a una imagen cualquiera. De tal forma el programa a través de la red neuronal VGG19 (https://arxiv.org/abs/1409.1556) identifica la complejidad que compone a la imagen 
que contiene el estilo (llamaremos imagen estilo) y a la imagen cualquiera (que llamaremos imagen contenido). Una vez identificada la complejitud se procede a traspasar
la imformación mediante un proceso de optimización de manera iterativa.


### Como hacerlo funcionar

* Abrir el archivo DeepArt.ipynb seleccionar la imagen contenido y la imagen estilo a utilizar, de preferencia almacener en la carpeta entrada y estilo
respectivamente y compilar reiniciando el kernel.

<!-- COMO EMPEZAR-->
## Como Empezar
Creamos un entorno virtual, ya sea con dockers o anaconda con los siguientes requisitos:

### Prerequisitos
-Crear un entorno virtual en anaconda o docker con las siguientes versiones:
* Python=3.9
* Tensorflow=2.6.0
* Keras=2.6.0
* Matplotlib
* Numpy
