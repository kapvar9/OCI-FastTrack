# Creación de maquinas virtuales

Esta sección contiene 2 partes:
- [Máquinas Virtuales](#aprendamos-un-poco-sobre-lo-que-es-una-vcn)
- [Laboratorio 3](#laboratorio-2-exploremos-una-vcn)

## Aprendamos un poco sobre las máquinas virtuales 

Oracle Cloud Infrastructure permite aprovisionar y gestionar hosts de cómputo conocidos como instancias. Puedes crear instancias según sea necesario para satisfacer tus requisitos de cómputo y aplicaciones. Después de crear una instancia, puedes acceder a ella de forma segura desde tu computadora, reiniciarla, adjuntar y desvincular volúmenes y cerrarla cuando ya no la necesites. Esto proporciona flexibilidad y escalabilidad para satisfacer las necesidades de tu infraestructura de TI en la nube.

Para saber más, puedes consultar la documentación de OCI 🤓➡️ https://docs.oracle.com/en-us/iaas/Content/Compute/Concepts/computeoverview.htm

## Laboratorio 3: Creación de máquinas virtuales

En este laboratorio crearemos 2 máquinas virtuales. **Cada máquina virtual debe estar en un AD diferente**. Para ellos seguiremos los siguientes pasos:
- [Paso 1:]
- [Paso 1:]
- [Paso 1:]

### Paso 1: Crear un par de llaves SSH

1. Abrimos el escritorio remoto y el terminal 

  ![imagen](../PrimerosPasos/imagenes/paso23.png)

2. Para crear el par de llaves usamos el comando:

   ```
   ssh-keygen -t rsa
   ```
   - Mantenga el nombre original de la llave (id_rsa) aprentando enter
   - El campo "Key Passphrase" es opcional

   ![imagen](../Lab3-MaquinasVirtuales/imagenes/lab3-1.png)

3. Para ver el contenido de la llave pública, ejecuta este comando:
   
   ```
   cat ~/.ssh/id_rsa.pub
   ```
  > **Note:** Si no sabes la combinación de teclas para el símbolo "~" (virgulilla), dentro del terminal puedes abrir Google Chrome, buscar el símbolo, copiarlo y pegarlo en el terminal

  * Selecciona y copia el contenido de la llave. Usaremos esto para la creación de las máquinas virtuales.
    
    ![imagen](../Lab3-MaquinasVirtuales/imagenes/lab3-2.png)
    
4. 
   
