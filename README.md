# Practicas de Entornos
## P02-30 Resolución de conflictos
Esta práctica busca resolver lso conflictos generados por causa de cambios en ficheros y
su sincronización con repositorio remoto en distintas situaciones:
* Situación 1. Intentar un push sobre un remoto con cambios no incorporados a local
Se puede resolver haciendo un pull o un fetch y de nuevo un push.
En esta simulación vamos a intentar subir este fichero README.md al remoto sin haber incorporado 
cambios previos existentes en el remoto.
* Situación 2. Añadir en dos instancias locales
 una línea a un mismo fichero.
 Al hacer el segundo push aparece el conflicto y nos pide que lo resolvamos
 eligiendo la versión que más nos interese: la ya incorporada al remoto o la que estamos intentando.
* Situación 3. Ocurre lo mismo aunque el cambio tenga lugar en distintas líneas.