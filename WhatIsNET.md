# Que es .NET

Es un ecosistema para desarrollo de aplicaciones.
## NET CLI
Es la consola de comandos que viene con el SDK de .NET. Sino podemos usar Visual Studio.
## CLR (Common Language Runtime)
Es la base sobre la cual se construyen todas las aplicaciones .NET.
El Runtime tiene features como:
* Garbage collection: si ya no se usa, se elimina.
* Diseño multiplataforma: solo necesito el runtime para el entorno donde quiero correr mi app. No necesito recompilar nada.
* Alto nivel de soporte para lenguajes de programación
* Seguridad de memoria: previene bugs que pueden hacer los programadores sobre cómo está utilizado el espacio en memoria. Ejemplo: querer acceder al 11vo espacio de memoria de una lista que declaramos de 10 elementos.
* Seguridad de tipos: Nos arroja un error al querer asignar un int a una variable declarada como string.

## Funcionamiento
Primero que nada, debemos programar en un lenguaje tolerado por .NET, como C#, para escribir el codigo fuente.
Antes de que el software corra nuestro codigo, debe compilares.

El *.NET Compiler* es un programa que convierte el codigo fuente en un lenguaje intermedio (IL).
El compiler guarda ese codigo en un archivo llamado *.NET Assembly*.

eL *NET Runtime* es un ambiente de ejecucion para tu compilado Assembly. Es lo qu ejecuta y administra tu aplicacion mientras corre en un sistema operativo.

## El software y sus capas

* Al nivel mas bajo, el software se comunica directamente con el hardware de tu computadora. Controla el flujo de informacion a la placa madre, procesadores, memoria y discos.
* Al siguiente nivel, le permite al usuario proveer instrucciones mediante un sistema operativo.
* Al siguiente nivel, software como .NET povee una forma para que tu desarrollares y corras aplicaciones.
* Al siguiente nivel, los frameworks de aplicaciones y librerias de funcionalidades te permiten repidamente construir mejores aplicaciones utilizando menos esfuerzo que con otros metodos de desarrollo.

Una libreria de codigo encapsula funcionalidad para un proposito especifico en un solo assembly.
Hay cientos de librerias disponibles para .NET.
Como desarrollador, construyes gracias a el trabajo de otros desarrolladores. Ahorras energia y tiempo ya que no tienes que construir y mantener cada funcion tu mismo.

