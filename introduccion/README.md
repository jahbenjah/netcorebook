# 1. Introducción

Cuando desarrollamos una app móvil donde se necesita que el usuario guarde información de forma permanente, como por ejemplo una lista de tareas, la información se guarda en una base de datos. Se recomienda que la app no se conecte directamente a la base de datos, si no mediante servicios REST. 

También algunos sistemas Web desarrollados con frameworks Javascript como Angular, React o Vue, la información se obtiene mediante servicios REST.

Escribí este pequeño tutorial para ayudar a los programadores a crear servicios REST con .NET Core en español, con una sencilla aplicación de ejemplo.

Espero que sea de ayuda para programadores ya sea de .NET o de otros lenguajes como Java, PHP. Este tutorial esta escrito en C\#.

En esta serie de tutoriales explicaré paso a paso una guía para crear los servicios REST con .NET Core y Entity Framework Core. 

Explicaré como crear una aplicación de inicio a fin, donde aprenderás lo siguiente:

* Como llevar el control de código fuente de tu proyecto
* Como manejar versiones de tu base de datos \(mediante migraciones\)
* Entity Framework Core para las operaciones de altas, bajas, cambios, lectura \(SQL Server, MySQL\)
* Servicios REST \(con documentación en swagger\)
* Seguridad para tus servicios con OAUTH
* Pruebas unitarias
* Pruebas de integración
* Como publicar la aplicación en IIS y en Linux \(Ubuntu\)

Se debe tener conocimientos básicos de C\# y programación orientada a objetos.

### ¿Porqué ASP.NET Core?

ASP.NET Core fue creado para ser multiplataforma \(Windows,Mac,Linux\), Open Source y con mejoras en el rendimiento. 

Entity Framework Core también fue rediseñado para hacerlo más eficiente.

### Requisitos

[Visual Studio Code](https://code.visualstudio.com/download) o [Visual Studio Comunity](https://visualstudio.microsoft.com/es/vs/community/)

[SQL Server Express](https://www.microsoft.com/es-mx/sql-server/sql-server-editions-express) o [MySQL Comunity Version](https://dev.mysql.com/downloads/mysql/)

En este tutorial mostraré ejemplos con Visual Studio Comunity 

Para MySql utilizare [DB Forge for MySQL Express](https://www.devart.com/dbforge/mysql/studio/download.html) y el [MySQLWorkbench](https://dev.mysql.com/downloads/workbench/) 

### Código de ejemplo

El código de ejemplo está en Github lo puedes descargar [aquí](https://github.com/apis3445/CaducaRest)

