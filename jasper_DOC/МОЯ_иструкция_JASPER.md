#00. Место хранения проекта от JasperStudio.
/home/borisenko/JaspersoftWorkspace/MyReports/bin




#1. JASPER_Studio

Запуск - без инстилляции,
просто щелчком по иконке  файла "Jaspersoft Studio", расположенного в архиве исходников.





#bild 
его надо забирать из папки /home/borisenko/JaspersoftWorkspace/MyReports/bin,
что прописано в настройках Defoult_output_folder,
расположенной в меню по адресу
Project/Properies/Java_Build_path

файлик с билдом переносить в рабочую папку ручками
и далее запускать Виталин скрипт для генерации pdf.

В результате билдинга файл с билдом НЕ создается, а лишь перетирается имеющийся(!).
Т.е. изначально он должен присутствовать в  /home/borisenko/JaspersoftWorkspace/MyReports/bin.










.....................
#2. Плагин от Виталия Александрова
- для наполнения  данными и перевода его в .pdf-формат.
## Команда для запуска плагина
java -jar esbkts2pdf.jar -jp /home/borisenko/Desktop/jasper/target/jasperIn/ -o /home/borisenko/Desktop/jasper/target/jasperOut/out.pdf







#3. JasperReports 6.16.0
- Просмотр созданного и заполненного документа




#4. Объект работы
redmine - https://redmine.stdpr.ru/issues/50990#change-422557
репозиторий в gitLab'e - http://172.20.255.84/epts_legacy/epts_legacy_src/blob/sbkts/reports/src/main/jasperreports/esbkts.jrxml - не верный.
репозиторий в gitLab'e - http://172.20.255.84/epts_legacy/epts_legacy_src/tree/sbkts/reports/src/main/jasperreports/esbkts.jrxml - верный.
                        http://172.20.255.84/epts_legacy/epts_legacy_src/tree/sbkts/reports/src/main/jasperreports

##1.
http://172.20.255.84/epts_legacy/epts_legacy_src(/blob/sbkts/)reports/src/main/jasperreports/esbkts.jrxml
путь в проекте - epts_legacy_src  reports  src  main  jasperreports  esbkts.jrxml

изначальный коммит - fc451440543ef39d6cca95a45db187095ef48175
созданная на его основе ветка - jasper_esbkts   (результаты по обеим объектам работы выложены сюда).
jasper_blunk - ветка, которая отходит от sbkts-ветки.



##2.
http://172.20.255.84/epts_legacy/epts_legacy_src(/blob/sbkts/)reports/src/main/jasperreports/esbkts_attributes.jrxml
путь в проекте - epts_legacy_src  reports  src  main  jasperreports  esbkts_attributes.jrxml

изначальный коммит - 1cc6ce6c9be75dc52a583d87551c90320cebca1b
созданная на его основе ветка - jasper_esbkts_attributes

Изначальный файл был практически пустой, поэтому
- изначальный файл переименовал в esbkts_attributes_0.jrxml,
- в роли заготовки взял файл ##1, переименовав его в esbkts_attributes.jrxml.



## Вставка base64-картинки
new java.io.ByteArrayInputStream(org.apache.commons.codec.binary.Base64.decodeBase64("".getBytes()))






.........................
# JASPER_Studio
## Аккаунт
https://community.jaspersoft.com/user

paswort - 548655618Zz.

User Name 016
Real Name Nick Borissenko
E-mail 016@rambler.ru
Location United States
State/Province California
Company Info
Primary Role Software Dev - Developer
Company sw
Company Size 1-100 Employees
Stats
Member For 8 min 48 sec
Last Access Jan 13 2021 - 2:11am

## Загрузка
https://community.jaspersoft.com/project/jaspersoft-studio/releases

## Тоже предлагают загрузить
https://betacode.net/10247/install-jaspersoft-studio-for-eclipse









# jasper-reports
##
туториал
https://riptutorial.com/Download/jasper-reports-ru.pdf
https://habr.com/ru/sandbox/23741/ - советы
https://betacode.net/10271/jasperreport-tutorial-for-beginners

