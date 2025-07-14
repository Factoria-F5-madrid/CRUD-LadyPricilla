#  **Investigación sobre Django**
![Texto alternativo](https://ws.apms.io/api/_files/NydJSQz2pxfUmD5yTEe2FR/download/)

##  **Parte 1: Aplicación CRUD y Django**
**1. ¿Qué es un CRUD  y cuál es su propósito en el desarrollo de aplicaciones web?** <br><br>
   Es un acrÓnimo que representa las operaciones básicas que pueden realizar dobre los datos:
   * **C** = Create 
   * **R** = Read
   * **U** = Update
   * **D** = Delete
      
   Su propósito es manejar datos(base datos) , diseñar interfaces(formularios, etc), organización
   del código(crear APIS).<br>
   **Ejemplo:**<br>
   La app de Amazon que usamso en el mobil es un ejemplo de un CRUD ya que te permite 
   CREATE  una cuenta, agregar productos, READ  navegar por productos, lees descripciones,
   etc.Ademas te permite UPDATE , cambiar tu direccion,<br> modificar el carrito y hacer 
   un DELETE, eliminar productos de un carrito, cancelar pedidos, etc. <br><br>
**2. ¿Qué son los patrones  de arquitectura en desarrollo de software?** <br><br> 
   Es una guia a seguir(ex. planos) para construir nuestras aplicaciones de la manera más organizada sea más facil de
   <br> 
   mantener  en un futuro.<br><br>
   **¿Qué es el patrón MVC (Modelo–Vista–Controlador)?**  
      Divide la app en tres partes: datos(modelo), pantalla(vista) y vista lógica(controlador)<br>
    **¿Qué es el patrón MVT (Modelo–Vista–Template)?**  
     Es una forma de construir aplicaciones web. Se divide en tres partes:logica datos(modelo), logica de 
     presentación(vista)<br> 
     y la   manera como se muestran los datos al usuario (Template). Es utilizado por el framework  Django<br>
    **Diferencias entre MVC y MVT**<br>
     En MVC, el **Controlador** es quien maneja la lógica de la aplicación y decide que mostrar.
     Mientras que en  **MVT** la lógica la maneja la **Vista**  y el **Template** se encargade mostrar los datos.<br>
    **¿Cuál de estos dos patrones se usa en Django?**<br>
     Django utiliza el **MVT** tu defines el modelo , la vista( lógica ) y el template( con HTML) y Django conecta 
     todo.
     
   
   
   
   .
