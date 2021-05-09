# Indicador de temperatura

sudo apt-get install indicator-cpufreq

# Instalar java

sudo apt install openjdk-11-jdk

sudo update-alternatives --config java

>> /usr/lib/jvm/java-11-openjdk-amd64/bin/java

nvim /etc/environment

JAVA_HOME="/usr/lib/jvm/java-11-openjdk-amd64/bin/java"

# Install Git

sudo apt install git

## config
git config --global user.name "Manuel Guarniz"
git config --global user.email cruzemg95@gmail.com
~/.gitconfig

# Install snap

sudo apt install snapd

# Install Postman

sudo snap install postman

# Install Ngrok (exponer puertos)

sudo snap install ngrok

# Install MailSpring

sudo snap install mailspring

# Install Maven

sudo apt install mvn

# Install Sprint Tool Suite

sudo tar -xzf Postman-linux-x64-8.3.1.tar.gz

sudo mv sts-4.10.0.RELEASE/ /opt/

sudo gedit /usr/share/applications/Spring.desktop

```
[Desktop Entry]
Version=4.0
Type=Application
Name=Spring Tool Suite
Icon=/opt/sts-4.10.0.RELEASE/icon.xpm
Exec=/opt/sts-4.10.0.RELEASE/SpringToolSuite4
Comment=Spring Tool Suite
Categories=Development;IDE;
Terminal=false
```
# Agregar paquetes a la lista de deb

sudo gedit /etc/apt/sources.list

