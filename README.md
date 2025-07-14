#  **Investigación sobre Django**
![Texto alternativo](https://ws.apms.io/api/_files/NydJSQz2pxfUmD5yTEe2FR/download/)

##  **Parte 1: Aplicación CRUD y Django**
**1. ¿Qué es un CRUD  y cuál es su propósito en el desarrollo de aplicaciones web?** <br><br>
   Es un acrónimo que representa las operaciones básicas que pueden realizar dobre los datos:
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
     todo.<br><br>
 **3. ¿Cómo se estructura un proyecto en Django? Explicar brevemente el rol de los 
    modelos, vistas, templates y URLs.**  
    Cuando creas un proyecto en **Django** se divide en **modulos(apps)** y cada app tiene un componente clave.<br> 
    Django tiene los siguientes componentes
 * **Modelos**:
       Definen los datos que se guardan en la base de datos.(Una entidad con sus atributos)
 * **Vistas**:
       Procesan la logica y deciden que mostrar. (Mostrar los productos disponibles)
 * **Templates**: 
       Son las páginas HTML que ve el usuario (Una pagina con fotos, precios de los productos)
 * **URLs**: 
       Conectan direcciones web con vistas (/productos/ muestra la lista de productos).
  
 <p align="left">
     <img src="image.png" alt="Estructura de Django" width="300"/>
 </p>
 
   **¿Para qué se usa el signo “%%” en los templates?** <br>
    Se usa para **Evitar errores** cuando el simbolo  % podria confuncdirse con instrucciones de formato.
    El doble %% se convierte en un solo % cuando se muestra.<br>
    Ex.<br>
    mensaje = "Descuento del 20%%"<br>
**4. ¿Cuál es el flujo de datos entre un formulario HTML y la base de datos en Django?**

   
 
   
   
   .
