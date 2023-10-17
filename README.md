### Как установить ARIS Express на Mac OS (ARM)

_Стоит отметить, что данный способ установки сработал на mac os на архитектуре
чипов m1 и m2._

1) Включить надежный и стабильный VPN.
2) Заходим на сайт установки ARIS Express (https://www.ariscommunity.com/aris-express/download) и выбираем `Free download
for Other Systems`. Если вы не видите этого окна, то необходимо нажать на `log in`  и войти
в заранее зарегистрированный аккаунт
<br/>
<img src="images/1.png" heigh=400 width=600>
3) Скачиваем файл `express.jnlp` и перетаскиваем его на рабочий стол
4) Заходим на сайт Java SE Development Kit 8 (https://www.oracle.com/java/technologies/downloads/#java8-mac) и скачиваем
для Mac os `ARM64 DMG Installer`. Для скачивании у вас потребуется авторизация в аккаунте Oracle - регистрируемся в открывшимся окне.
<br/>
<img src="images/2.png" heigh=400 width=600>
5) Устанавливаем Java SE Development Kit 8
6) Открываем с включенным VPN `express.jnlp` таким способом (правая кнопка мыши)
<br/>
<img src="images/3.png" heigh=400 width=600>
7) Устанавливаем данный файл.
8) После полной установки вы, вероятно, получите предупреждение о том, что запускаемое приложение
заблокировано системой безопасности Java
<br/>
<img src="images/4.png" heigh=400 width=600>
9) Необходимо зайти в Системные настройки и найти там раздел `Java`
<br/>
<img src="images/5.png" heigh=400 width=600>
10) При нажатии на данный раздел у вас откроется `Java Control Panel`. Переходим в пункт `Security`
<br/>
<img src="images/6.png" heigh=400 width=600>
11) Нажимаем на `Edit Site List` и добавляем туда поле с Location `https://download.ariscommunity.com`
<br/>
<img src="images/7.png" heigh=400 width=600>
12) По итогу у вас должно быть также, как на представленном скрине
<br/>
<img src="images/8.png" heigh=400 width=600>
13) Запускаем `express.jnlp` заново, принимаем риски и подтверждаем намерение запустить приложение
<br/>
<img src="images/9.png" heigh=400 width=600>
14) При появлении данного окна нажимаем OK
<br/>
<img src="images/10.png" heigh=400 width=600>
15) Если приложение запросит обновиться на новую версию, но отклоняем данное приложение (Skip This Version/Remind Me Later)
<br/>
<img src="images/11.png" heigh=400 width=600>
16) На данном шаге мы можем удалить `express.jnlp`. Запуск приложения производится `ARIS Express 2.4i` также через правую кнопку мыши (шаг 6)
<br/>
<img src="images/12.png" heigh=200 width=300>

**Готово!**