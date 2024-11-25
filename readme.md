# Laboratorio de Git

Este repositorio documenta los pasos básicos para trabajar con Git y GitHub, incluyendo la creación de ramas, commits y merges.

## Pasos realizados

1. Inicializar el repositorio local:
   ```git init```

2. Añadir y commitear los archivos iniciales:
   ```git add .```
   ```git commit -m "Primer commit"```

3. Enlazar con el repositorio remoto en GitHub:
   ```git remote add origin [URL-del-repositorio]```
   ```git push -u origin master```

4. Crear y cambiar a la rama `development`:
   ```git branch development```
   ```git checkout development```

5. Hacer cambios en la rama `development`, añadirlos, y realizar un commit:
   ```git commit -am "Cambios en development"```
   ```git push -u origin development```

6. Volver a la rama `master` y hacer el merge de `development` a `master`:
   ```git checkout master```
   ```git merge development```

7. Subir los cambios finales al repositorio remoto:
   ```git push origin master```


