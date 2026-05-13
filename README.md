# Ejercicio Práctico de GitHub

Este es un proyecto de demostración muy sencillo creado para practicar los comandos básicos de Git y GitHub durante una presentación. 🚀

## Guía Rápida de Comandos

A continuación tienes los comandos que debes usar en la terminal paso a paso:

### 1. Clonar el repositorio
Si es la primera vez y necesitas descargar el proyecto a tu computadora:
```bash
git clone <URL_DEL_REPOSITORIO>
```
*(Reemplaza `<URL_DEL_REPOSITORIO>` con el enlace real del repo en GitHub).*

---

### 2. Preparar los cambios
Una vez que hayas modificado un archivo (por ejemplo, `index.html`), debes decirle a Git que prepare esos archivos para ser guardados. 
Para agregar **todos** los archivos modificados usa:
```bash
git add .
```

---

### 3. Crear el Commit
Ahora vas a "guardar" esos cambios localmente con un mensaje descriptivo:
```bash
git commit -m "Escribe aquí lo que modificaste, ej: Actualizado el saludo"
```
*(El error que tuviste antes ocurrió porque primero necesitas hacer `git add .` antes del `git commit`, o usar la combinación `git commit -am "mensaje"` si el archivo ya existía).*

---

### 4. Subir los cambios a GitHub (Push)
Para que todos los demás puedan ver tus cambios en el repositorio principal:
```bash
git push
```

---

### 5. Descargar cambios de los demás (Pull)
Si alguien más ya subió cambios y quieres actualizar tu versión local antes de trabajar:
```bash
git pull
```

## Resumen para tu compañero en la presentación:
1. `git clone <URL>`
2. Edita el archivo `index.html`.
3. `git add .`
4. `git commit -m "Mi nuevo cambio"`
5. `git push`
