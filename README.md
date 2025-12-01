# RETO GIT

Pagina web sencilla de HTML Y CSS el proceso que se llevara a cabo es una rama para HTML y la otra para CSS y ya luego estas dos fusionarlas correctamente

# PASO 1 

Creacion de Rama 1 y Rama 2

-- git branch -m juan          (HTML)
-- git branch -m main          (Probar funcionamiento README)
-- git branch -m manrique      (CSS)

# PASO 2 

Hacer todo el HTML Y CSS y subirlo en diferentes RAMAS

# PASO 3

Subir el primer archivo "HTML" a la rama juan

-- git add index.html
-- git commit "..."
-- git push origin juan

# PASO 4

Subir el segundo archivo "CSS" a la rama manrique

-- git add style.css
-- git commit -m "..."
-- git push origin manrique

# PASO 5 

Union de MERGE de los 2 archivos

-- git fetch origin
-- git checkout juan
-- git pull origin juan
-- git merge --no-ff manrique -m "Conectar CSS con HTML"
-- git add .
-- git commit --no-edit
-- git merge --no-ff juan -m "Conectar HTML con CSS"
-- git push origin juan

# PASO 6  

Subir README de todo este paso a paso

# ADICIONAL (LA RAMA JUAN ES LA ORIGIN LA MAIN, YA QUE TUVE UN FALLO)