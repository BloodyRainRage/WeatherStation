# Simple Weather Station<br>
Добавленно 2 сроки /etc/modules<br>
i2c-bcm2708<br>
i2c-dev<br>
<p>
Раскомментировано в /boot/config.txt<br>
dtparam=i2c_arm<br>
Добавлено<br>
dtparam=i2c1=on<br>
<p>
Используемые пакеты<br>
sqlite3<br>
apache2<br>
Устанавливаем i2c <br>
python-smbus<br>
i2c-tools<br>
<p>
Сделать ребут и проверить работу модуля с помощью i2cdetect -y 1<br>
