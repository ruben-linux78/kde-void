# kde-void es un script de bash para instalar kde plasma completo, mas complementos, en void linux glibc.
# Tras una instalación basica de void linux glibc, descargate el script de instalación. Por ejemplo clonando el repositorio.
# Instalate git.
sudo xbps-install -S git
# Clona el repositorio en tu sistema.
git clone https://github.com/ruben-linux78/kde-void.git
# Entra dentro del nuevo directorio kde-void.
cd kde-void
# Le das permisos de ejecución al script.
sudo chmod +x kde-void
# Ejecutas el script con sudo, para que pueda instalar programas y sigue algunas instrucciones basicas.
sudo ./kde-void
