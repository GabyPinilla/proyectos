# Notas
### Para subir documentos RMarkdown a GitHub con gráficos:
1. Crear un repositorio en GithHub.
2. Crear un nuevo proyecto en RStudio, seleccionar *Control de versión Git* y crear archivo RMarkdown.
3. Una vez que el archivo esté listo, escribir "output: github_document" y luego seleccionar *Knit* para guardarlo con la extensión .Rmd.
4. En la ventana donde dice *Files, Plots, Packages...* seleccionar *Files*. Junto al archivo .Rmd aparecerá .Rproj, una carpeta que contiene los gráficos y .md, el cual será utilizado para subirlo a GitHub. Para esto, se debe seleccionar la ventana *Git* de RStudio, dar clic en la casilla del archivo .md y en la casilla de las fotos, comentar en *commit* y apretar la flecha verde de push.
5. Refrescar GitHub y aparecerá el documento .dm con el código y los gráficos.
