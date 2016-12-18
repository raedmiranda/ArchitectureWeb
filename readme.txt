1. Crea una carpeta  en tu disco duro con el nombre del proyecto
2. Clic derecho, abrir en VS Code
3. Selecciona de la barra izquierda Git.
4. Clic en el boton Initialize Git Repository
5. Abre el terminal Ctrl + ñ
6. git remote add origin https://github.com/raedmiranda/ArchitectureWeb.git
7. Listo.

git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
[remote "origin"]
	url = https://github.com/raedmiranda/ArchitectureWeb.git
	fetch = +refs/heads/*:refs/remotes/origin/*
