# SetUp
los pasos para instalar el ambiente de desarrollo para aplicaciones de consola en C#
Setup 

En el programa de C#, debemos usar el Visual Studio para crear y ejecutar una aplicación de consola y explorar algunas características del entorno. la descarga es gratuita solo se necesita llenar lo que se que quiera para instalar esto.

Para abrir un nuevo proyecto de aplicación de C# en el tipo de proyecto se incluyen todos los archivos de plantilla que vamos a necesitar, sin necesidad de agregar nada más.

En el panel izquierdo del cuadro de diálogo Nuevo proyecto, expanda C# y elija .NET Core. En el panel central, elija Aplicación de consola (.NET Core) . Después, asigne el nombre que desee trabajar en la llantilla de proyecto Aplicación de consola (.NET Core) en el cuadro de diálogo Nuevo proyecto en el IDE de Visual Studio

<img width="393" alt="1 - new-project-csharp-calculator-console-app" src="https://user-images.githubusercontent.com/50472477/64923535-7ed9aa00-d78f-11e9-9245-cbf973aefc36.png">

Agregar una carga de trabajo (opcional)
Si no ve la plantilla de proyecto Aplicación de consola (.NET Core) , puede obtenerla si agrega la carga de trabajo Desarrollo plataforma de .NET Core. Esta es la manera de hacerlo en cualquier programa que se pueda trabajar dependiendo del proyecto que pida.

Opción 1: Uso del cuadro de diálogo Nuevo proyecto
Elegir el vínculo de Abrir el Instalador de Visual Studio en el panel de la izquierda del cuadro de diálogo Nuevo proyecto.
Elijir el vínculo Abrir el Instalador de Visual Studio del cuadro de diálogo Nuevo proyecto

<img width="252" alt="2-csharp-open-visual-studio-installer-generic-dark" src="https://user-images.githubusercontent.com/50472477/64923538-839e5e00-d78f-11e9-8a84-80bc6bfff026.png">

Opción 2: Uso de la barra del menú Herramientas
Sirve como para que pueda tener al frente de la ventana sin tener que cerrarlo y abrirlo mas que estar al frente.
Se iniciará el Instalador de Visual Studio. Elija la carga de trabajo Desarrollo multiplataforma de .NET Core y, después, elija Modificar. Abra Visual Studio 2019.

En el cuadro de búsqueda de la ventana Crear un proyecto, escriba consola. Seguidamente, elija C# en la lista de lenguajes y luego, Windows en la lista de plataformas.
Después de aplicar los filtros de lenguaje y plataforma, elija la plantilla Aplicación de consola (.NET Core) y luego, eligir la plantilla C# para Aplicación de consola (.NET Framework) para trabajar con otro tipo de consola sin tener que usar el .NET Core.

![3-create-new-project-dark-theme](https://user-images.githubusercontent.com/50472477/64923541-8ac56c00-d78f-11e9-940b-d08cc87c620c.png)

El vínculo "Instalar más herramientas y características" del mensaje "¿No encuentra lo que busca?" que aparece en la ventana "Crear proyecto"

Luego, en el Instalador de Visual Studio, eligir la carga de trabajo Desarrollo multiplataforma de .NET Core. para la carga de trabajo Desarrollo multiplataforma de .NET Core en el instalador de Visual Studio después, elije el botón Modificar en el Instalador de Visual Studio. Es posible que se le pida que guarde su trabajo; si es así, hágalo. Seguidamente, elija Continuar para instalar la carga de trabajo. Luego, vuelva al paso 2 de este procedimiento "Crear un proyecto".

<img width="513" alt="4-csharp-create-new-project-search-console-net-core-filtered" src="https://user-images.githubusercontent.com/50472477/64923547-9022b680-d78f-11e9-911a-46193ec5c86c.png">

Visual Studio abre el nuevo proyecto, que incluye código predeterminado de "Hello World".
Creación de la aplicación
En primer lugar, exploraremos algunos cálculos de enteros básicos en C#. Después, agregaremos código para crear los parámetros, métodos y propiedades en el programa. Después de eso, depuraremos la aplicación para buscar y corregir errores. Por último, perfeccionaremos el código para que sea más eficaz.

Análisis de las operaciones matemáticas con enteros
Empecemos con algunos cálculos básicos de enteros en C#. en el editor de código, elimine el código predeterminado "Hello World". eliminando el código "Hello World" predeterminado de la nueva aplicación del programa.

<img width="514" alt="5-csharp-name-your-calculator-project" src="https://user-images.githubusercontent.com/50472477/64923548-93b63d80-d78f-11e9-9ed8-25076b6a9caf.png">

Tenga en cuenta que, al hacerlo, la función IntelliSense en Visual Studio le ofrece la opción de auto completar la entrada para la animación de código de cálculos de enteros o propiedades que muestra la función auto completar de IntelliSense en el IDE de Visual Studio

Elija la función del programa para ejecutar el programa, o bien presione F5. La elección del botón correr para ejecutar la aplicación desde la barra de herramientas.

![6  dotnet-ruta-fisica](https://user-images.githubusercontent.com/50472477/64923551-99138800-d78f-11e9-961b-b3de057deec3.png)


**Instalación de dotnet core 2.2.**

En este mini tutorial, estará los pasos para instalar el NET CORE 2.2 en Visual Studio 2015 (community).
Primer paso, bajar el SDK desde la pagina oficial de Microsoft, en el boton “Download .NET Core SDK”.
EL SDK queda instalado en esta ruta: C:\Program Files\dotnet


https://tydw.files.wordpress.com/2019/04/dotnet-ruta-fisica.png

![7 --09](https://user-images.githubusercontent.com/50472477/64923558-9fa1ff80-d78f-11e9-92ea-413905ddc427.png)

![8--10](https://user-images.githubusercontent.com/50472477/64923561-a3358680-d78f-11e9-99f3-8198e173cae5.png)

Pero no instala la interfaz gráfica para el VS 2015 aun.

Para esto debemos bajar los siguientes software:

01 dotnet-sdk-2.2.202-win-x64.exe Mencionado al inicio.
02 dotnet-standard-support-vs2015-2.0.0-win-x86.msi
03 DotNetCore.1.0.0-VS2015Tools.Preview2.exe

Estos dos últimos son opcionales (si no los tienes instalados)

04 .Net Framework 7.2 (NDP472-DevPack-ENU.exe)
05 SP 3 para VS 20115 (vs2015.3.exe)

1) Instalacion de Microsoft .NET Core SDK 2.2.202

2) Microsft .NET Core 1.0.0 VS 2015 Tooling Preview 2
https://tydw.files.wordpress.com/2019/04/01.png
https://tydw.files.wordpress.com/2019/04/02.png
https://tydw.files.wordpress.com/2019/04/03.png
https://tydw.files.wordpress.com/2019/04/05.png
https://tydw.files.wordpress.com/2019/04/06.png
https://tydw.files.wordpress.com/2019/04/07.png

3) creado un proyecto Web APi con NET CORE en Visual Studio 2015

![9--13](https://user-images.githubusercontent.com/50472477/64923563-a6c90d80-d78f-11e9-8c45-753af738ab08.png)

![10---14](https://user-images.githubusercontent.com/50472477/64923564-ab8dc180-d78f-11e9-82f4-e4c9d1d790eb.png)

4) Corregir Errores de Referencias con Nuget (Package Restore Failed)

![11----15](https://user-images.githubusercontent.com/50472477/64923566-af214880-d78f-11e9-9a2e-a1325eca877d.png)

Agregar “dotnet-core” con el link https://dotnet.myget.org/F/dotnet-core/api/v3/index.json

https://tydw.files.wordpress.com/2019/04/15.png

Ejecutar el comando “dotnet restore”

![12---18](https://user-images.githubusercontent.com/50472477/64923572-bea09180-d78f-11e9-804f-1361365b34af.png)

Y con esto ya podemos crear aplicaciones ligeras con NET CORE 2.2 en Visual Studio 2015.
El Visual Studio 2017 ya lo trae incorporado e imagino que la visal studio 2019 también lo tendrá integrado.

Esta página forma parte del curso Temas de Informática por Bartolomé Sintes Marco
que se distribuye bajo una Licencia Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional (CC BY-SA 4.0).

http://www.mclibre.org/consultar/informatica/lecciones/vsc-instalacion.html
