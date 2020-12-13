#Simple Weather Station<br>
Добавленно 2 сроки /etc/modules<br>
i2c-bcm2708
i2c-dev
<p>
Раскомментировано в /boot/config.txt
dtparam=i2c_arm
Добавлено
dtparam=i2c1=on
<p>
Используемые пакеты
sqlite3
apache2
Устанавливаем i2c 
python-smbus
i2c-tools

Сделать ребут и проверить работу модуля с помощью i2cdetect -y 1
