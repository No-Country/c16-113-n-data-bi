Conexión a MySQL desde Power BI
Introducción:

Este documento describe los pasos necesarios para conectar Power BI a una base de datos MySQL, tener en cuenta que se puede hasta máximo 5 conexiones en simultaneo ya que es una base de datos gratuita en una nube de clever cloud

Requisitos:

Power BI Desktop
Conexión a internet
Credenciales de la base de datos MySQL
Pasos:

Markdown
# Abrir Power BI Desktop e iniciar un nuevo informe en blanco.

Power BI Desktop.exe

# En la pestaña **Inicio**, seleccionar **Obtener datos**.

Inicio -> Obtener datos

# En el cuadro de diálogo **Obtener datos**, seleccionar **Base de datos** > **MySQL**.

Obtener datos -> Base de datos -> MySQL

# En el cuadro de diálogo **Base de datos MySQL**, seleccionar **Conexión básica**.

Base de datos MySQL -> Conexión básica

# Introducir la siguiente información:

* **Servidor**: El nombre del servidor MySQL.
* **Base de datos**: El nombre de la base de datos MySQL.
* **Usuario**: El nombre de usuario de la base de datos MySQL.
* **Contraseña**: La contraseña del nombre de usuario de la base de datos MySQL.

Servidor: bfdehrgcxcsyt5xnpchs-mysql.services.clever-cloud.com
Base de datos: bfdehrgcxcsyt5xnpchs
Usuario: uejock9ipcillxlu
Contraseña: iJ0eaKoST3btFt2oOD7j

# Seleccionar **Probar conexión** para verificar la conexión.

Probar conexión

# Seleccionar **Transformar datos** para cargar la tabla en Power BI.

Transformar datos

# En el editor de Power Query, seleccionar la tabla que desea cargar y seleccionar **Cargar**.

# La tabla se cargará en Power BI.
Usa el código con precaución.
Consejos:

Si necesita usar una conexión avanzada, puede seleccionar Conexión avanzada en el cuadro de diálogo Base de datos MySQL.
Puede usar el editor de Power Query para transformar los datos antes de cargarlos en Power BI.
Para obtener más información sobre cómo conectarse a MySQL desde Power BI, puede consultar la documentación de Microsoft: [se quitó una URL no válida]
Ejemplo:

En este ejemplo, nos conectaremos a la base de datos MySQL "bfdehrgcxcsyt5xnpchs" con el nombre de usuario "uejock9ipcillxlu" y la contraseña "iJ0eaKoST3btFt2oOD7j".

Markdown
# Ejemplo:

# Conectarse a la base de datos MySQL "bfdehrgcxcsyt5xnpchs" con el nombre de usuario "uejock9ipcillxlu" y la contraseña "iJ0eaKoST3btFt2oOD7j".

Servidor: bfdehrgcxcsyt5xnpchs-mysql.services.clever-cloud.com
Base de datos: bfdehrgcxcsyt5xnpchs
Usuario: uejock9ipcillxlu
Contraseña: iJ0eaKoST3btFt2oOD7j

# Seleccionar **Probar conexión** para verificar la conexión.
# Seleccionar **Transformar datos** para cargar la tabla en Power BI.
# En el editor de Power Query, seleccionar la tabla que desea cargar y seleccionar **Cargar**.
# La tabla se cargará en Power BI.
Usa el código con precaución.
Conclusión:

En este documento, hemos descrito los pasos necesarios para conectar Power BI a una base de datos MySQL, utilizando código Markdown.

Nota:

Este código es solo un ejemplo y puede ser necesario modificarlo para adaptarlo a su entorno específico.

