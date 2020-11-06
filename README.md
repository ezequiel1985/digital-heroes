# digital-heroes-cn22
Resumen clase 02-11-2020

PREGUNTAR:
app.get('*', function (req, res) {
    res.sendFile(__dirname + '/public/' + req.url)
})

# En GITHUN
1) copiamos la URL del repositorio que queremos trabajar.

# En TERMINAL/CONSOLA
1) Ingresamos desde terminal a la carpeta donde queremos alojar el repositorio a codear 
Terminal = cd C:\Users\Ezequiel\Digital House\repositorios

2) Abrimos VSC 
Terminal: code .

3) Instalamos/habilitamos express
Terminal (tambien podemos usar la de VSC): npm i express

4) Verificamos nodemon
Terminal: npm install -g nodemon
"npm init" instala el archivo package.json , se inicializa el proyecto, y en el se van a guardar las distintas 
librerias.
La propiedad main es el entry point (app.js) y genera en el package.json un bloque de codigo con la propiedad main.
Instalar libreria 
terminal: npm install libreriaAInstalar --save (package.json hay que instalarla si no la trae)
VSC: vamos a ver la carpeta "node modules" donde se instalan las carpetas de las librerias.

4) Activamos nodemon
Terminal: npm start

# 5) trabajamos con el código en VSC. Ver el archivo app.js
terminal: git status (para ver las actualizaciones a realizar)
terminal: git add archivo (para actualizar cada archivo) 
terminal git commit -m "comentario" 

6) Apuntamos al repositorio. 
Terminal: git remote add origin "URLrepo" (si lo bajamos de GITHUB se set-url en lugar de add)

7)verigicamos que esten apuntados (push vs pull)
terminal:git remote -v 

8)Apuntamos a la rama main (o la que querramos)
Terminal: git branch -m main

9) pusheamos la info a GITHUB
terminal: git push -u origin main
