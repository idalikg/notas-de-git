##Curso GIT desde cero
Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos. 

### Zonas de Git
1. Directorio de trabajo (working area - PC)
2. Área de preparación(staging area - sistema)
3. Directorio Git (repositorio GitHub)

### Flujo de trabajo básico en Git
1. Modificas una serie de archivos en tu directorio de trabajo.
2. Preparas los archivos, añadiéndolos a tu área de preparación.
3. Confirmas los cambios, lo que toma los archivos tal y como están en el área de preparación y almacena esa copia instantánea de manera permanente en tu directorio de Git.

### Configurando Git por primera vez
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
git config --global core.editor nano
git config --global core.editor subl
    --> Para esto hay que agregar la ruta del ejecutable de sublime text 3 en las variables de entorno del sistema
git config --list
```

Esta línea fue creada en la rama master como ejemplo de divergencia de dos ramas.

