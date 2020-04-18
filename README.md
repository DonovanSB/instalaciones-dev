# Flutter
- Descargar el SDK de la pagina oficial

https://flutter.dev/docs/get-started/install
- Extraiga el archivo en la ubicación deseada, por ejemplo
```
cd ~/development
tar xf ~/Downloads/flutter_linux_v1.12.13+hotfix.9-stable.tar.xz
```
- Agregar flutter a las variables de entorno, editando
```
sudo nano $HOME/.bashrc
```
Y agregar al final
```
export PATH="$PATH:[PATH_TO_FLUTTER_GIT_DIRECTORY]/bin"
```
- Reiniciar la terminal y verificar
```
flutter doctor
```

## Android Estudio
para usuarios de 64 bits
```
sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386
```
Descargar android studio de la pagina oficial y descomprimir en un lugar como:
```
/usr/share
```
agregar android-estudio a sus aplicaciones de escritorio. Creando un archivo en:
```
/usr/share/applications/android-studio.desktop
```
con el siguiente contenido:
```
[Desktop Entry]
Categories=GNOME;GTK;Development;IDE;
Comment=Integrated Android developer tools for development and debugging.
Exec=/usr/share/android-studio/bin/studio.sh
Icon=androidstudio
Name=Android Studio
Terminal=false
Type=Application
Version=1.0
X-Deepin-Vendor=user-custom
```
Abrir andriod-studio y continuar con la instalacion.

## Visual studio code
Instalar de la pagina oficial.
algunas extensiones (ctrl + p):
```
ext install Nash.awesome-flutter-snippets
ext install CoenraadS.bracket-pair-colorizer-2
ext install Dart-Code.dart-code
ext install Dart-Code.flutter
ext install PKief.material-icon-theme
ext install quicktype.quicktype
ext install formulahendry.terminal
ext install fabiospampinato.vscode-monokai-night
```
json settings
```
"bracket-pair-colorizer-2.colors": [
    "#fafafa",
    "#9F51B6",
    "#F7C244",
    "#F07850",
    "#9CDD29",
    "#C497D4"
],
```
# Git
```
sudo apt install git-all
git config --global user.name "name"
git config --global user.email "correo@gmail.com"
git config --global credential.helper store
```
# Node js
Descargar node de la pagina oficial y descomprimir en una carpeta como:
```
/home/USER/Documents/development
```
agregar a las variables de entorno
```
export PATH="$PATH:/home/donovan/Documents/development/node-v13.13.0-linux-x64/bin"
```
Para usar con sudo se deben vincular a /src/local/bin
```
sudo ln -s /home/donovan/Documents/development/node-v13.13.0-linux-x64/bin/node /usr/local/bin/node
sudo ln -s /home/donovan/Documents/development/node-v13.13.0-linux-x64/bin/npm /usr/local/bin/npm
```
Algunos paquetes
* Nodemon
```
sudo npm install -g nodemon
```

# Typescript 
```
sudo npm install -g typescript
```
# Angular
```
sudo npm install -g @angular/cli
```
# IONIC
```
sudo npm install -g @ionic/cli
```