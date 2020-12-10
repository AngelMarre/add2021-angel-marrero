# Servidor de Impresión en Windows

## 1.3 Probar la impresora en local

Para crear un archivo PDF no hará falta que cambies la aplicación que estés usando, simplemente ve a la opción de imprimir y selecciona "Impresora PDF", en segundos tendrás creado tu archivo PDF.



![](IMAGENES/1.3.1.png )









Puedes probar la nueva impresora abriendo el Bloc de notas y creando un fichero luego selecciona imprimir. Cuando finalice el proceso se abrirá un fichero PDF con el resultado de la impresión.

    Probar la impresora remota imprimiendo documento imprimirXXs-local.


![](IMAGENES/1.3.2.png )





## 2.2 Comprobar desde el cliente

Vamos al cliente:

    Buscar recursos de red del servidor. Si tarda en aparecer ponemos \\ip-del-servidor en la barra de navegación.
    Seleccionar impresora -> botón derecho -> conectar.
     
   ![](IMAGENES/2.2.1.png )
   
   ![](IMAGENES/2.2.2.png )

    
    
        Ponemos usuario/clave del Windows Server.
    Ya tenemos la impresora remota configurada en el cliente.
    
  ![](IMAGENES/2.2.3.png )
    
    
    Probar la impresora remota imprimiendo documento imprimirXXw-remoto.

 ![](IMAGENES/2.2.4.png )





## 3.3 Comprobar desde el navegador

    
Vamos a realizar seguidamente una prueba sencilla en tu impresora de red:

    Accede a la configuración de la impresora a través del navegador. 
      Poner en pausa los trabajos de impresión de la impresora.
![](IMAGENES/3.3.1.png )  
    Ir a MV cliente.
    Probar la impresora remota imprimiendo documento imprimirXXw-web.
    
![](IMAGENES/3.3.2.png )

        Comprobar que al estar la impresora en pausa, el trabajo aparece en cola de impresión.
        
![](IMAGENES/3.3.3.png )         
    Finalmente pulsa en reanudar el trabajo para que tu documento se convierta a PDF.
    
![](IMAGENES/3.3.4.png ) 
   
   
   
   Si tenemos problemas para que aparezca el PDF en el servidor, iniciar el programa PDFCreator y esperar un poco.
