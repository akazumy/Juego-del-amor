echo "# declaracion" >> README.md  # Agrega contenido al README.md
git init  # Inicializa un nuevo repositorio local
git add README.md  # Agrega el README.md al área de preparación
git commit -m "first commit"  # Crea el primer commit con un mensaje
git branch -M main  # Cambia el nombre de la rama a 'main'
git remote add origin https://github.com/akazumy/Juego-del-amor.git  # Agrega el repositorio remoto
git push -u origin main  # Sube los cambios al repositorio remoto