# Android Studio





Install-Android-Studio-On-Ubuntu
Install JRE & JDK

Install JRE - 7 or upper virsion from Software Center
Install JDK - 7 or upper virsion form Software Center

OR

sudo apt-add-repository ppa:webupd8team/java
sudo apt-get update
sudo apt-get install oracle-java8-installer

Check Java Version

javac -version  (For JRE)
java -version    (For JDK)

For "Unable to run mksdcard SDK tool."(ubuntu 14.04)

sudo apt-get install lib32z1 lib32ncurses5 lib32bz2-1.0 lib32stdc++6

Download All Android Studio Package(For Linux Package)

From here http://developer.android.com/sdk/index.html
Unzip & Save

Unzip Downloaded Zip file & Save it on Home Directory.
Run this command

cd /home/USER_Name/android-studio/bin
sudo chmod 777 -R studio.sh
./studio.sh

Add Github in Android Studio

Go to
File > Setting > Version Controll > Github 

Fill : Username and Password.

Install Git Using this Command

sudo apt-get install git

Enabel VCS

Go to VCS > Enable VCS >> Select git from box Press OK 

Now Github is Connected .
To Download Old source code

Go to VCS > Checkout from Version Controll > Github > "Here Set your github username: and Password: "

Set Android Master Password: and Confirm it. 

Select your repository  press OK.

Share on Github

Go to VCS > Import into Version Controll > "Select" Share on Gtihub .

Comite , Push .

SATA Details

https://www.cyberciti.biz/faq/linux-command-to-find-sata-harddisk-link-speed/




Se ao iniciar o Android Studio receber a mensagem abaixo.

    Gtk-Message: 06:07:13.916: Failed to load module “canberra-gtk-module”

Instale o pacote abaixo.

$ sudo apt-get install libcanberra-gtk-module

Após a instalação do pacote o problema estara solucionado, testado em Ubuntu 18.04
