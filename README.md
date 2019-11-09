

# Git

## Sistema de Control de Versiones

### Comandos Iniciales   

**Inicializar repositorio:** `Git init`  
**Ver el estado actual del repositorio:** `Git status`  
**Ver el estado actual del repositorio resumido:** `Git status -s`  
**Agregar todos los archivos al escenario:** `Git add *`  
**Realizar captura del código:** `Git commit -m "Título o mensaje"`  
**Ver historial de capturas:** `Git log`  
**Ver historial de capturas resumido:** `Git log --oneline`  

### Comandos Intermedios

**Recuperar todos los cambios desde el último commit:** `Git checkout -- .`  
**Conocer los cambios realizados entre el último commit y el momento actual:** `Git diff`  
**Conocer los cambios realizados entre el último commit y el momento actual en el escenario:** `Git diff --staged`  
**Quitar del escenario y mover al área de trabajo:** `Git reset archivo`  
**Agregar todos los archivos al escenario y realizar captura del código:** `Git commit -am "Título o mensaje"`  
**Renombrar archivos:** `Git mv antiguo.md nuevo.md`  
**Eliminar archivos:** `Git rm archivo.md`  
**Actualizar repositorio:** `Git add -u`  
**Crear etiqueta:** `Git tag nombre`  
**Crear etiqueta detallada:** `Git tag -a v1.0 -m "Versión de lanzamiento"`  
**Crear etiqueta a commit creado:** `Git tag -a v0.1 hashcommit -m "Versión alfa"`  
**Listar etiquetas:** `Git tag`  
**Eliminar etiqueta:** `Git tag -d nombre`  
**Conocer los detalles de una etiqueta:** `Git show etiqueta`  
**Subir las etiquetas al repositorio remoto:** `Git push --tags`  

### Comandos Avanzados

**Crear rama:** `Git branch rama-nombre`  
**Crear rama y situarse en ella:** `Git checkout -b rama-nombre`  
**Listar ramas creadas:** `Git branch`  
**Listar ramas locales y remotas:** `Git branch -a`  
**Ver diferencias entre ramas:** `Git diff master rama-nombre`  
**Cambiar de rama:**  `Git checkout rama-nombre`  
**Unir ramas:** `Git merge rama-nombre`  
**Eliminar rama:** `Git branch -d rama-nombre`  
**Enmendar mensaje del último commit:** `Git commit --amend -m "Título corregido"`  
**Volver al commit anterior para modificarlo:** `Git reset --soft HEAD^`  
**Volver en el tiempo a un commit anterior:** `Git reset --soft hashcommit`  
**Volver en el tiempo a un commit anterior eliminando los cambios realizados:** `Git reset --hard hashcommit`  
**Agregar origen de repositorio remoto:** `Git remote add origin https://github.com/zencsoft/remoto.git`  
**Subir a repositorio remoto:** `Git push -u origin master`  
**Descargar últimos cambios del repositorio remoto:** `Git pull`  
**Descargar últimos cambios del repositorio remoto sin merge automático:** `Git fetch`  
**Tener todo el trabajo realizado durante el paso del tiempo:** `Git reflog`  

