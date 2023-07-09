## Задание 1
mkdir Kennel \
cd ~/Kennel\
cat > home_animals\
cat > pack_animals\
cat home_animals pack_animals > animals\
cat animal\
mv animals mans_friends\
ls -ali
## Задание 2
cd ..\
mkdir Kennel_system\
cd ~/Kennel\
mv mans_friends ~/Kennel_system\
cd ~/Kennel_system\
ls -ali
## Задание 3
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb \
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb\
sudo apt-get update\
sudo apt-get install mysql-server
## Задание 4
sudo dpkg -i google-earth-pro-stable_current_amd64.deb\
sudo dpkg -r google-earth-pro-stable
