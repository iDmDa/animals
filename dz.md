  ## Задание
#### 1. Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).

        dm@dm-VirtualBox:~$ cat > pets
        Собаки 
        Кошки
        Хомяки
        dm@dm-VirtualBox:~$ cat > pack_animals
        Лошади
        Верблюды
        Ослы
        dm@dm-VirtualBox:~$ cat pets pack_animals > all_pets
        dm@dm-VirtualBox:~$ cat all_pets
        Собаки
        Кошки
        Хомяки
        Лошади
        Верблюды
        Ослы
        dm@dm-VirtualBox:~$ mv all_pets people_friends

#### 2. Создать директорию, переместить файл туда.

        dm@dm-VirtualBox:~$ mkdir animals
        dm@dm-VirtualBox:~$ mv people_friends animals

#### 3. Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.

        dm@dm-VirtualBox:~$ sudo apt install mysql-server

####  4. Установить и удалить deb-пакет с помощью dpkg.

        dm@dm-VirtualBox:~$ wget http://archive.ubuntu.com/ubuntu/pool/main/t/tnftp/ftp_20230507-2_all.deb
        dm@dm-VirtualBox:~$ sudo dpkg -i ftp_20230507-2_all.deb
        dm@dm-VirtualBox:~$ sudo dpkg -r ftp

#### 5. Выложить историю команд в терминале ubuntu

История команд:

        250  cat > pets
        251  cat > pack_animals
        252  cat pets pack_animals > all_pets
        253  cat all_pets
        254  mv all_pets people_friends
        255  mkdir animals
        256  mv people_friends animals
        257  sudo nano /etc/apt/sources.list.d/mysql.list
        258  sudo apt update
        259  sudo apt install mysql-server
        260  wget http://archive.ubuntu.com/ubuntu/pool/main/t/tnftp/ftp_20230507-2_all.deb
        261  sudo dpkg -i ftp_20230507-2_all.deb
        262  sudo dpkg -r ftp
        263  history

#### 6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные войдут: Лошади, верблюды и ослы).

