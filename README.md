# Script de bash para instalar kde plasma en void linux glibc.
# Tras la instalación del sistema base, descargate el script de instalación. 
# Por ejemplo clonando el repositorio.
# Instala git.
sudo xbps-install -S git
# Clona el repositorio.
git clone https://github.com/ruben-linux78/kde-void.git
# Entra dentro del directorio creado.
cd kde-void
# Dale permisos de ejecución al script.
sudo chmod +x kde-void
# Ejecuta el script con sudo o doas.
sudo ./kde-void
