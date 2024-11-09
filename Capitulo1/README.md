# Sistema Monolítico .net Core 8 [Lista de Laboratorios](../README.md)

En este laboratorio se implementa una aplicación monolítica de .net core usando Visual Studio 2022


## Objetivos
- Comprender la estructura de un sistema monolítico
- Iniciar y probar un sistema monolítico
- Analizar los componentes del sistema
- Entender MVC 


## Diagrama 

Se espera que el alumno analice la siguiente estructura de aplicación. 

![diagrama](../images/1/diagramaMVC.png)



## Instrucciones 

1. Descargar la aplicación que se encuentra en la carpeta **[Capitulo1](../Capitulo1)** con el nombre **MVCMonolitico**

2. Abrir Visual Studio 2022 
<br>
![opcion](../images/1/2.png)

3. Abrir la solución
<br>

![solucion](../images/1/3.png)

4.  Abrir la consola de administración de paquetes nuget **Herramientas** -> **Administrador de paquetes nuget**->**Consola de administrador de paquetes**
<br>

![alt text](../images/1/4.png)

5. En la terminal ejecutar el comando 

```bash
donet restore
```
![restore](../images/1/5.png)


6. Analizar las clases y el código que esta en el proyecto

![alt text](../images/1/6.png)

7. Iniciar la aplicación

![alt text](../images/1/7.png)

> Es posible que la aplicación tarde en iniciar la primera vez.



# Resultado esperado

Al iniciar la aplicación usted debería de observar algo similar a la pantalla. 

![alt text](../images/1/8.png)

> Insertar datos en la aplicación y observar el funcionamiento. 

> Tome nota de la arquitectura usada, ya que en los microservicios la organización de código es similar. 