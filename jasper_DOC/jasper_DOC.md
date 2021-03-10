https://www.tutorialspoint.com/jasper_reports/jasper_report_groups.htm

https://coderlessons.com/tutorials/java-tekhnologii/uznaite-jasperreports/jasperreports-kratkoe-rukovodstvo
https://community.jaspersoft.com/project/jaspersoft-studio
https://www.tutorialspoint.com/jasper_reports/jasper_report_sections.htm

https://betacode.net/10271/jasperreport-tutorial-for-beginners


# JasperReports — Начало работы
Отчет — это значимое, четкое и обобщенное представление информации. Обычно рутинные действия автоматизируются, а данные обобщаются в «Отчеты» для поддержки принятия решений. Отчеты представляют обычные грязные данные в виде диаграмм, графиков и других форм графического представления.

## Шаблон отчета
Как правило, следующая схема используется для создания отчетов большинством коммерческих инструментов создания отчетов.

ЗАГЛАВИЕ
ЗАГОЛОВОК СТРАНИЦЫ
ColumnHeader
ДЕТАЛЬ
Подвал колонки
PageFooter
РЕЗЮМЕ
Ниже приведены описания каждого элемента, упомянутого на диаграмме.

S.NO	Элемент и описание
1	
заглавие

Заголовок содержит «Заголовок» отчета. Он появляется только один раз в самом начале отчета, например, «Отчет о точках обучения».

2	
Заголовок страницы

PageHeader может содержать информацию о дате и времени и / или название организации. Это появляется в верхней части каждой страницы.

3	
ColumnHeader

ColumnHeader перечисляет имена тех конкретных полей, которые вы хотите отобразить в отчете, например, «Имя автора», «Начальный час», «Конечный час», «Отработанные часы», «Дата» и т. Д.

4	
подробно

Подробно — это та часть, где отображаются записи определенных полей (перечисленных в columnHeader), например, «Маниша», «9:00», «18:00», «9», «10.02.2013».

5	
Подвал колонки

ColumnFooter может отображать суммирование любого поля, например, «Всего отработанных часов:« 180 ».

6	
PageFooter

PageFooter может содержать информацию о количестве страниц. Он появляется внизу каждой страницы, например, «1/23».

7	
резюме

Сводка содержит информацию, выведенную из части «детализация», например, после перечисления количества часов, отработанных каждым автором, общее количество отработанных часов каждым автором может быть помещено в визуальную диаграмму, такую ​​как круговая диаграмма, график и т. Д., Для лучшего сравнения.

заглавие

Заголовок содержит «Заголовок» отчета. Он появляется только один раз в самом начале отчета, например, «Отчет о точках обучения».

Заголовок страницы

PageHeader может содержать информацию о дате и времени и / или название организации. Это появляется в верхней части каждой страницы.

ColumnHeader

ColumnHeader перечисляет имена тех конкретных полей, которые вы хотите отобразить в отчете, например, «Имя автора», «Начальный час», «Конечный час», «Отработанные часы», «Дата» и т. Д.

подробно

Подробно — это та часть, где отображаются записи определенных полей (перечисленных в columnHeader), например, «Маниша», «9:00», «18:00», «9», «10.02.2013».

Подвал колонки

ColumnFooter может отображать суммирование любого поля, например, «Всего отработанных часов:« 180 ».

PageFooter

PageFooter может содержать информацию о количестве страниц. Он появляется внизу каждой страницы, например, «1/23».

резюме

Сводка содержит информацию, выведенную из части «детализация», например, после перечисления количества часов, отработанных каждым автором, общее количество отработанных часов каждым автором может быть помещено в визуальную диаграмму, такую ​​как круговая диаграмма, график и т. Д., Для лучшего сравнения.

JasperReports
Ниже приведены общие проблемы, с которыми сталкиваются при разработке отчета.

Основные изменения — обычно отражают изменения или улучшения бизнеса, необходимые для изменения основной логики отчета.

Экспорт результатов — существует широкий спектр форматов, в которые может быть экспортирован ваш отчет, например: HTML, текст, PDF, MS Excel, RTF, ODT, значения через запятую, XML или изображение.

Сложные отчеты — хороший отчет.

Отчеты о диаграммах — визуальные диаграммы, например, График, Круговая диаграмма, Линия XY, Столбец, Метр и Временные ряды.

Основные изменения — обычно отражают изменения или улучшения бизнеса, необходимые для изменения основной логики отчета.

Экспорт результатов — существует широкий спектр форматов, в которые может быть экспортирован ваш отчет, например: HTML, текст, PDF, MS Excel, RTF, ODT, значения через запятую, XML или изображение.

Сложные отчеты — хороший отчет.

Отчеты о диаграммах — визуальные диаграммы, например, График, Круговая диаграмма, Линия XY, Столбец, Метр и Временные ряды.

Чтобы устранить накладные расходы, упомянутые выше, и упростить процесс отчетности, было представлено множество платформ, инструментов, библиотек и сторонних приложений. JasperReports является одним из них.

JasperReports — это движок Java-отчетов с открытым исходным кодом. Он основан на Java и не имеет собственного синтаксиса выражений. JasperReports имеет возможность доставлять богатый контент на экран, на принтер или в файлы PDF, HTML, XLS, RTF, ODT, CSV, TXT и XML. Поскольку это не отдельный инструмент, его нельзя установить самостоятельно. Вместо этого он встраивается в приложения Java путем включения его библиотеки в CLASSPATH приложения.

JasperReports — это библиотека классов Java, и она не предназначена для конечных пользователей, а скорее предназначена для разработчиков Java, которым необходимо добавить возможности отчетности в свои приложения.

Особенности JasperReports
Некоторые из важных особенностей JasperReports —

Имеет гибкий макет отчета.

Он может представлять данные в текстовом или графическом виде.

Разработчики могут предоставлять данные несколькими способами.

Он может принимать данные из нескольких источников данных.

Он может генерировать водяные знаки (водяной знак похож на вторичное изображение, которое накладывается поверх основного изображения).

Он может генерировать подотчеты.

Он способен экспортировать отчеты в различных форматах.

Имеет гибкий макет отчета.

Он может представлять данные в текстовом или графическом виде.

Разработчики могут предоставлять данные несколькими способами.

Он может принимать данные из нескольких источников данных.

Он может генерировать водяные знаки (водяной знак похож на вторичное изображение, которое накладывается поверх основного изображения).

Он может генерировать подотчеты.

Он способен экспортировать отчеты в различных форматах.

JasperReports — Настройка среды
JasperReports — это чистая библиотека Java, а не отдельное приложение. Он не может работать сам по себе, поэтому его необходимо встроить в другое клиентское или серверное Java-приложение. Поскольку он основан на Java, его можно запускать на любой платформе, поддерживающей Java (JDK 1.3 и выше). Все функциональные возможности JasperReport собраны в одном файле JAR, jasperreports-xxxjar. Этот JAR, а также необходимые и дополнительные библиотеки (файл .ZIP) можно загрузить с сайта: JasperReport Library Link . Загрузите последнюю версию по этой ссылке.

ZIP-файл включает JAR-файл JasperReports вместе с исходным кодом JasperReports, зависимыми JAR-файлами и множеством примеров, демонстрирующих функциональные возможности JasperReport.

JasperReport Environment
Чтобы приступить к созданию отчетов, нам нужно подготовить среду. Извлеките загруженный файл JasperReport.ZIP в любое место (в нашем случае мы распаковали его в C: \ tools \ jasperreports-5.0.1). Структура каталогов извлеченного файла такая же, как показано ниже —

Структура каталогов Jasper

Вот деталь всех каталогов —

build — Содержит скомпилированные файлы классов JasperReport.

демо — содержит различные примеры, демонстрирующие несколько аспектов функциональности JasperReports.

dist — содержит файл jasperreports-xxxjar. Мы добавим этот JAR-файл в наш CLASSPATH, чтобы воспользоваться JasperReports.

docs — содержит локальную копию документации JasperReports.

lib — содержит все JAR-файлы, необходимые как для сборки JasperReports, так и для использования в наших приложениях.

src — содержит исходный код JasperReports.

build.xml — ANT-файл сборки для сборки исходного кода JasperReports. Если мы не собираемся изменять JasperReports, нам не нужно использовать этот файл, поскольку JasperReports распространяется в скомпилированной форме.

changes.txt — текстовый документ, объясняющий различия между текущей и предыдущими версиями библиотеки классов JasperReports.

license.txt — текстовый документ, который содержит полный текст лицензии LGPL (Lesser General Public License).

readme.txt — текстовый документ, содержащий инструкции о том, как построить и выполнить предоставленные примеры.

build — Содержит скомпилированные файлы классов JasperReport.

демо — содержит различные примеры, демонстрирующие несколько аспектов функциональности JasperReports.

dist — содержит файл jasperreports-xxxjar. Мы добавим этот JAR-файл в наш CLASSPATH, чтобы воспользоваться JasperReports.

docs — содержит локальную копию документации JasperReports.

lib — содержит все JAR-файлы, необходимые как для сборки JasperReports, так и для использования в наших приложениях.

src — содержит исходный код JasperReports.

build.xml — ANT-файл сборки для сборки исходного кода JasperReports. Если мы не собираемся изменять JasperReports, нам не нужно использовать этот файл, поскольку JasperReports распространяется в скомпилированной форме.

changes.txt — текстовый документ, объясняющий различия между текущей и предыдущими версиями библиотеки классов JasperReports.

license.txt — текстовый документ, который содержит полный текст лицензии LGPL (Lesser General Public License).

readme.txt — текстовый документ, содержащий инструкции о том, как построить и выполнить предоставленные примеры.

По сути, мы используем только jasperreports-xxxjar в dist и JAR в каталоге lib для генерации отчетов. Поскольку JasperReports является инструментом с открытым исходным кодом, если во время выполнения в jasperreports-xxxjar обнаружен какой-либо дефект или ошибка, мы можем исправить это и снова собрать JAR-файл, используя файл build.xml.

Установите CLASSPATH
Чтобы использовать JasperReport, нам нужно установить следующие файлы в наш CLASSPATH:

jasperreports-xxxjar, где xxx — версия JasperReports. Это находится в каталоге C: \ tools \ jasperreports-xxx \ dist).

Все файлы JAR в подкаталоге lib (C: \ tools \ jasperreports-xxx \ lib).

jasperreports-xxxjar, где xxx — версия JasperReports. Это находится в каталоге C: \ tools \ jasperreports-xxx \ dist).

Все файлы JAR в подкаталоге lib (C: \ tools \ jasperreports-xxx \ lib).

На момент установки мы использовали JasperReport версии 5.0.1. Щелкните правой кнопкой мыши «Мой компьютер» и выберите «Свойства», нажмите кнопку «Переменные среды» на вкладке «Дополнительно». Теперь обновите переменную ‘Path’ с помощью этой C: \ tools \ jasperreports-5.0.1 \ dist \ jasperreports-5.0.1.jar: C: \ tools \ jasperreports-5.0.1 \ lib . Теперь вы готовы создавать свои отчеты.

Во всех примерах этого руководства мы использовали задачи ANT для создания отчетов. Файл сборки заботится об импорте всех необходимых файлов JAR для генерации отчетов. Следовательно, установка CLASSPATH, как упомянуто выше, поможет только тем, кто хочет создавать отчеты без использования ANT.

Настройка сборки
Все примеры в этом уроке —

были написаны с использованием простого текстового редактора.

были сохранены в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint.

были скомпилированы и выполнены из командной строки, используя Apache ANT. Мы будем использовать файл baseBuild.xml , который мы импортируем в файл ANT build.xml в следующих главах. Сохраните этот файл в C: \ tools \ jasperreports-5.0.1 \ test. Ниже приводится содержимое файла baseBuild.xml —

были написаны с использованием простого текстового редактора.

были сохранены в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint.

были скомпилированы и выполнены из командной строки, используя Apache ANT. Мы будем использовать файл baseBuild.xml , который мы импортируем в файл ANT build.xml в следующих главах. Сохраните этот файл в C: \ tools \ jasperreports-5.0.1 \ test. Ниже приводится содержимое файла baseBuild.xml —

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportExample" basedir = ".">
   <description>Previews our JasperReport XML Design</description>
   <property name = "file.name" value = "jasper_report_template" />
   
   <!-- Directory where the JasperReports project file was extracted
   needs to be changed to match the local environment -->
   <property name = "jasper.dir" value = "../" />
   <property name = "dist.dir" value = "${jasper.dir}/dist" />
   <property name = "lib.dir" value = "${jasper.dir}/lib" />
   <property name = "src.dir" value = "src" />
   <property name = "classes.dir" value = "classes" />
   <property name = "main-class" value = "com.tutorialspoint.HelpMe" />

   <path id = "classpath">
      <pathelement location = "./" />
      <pathelement location = "${classes.dir}" />
	  
      <fileset dir = "${lib.dir}">
         <include name = "**/*.jar" />
      </fileset>
	  
      <fileset dir = "${dist.dir}">
         <include name = "**/*.jar" />
      </fileset>
   </path>
   
   <target name = "compile" depends = "clean-sample">
      <mkdir dir = "${classes.dir}"/>
		
      <javac srcdir = "${src.dir}" destdir = "${classes.dir}" 
         classpathref = "classpath" />
   </target>
   
   <target name = "run" depends = "compile">
      <echo message = "Running class : ${main-class}"/>
	  
      <java fork = "true" classname = "${main-class}">
         <classpath>
            <path refid = "classpath" />
         </classpath>
      </java>
   </target>
   
   <target name = "clean-sample">
      <delete dir = "${classes.dir}" />
      <delete file = "./${file.name}.jasper" />
      <delete file = "./${file.name}.jrprint" />
   </target>
   
</project>
Этот файл имеет все необходимые цели, такие как очистка каталогов, компиляция java-файлов и выполнение файлов классов.

Ниже приведены подробности, упомянутые различными каталогами в baseBuild.xml. Предполагая, что текущим каталогом является C: \ tools \ jasperreports-5.0.1 \ test) —

jasper.dir — это каталог C: \ tools \ jasperreports-5.0.1

lib.dir — это каталог C: \ tools \ jasperreports-5.0.1 \ lib

src.dir — это C: \ tools \ jasperreports-5.0.1 \ test \ src

classes.dir — это C: \ tools \ jasperreports-5.0.1 \ test \ classes

основной класс — com.tutorialspoint.HelpMe. Этот класс выполняется простым классом, когда имя файла класса не передается из командной строки. Сохраните этот файл в C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint.

jasper.dir — это каталог C: \ tools \ jasperreports-5.0.1

lib.dir — это каталог C: \ tools \ jasperreports-5.0.1 \ lib

src.dir — это C: \ tools \ jasperreports-5.0.1 \ test \ src

classes.dir — это C: \ tools \ jasperreports-5.0.1 \ test \ classes

основной класс — com.tutorialspoint.HelpMe. Этот класс выполняется простым классом, когда имя файла класса не передается из командной строки. Сохраните этот файл в C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint.

package com.tutorialspoint;

public class HelpMe {
   public static void main(String[] args) {
      System.out.println("This is the default class executed."
         + "Please pass the fully qualified class" + " name to be executed as command line"
         + " parameter, for example," + " com.tutorialspoint.HelpMe ");
   }
}
Джаспер Менеджеры Классы
Существует несколько классов, которые будут использоваться для компиляции дизайна отчета JRXML, для заполнения отчета, печати отчета, экспорта в файлы PDF, HTML и XML, просмотра сгенерированных отчетов и дизайна отчета.

Классы менеджера

Список этих классов —

net.sf.jasperreports.engine.JasperCompileManager — используется для компиляции шаблона отчета JRXML.

net.sf.jasperreports.engine.JasperFillManager — используется для заполнения отчета данными из источника данных.

net.sf.jasperreports.engine.JasperPrintManager — используется для печати документов, созданных библиотекой JasperReports.

net.sf.jasperreports.engine.JasperExportManager — используется для получения содержимого PDF, HTML или XML для документов, созданных в процессе заполнения отчета.

net.sf.jasperreports.view.JasperViewer — представляет собой простое приложение Java Swing, которое может загружать и отображать отчеты.

net.sf.jasperreports.view.JasperDesignViewer — используется во время разработки для предварительного просмотра шаблонов отчетов.

net.sf.jasperreports.engine.JasperCompileManager — используется для компиляции шаблона отчета JRXML.

net.sf.jasperreports.engine.JasperFillManager — используется для заполнения отчета данными из источника данных.

net.sf.jasperreports.engine.JasperPrintManager — используется для печати документов, созданных библиотекой JasperReports.

net.sf.jasperreports.engine.JasperExportManager — используется для получения содержимого PDF, HTML или XML для документов, созданных в процессе заполнения отчета.

net.sf.jasperreports.view.JasperViewer — представляет собой простое приложение Java Swing, которое может загружать и отображать отчеты.

net.sf.jasperreports.view.JasperDesignViewer — используется во время разработки для предварительного просмотра шаблонов отчетов.

Настройка Apache ANT
Мы собираемся собрать все примеры, используя Apache ANT. Поэтому, пожалуйста, ознакомьтесь с главой ANT — Настройка среды, чтобы настроить Apache ANT в вашей системе.

JasperReports — Жизненный цикл
Основная цель JasperReports — создание ориентированных на страницы, готовых к печати документов простым и гибким способом. Следующая блок-схема изображает типичный рабочий процесс при создании отчетов.

Жизненный цикл Джаспер

Как показано на рисунке, жизненный цикл состоит из следующих фаз:

Разработка отчета. На этом шаге мы создаем файл JRXML, который представляет собой документ XML, содержащий определение макета отчета. Мы можем использовать любой текстовый редактор или iReportDesigner, чтобы создать его вручную. Если используется iReportDesigner, макет разрабатывается визуально, поэтому реальную структуру JRXML можно игнорировать.

Компиляция отчета. На этом этапе JRXML компилируется в двоичный объект, называемый файлом Jasper (* .jasper). Эта компиляция сделана из соображений производительности. Файлы Jasper — это то, что вам нужно присылать вместе с приложением для запуска отчетов.

Выполнение отчета (Заполнение данных в отчете) — на этом этапе данные из приложения заполняются в скомпилированном отчете. Класс net.sf.jasperreports.engine.JasperFillManager предоставляет необходимые функции для заполнения данных в отчетах. Создается файл печати Jasper (* .jrprint), который можно использовать для печати или экспорта отчета.

Экспорт отчета в желаемый формат. На этом этапе мы можем экспортировать файл печати Jasper, созданный на предыдущем шаге, в любой формат, используя JasperExportManager. Поскольку Jasper предоставляет различные формы экспорта, следовательно, с одним и тем же вводом, мы можем создать несколько представлений данных.

Разработка отчета. На этом шаге мы создаем файл JRXML, который представляет собой документ XML, содержащий определение макета отчета. Мы можем использовать любой текстовый редактор или iReportDesigner, чтобы создать его вручную. Если используется iReportDesigner, макет разрабатывается визуально, поэтому реальную структуру JRXML можно игнорировать.

Компиляция отчета. На этом этапе JRXML компилируется в двоичный объект, называемый файлом Jasper (* .jasper). Эта компиляция сделана из соображений производительности. Файлы Jasper — это то, что вам нужно присылать вместе с приложением для запуска отчетов.

Выполнение отчета (Заполнение данных в отчете) — на этом этапе данные из приложения заполняются в скомпилированном отчете. Класс net.sf.jasperreports.engine.JasperFillManager предоставляет необходимые функции для заполнения данных в отчетах. Создается файл печати Jasper (* .jrprint), который можно использовать для печати или экспорта отчета.

Экспорт отчета в желаемый формат. На этом этапе мы можем экспортировать файл печати Jasper, созданный на предыдущем шаге, в любой формат, используя JasperExportManager. Поскольку Jasper предоставляет различные формы экспорта, следовательно, с одним и тем же вводом, мы можем создать несколько представлений данных.

Подробный обзор каждого из вышеперечисленных шагов будет дан в последующих главах.

JasperReports — Дизайн
Шаблоны JRXML (или файлы JRXML) в JasperReport являются стандартными файлами XML с расширением .jrxml. Все файлы JRXML содержат тег <jasperReport> в качестве корневого элемента. Это, в свою очередь, содержит много подэлементов (все они являются необязательными). Платформа JasperReport может обрабатывать различные виды источников данных. В этом руководстве мы покажем, как сгенерировать базовый отчет, просто передав набор объектов данных Java (используя Java-бины) в JasperReport Engine. Окончательный отчет должен отображать список людей с категориями, включая их имена и страны.

В этой главе рассматриваются следующие шаги, чтобы описать — как спроектировать JasperReport —

Создание шаблона отчета JRXML и.
Предварительный просмотр шаблона отчета XML.
Создание шаблона отчета JRXML
Создайте файл JRXML, который является jasper_report_template.jrxml, с помощью текстового редактора и сохраните этот файл в C: \ tools \ jasperreports-5.0.1 \ test согласно нашей настройке среды.

<?xml version = "1.0" encoding = "UTF-8"?>
<!DOCTYPE jasperReport PUBLIC "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth = "555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20">
  
   <queryString>
      <![CDATA[]]>
   </queryString>
   
   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>
	
   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>
	
   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" width = "535" 
               height = "15" backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
			
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
  
      </band>
   </columnHeader>
 
    <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" width = "535" 
               height = "14" backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
			
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>

      </band>
   </detail>
	
</jasperReport>
Вот подробности основных полей в приведенном выше шаблоне отчета —

<queryString> — Это пусто (так как мы передаем данные через Java Beans). Обычно содержит оператор SQL, который извлекает результат отчета.

<имя поля> — этот элемент используется для отображения данных из источников данных или запросов в шаблоны отчетов. имя повторно используется в теле отчета и учитывает регистр.

<fieldDescription> — этот элемент сопоставляет имя поля с соответствующим элементом в файле XML.

<staticText> — определяет статический текст, который не зависит от источников данных, переменных, параметров или выражений отчета.

<textFieldExpression> — определяет внешний вид поля результата.

$ F {страна} — это переменная, которая содержит значение предопределенного поля результата в теге <имя поля>.

<band> — Полосы содержат данные, которые отображаются в отчете.

<queryString> — Это пусто (так как мы передаем данные через Java Beans). Обычно содержит оператор SQL, который извлекает результат отчета.

<имя поля> — этот элемент используется для отображения данных из источников данных или запросов в шаблоны отчетов. имя повторно используется в теле отчета и учитывает регистр.

<fieldDescription> — этот элемент сопоставляет имя поля с соответствующим элементом в файле XML.

<staticText> — определяет статический текст, который не зависит от источников данных, переменных, параметров или выражений отчета.

<textFieldExpression> — определяет внешний вид поля результата.

$ F {страна} — это переменная, которая содержит значение предопределенного поля результата в теге <имя поля>.

<band> — Полосы содержат данные, которые отображаются в отчете.

Как только дизайн отчета будет готов, сохраните его в каталоге C: \.

Предварительный просмотр шаблона отчета XML
В JAR-файле JasperReports имеется утилита net.sf.jasperreports.view.JasperDesignViewer , которая помогает в предварительном просмотре дизайна отчета без необходимости его компиляции или заполнения. Эта утилита является автономным приложением Java, поэтому может быть выполнена с использованием ANT.

Давайте напишем ANT target viewDesignXML для просмотра JRXML. Итак, давайте создадим и сохраним build.xml в каталоге C: \ tools \ jasperreports-5.0.1 \ test (должен быть расположен в том же каталоге, где находится JRXML). Вот файл build.xml —

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewDesignXML" basedir = ".">

   <import file = "baseBuild.xml" />
   <target name = "viewDesignXML" description = "Design viewer is 
      launched to preview the JXML report design.">
      
      <java classname = "net.sf.jasperreports.view.JasperDesignViewer" fork = "true">
         <arg value = "-XML" />
         <arg value = "-F${file.name}.jrxml" />
         <classpath refid = "classpath" />
      </java>
   </target>

</project>
Далее, давайте откроем командную строку и перейдем в каталог, где находится build.xml. Выполните команду ant (так как viewDesignXML является целью по умолчанию). Вывод следующий —

C:\tools\jasperreports-5.0.1\test>ant
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

viewDesignXML:
[java] log4j:WARN No appenders could be found for logger
(net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
[java] log4j:WARN Please initialize the log4j system properly.
Предупреждение Log4j можно игнорировать, и в результате вышеописанного выполнения открывается окно с меткой «JasperDesignViewer», отображающее предварительный просмотр шаблона нашего отчета.

Jasper Design Viewer

Как видим, отображаются только выражения отчета для получения данных, поскольку JasperDesignViewer не имеет доступа к фактическому источнику данных или параметрам отчета. Завершите работу JasperDesignViewer, закрыв окно или нажав Ctrl-c в окне командной строки.

JasperReports — Составление дизайна отчетов
Мы сгенерировали шаблон JasperReport (файл JRXML) в предыдущей главе. Этот файл нельзя использовать напрямую для создания отчетов. Он должен быть скомпилирован в собственный двоичный формат JasperReport, называемый файлом Jasper . При компиляции мы преобразуем объект JasperDesign в объект JasperReport —

Jasper Report Compiling

Интерфейс net.sf.jasperreports.engine.design.JRCompiler играет центральную роль во время компиляции. Этот интерфейс имеет несколько реализаций в зависимости от языка, используемого для выражений отчета, который может быть написан на Java, Groovy, JavaScript или любом другом языке сценариев, если реализация компилятора может оценить его во время выполнения.

Мы можем скомпилировать файл JRXML следующими двумя способами:

Программная компиляция.
Компиляция через задачу ANT.
Программная компиляция JRXML
JasperReports API предлагает класс фасада net.sf.jasperreports.engine.JasperCompileManager для компиляции JasperReport. Этот класс состоит из нескольких открытых статических методов для компиляции шаблонов отчетов. Источником шаблонов могут быть файлы, потоки ввода и / или объекты памяти.

Содержимое файла JRXML (jasper_report_template.jrxml) выглядит следующим образом. Он сохраняется в каталоге C: \ tools \ jasperreports-5.0.1 \ test —

<?xml version = "1.0" encoding = "UTF-8"?>
<!DOCTYPE jasperReport PUBLIC "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth = "555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20">

   <queryString>
      <![CDATA[]]>
   </queryString>
   
   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>
   
   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>
   
   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" 
               width = "535" height = "15" backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>

            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>
   
   <detail>
      <band height = "16">
		
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" 
               width = "535" height = "14" backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
               
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
	
</jasperReport>
Следующий код демонстрирует компиляцию вышеуказанного файла jasper_report_template.jrxml .

package com.tutorialspoint;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperCompileManager;

public class JasperReportCompile {

   public static void main(String[] args) {
      String sourceFileName = "C://tools/jasperreports-5.0.1/test" + 
         "/jasper_report_template.jrxml";

      System.out.println("Compiling Report Design ...");
      try {
          /**
          * Compile the report to a file name same as
          * the JRXML file name
          */
         JasperCompileManager.compileReportToFile(sourceFileName);
      } catch (JRException e) {
         e.printStackTrace();
      }
      System.out.println("Done compiling!!! ...");
   }
}
Компиляция шаблонов
В качестве следующего шага давайте сохраним указанное выше содержимое в файле C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportCompile.java и импортируем baseBuild.xml в файл build.xml, как показано ниже. В baseBuild.xml уже есть цели компиляции и запуска —

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "run" basedir = ".">

   <import file = "baseBuild.xml"/>

</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportCompile как —

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class = com.tutorialspoint.JasperReportCompile
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml
compile:
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:27:
   warning: 'includeantruntime' was not set, defaulting to
   build.sysclasspath=last;set to false for repeatable builds
   [javac] Compiling 1 source file to C:\tools\jasperreports-5.0.1\test\classes

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportCompile
   [java] Compiling Report Design ...
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [java] log4j:WARN Please initialize the log4j system properly.
   [java] Done compiling!!! ...

BUILD SUCCESSFUL
Total time: 8 seconds
В результате вышеупомянутой компиляции вы увидите, что файл шаблона jasper_report_template.jasper сгенерирован в каталоге C: \ tools \ jasperreports-5.0.1 \ test.

Предварительный просмотр скомпилированного шаблона отчета
Net.sf.jasperreports.view.JasperDesignViewer можно использовать для предварительного просмотра шаблонов скомпилированных отчетов и шаблонов JRXML.

Чтобы двигаться дальше, давайте добавим новый целевой viewDesign в вышеупомянутый файл build.xml, который позволит нам предварительно просмотреть скомпилированный отчет. Ниже приведен пересмотренный build.xml —

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewDesign" basedir = ".">

   <import file = "baseBuild.xml" />
   <target name = "viewDesign" description="Design viewer is launched 
      to preview the compiled report design.">
      
      <java classname = "net.sf.jasperreports.view.JasperDesignViewer" fork = "true">
         <arg value = "-F${file.name}.jasper" />
         <classpath refid = "classpath" />
      </java>
   </target>

</project>
Давайте выполним команду — ant (viewDesign — цель по умолчанию) в командной строке. Откроется окно JasperDesignViewer с файлом Jasper, как показано ниже:

Jasper Design Viewer

Компиляция через ANT Task
Поскольку компиляция шаблона отчета больше напоминает задание времени разработки, чем задание времени выполнения, в библиотеке JasperReport есть настраиваемая задача ANT. В определенных ситуациях, когда файл JRXML создается во время выполнения, мы не можем использовать эту задачу ANT. Пользовательская задача ANT называется JRC и реализуется классом: net.sf.jasperreports.ant.JRAntCompileTask . Его синтаксис и поведение очень похожи на встроенную задачу <javac> ANT.

Компиляция шаблонов
Давайте добавим новый целевой compilereportdesing в наш существующий build.xml. Здесь исходная папка указывается с помощью вложенного тега <src> с наборами файлов. Вложенный тег источника позволяет составлять шаблоны отчетов, которые разбросаны по разным местам и не сгруппированы в одной корневой папке источника отчетов. Ниже приведен пересмотренный build.xml —

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "compilereportdesing" basedir = ".">
   
   <import file = "baseBuild.xml" />
   <target name = "viewDesign" description = "Design viewer is 
      launched to preview the compiled report design.">
      
      <java classname = "net.sf.jasperreports.view.JasperDesignViewer" fork = "true">
         <arg value = "-F${file.name}.jasper" />
         <classpath refid = "classpath" />
      </java>
		
   </target>

   <target name = "compilereportdesing" description = "Compiles the 
      JXML file and produces the .jasper file.">
		
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   </target>

</project>
Далее, давайте откроем командную строку и перейдем в каталог, где находится build.xml. Выполните команду ant (compilereportdesing является целью по умолчанию); Выход выглядит следующим образом —

C:\tools\jasperreports-5.0.1\test>ant
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See
   http://logging.apache.org/log4j/1.2/faq.html#noconfig
   for more info.
   [jrc] File :
   C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

BUILD SUCCESSFUL
Total time: 5 seconds
Файл jasper_report_template.jasper создается в файловой системе (в нашем случае это каталог C: \ tools \ jasperreports-5.0.1 \ test). Этот файл идентичен файлу, сгенерированному программно с помощью вызова net.sf.jasperreports.engine.JasperCompileManager.compileReportToFile (). Мы можем просмотреть этот файл яшмы, выполнив ant viewDesign .

JasperReports — Заполнение отчетов
Основная цель любого инструмента отчетности — выпуск документов высокого качества. Процесс заполнения отчетов помогает инструменту отчетности достичь этого путем манипулирования наборами данных.

Основные входные данные, необходимые для процесса заполнения отчета:

Шаблон отчета — это фактический файл JasperReport.

Параметры отчета — это в основном именованные значения, которые передаются в механизм заполнения отчета. Мы обсудим их в главе « Параметры отчета» .

Источник данных — мы можем заполнить файл Jasper из ряда источников данных, таких как запрос SQL, файл XML, файл csv, запрос HQL (Hibernate Query Language), коллекция Java Beans и т. Д. Это будет подробно обсуждаться в главе « Источники данных отчета» .

Шаблон отчета — это фактический файл JasperReport.

Параметры отчета — это в основном именованные значения, которые передаются в механизм заполнения отчета. Мы обсудим их в главе « Параметры отчета» .

Источник данных — мы можем заполнить файл Jasper из ряда источников данных, таких как запрос SQL, файл XML, файл csv, запрос HQL (Hibernate Query Language), коллекция Java Beans и т. Д. Это будет подробно обсуждаться в главе « Источники данных отчета» .

Выходные данные, генерируемые этим процессом, представляют собой документ .jrprint, который готов для просмотра, печати или экспорта в другие форматы. Класс фасада net.sf.jasperreports.engine.JasperFillManager обычно используется для заполнения шаблона отчета данными. Этот класс имеет различные методы fillReportXXX (), которые заполняют шаблоны отчетов (шаблоны могут находиться на диске, выбираться из входных потоков или предоставляться непосредственно в оперативной памяти).

В этом классе фасада есть две категории методов fillReportXXX ():

Первый тип, получить объект java.sql.Connection в качестве третьего параметра. В большинстве случаев отчеты заполняются данными из реляционной базы данных. Это достигается путем —

Подключитесь к базе данных через JDBC.

Включите SQL-запрос в шаблон отчета.

Движок JasperReports использует переданное соединение и выполняет запрос SQL.

Таким образом, создается источник данных отчета для заполнения отчета.

Второй тип, получает объект net.sf.jasperreports.engine.JRDataSource, когда данные, которые необходимо заполнить, доступны в других формах.

Первый тип, получить объект java.sql.Connection в качестве третьего параметра. В большинстве случаев отчеты заполняются данными из реляционной базы данных. Это достигается путем —

Подключитесь к базе данных через JDBC.

Включите SQL-запрос в шаблон отчета.

Движок JasperReports использует переданное соединение и выполняет запрос SQL.

Таким образом, создается источник данных отчета для заполнения отчета.

Второй тип, получает объект net.sf.jasperreports.engine.JRDataSource, когда данные, которые необходимо заполнить, доступны в других формах.

Заполнение шаблонов отчетов
Давайте напишем шаблон отчета. Содержимое файла JRXML (C: \ tools \ jasperreports-5.0.1 \ test \ jasper_report_template.jrxml) приведено ниже:

<?xml version = "1.0" encoding = "UTF-8"?>
<!DOCTYPE jasperReport PUBLIC "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth = "555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20">

   <queryString>
      <![CDATA[]]>
   </queryString>
   
   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>
   
   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>

   <columnHeader>
      <band height = "23">
  
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" 
               width = "535" height = "15" backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
			
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
				
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>
   
   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" 
               width = "535" height = "14" backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
	
</jasperReport>
Далее, давайте передадим коллекцию объектов данных Java (Java-бинов) в JasperReport Engine, чтобы заполнить этот скомпилированный отчет.

Напишите POJO DataBean.java, который представляет объект данных (Java bean). Этот класс определяет два объекта String, т. Е. «Имя» и «страна». Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint .

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Напишите класс DataBeanList.java, который имеет бизнес-логику для генерации коллекции объектов Java-бина. Затем он передается в движок JasperReports для генерации отчета. Здесь мы добавляем 4 объекта DataBean в список. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint .

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Напишите файл основного класса JasperReportFill.java , который получает коллекцию Java-бинов из класса (DataBeanList) и передает ее в механизм JasperReports, чтобы заполнить шаблон отчета. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint .

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = 
         "c://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";
      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource = new 
         JRBeanCollectionDataSource(dataList);
      Map parameters = new HashMap();
      try {
         JasperFillManager.fillReportToFile( 
            sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Генерация отчетов
Теперь мы скомпилируем и выполним эти файлы, используя наш обычный процесс сборки ANT. Файл build.xml как показано ниже —

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "executereport" basedir = ".">
   <import file = "baseBuild.xml"/>

   <target name = "executereport" depends = "compile,compilereportdesing,run">
      <echo message = "Im here"/>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
         
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
		
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill ( executereport является целью по умолчанию) следующим образом:

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class = com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

compile:
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:27:
   warning: 'includeantruntime' was not set, defaulting to
   build.sysclasspath=last; set to false for repeatable builds
   [javac] Compiling 1 source file to
   C:\tools\jasperreports-5.0.1\test\classes

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 8 seconds
В результате выполнения вышеупомянутого файла jasper_report_template.jrprint создается в том же каталоге, что и файл .jasper (в этом случае он создается в C: \ tools \ jasperreports-5.0.1 \ test).

Jasper Report — Просмотр и печать отчетов
Выходные данные процесса заполнения отчета Объекты JasperPrint можно просматривать с помощью встроенного компонента средства просмотра, либо распечатывать, либо экспортировать в более популярные форматы документов, такие как PDF, HTML, RTF, XLS, ODT, CSV или XML. Просмотр и печать документов Jasper будут обсуждаться в этой главе, а экспорт будет обсуждаться в следующей главе, т.е. «Экспорт отчетов».

Просмотр отчетов
JasperReport предоставляет встроенную программу просмотра для просмотра сгенерированных отчетов в исходном формате. Это компонент на основе свинга, и другие приложения Java могут интегрировать этот компонент без необходимости экспортировать документы в другие форматы для просмотра или печати. Класс net.sf.jasperreports.view.JRViewer представляет этот визуальный компонент. Этот класс также может быть настроен в соответствии с потребностями приложения путем его подклассификации.

JasperReports также имеет приложение Swing, которое использует визуальный компонент для просмотра отчетов. Это приложение помогает просматривать отчеты в том же формате, что и * .jrprint. Это приложение Swing реализовано в классе net.sf.jasperreports.view.JasperViewer . Чтобы просмотреть отчеты, использующие этот класс, нам нужно обернуть его в цель ANT.

Просмотр сгенерированного отчета
В следующем примере показано, как просмотреть отчет с помощью класса JasperViewer.

Давайте напишем шаблон отчета. Содержимое файла JRXML (C: \ tools \ jasperreports-5.0.1 \ test \ jasper_report_template.jrxml) приведено ниже:

<?xml version = "1.0" encoding = "UTF-8"?>
<!DOCTYPE jasperReport PUBLIC "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth = "555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20">

   <queryString>
      <![CDATA[]]>
   </queryString>
   
   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>
   
   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>
   
   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" 
               width = "535" height = "15" backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>
   
   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" 
               width = "535" height = "14" backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
	
</jasperReport>
Далее, давайте передадим коллекцию объектов данных Java (Java-бинов) в JasperReports Engine, чтобы заполнить этот скомпилированный отчет.

Напишите POJO DataBean.java, который представляет объект данных (Java bean). Этот класс определяет два объекта String, т.е. «имя» и «страна». Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint .

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Напишите класс DataBeanList.java, который имеет бизнес-логику для генерации коллекции объектов Java-бина. Затем он передается в движок JasperReports для генерации отчета. Здесь мы добавляем 4 объекта DataBean в список. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint .

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Напишите файл основного класса JasperReportFill.java , который получает коллекцию Java-бинов из класса (DataBeanList) и передает ее в механизм JasperReports, чтобы заполнить шаблон отчета. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint .

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = 
         "c://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";
      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource = new 
         JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      try {
         JasperFillManager.fillReportToFile( 
            sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Давайте напишем целевой viewFillReport в файл build.xml. Файл build.xml выглядит следующим образом:

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml"/>

   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer
      to preview the report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc"
         classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFillReport является целью по умолчанию). В результате мы видим окно JasperViewer, как показано на приведенном ниже экране —

Jasper Report Viewer

Печать отчетов
Мы можем напечатать документы, сгенерированные библиотекой JasperReports (в их собственном формате, то есть объектах JasperPrint ), используя класс net.sf.jasperreports.engine.JasperPrintManager . Это фасадный класс, использующий API печати Java 2. Мы также можем распечатать документы после экспорта документов JasperReport в другие форматы, такие как HTML или PDF.

Печать сгенерированного отчета
Следующий код демонстрирует печать отчета. Давайте обновим наш существующий класс JasperReportFill. Мы будем использовать метод JasperPrintManager.printReport () . Этот метод принимает имя исходного файла (здесь мы передаем файл .jrprint , который мы сгенерировали на предыдущем шаге, используя метод JasperFillManager.fillReportToFile ()) в качестве первого параметра. Второй параметр — это логическое значение для отображения стандартного диалогового окна печати (здесь мы установили его значение true ).

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.JasperPrintManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = "c://tools/jasperreports-5.0.1/" +
         "test/jasper_report_template.jasper";
      String printFileName = null;
      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource = new 
         JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      try {
    	   printFileName = JasperFillManager.fillReportToFile( 
            sourceFileName, parameters, beanColDataSource);
         if(printFileName != null){
            JasperPrintManager.printReport( printFileName, true);
         }
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Теперь давайте сохраним этот файл в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint . Мы скомпилируем и выполним этот файл, используя ANT. Содержимое build.xml приведено ниже.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "executereport" basedir = ".">
   <import file = "baseBuild.xml"/>

   <target name = "executereport" depends = "compile,compilereportdesing,run">
      <echo message = "Im here"/>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc"
         classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
		
   </target>
	
</project>
Далее, давайте откроем командную строку и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportPrint . В результате появится диалоговое окно печати. Нажмите кнопку ОК, чтобы распечатать документ.

JasperReports — Экспорт отчетов
В предыдущей главе мы видели, как распечатать и просмотреть документ, сгенерированный JasperReport. Здесь мы увидим, как преобразовать или экспортировать эти отчеты в другие форматы, такие как PDF, HTML и XLS. Класс фасада net.sf.jasperreports.engine.JasperExportManager предоставляется для достижения этой функциональности. Экспорт означает преобразование объекта JasperPrint (файл .jrprint) в другой формат.

Следующий код (JasperReportExport.java) демонстрирует процесс экспорта документа JasperReport. JasperExportManager предоставляет методы для экспорта отчета только в PDF, HTML и XML. Для экспорта в формат XLS мы использовали класс net.sf.jasperreports.engine.export.JRXlsExporter . Этот код генерирует следующие три файла —

sample_report.pdf
sample_report.html
sample_report.xls
Экспорт в другие форматы
Давайте напишем шаблон отчета. Содержимое файла JRXML (C: \ tools \ jasperreports-5.0.1 \ test \ jasper_report_template.jrxml) приведено ниже:

<?xml version = "1.0" encoding = "UTF-8"?>
<!DOCTYPE jasperReport PUBLIC "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth = "555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20">

   <queryString>
      <![CDATA[]]>
   </queryString>
   
   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>
   
   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>
   
   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" 
               width = "535" height = "15" backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>

   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" 
               width = "535" height = "14" backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
            <text><![CDATA[]]> </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
               
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
	
</jasperReport>
Далее содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java указано ниже —

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Напишите файл основного класса JasperReportFill.java , который получает коллекцию Java-бинов из класса (DataBeanList) и передает ее в механизм JasperReports, чтобы заполнить шаблон отчета. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint .

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JRExporterParameter;
import net.sf.jasperreports.engine.JasperExportManager;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;
import net.sf.jasperreports.engine.export.JRXlsExporter;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = "c://tools/jasperreports-5.0.1/"
         + "test/jasper_report_template.jasper";
      String printFileName = null;
      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();
      JRBeanCollectionDataSource beanColDataSource =
         new JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      try {
         printFileName = JasperFillManager.fillReportToFile(sourceFileName,
            parameters, beanColDataSource);
         if (printFileName != null) {
            /**
             * 1- export to PDF
             */
            JasperExportManager.exportReportToPdfFile(printFileName,
               "C://sample_report.pdf");

            /**
             * 2- export to HTML
             */
            JasperExportManager.exportReportToHtmlFile(printFileName,
               "C://sample_report.html");

            /**
             * 3- export to Excel sheet
             */
            JRXlsExporter exporter = new JRXlsExporter();

            exporter.setParameter(JRExporterParameter.INPUT_FILE_NAME,
               printFileName);
            exporter.setParameter(JRExporterParameter.OUTPUT_FILE_NAME,
               "C://sample_report.xls");

            exporter.exportReport();
         }
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Здесь мы включили логику для экспорта файла печати jasper в формат pdf, html и xls.

Генерация отчетов
Давайте скомпилируем и выполним вышеуказанные файлы, используя наш обычный процесс сборки ANT. Файл build.xml как показано ниже —

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "executereport" basedir = ".">
   <import file = "baseBuild.xml"/>

   <target name = "executereport" depends = "compile,compilereportdesing,run">
      <echo message = "Im here"/>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc"
         classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>
	
</project>
Перейдите в командную строку и перейдите в каталог C: \ tools \ jasperreports-5.0.1 \ test, где находится файл build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill . Выход выглядит следующим образом —

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defaulting t
   [javac] Compiling 4 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

executereport:
   [echo] Im here

BUILD SUCCESSFUL
Total time: 32 seconds
В результате выполнения выше вы найдете три файла sample_report.pdf, sample_report.html, sample_report.xls, сгенерированные в каталоге C: \.

Параметры отчетов
Основные входные данные для заполнения отчета — шаблон отчета, параметры и источники данных. В этой главе будут описаны параметры, а в следующей главе мы обсудим источники данных.

Параметры — это ссылки на объекты, которые передаются при заполнении отчета в механизм отчетов. Данные, которые не могут быть переданы через источник данных, могут быть переданы с использованием параметров. Данные, такие как имя автора, название отчета и т. Д., Могут передаваться через параметры. Шаблон JasperReports или шаблон JRXML могут иметь ноль или более элементов параметров.

Объявление параметров
Объявление параметров следующим образом —

<parameter name = "exampleParameter" class = "java.lang.String" />
Атрибут имени
Атрибут name элемента <parameter> является обязательным. Он ссылается на параметр в выражениях отчета по имени. Имя параметра должно быть одним словом. Он не должен содержать никаких специальных символов, таких как точка или запятая.

Атрибут класса
Атрибут class также является обязательным и определяет имя класса для значений параметров. Значением по умолчанию является java.lang.String . Это может быть изменено на любой класс, доступный во время выполнения. Независимо от типа параметра отчета, механизм заботится о приведении в выражениях отчета, в которых используется токен $ P {}, поэтому нет необходимости выполнять ручное приведение.

Значения параметров отчета всегда упаковываются в объект java.util.Map, ключом которого является имя параметра. Параметры отчета можно использовать в строке запроса отчета, чтобы дополнительно настроить набор данных, извлеченных из базы данных. Они действуют как динамические фильтры в запросе, который предоставляет данные для отчета.

Встроенные параметры
Ниже приведены предварительно определенные параметры отчета, готовые к использованию в выражениях.

S.NO	Имя параметра и описание
1	
REPORT_PARAMETERS_MAP

Содержит карту со всеми определенными пользователем и встроенными параметрами.

2	
REPORT_CONNECTION

Это указывает на предоставленный пользователем класс java.sql.Connection, используемый для источников данных JDBC.

3	
REPORT_DATA_SOURCE

Это предоставленный пользователем экземпляр JRDataSource, представляющий либо один из встроенных типов источников данных, либо определенный пользователем.

4	
REPORT_MAX_COUNT

Это значение java.lang.Integer , позволяющее пользователям ограничивать записи из источника данных.

5	
REPORT_SCRIPTLET

Это указывает на net.sf.jasperreports.engine.JRAbstractScriptlet и содержит экземпляр сценария отчета, предоставленного пользователем.

6	
REPORT_LOCALE

Это экземпляр java.util.Locale , содержащий требуемый языковой пакет для комплекта ресурсов.

7	
REPORT_RESOURCE_BUNDLE

Это указывает на объект java.util.ResourceBundle и содержит локализованные сообщения.

8	
REPORT_TIME_ZONE

Это экземпляр java.util.TimeZone , используемый для форматирования даты.

9	
REPORT_VIRTUALIZER

Это экземпляр объекта net.sf.jasperreports.engine.JRVirtualizer , который используется для виртуализации страницы (оптимизирует потребление памяти).

10	
REPORT_CLASS_LOADER

Это экземпляр java.lang.ClassLoader, который будет использоваться в процессе заполнения отчета для загрузки ресурсов, таких как изображения, шрифты и шаблоны вложенных отчетов.

11	
IS_IGNORE_PAGINATION

Если установлено значение java.lang.Boolean.TRUE, отчет будет сгенерирован на одной длинной странице, и разрыв страницы не произойдет.

REPORT_PARAMETERS_MAP

Содержит карту со всеми определенными пользователем и встроенными параметрами.

REPORT_CONNECTION

Это указывает на предоставленный пользователем класс java.sql.Connection, используемый для источников данных JDBC.

REPORT_DATA_SOURCE

Это предоставленный пользователем экземпляр JRDataSource, представляющий либо один из встроенных типов источников данных, либо определенный пользователем.

REPORT_MAX_COUNT

Это значение java.lang.Integer , позволяющее пользователям ограничивать записи из источника данных.

REPORT_SCRIPTLET

Это указывает на net.sf.jasperreports.engine.JRAbstractScriptlet и содержит экземпляр сценария отчета, предоставленного пользователем.

REPORT_LOCALE

Это экземпляр java.util.Locale , содержащий требуемый языковой пакет для комплекта ресурсов.

REPORT_RESOURCE_BUNDLE

Это указывает на объект java.util.ResourceBundle и содержит локализованные сообщения.

REPORT_TIME_ZONE

Это экземпляр java.util.TimeZone , используемый для форматирования даты.

REPORT_VIRTUALIZER

Это экземпляр объекта net.sf.jasperreports.engine.JRVirtualizer , который используется для виртуализации страницы (оптимизирует потребление памяти).

REPORT_CLASS_LOADER

Это экземпляр java.lang.ClassLoader, который будет использоваться в процессе заполнения отчета для загрузки ресурсов, таких как изображения, шрифты и шаблоны вложенных отчетов.

IS_IGNORE_PAGINATION

Если установлено значение java.lang.Boolean.TRUE, отчет будет сгенерирован на одной длинной странице, и разрыв страницы не произойдет.

пример
Давайте передадим ReportTitle и Author в отчет (сгенерированный JasperReportFill.java). Исправленный файл C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java выглядит следующим образом:

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = 
         "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource =
      new JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      /**
       * Passing ReportTitle and Author as parameters
       */
      parameters.put("ReportTitle", "List of Contacts");
      parameters.put("Author", "Prepared By Manisha");

      try {
         JasperFillManager.fillReportToFile(
         sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java указано ниже —

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Давайте добавим параметры < ReportTitle > и < Author > к нашему существующему шаблону отчета (глава « Конструкции отчета» ). Название и автор отчета будут отображаться в начале отчета. Пересмотренный шаблон отчета (jasper_report_template.jrxml) выглядит следующим образом. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test —

<?xml version = "1.0"?>
<!DOCTYPE jasperReport PUBLIC
   "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" pageWidth = "595"
   pageHeight = "842" columnWidth = "515"
   leftMargin = "40" rightMargin = "40" topMargin = "50" bottomMargin = "50">
	
   <parameter name = "ReportTitle" class = "java.lang.String"/>
   <parameter name = "Author" class = "java.lang.String"/>

   <queryString>
      <![CDATA[]]>
   </queryString>

   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>

   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>

   <title>
      <band height = "70">
         
         <line>
            <reportElement x = "0" y = "0" width = "515" height = "1"/>
         </line>
         
         <textField isBlankWhenNull = "true" bookmarkLevel = "1">
            <reportElement x = "0" y = "10" width = "515" height = "30"/>
           
            <textElement textAlignment = "Center">
               <font size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{ReportTitle}]]>
            </textFieldExpression>
				
            <anchorNameExpression>
               <![CDATA["Title"]]>
            </anchorNameExpression>
         </textField>
         
         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "40" width = "515" height = "20"/>
            
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{Author}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </title>

   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" width = "535" height = "15"
               backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>

   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" width = "535" height = "14"
               backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
	
</jasperReport>
Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />

   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview
      the report stored in the .JRprint file.">
      
		
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>

</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) следующим образом:

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28: warning:
   'includeantruntime' was not set, defaulting to build.sysclasspath=last;
   set to false for repeatable builds
   [javac] Compiling 7 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig
   for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 18 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на следующем экране —

Пример параметра отчета Jasper

Здесь мы видим, что заголовок отчета «Список контактов» и «Автор подготовлен Манишей» отображаются в начале отчета.

Источники данных отчета
Источники данных — это структурированный контейнер данных. При создании отчета механизм JasperReports получает данные из источников данных. Данные могут быть получены из баз данных, файлов XML, массивов объектов и коллекции объектов. Мы видели в главе Заполнение отчетов , метод fillReportXXX () ожидает получить источник данных отчета, который должен заполнить, в виде объекта net.sf.jasperreports.engine.JRDataSource или java.sql.Connection ( когда данные отчета находятся в реляционной базе данных).

Интерфейс JRDataSource имеет только два метода, которые должны быть реализованы:

public boolean next () выбрасывает JRException;

Во время заполнения отчета этот метод вызывается для объекта источника данных механизмом отчетов при итерации по данным.

public Object getFieldValue (JRField jrField) генерирует JRException;

Этот метод предоставляет значение для каждого поля отчета в текущей записи источника данных.

public boolean next () выбрасывает JRException;

Во время заполнения отчета этот метод вызывается для объекта источника данных механизмом отчетов при итерации по данным.

public Object getFieldValue (JRField jrField) генерирует JRException;

Этот метод предоставляет значение для каждого поля отчета в текущей записи источника данных.

Единственный способ получить данные из источника данных — использовать поля отчета. Существует несколько реализаций по умолчанию интерфейса JRDataSource, в зависимости от способа получения записей в источнике данных.

Реализация источников данных
В таблице, приведенной ниже, обобщены источники данных и классы их реализации.

Источник данных	Класс реализации
JDBC	net.sf.jasperreports.engine.JRResultSetDataSource
JavaBean	net.sf.jasperreports.engine.data.JRBeanCollectionDataSource, net.sf.jasperreports.engine.data.JRBeanArrayDataSource
Карта на основе	net.sf.jasperreports.engine.data.JRMapArrayDataSource, net.sf.jasperreports.engine.data.JRMapCollectionDataSource
TableModel	net.sf.jasperreports.engine.data.JRTableModelDataSource
XML	net.sf.jasperreports.engine.data.JRXmlDataSource
CSV	net.sf.jasperreports.engine.data.JRCsvDataSource
XLS	net.sf.jasperreports.engine.data.JRXlsDataSource
пустой	net.sf.jasperreports.engine.JREmptyDataSource
Источники данных JDBC
Класс JRResultSetDataSource создает объект java.sql.ResultSet . Это наиболее часто используемые реализации источника данных, когда данные отчета извлекаются из реляционной базы данных. Если вместо этого в движок передается java.sql.Connection , он сначала выполняет связанный запрос и сохраняет возвращенный объект java.sql.ResultSet в экземпляре JRResultSetDataSource.

Источники данных JavaBean
Классы JRBeanArrayDataSource и JRBeanCollectionDataSource представляют реализации, которые могут обернуть массивы и коллекции объектов JavaBean. Каждый объект в массиве или коллекции будет рассматриваться как одна запись в этом типе источника данных. Отображение между конкретным свойством JavaBean и соответствующим полем отчета выполняется в соответствии с соглашениями об именах. Имя поля отчета должно совпадать с именем свойства JavaBean, как указано в спецификациях JavaBeans.

Во всех примерах этого урока мы использовали JRBeanCollectionDataSource.

Источники данных на основе карт
Классы реализации JRMapArrayDataSource и JRMapCollectionDataSource полезны, если родительское приложение уже хранит данные отчетов, доступные в памяти, как объекты java.util.Map . Каждый объект Map в обернутом массиве или коллекции считается виртуальной записью в источнике данных, и значение каждого поля отчета извлекается из карты с использованием поля отчета, названного ключом.

TableModel Источники данных
Во многих клиентских приложениях данные отображаются в табличном формате. Общее требование во многих приложениях — разрешить пользователю печатать этот табличный формат в виде отчета. Класс реализации JRTableModelDataSource делает задачу генерации отчетов из табличного формата тривиальной для приложений Swing. Этот класс оборачивает объект javax.swing.table.TableModel. Столбцы в обернутом объекте TableModel могут быть доступны либо по их именам, либо по их индексам на основе 0.

Источники данных XML
Класс JRXmlDataSource является реализацией источника данных, основанной на DOM, которая использует выражения XPath для выбора данных из документа XML. Записи в источнике данных XML представлены элементами узла, выбранными с помощью выражения XPath. Значения полей извлекаются из каждой записи с использованием выражения XPath, предоставленного описанием поля (элемент <fieldDescription> в JRXML).

XPath — это язык, используемый для навигации по атрибутам и элементам XML-документа. Дополнительную информацию о XPath можно найти по адресу http://www.w3.org/TR/xpath.

Источники данных CSV
JRCsvDataSource представляет реализацию для источников данных, которые извлекают их данные из структурированных текстовых файлов; обычно CSV. Значения полей извлекаются с использованием их индекса столбца.

Источники данных XLS
JRXlsDataSource представляет реализацию для источников данных, которые получают их данные из документов Excel. Отображение полей отчета для этой реализации источника данных также основано на индексе столбца поля.

Пустые источники данных
Класс JREmptyDataSource имитирует источник данных с заданным количеством виртуальных пустых записей внутри. Он используется инструментами пользовательского интерфейса для предоставления основных функций предварительного просмотра отчетов, либо в специальных шаблонах отчетов, либо для целей тестирования и отладки.

Перезаписываемые источники данных
Net.sf.jasperreports.engine.JRRewindableDataSource расширяет базовый интерфейс JRDataSource . Он добавляет только один метод, называемый moveFirst (), к интерфейсу. Этот метод предназначен для перемещения курсора на первый элемент в источнике данных.

Перезаписываемые источники данных полезны при работе с вложенными отчетами, помещенными в полосу, которая не может быть разделена из-за параметра isSplitAllowed = «false», и на текущей странице недостаточно места для отображения вложенного отчета.

Все вышеперечисленные реализации источника данных можно перематывать, за исключением JRResultSetDataSource , поскольку он не поддерживает перемещение указателя записи назад. Это создает проблему, только если этот источник данных используется вручную, чтобы обернуть java.sql.ResultSet перед передачей его в подотчет. Нет проблем, если запрос SQL находится в шаблоне подотчета, так как механизм выполнит его снова при перезапуске подотчета на следующей странице.

Поставщики источников данных
Библиотека JasperReports имеет интерфейс net.sf.jasperreports.engine.JRDataSourceProvider . Это помогает в создании и удалении объектов источника данных. При создании шаблона отчета с использованием инструментов с графическим интерфейсом необходим специальный инструмент для настройки источника данных отчета. JRDataSourceProvider — это стандартный способ подключения пользовательских источников данных в инструмент проектирования. Пользовательская реализация этого интерфейса должна реализовывать следующие методы, которые позволяют создавать и утилизировать объекты источника данных, а также методы для перечисления доступных полей отчета внутри источника данных, если это возможно —

public boolean supportsGetFieldsOperation();

public JRField[] getFields(JasperReport report)
   throws JRException, UnsupportedOperationException;

public JRDataSource create(JasperReport report) throws JRException;

public void dispose(JRDataSource dataSource) throws JRException;
Поля отчетов
Поля отчета — это элементы, которые отображают данные между источником данных и шаблоном отчета. Поля могут быть объединены в выражениях отчета для получения желаемого результата. Шаблон отчета может содержать ноль или более элементов <field>. При объявлении полей отчета источник данных должен предоставлять данные, соответствующие всем полям, определенным в шаблоне отчета.

Полевая декларация
Объявление поля выполняется, как показано ниже —

<field name = "FieldName" class = "java.lang.String"/>
Атрибут имени
Атрибут name элемента <field> является обязательным. Он ссылается на поле в выражениях отчета по имени.

Атрибут класса
Атрибут class указывает имя класса для значений поля. Значением по умолчанию является java.lang.String . Это может быть изменено на любой класс, доступный во время выполнения. Независимо от типа поля отчета, механизм заботится о приведении в выражениях отчета, в которых используется токен $ F {}, что делает ненужным ручное приведение.

Описание поля
Элемент <fieldDesciption> является необязательным элементом. Это очень полезно при реализации пользовательского источника данных. Например, мы можем сохранить ключ или некоторую информацию, с помощью которой мы можем извлечь значение поля из пользовательского источника данных во время выполнения. Используя элемент <fieldDesciption> вместо имени поля, вы можете легко преодолеть ограничения соглашений об именах полей при получении значений полей из источника данных.

Ниже приведен фрагмент кода из нашего существующего файла JRXML (глава « Проекты отчетов» ). Здесь мы можем увидеть использование элементов name , class и fieldDescription .

<field name = "country" class = "java.lang.String">
   <fieldDescription><![CDATA[country]]></fieldDescription>
</field>

<field name = "name" class = "java.lang.String">
   <fieldDescription><![CDATA[name]]></fieldDescription>
</field>
Сортировать поля
В тех случаях, когда требуется сортировка данных и реализация источника данных не поддерживает ее (например, источник данных CSV), JasperReports поддерживает сортировку источников данных на основе полей в памяти. Сортировка может быть выполнена с использованием одного или нескольких элементов <sortField> в шаблоне отчета.

Если указано хотя бы одно поле сортировки, в процессе заполнения отчета источник данных передается в экземпляр JRSortableDataSource . Это, в свою очередь, выбирает все записи из источника данных, выполняет сортировку в памяти в соответствии с указанными полями и заменяет исходный источник данных.

Имя поля сортировки должно совпадать с именем поля отчета. Поля, используемые для сортировки, должны иметь типы, которые реализуют java.util.Comparable. Естественная сортировка по порядку выполняется для всех полей, кроме полей типа java.lang.String (для типа String используется сортировщик, соответствующий локали заполнения отчета). Если указано несколько полей сортировки, сортировка будет выполняться с использованием полей в качестве ключей сортировки в порядке их появления в шаблоне отчета. Следующий пример демонстрирует функцию сортировки.

Пример отсортированного отчета
Давайте добавим элемент < sortField > в наш существующий шаблон отчета (Глава Отчеты по дизайну ). Давайте разберем поле страны по убыванию. Пересмотренный шаблон отчета (jasper_report_template.jrxml) выглядит следующим образом. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test —

<?xml version = "1.0"?>
<!DOCTYPE jasperReport PUBLIC
   "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports" xmlns:xsi = 
   "http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation = 
   "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd" 
   name = "jasper_report_template" pageWidth = "595" pageHeight = "842" 
   columnWidth = "515" leftMargin = "40" rightMargin = "40" 
   topMargin = "50" bottomMargin = "50">
	
   <parameter name = "ReportTitle" class = "java.lang.String"/>
   <parameter name = "Author" class = "java.lang.String"/>
   
   <queryString>
      <![CDATA[]]>
   </queryString>
   
   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>
   
   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>
  
   <sortField name = "country" order = "Descending"/>
   <sortField name = "name"/>
   
   <title>
      <band height = "70">
         
         <line>
            <reportElement x = "0" y = "0" width = "515" height = "1"/>
         </line>
         
         <textField isBlankWhenNull = "true" bookmarkLevel = "1">
            <reportElement x = "0" y = "10" width = "515" height = "30"/>
            
            <textElement textAlignment = "Center">
               <font size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{ReportTitle}]]>
            </textFieldExpression>
            
            <anchorNameExpression>
               <![CDATA["Title"]]>
            </anchorNameExpression>
         </textField>
            
         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "40" width = "515" height = "20"/>
            
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{Author}]]>
            </textFieldExpression>
            
         </textField>
      
      </band>
   </title>

   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" width = "535" height = "15"
               backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>
  
   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" width = "535" height = "14"
               backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
				
            <textElement />
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>

</jasperReport>
Java-коды для заполнения отчетов остаются без изменений. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName =
      "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource =
      new JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      /**
       * Passing ReportTitle and Author as parameters
       */
      parameters.put("ReportTitle", "List of Contacts");
      parameters.put("Author", "Prepared By Manisha");

      try {
         JasperFillManager.fillReportToFile(
         sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java указано ниже —

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview
      the report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
		
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) следующим образом:

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28: warning:
   'includeantruntime' was not set, defaulting to build.sysclasspath=last;
   set to false for repeatable builds
   [javac] Compiling 7 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig
   for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 18 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —

Пример сортировки поля отчета Jasper

Здесь мы видим, что названия стран расположены в порядке убывания в алфавитном порядке.

Выражение отчета
Выражения отчета — это мощные функции JasperReports, которые позволяют нам отображать рассчитанные данные в отчете. Расчетные данные — это данные, которые не являются статическими и не передаются в качестве параметра отчета или поля источника данных. Выражения отчета строятся на основе объединения параметров отчета, полей и статических данных. Язык Java используется для написания выражений отчета по умолчанию. Компиляторы JasperReports поддерживают другие языки сценариев для выражений отчетов, такие как язык сценариев Groovy, JavaScript или сценарий BeanShell.

Эта глава объяснит вам — как работают выражения отчетов, предполагая, что они написаны только на языке Java. В шаблоне отчета JRXML есть несколько элементов, которые определяют выражения как —

<VariableExpression>
<InitialValueExpression>
<GroupExpression>
<PrintWhenExpression>
<ImageExpression>
<TextFieldExpression>
Декларация Декларации
По сути, все выражения отчета являются выражениями Java, которые могут ссылаться на поля отчета, переменные отчета и параметры отчета.

Ссылка на поле в выражении
Чтобы использовать ссылку на поле отчета в выражении, имя поля должно быть помещено между последовательностями символов $ F { и } , как показано ниже —

<textfieldexpression>
   $F{Name}
</textfieldexpression>
Ниже приведен фрагмент кода из нашего существующего файла JRXML (глава Проекты отчетов) —

<textFieldExpression class = "java.lang.String">
   <![CDATA[$F{country}]]>
</textFieldExpression>
Ссылка на переменную в выражении
Чтобы ссылаться на переменную в выражении, мы должны поместить имя переменной между $ V { и }, как показано в примере, приведенном ниже —

<textfieldexpression>
   "Total height : " + $V{SumOfHeight} + " ft."
</textfieldexpression>
Ссылка на параметр в выражении
Чтобы ссылаться на параметр в выражении, имя параметра должно быть помещено между $ P { и }, как показано в примере, приведенном ниже —

<textfieldexpression>
   "ReportTitle : " + $P{Title}
</textfieldexpression>
Ниже приведен фрагмент кода из нашего существующего файла JRXML, который демонстрирует ссылку на параметр в выражении. (JRXML из главы « Проекты отчетов» ) —

<textField isBlankWhenNull = "true" bookmarkLevel = "1">
   <reportElement x = "0" y = "10" width = "515" height = "30"/>
   
   <textElement textAlignment = "Center">
      <font size = "22"/>
   </textElement>
   
   <textFieldExpression class = "java.lang.String">
      <![CDATA[$P{ReportTitle}]]>
   </textFieldExpression>
   
   <anchorNameExpression>
      <![CDATA["Title"]]>
   </anchorNameExpression>
</textField>

<textField isBlankWhenNull = "true">
   <reportElement  x = "0" y = "40" width = "515" height = "20"/>
   
   <textElement textAlignment = "Center">
      <font size = "10"/>
   </textElement>
   
   <textFieldExpression class = "java.lang.String">
      <![CDATA[$P{Author}]]>
   </textFieldExpression>
</textField>
Как вы видели выше, ссылки на параметры, поля и переменные на самом деле являются реальными объектами Java. Зная их класс из объявления параметра, поля или переменной, сделанного в шаблоне отчета, мы можем даже вызывать методы для этих ссылок на объекты в выражениях.

В следующем примере показано, как извлечь и отобразить первую букву из поля отчета java.lang.String «Имя».

<textFieldExpression>
   $F{Name}.substring(0, 1)
</textFieldExpression>
Ссылка на ресурсный пакет в выражении
Чтобы ссылаться на ресурс в выражении, ключ должен быть помещен между $ R { и }, как показано в примере, приведенном ниже —

<textfieldexpression>
   $R{report.title}
</textfieldexpression>
На основе предоставленного во время выполнения языкового стандарта и ключа report.title загружается пакет ресурсов, связанный с шаблоном отчета. Следовательно, заголовок отчета отображается путем извлечения значения String из пакета ресурсов. Больше о интернационализации можно найти в главе Интернационализация .

Калькулятор
Калькулятор — это объект в JasperReports, который оценивает выражения и увеличивает переменные или наборы данных во время заполнения отчета. В процессе компиляции информация создается и сохраняется компилятором в отчете компиляции. Эта информация используется во время заполнения отчета для создания экземпляра класса net.sf.jasperreports.engine.fill.JRCalculator.

Исходный файл Java генерируется и компилируется компиляторами отчетов на основе Java на лету. Этот сгенерированный класс является подклассом JRCalculator, и байт-код, созданный при его компиляции, хранится внутри объекта JasperReport. Этот байт-код загружается во время заполнения отчета, и создается результирующий класс для получения объекта калькулятора, необходимого для вычисления выражения.

Условные выражения
JasperReports не поддерживает операторы if-else при определении переменных выражений. Вместо этого вы можете использовать троичные операторы {cond}? {заявление 1}: {заявление 2} . Этот оператор может быть вложен в выражение Java для получения желаемого результата на основе нескольких условий.

Пример условного выражения в отчете
Давайте изменим существующий шаблон отчета (Глава Report Designs ) и добавим условное выражение для страны поля. Пересмотренный шаблон отчета (jasper_report_template.jrxml) выглядит следующим образом. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test —

<?xml version = "1.0"?>
<!DOCTYPE jasperReport PUBLIC
   "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports" 
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation = 
   "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd" 
   name = "jasper_report_template" pageWidth = "595" pageHeight = "842" 
   columnWidth = "515" leftMargin = "40" rightMargin = "40" 
   topMargin = "50" bottomMargin = "50">

   <parameter name = "ReportTitle" class = "java.lang.String"/>
   <parameter name = "Author" class = "java.lang.String"/>
   
   <queryString>
      <![CDATA[]]>
   </queryString>
   
   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>
   
   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>
   
   <sortField name = "country" order = "Descending"/>
   <sortField name = "name"/>
   
   <title>
      <band height = "70">
         
         <line>
            <reportElement x = "0" y = "0" width = "515" height = "1"/>
         </line>
         
         <textField isBlankWhenNull = "true" bookmarkLevel = "1">
            <reportElement x = "0" y = "10" width = "515" height = "30"/>
            
            <textElement textAlignment = "Center">
               <font size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{ReportTitle}]]>
            </textFieldExpression>
            
            <anchorNameExpression>
               <![CDATA["Title"]]>
            </anchorNameExpression>
         </textField>
            
         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "40" width = "515" height = "20"/>
            
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{Author}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </title>
   
   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" width = "535" height = "15"
               backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
				
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>

   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" width = "535" height = "14"
               backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
				
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}.isEmpty() ? "NO COUNTRY" : $F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
			
      </band>
   </detail>
	
</jasperReport>
Java-коды для заполнения отчета следующие. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java имеет вид —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName =
      "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource =
      new JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      /**
       * Passing ReportTitle and Author as parameters
       */
      parameters.put("ReportTitle", "List of Contacts");
      parameters.put("Author", "Prepared By Manisha");

      try {
         JasperFillManager.fillReportToFile(
         sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java имеет вид —

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Мы добавим новую запись с полем страны как пустую в наш список Java-бинов. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java имеет вид —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California")); 
      dataBeanList.add(produce("Tanmay", ""));
      
      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}

# Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен находиться в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview
      the report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) как —

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defaulting to build.sysclasspath=last;
   set to false for repeatable builds
   [javac] Compiling 3 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See
   http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
    [java] log4j:WARN No appenders could be found for logger
    (net.sf.jasperreports.extensions.ExtensionsEnvironment).
    [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 5 minutes 5 seconds

C:\tools\jasperreports-5.0.1\test>
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —

Пример выражения отчета Jasper

Здесь, как мы видим, для последней записи мы не передали никаких данных для страны поля, печатается «НЕТ СТРАНЫ».

Переменные отчета
Переменные отчета — это специальные объекты, построенные поверх выражения отчета.

Переменные отчета упрощают следующие задачи —

Выражения отчета, которые интенсивно используются в шаблоне отчета. Эти выражения могут быть объявлены только один раз с помощью переменных отчета.

Переменные отчета могут выполнять различные вычисления на основе соответствующих значений выражений, таких как число, сумма, среднее, самое низкое, наибольшее, дисперсия и т. Д.

Выражения отчета, которые интенсивно используются в шаблоне отчета. Эти выражения могут быть объявлены только один раз с помощью переменных отчета.

Переменные отчета могут выполнять различные вычисления на основе соответствующих значений выражений, таких как число, сумма, среднее, самое низкое, наибольшее, дисперсия и т. Д.

Если переменные определены в дизайне отчета, то на них могут ссылаться новые переменные в выражениях. Следовательно, порядок, в котором переменные объявляются в дизайне отчета, важен.




# Объявление переменной
Объявление переменной выглядит следующим образом:

<variable name = "CityNumber" class = "java.lang.Integer" incrementType = "Group"
   incrementGroup = "CityGroup" calculation = "Count">
   <variableExpression>
      <![CDATA[Boolean.TRUE]]>
   </variableExpression>
</variable>
Как видно выше, элемент <variable> содержит количество атрибутов. Эти атрибуты приведены ниже —

Атрибут имени
Подобно параметрам и полям , атрибут name элемента </ variable> является обязательным. Это позволяет ссылаться на переменную по объявленному имени в выражениях отчета.

Атрибут класса
Атрибут class также является обязательным, который указывает имя класса для значений переменной. Значением по умолчанию является java.lang.String . Это можно изменить на любой класс, доступный в пути к классам, как во время составления отчета, так и во время заполнения отчета. Движок заботится о приведении типов в выражениях отчетов, которые использует токен $ V {}, поэтому приведение типов вручную не требуется.

расчет
Этот атрибут определяет — какой расчет выполнить по переменной при заполнении отчета. В следующих подразделах описываются все возможные значения атрибута вычисления элемента <variable>.

Среднее — значение переменной является средним значением каждого ненулевого значения выражения переменной. Действительно только для числовых переменных.

Count — значение переменной является количеством ненулевых экземпляров выражения переменной.

Первый — значение переменной — это значение первого экземпляра выражения переменной. Последующие значения игнорируются.

Highest — значение переменной является наибольшим значением для выражения переменной.

Наименьшее — значение переменной является наименьшим значением для выражения переменной в отчете.

Ничего — расчет переменной не производится.

StandardDeviation — значение переменной — это стандартное отклонение всех ненулевых значений, соответствующих выражению отчета. Действительно только для числовых переменных.

Sum — значение переменной является суммой всех ненулевых значений, возвращаемых выражением отчета.

Система — значение переменной представляет собой пользовательский расчет (вычисление значения для этой переменной самостоятельно с использованием функциональности скриптлетов JasperReports).

Дисперсия — значение переменной — это дисперсия всех ненулевых значений, возвращаемых вычислением выражения переменной отчета.

Среднее — значение переменной является средним значением каждого ненулевого значения выражения переменной. Действительно только для числовых переменных.

Count — значение переменной является количеством ненулевых экземпляров выражения переменной.

Первый — значение переменной — это значение первого экземпляра выражения переменной. Последующие значения игнорируются.

Highest — значение переменной является наибольшим значением для выражения переменной.

Наименьшее — значение переменной является наименьшим значением для выражения переменной в отчете.

Ничего — расчет переменной не производится.

StandardDeviation — значение переменной — это стандартное отклонение всех ненулевых значений, соответствующих выражению отчета. Действительно только для числовых переменных.

Sum — значение переменной является суммой всех ненулевых значений, возвращаемых выражением отчета.

Система — значение переменной представляет собой пользовательский расчет (вычисление значения для этой переменной самостоятельно с использованием функциональности скриптлетов JasperReports).

Дисперсия — значение переменной — это дисперсия всех ненулевых значений, возвращаемых вычислением выражения переменной отчета.

Инкремент FactoryClass
Этот атрибут определяет класс, используемый для вычисления значения переменной при заполнении текущей записи в отчете. Значением по умолчанию будет любой класс, реализующий net.sf.jasperreports.engine.fill.JRIncrementerFactory . Класс фабрики будет использоваться механизмом для создания экземпляров инкрементных объектов во время выполнения в зависимости от атрибута вычисления, установленного для переменной.

IncrementType
Это определяет, когда пересчитать значение переменной. Этот атрибут использует значения, как показано ниже:

Столбец — значение переменной пересчитывается в конце каждого столбца.

Группа — значение переменной пересчитывается при изменении группы, указанной в incrementGroup.

Нет — значение переменной пересчитывается с каждой записью.

Страница — значение переменной пересчитывается в конце каждой страницы.

Отчет — значение переменной пересчитывается один раз, в конце отчета.

Столбец — значение переменной пересчитывается в конце каждого столбца.

Группа — значение переменной пересчитывается при изменении группы, указанной в incrementGroup.

Нет — значение переменной пересчитывается с каждой записью.

Страница — значение переменной пересчитывается в конце каждой страницы.

Отчет — значение переменной пересчитывается один раз, в конце отчета.

IncrementGroup
Это определяет имя группы, в которой значение переменной пересчитывается, когда incrementType имеет значение Group . Это берет имя любой группы, объявленной в шаблоне отчета JRXML.

ResetType
Это определяет, когда значение переменной сбрасывается. Этот атрибут использует значения, как показано ниже:

Столбец — значение переменной сбрасывается в начале каждого столбца.

Группа — значение переменной сбрасывается при изменении группы, указанной в incrementGroup.

None — значение переменной никогда не сбрасывается.

Страница — значение переменной сбрасывается в начале каждой страницы.

Отчет — значение переменной сбрасывается только один раз, в начале отчета.

Столбец — значение переменной сбрасывается в начале каждого столбца.

Группа — значение переменной сбрасывается при изменении группы, указанной в incrementGroup.

None — значение переменной никогда не сбрасывается.

Страница — значение переменной сбрасывается в начале каждой страницы.

Отчет — значение переменной сбрасывается только один раз, в начале отчета.

ResetGroup
Это определяет имя группы, в которой значение переменной сбрасывается, когда resetType имеет значение Group . Значения для этого атрибута будут именем любой группы, объявленной в шаблоне отчета JRXML.



## Встроенные переменные отчета
Есть несколько встроенных системных переменных, готовых к использованию в выражениях, а именно:

S.NO	Имя и описание переменной
1	
НОМЕР СТРАНИЦЫ

Значением этой переменной является номер текущей страницы. Его можно использовать для отображения как номера текущей страницы, так и общего количества страниц, используя специальную функцию элементов текстового поля JasperReports, атрибутvaluationTime.

2	
COLUMN_NUMBER

Эта переменная содержит текущий номер столбца.

3	
REPORT_COUNT

Эта переменная отчета содержит общее количество обработанных записей.

4	
КОЛИЧЕСТВО СТРАНИЦ

Эта переменная содержит количество записей, которые были обработаны при создании текущей страницы.

5	
COLUMN_COUNT

Эта переменная содержит количество записей, которые были обработаны при создании текущего столбца.

6	
GroupName_COUNT

Имя этой переменной происходит от имени группы, которой она соответствует, с суффиксом последовательности _COUNT. Эта переменная содержит количество записей в текущей группе.

НОМЕР СТРАНИЦЫ

Значением этой переменной является номер текущей страницы. Его можно использовать для отображения как номера текущей страницы, так и общего количества страниц, используя специальную функцию элементов текстового поля JasperReports, атрибутvaluationTime.

COLUMN_NUMBER

Эта переменная содержит текущий номер столбца.

REPORT_COUNT

Эта переменная отчета содержит общее количество обработанных записей.

КОЛИЧЕСТВО СТРАНИЦ

Эта переменная содержит количество записей, которые были обработаны при создании текущей страницы.

COLUMN_COUNT

Эта переменная содержит количество записей, которые были обработаны при создании текущего столбца.

GroupName_COUNT

Имя этой переменной происходит от имени группы, которой она соответствует, с суффиксом последовательности _COUNT. Эта переменная содержит количество записей в текущей группе.

пример
Давайте добавим переменную ( countNumber ) к существующему шаблону отчета (глава « Конструкции отчета» ). Мы будем добавлять префикс к каждой записи. Пересмотренный шаблон отчета (jasper_report_template.jrxml) выглядит следующим образом. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test —

<?xml version = "1.0"?>
<!DOCTYPE jasperReport PUBLIC
   "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" pageWidth = "595"
   pageHeight = "842" columnWidth = "515"
   leftMargin = "40" rightMargin = "40" topMargin = "50" bottomMargin = "50">
	
   <parameter name = "ReportTitle" class = "java.lang.String"/>
   <parameter name = "Author" class = "java.lang.String"/>

   <queryString>
      <![CDATA[]]>
   </queryString>

   <field name = "country" class = "java.lang.String">
      <fieldDescription>
         <![CDATA[country]]>
      </fieldDescription>
   </field>

   <field name = "name" class = "java.lang.String">
      <fieldDescription>
         <![CDATA[name]]>
      </fieldDescription>
   </field>
   
   <variable name = "countNumber" class = "java.lang.Integer" calculation = "Count">
      <variableExpression>
         <![CDATA[Boolean.TRUE]]>
      </variableExpression>
   </variable>
   
   <title>
      <band height = "70">
         
         <line>
            <reportElement x = "0" y = "0" width = "515" height = "1"/>
         </line>
			
         <textField isBlankWhenNull = "true" bookmarkLevel = "1">
            <reportElement x = "0" y = "10" width = "515" height = "30"/>
            
            <textElement textAlignment = "Center">
               <font size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{ReportTitle}]]>
            </textFieldExpression>
            
            <anchorNameExpression>
               <![CDATA["Title"]]>
            </anchorNameExpression>
         </textField>
         
         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "40" width = "515" height = "20"/>
            
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{Author}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </title>

   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" width = "535"	height = "15"
               backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>

   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" width = "535" height = "14"
               backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
				
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA["  " + String.valueOf($V{countNumber}) +"."+$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>

</jasperReport>
Java-коды для заполнения отчетов остаются без изменений. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName =
      "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource =
      new JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      /**
       * Passing ReportTitle and Author as parameters
       */
      parameters.put("ReportTitle", "List of Contacts");
      parameters.put("Author", "Prepared By Manisha");

      try {
         JasperFillManager.fillReportToFile(
         sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java указано ниже —

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   
   <import file = "baseBuild.xml" />
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview
      the report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc"
         classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) как —

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28: warning:
   'includeantruntime' was not set, defaulting to build.sysclasspath=last;
   set to false for repeatable builds
   [javac] Compiling 7 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig
   for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 18 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как на экране ниже —

## Пример переменной отчета Jasper

Здесь мы видим, что счетчик имеет префикс для каждой записи.

Разделы отчета
Мы обсудили структуру простого шаблона отчета в главе « Начало работы» . Аналогичным образом JasperReports структурирует шаблон отчета в несколько разделов. Разделы — это части отчета, которые имеют указанную высоту и могут содержать объекты отчета, такие как линии, прямоугольники, изображения или текстовые поля.

Механизм отчетов просматривает виртуальные записи предоставленного источника данных отчета во время заполнения отчета. В зависимости от поведения, определенного в каждом разделе, механизм обрабатывает каждый раздел отчета, когда это необходимо. Например, подробный раздел отображается для каждой записи в источнике данных. Когда возникают разрывы страниц, верхний и нижний колонтитулы страницы отображаются по мере необходимости.

В JasperReports разделы терминологии и отчета также называются полосами отчета . Разделы состоят из одной или нескольких полос. Эти разделы заполняются повторно во время создания отчета и готовят окончательный документ.





# Основные разделы
Шаблон отчета в JasperReports имеет следующие основные разделы —

<title></title>

<pageheader></pageheader>

<columnheader></columnheader>

<groupheader></groupheader>

<detail></detail>

<groupfooter></groupfooter>

<columnfooter></columnfooter>

<pagefooter></pagefooter>

<lastpagefooter></lastpagefooter>

<summary></summary>

<nodata></nodata>

<background></background>
Следующая таблица суммирует каждый из разделов —

## S.NO	Раздел и описание
1	
заглавие

Этот раздел появляется только один раз в начале отчета.

2	
Заголовок страницы

Этот раздел появляется в начале каждой страницы в созданном документе.

3	
Заголовок столбца

Этот раздел появляется в начале каждого столбца в сгенерированном документе. Если в отчете определен только один столбец, то разделы верхнего и нижнего колонтитулов игнорируются.

4	
Заголовок группы

Этот раздел представлен группой отчетов (глава Группы ). Каждый раз, когда выражение группировки изменяет свое значение, раздел заголовка группы печатается над разделом сведений. В случае, если определено более одной группы, заголовок группы печатается в порядке определения группы.

5	
подробность

Этот раздел повторяется для каждой строки данных, предоставленной источником данных отчета. Детальный раздел может быть сделан из нескольких полос.

6	
Нижний колонтитул группы

Этот раздел представлен группой отчетов (глава Группы ). Раздел нижнего колонтитула группы печатается под разделом сведений до изменения значения выражения группировки. Нижний колонтитул группы всегда печатается для последней строки данных в источнике данных. В случае, если определено более одной группы, нижний колонтитул группы печатается в обратном порядке определения группы.

7	
Нижний колонтитул

Этот раздел отображается внизу каждого столбца. Если количество столбцов в отчете равно 1, то разделы верхнего и нижнего колонтитула игнорируются.

8	
Нижний колонтитул страницы

Этот раздел отображается внизу каждой страницы.

9	
Нижний колонтитул последней страницы

Этот раздел заменяет обычный нижний колонтитул на последней странице отчета. В случае, если раздел резюме также присутствует, то это может быть не самая последняя страница документа. Этот раздел иногда полезен, когда сводная информация должна отображаться внизу последней страницы.

10	
Резюме

Этот раздел появляется только один раз в конце отчета.

11	
Нет данных

Этот раздел печатается, когда для свойства отчета « Когда нет данных» установлено значение « Нет данных» . Если в шаблоне отчета определен раздел <noData> и 
если источник данных пуст, то во время заполнения будет учитываться только раздел <noData>, и его содержимое будет выводить отчет.

12	
Фон

Фоновый раздел отображается на каждой странице и не может перейти на следующую страницу. 
Элементы, размещенные в этом разделе, оцениваются во время инициализации страницы и отображаются в фоновом режиме. 
Все остальные объекты страницы отображаются поверх фоновых объектов. Этот раздел полезен для создания водяных знаков на странице.



# Элементы раздела
Все вышеупомянутые разделы отчета не являются обязательными. Но у любого шаблона отчета будет хотя бы один такой раздел. Каждый из этих разделов содержит один элемент < band > в качестве единственного подэлемента. < Band > может содержать ноль или более следующих подэлементов —

<line>, <rectangle>, <ellipse>, <image>, <staticText>, <textField>, <subReport> или <elementGroup>

## Каждый из этих элементов должен содержать один < reportElement > в качестве первого элемента (кроме elementGroup). 
< ReportElement > определяет способ размещения данных для этого конкретного элемента. 
В отличие от переменных и параметров, элементы отчета не обязательно должны иметь имя, потому что обычно вам не нужно получать какой-либо отдельный элемент внутри шаблона отчета.



## В таблице ниже приведены атрибуты < reportElement > —

атрибут  	Описание	Допустимые значения
X	Определяет координату x элемента band.	Целочисленное значение, обозначающее координату x элемента в пикселях. Этот атрибут обязателен.
Y	Определяет координату y элемента band.	Целочисленное значение, указывающее координату y элемента в пикселях. Этот атрибут обязателен.
ширина	Определяет ширину элемента полосы.	Целочисленное значение, указывающее ширину элемента в пикселях. Этот атрибут обязателен.
рост	Определяет высоту элемента группы.	Целочисленное значение, обозначающее высоту элемента в пикселях. Этот атрибут обязателен.
ключ	Уникальный идентификатор элемента группы.	Уникальное строковое значение.


### stretchType	Определяет, как растягивается элемент, когда растягивается содержащаяся полоса	
>NoStretch (по умолчанию) — элемент не растягивается.
>RelativeToTallestObject — элемент растянется, чтобы вместить самый высокий объект в его группе.
>RelativeToBand — элемент будет растягиваться, чтобы соответствовать высоте полосы.

В версии из Перехвата было так:
## isStretchWithOverflow="true"

positionType	Определяет позицию элемента, когда полоса растягивается.	
Float — элемент будет перемещаться в зависимости от размера окружающих элементов.

FixRelativeToTop (по умолчанию) — элемент будет сохранять фиксированную позицию относительно вершины полосы.

FixRelativeToBottom — Элемент будет сохранять фиксированное положение относительно основания группы.

isPrintRepeatedValues	Указывает, будут ли напечатаны повторяющиеся значения.	
true (по умолчанию) — повторные значения будут напечатаны.
isPrintRepeatedValues="false" — повторяющиеся значения не будут напечатаны.


Режим	Определяет фоновый режим элемента	Непрозрачный, прозрачный
isRemoveLineWhenBlank	Указывает, должен ли элемент быть удален, когда он пуст, и нет других элементов в том же горизонтальном пространстве.	правда, ложь
## isPrintInFirstWholeBand	
- Указывает, должен ли элемент печататься во всей полосе, то есть полосе, которая не разделена между страницами отчета или столбцами.	правда, ложь

## isPrintWhenDetailOverFlows	
- Указывает, будет ли элемент печататься при переполнении полосы на новую страницу или столбец.	правда, ложь
>isPrintWhenDetailOverflows="false"

printWhenGroupChanges	Указывает, что элемент будет напечатан при изменении указанной группы.	Строковое значение.

ForeColor	Определяет цвет переднего плана элемента.	Либо шестнадцатеричное значение RGB с предшествующим символом #, либо одно из следующих предварительно определенных значений: черный, синий, голубой, темно-серый, серый, зеленый, светло-серый, пурпурный, оранжевый, розовый, красный, желтый, белый.
BackColor	Определяет цвет фона элемента.	То же, что и допустимые значения для forecolor
NoStretch (по умолчанию) — элемент не растягивается.

### RelativeToTallestObject 
— элемент растянется, чтобы вместить самый высокий объект в его группе.

### RelativeToBand 
элемент будет растягиваться, чтобы соответствовать высоте полосы.

### Float 
— элемент будет перемещаться в зависимости от размера окружающих элементов.

FixRelativeToTop (по умолчанию) — элемент будет сохранять фиксированную позицию относительно вершины полосы.

FixRelativeToBottom — Элемент будет сохранять фиксированное положение относительно основания группы.




# Атрибуты раздела
Ниже приведены атрибуты раздела отчета.

Рост
Высота раздела определяет высоту в пикселях для этого конкретного раздела и очень важна в общем дизайне отчета.

Распечатать при выражении
Булево выражение, определяющее, следует ли печатать раздел или нет.



## splitType - Разрешено разделение
Флаг, указывающий, разрешено ли разделение раздела, если он не помещается на текущей странице. 
Если true, раздел будет перенесен на следующую страницу. 
Обратите внимание, что в случае, если раздел не помещается на следующей странице, он будет разделен независимо от значения флага. 
splitType может принимать следующие значения —

splitType = «Stretch» Разбивает растянутое содержимое. Если раздел растягивается на текущей странице (если доступное пространство меньше заявленной высоты), 
область, добавленная к исходной высоте, может быть разделена на следующую страницу.
splitType = «Prevent» Запретить разделение с первой попытки. Если раздел не помещается на следующей странице, разделение происходит нормально, поскольку предотвращение разделения полосы действует только при первой попытке разделения.
splitType = «Немедленно» Разделить немедленно. Полоске разрешено делиться где угодно, кроме как выше, ее верхний элемент.



пример
Чтобы продемонстрировать каждый раздел, напишем шаблон отчета (jasper_report_template.jrxml). 
Сохраните этот файл в каталоге C: \ tools \ jasperreports-5.0.1 \ test . 
В этом файле мы будем отображать текст в каждом из разделов (мы обсуждали выше). Содержимое файла приведено ниже.

<?xml version = "1.0" encoding = "UTF-8"?>

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" pageWidth = "300" pageHeight = "300" 
   columnWidth = "300" leftMargin = "0" rightMargin = "0" 
   topMargin = "0" bottomMargin = "0" >

   <title>
      <band height = "50">
         
         <textField>
            <reportElement x = "100" y = "16" width = "100" height = "20"/>
            <textElement/>
            
            <textFieldExpression>
               <![CDATA["Title"]]>
            </textFieldExpression>
        
         </textField>
      
      </band>
   </title>
   
   <pageHeader>
      <band height = "40">
         
         <textField>
            <reportElement  mode = "Opaque" x = "100" y = "10" 
               width = "90" height = "20"/>
            
            <textElement>
               <font isBold = "true"/>
            </textElement>
            
            <textFieldExpression>
               <![CDATA["Page Header"]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </pageHeader>
   
   <columnHeader>
      <band height = "40">
            
         <textField>
            <reportElement  x = "100" y = "10" width = "90" height = "20"/>
            
            <textElement>
               <font isItalic = "true"/>
            </textElement>
            
            <textFieldExpression>
               <![CDATA["Column Header"]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </columnHeader>
   
   <detail>
      <band height ="40">
         
         <textField>
            <reportElement mode = "Opaque" x = "100" y = "10" 
               width = "90" height = "20" backcolor = "#99CCFF"/>
            <textElement/>
            
            <textFieldExpression>
               <![CDATA["Report Details"]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
   
   <columnFooter>
      <band height = "40">
         
         <textField>
            <reportElement  x = "100" y = "10" width = "90" height = "20"/>
            <textElement/>
            
            <textFieldExpression>
               <![CDATA["Column Footer"]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </columnFooter>
   
   <pageFooter>
      <band height = "40">
         
         <textField>
            <reportElement  x = "100" y = "10" width = "90" height = "20"/>
            <textElement/>
            
            <textFieldExpression>
               <![CDATA["Page Footer"]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </pageFooter>
   
   <lastPageFooter>
      <band height = "40">
         
         <textField>
            <reportElement  x = "100" y = "10" width = "90" height = "20"/>
            <textElement/>
            
            <textFieldExpression>
               <![CDATA["Last Page Footer"]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </lastPageFooter>
   
   <summary>
      <band height = "40">
         
         <textField>
            <reportElement  x = "100" y = "10" width = "90" height = "20"/>
            <textElement/>
            
            <textFieldExpression>
               <![CDATA["Summary"]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </summary>
	
</jasperReport>
Код Java для заполнения и генерации отчета приведен ниже. Давайте сохраним этот файл JasperReportFill.java в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint.

package com.tutorialspoint;

import net.sf.jasperreports.engine.JREmptyDataSource;
import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;

public class JasperReportFill {
   public static void main(String[] args) {
      String sourceFileName = "C://tools/jasperreports-5.0.1/test/" + 
         "jasper_report_template.jasper";

      try {
         JasperFillManager.fillReportToFile(sourceFileName, null,
            new JREmptyDataSource());
      } catch (JRException e) {
         // TODO Auto-generated catch block
         e.printStackTrace();
      }

   }
}
Здесь мы используем экземпляр JREmptyDataSource при заполнении отчетов, чтобы имитировать источник данных с одной записью в нем, но со всеми полями в этой единственной записи, равными нулю.



# Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml взят из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   
   <import file = "baseBuild.xml" />
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview 
      the report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
		
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc"
         classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) следующим образом:

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defau
   [javac] Compiling 1 source file to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFac
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnviro
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnviro
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 18 minutes 22 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как на экране ниже —


## Пример раздела отчета Jasper

Здесь мы видим, что в каждом из разделов напечатан текст. Следует отметить, что, поскольку JRXML содержит элемент <lastPageFooter>, он будет отображаться на последней странице отчета вместо отображаемого элемента <pageFooter>. Элементы <columnHeader> и <columnFooter> будут отображаться только в отчете, если в нем более одного столбца.

Группы отчетов
Группы в JasperReports помогают систематизировать данные отчета. Группа отчетов представляет собой последовательность последовательных записей в источнике данных, которые имеют что-то общее, например, значение определенных полей отчета. Группа отчетов определяется элементом <group>. Отчет может иметь любое количество групп. После объявления группы могут быть переданы по всему отчету.

Группа отчетов состоит из трех элементов:

Выражение группы — это указывает на данные, которые должны измениться, чтобы начать новую группу данных.

Раздел заголовка группы — Помогает разместить метку в начале сгруппированных данных.

Раздел нижнего колонтитула группы — Помогает разместить метку в конце сгруппированных данных.

Выражение группы — это указывает на данные, которые должны измениться, чтобы начать новую группу данных.

Раздел заголовка группы — Помогает разместить метку в начале сгруппированных данных.

Раздел нижнего колонтитула группы — Помогает разместить метку в конце сгруппированных данных.

Во время итерации по источнику данных во время заполнения отчета, если значение выражения группы изменяется, происходит разрыв группы и соответствующие разделы <groupFooter> и <groupHeader> вставляются в результирующий документ.

Механизм групп отчетов не выполняет никакой сортировки данных, предоставленных источником данных. Группировка данных работает, как ожидается, только в том случае, если записи в источнике данных уже упорядочены в соответствии с выражениями группы, использованными в отчете.



# Атрибуты группы
Элемент <group> содержит атрибуты, которые позволяют нам контролировать расположение сгруппированных данных. Атрибуты приведены в таблице ниже —

S.NO	Атрибут и описание
1	
название

Это обязательно. Он ссылается на группу в выражениях отчета по имени. Он следует тем же соглашениям об именах, которые мы упоминали для параметров отчета, полей и переменных отчета. Его можно использовать в других атрибутах JRXML, если вы хотите сослаться на определенную группу отчетов.

2	
isStartNewColumn

При значении true каждая группа данных начинается с нового столбца. Значением по умолчанию является false .

3	
isStartNewPage

Если задано значение true , каждая группа данных будет начинаться с новой страницы. Значением по умолчанию является false .

4	
isResetPageNumber

При значении true номер страницы отчета будет сбрасываться каждый раз при запуске новой группы. Значением по умолчанию является false.

5	
isReprintHeaderOnEachPage

Если установлено значение true , заголовок группы будет перепечатываться на каждой странице. Значением по умолчанию является false .

6	
### minHeightToStartNewPage
Определяет минимальный объем вертикального пространства, необходимого в нижней части столбца для размещения заголовка группы в текущем столбце. 
Сумма указана в отчетных единицах.
minHeightToStartNewPage="15"


7	
footerPosition

Отображает положение нижнего колонтитула группы на странице, а также его поведение по отношению к разделам отчета, которые следуют за ним. Его значения могут быть: Normal , StackAtBottom , ForceAtBottom и CollateAtBottom . Значением по умолчанию является Normal .

8	
## держитесь вместе
При значении true запрещает разделение группы с первой попытки разрыва.

название

Это обязательно. Он ссылается на группу в выражениях отчета по имени. Он следует тем же соглашениям об именах, которые мы упоминали для параметров отчета, полей и переменных отчета. Его можно использовать в других атрибутах JRXML, если вы хотите сослаться на определенную группу отчетов.

isStartNewColumn

При значении true каждая группа данных начинается с нового столбца. Значением по умолчанию является false .

isStartNewPage

Если задано значение true , каждая группа данных будет начинаться с новой страницы. Значением по умолчанию является false .

isResetPageNumber

При значении true номер страницы отчета будет сбрасываться каждый раз при запуске новой группы. Значением по умолчанию является false.

isReprintHeaderOnEachPage

minHeightToStartNewPage

Определяет минимальный объем вертикального пространства, необходимого в нижней части столбца для размещения заголовка группы в текущем столбце. Сумма указана в отчетных единицах.

footerPosition

Отображает положение нижнего колонтитула группы на странице, а также его поведение по отношению к разделам отчета, которые следуют за ним. Его значения могут быть: Normal , StackAtBottom , ForceAtBottom и CollateAtBottom . Значением по умолчанию является Normal .

держитесь вместе

При значении true запрещает разделение группы с первой попытки разрыва.

пример
Давайте добавим группу ( CountryGroup ) к существующему шаблону отчета (глава « Проекты отчетов» ). Вхождение каждой страны считается, и счет отображается в нижнем колонтитуле группы. В заголовке группы указывается количество каждой записи. Пересмотренный шаблон отчета (jasper_report_template.jrxml) выглядит следующим образом. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test —

<?xml version = "1.0"?>
<!DOCTYPE jasperReport PUBLIC
   "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" pageWidth = "595"
   pageHeight = "842" columnWidth = "515"
   leftMargin = "40" rightMargin = "40" topMargin = "50" bottomMargin = "50">

   <parameter name = "ReportTitle" class = "java.lang.String"/>
   <parameter name = "Author" class = "java.lang.String"/>

   <queryString>
      <![CDATA[]]>
   </queryString>

   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>

   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>
   
   <sortField name = "country" order = "Descending"/>
   <sortField name = "name"/>
   
   <variable name = "CountryNumber" class = "java.lang.Integer"
      incrementType = "Group" incrementGroup = "CountryGroup"
      calculation = "Count">
      <variableExpression><![CDATA[Boolean.TRUE]]></variableExpression>
   </variable>
   
   <group name = "CountryGroup" minHeightToStartNewPage = "60">
      <groupExpression><![CDATA[$F{country}]]></groupExpression>
      
      <groupHeader>
         <band height = "20">
            
            <textField evaluationTime = "Group" evaluationGroup = "CountryGroup"
               bookmarkLevel = "1">
               <reportElement mode = "Opaque" x = "0" y = "5" width = "515"
                  height = "15" backcolor = "#C0C0C0"/>
               
               <box leftPadding = "10">
                  <bottomPen lineWidth = "1.0"/>
               </box>
               <textElement/>
               
               <textFieldExpression class = "java.lang.String">
                  <![CDATA["  " + String.valueOf($V{CountryNumber}) + ". "
                  + String.valueOf($F{country})]]>
               </textFieldExpression>
               
               <anchorNameExpression>
                  <![CDATA[String.valueOf($F{country})]]>
               </anchorNameExpression>
            </textField>
         
         </band>
      </groupHeader>
      
      <groupFooter>
         <band height = "20">
            
            <staticText>
               <reportElement x = "400" y = "1" width = "60" height = "15"/>
               <textElement textAlignment = "Right"/>
               <text><![CDATA[Count :]]></text>
            </staticText>
            
            <textField>
               <reportElement x = "460" y = "1" width = "30" height = "15"/>
               <textElement textAlignment = "Right"/>
               
               <textFieldExpression class = "java.lang.Integer">
                  <![CDATA[$V{CountryGroup_COUNT}]]>
               </textFieldExpression>
            </textField>
         
         </band>
      </groupFooter>
   
   </group>
   
   <title>
      <band height = "70">
         
         <line>
            <reportElement x = "0" y = "0" width = "515" height = "1"/>
         </line>
         
         <textField isBlankWhenNull = "true" bookmarkLevel = "1">
            <reportElement x = "0" y = "10" width = "515" height = "30"/>
            
            <textElement textAlignment = "Center">
               <font size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{ReportTitle}]]>
            </textFieldExpression>
            
            <anchorNameExpression>
               <![CDATA["Title"]]>
            </anchorNameExpression>
         </textField>
            
         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "40" width = "515" height = "20"/>
            
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{Author}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </title>

   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" width = "535" height = "15"
               backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
               <text><![CDATA[]]>
            </text>
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>

   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" width = "535" height = "14"
               backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
				
            <textElement />
				
            <text>
               <![CDATA[]]>  
            </text>
         </staticText>
         
         <textField>
            <reportElement x = "414" y = "0" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
	
</jasperReport>
Java-коды для заполнения отчетов остаются без изменений. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName =
      "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource =
      new JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      /**
       * Passing ReportTitle and Author as parameters
       */
      parameters.put("ReportTitle", "List of Contacts");
      parameters.put("Author", "Prepared By Manisha");

      try {
         JasperFillManager.fillReportToFile(
         sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java указано ниже —

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml взят из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview 
      the report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) как —

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28: warning:
   'includeantruntime' was not set, defaulting to build.sysclasspath=last;
   set to false for repeatable builds
   [javac] Compiling 7 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig
   for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 18 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как на экране ниже —

Пример групп отчетов Jasper

Здесь мы видим, что каждая страна сгруппирована, и количество появлений каждой страны отображается в нижнем колонтитуле каждой группы.



# Шрифты
Отчет содержит текстовые элементы, и каждый из них может иметь свои настройки шрифта. Эти параметры можно указать с помощью тега < font >, доступного в теге <textElement>. Отчет может определить количество шрифтов. После определения они могут использоваться в качестве настроек по умолчанию или базовых шрифтов для других определений шрифтов по всему отчету.

Сообщить о шрифтах
Шрифт отчета — это набор настроек шрифта, объявленных на уровне отчета. Шрифт отчета можно повторно использовать во всем шаблоне отчета при настройке свойств шрифта текстовых элементов.

Шрифты отчетов теперь устарели. Не используйте элементы <reportFont />, объявленные внутри самого документа. Вместо этого используйте элемент <style />.

Атрибуты шрифта
В таблице ниже приведены основные атрибуты элемента < font > —

S.NO	Атрибут и описание
1	
Fontname

Имя шрифта, которое может быть именем физического шрифта, логического или именем семейства шрифтов из зарегистрированных расширений шрифтов JasperReports.

2	
размер

Размер шрифта измеряется в пунктах. По умолчанию это 10.

3	
isBold

Флаг, указывающий, требуется ли жирный шрифт. По умолчанию используется значение false.

4	
isItalic

Флаг, указывающий, требуется ли курсивный шрифт. По умолчанию используется значение false.

5	
isUnderline

Флаг, указывающий, требуется ли подчеркивание текста. По умолчанию используется значение false.

6	
isStrikeThrough

Флаг, указывающий, требуется ли зачеркивание текста. По умолчанию используется значение false.

7	
pdfFontName

Имя эквивалентного шрифта PDF, требуемого библиотекой iText при экспорте документов в формат PDF.

8	
pdfEncoding

Эквивалентная кодировка символов PDF, также требуемая библиотекой iText.

9	
isPdfEmbedded

Флаг, который указывает, должен ли шрифт быть встроен в сам документ. По умолчанию используется значение false. Если установлено значение true, помогает просматривать документ PDF без проблем.

Fontname

Имя шрифта, которое может быть именем физического шрифта, логического или именем семейства шрифтов из зарегистрированных расширений шрифтов JasperReports.

размер

Размер шрифта измеряется в пунктах. По умолчанию это 10.

isBold

Флаг, указывающий, требуется ли жирный шрифт. По умолчанию используется значение false.

isItalic

Флаг, указывающий, требуется ли курсивный шрифт. По умолчанию используется значение false.

isUnderline

Флаг, указывающий, требуется ли подчеркивание текста. По умолчанию используется значение false.

isStrikeThrough

Флаг, указывающий, требуется ли зачеркивание текста. По умолчанию используется значение false.

pdfFontName

Имя эквивалентного шрифта PDF, требуемого библиотекой iText при экспорте документов в формат PDF.

pdfEncoding

Эквивалентная кодировка символов PDF, также требуемая библиотекой iText.

isPdfEmbedded

Флаг, который указывает, должен ли шрифт быть встроен в сам документ. По умолчанию используется значение false. Если установлено значение true, помогает просматривать документ PDF без проблем.

Типы шрифтов
В JasperReports шрифты можно классифицировать как —

Логические шрифты. Пять типов шрифтов, распознаваемых платформой Java начиная с версии 1.0, называются логическими шрифтами. Это — Serif, SansSerif, Monospaced, Dialog и DialogInput . Эти логические шрифты не являются реальными библиотеками шрифтов, которые установлены где-либо в системе. Это просто имена типов шрифтов, распознаваемые средой исполнения Java. Они должны быть сопоставлены с каким-либо физическим шрифтом, который установлен в системе.

Физические шрифты. Эти шрифты представляют собой фактические библиотеки шрифтов, состоящие, например, из шрифтов TrueType или PostScript Type 1. Физические шрифты могут быть Arial, Time, Helvetica, Courier или любым другим количеством шрифтов, включая международные шрифты.

Расширения шрифтов — библиотека JasperReports может использовать шрифты, зарегистрированные на лету во время выполнения, благодаря встроенной поддержке расширений шрифтов. Список семейств шрифтов может быть сделан доступным для JasperReports с использованием расширения шрифта. Они сделаны из похожих шрифтов и поддерживают определенные локали.

Логические шрифты. Пять типов шрифтов, распознаваемых платформой Java начиная с версии 1.0, называются логическими шрифтами. Это — Serif, SansSerif, Monospaced, Dialog и DialogInput . Эти логические шрифты не являются реальными библиотеками шрифтов, которые установлены где-либо в системе. Это просто имена типов шрифтов, распознаваемые средой исполнения Java. Они должны быть сопоставлены с каким-либо физическим шрифтом, который установлен в системе.

Физические шрифты. Эти шрифты представляют собой фактические библиотеки шрифтов, состоящие, например, из шрифтов TrueType или PostScript Type 1. Физические шрифты могут быть Arial, Time, Helvetica, Courier или любым другим количеством шрифтов, включая международные шрифты.

Расширения шрифтов — библиотека JasperReports может использовать шрифты, зарегистрированные на лету во время выполнения, благодаря встроенной поддержке расширений шрифтов. Список семейств шрифтов может быть сделан доступным для JasperReports с использованием расширения шрифта. Они сделаны из похожих шрифтов и поддерживают определенные локали.

Как описано в таблице выше, нам нужно указать в атрибуте fontName имя физического шрифта, имя логического шрифта или имя семейства шрифтов из зарегистрированных расширений шрифтов JasperReports.

Название шрифта PDF
Библиотека JasperReports использует библиотеку iText при экспорте отчетов в PDF (формат переносимого документа). PDF-файлы можно просматривать на разных платформах и всегда будут выглядеть одинаково. Это отчасти потому, что в этом формате есть особый способ работы со шрифтами. Атрибут fontName бесполезен при экспорте в PDF. Атрибут pdfFontName существует там, где нам нужно указать настройки шрифта.

Библиотека iText знает, как обращаться со встроенными шрифтами и файлами TTF, и распознает следующие имена встроенных шрифтов:

курьер
Courier-Bold
Courier-BoldOblique
Courier-Oblique
Helvetica
Helvetica-Bold
Helvetica-BoldOblique
Helvetica-Косой
Условное обозначение
Times-Roman
Времена-Bold
Времена-BoldItalic
Времена-Italic
ZapfDingbats
Согласно предварительному условию библиотеки iText, для работы со шрифтами в качестве имени шрифта необходимо указать одно из следующего:

Имя встроенного шрифта из приведенного выше списка.

Имя файла TTF (True Type Font), который он может найти на диске.

Настоящее имя шрифта, при условии, что файл TTF, содержащий шрифт, был ранее зарегистрирован в iText или что псевдоним был определен при регистрации шрифта.

Имя встроенного шрифта из приведенного выше списка.

Имя файла TTF (True Type Font), который он может найти на диске.

Настоящее имя шрифта, при условии, что файл TTF, содержащий шрифт, был ранее зарегистрирован в iText или что псевдоним был определен при регистрации шрифта.

Исходя из вышеуказанных предварительных условий, атрибут pdfFontName может содержать одно из следующих значений:

Название встроенного шрифта PDF из приведенного выше списка.

Имя файла TTF, который может находиться на диске во время выполнения при экспорте в PDF.

Настоящее имя зарегистрированного шрифта.

Суффикс ключа (часть после net.sf.jasperreports.export.pdf.font ) для шрифта, зарегистрированного в iText, в качестве файла шрифта.

Название встроенного шрифта PDF из приведенного выше списка.

Имя файла TTF, который может находиться на диске во время выполнения при экспорте в PDF.

Настоящее имя зарегистрированного шрифта.

Суффикс ключа (часть после net.sf.jasperreports.export.pdf.font ) для шрифта, зарегистрированного в iText, в качестве файла шрифта.

Стандартные шрифты и наследование
Каждый текстовый элемент наследует атрибуты font и style от своего родительского элемента, который, в свою очередь, наследует эти атрибуты от своего родительского элемента. Если для элементов не определены стили и / или шрифты, будет применен стиль по умолчанию (и / или шрифт, но теперь он не рекомендуется), объявленный в корневом элементе <jasperReport />.

Определение стилей или шрифтов по умолчанию в JasperReports не является обязательным. Если для данного элемента шрифт не определен, механизм ищет либо унаследованные атрибуты шрифта, либо, если атрибуты не найдены таким образом, он ищет свойство net.sf.jasperreports.default.font.name в / Файл src / default.jasperreports.properties . Его значение определяет имя семейства шрифтов, которое будет использоваться, когда свойства шрифта не определены явно для текстового элемента или не унаследованы от его родителя.

Основные свойства шрифта по умолчанию и их значения, определенные в файле /src/default.jasperreports.properties, приведены в таблице ниже —

Имущество	Описание
net.sf.jasperreports.default.font.name = SansSerif	Имя шрифта по умолчанию.
net.sf.jasperreports.default.font.size = 10	Размер шрифта по умолчанию.
net.sf.jasperreports.default.pdf.font.name = Helvetica	Шрифт PDF по умолчанию.
net.sf.jasperreports.default.pdf.encoding = CP1252	Кодировка символов PDF по умолчанию.
net.sf.jasperreports.default.pdf.embedded = ложь	По умолчанию шрифты PDF не встроены.
пример
Чтобы продемонстрировать использование шрифтов и атрибутов шрифта для получения определенного внешнего вида текста, давайте напишем новый шаблон отчета (jasper_report_template.jrxml). Содержимое JRXML приведено ниже. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test. Здесь мы будем отображать текст в заголовке отчета в различных форматах шрифтов.

<?xml version = "1.0" encoding = "UTF-8"?>

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" pageWidth = "595" pageHeight = "842"
   columnWidth = "555" leftMargin = "20" rightMargin = "20" topMargin = "30"
   bottomMargin = "30">

   <title>
      <band height = "682">
      
      <staticText>
         <reportElement x = "0" y = "50" width = "150" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[Welcome to TutorialsPoint!]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "50" width = "390" height = "40"/>
         <textElement/>
         
         <text>
           <![CDATA[<staticText>
           <reportElement x = "0" y = "50" width = "150" height = "40"/>
           <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "0" y = "100" width = "150" height = "40"/>
         
         <textElement>
            <font size = "12"/>
         </textElement>
         
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "100" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "100" width = "150" height = "40"/>
            
            <textElement>
               <font size = "14"/>
            </textElement>
				
            <text> Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "0" y = "150" width = "150" height = "40"/>
         
         <textElement>
            <font fontName = "DejaVu Serif" size = "12" isBold = "false"/>
         </textElement>
			
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "150" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "250" width = "150" height = "40"/>
            
            <textElement>
               <font fontName = "DejaVu Serif" size = "12" isBold = "false"/>
            </textElement>
				
            <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "0" y = "200" width = "150" height = "40"/>
         
         <textElement>
            <font fontName = "DejaVu Serif" size = "12" isBold = "true"/>
         </textElement>
			
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "200" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "300" width = "150" height = "40"/>
            
            <textElement>
               <font fontName = "DejaVu Serif" size = "12" isBold = "true"/>
            </textElement>
				
            <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "0" y = "250" width = "150" height = "40"/>
         
         <textElement>
            <font fontName = "Monospaced" size = "12" isItalic = "true" 
               isUnderline = "true" pdfFontName = "Courier-Oblique"/>
         </textElement>
         
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "250" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "350" width = "150" height = "40"/>
            
            <textElement>
               <font fontName = "Monospaced" size = "12" isItalic = "true"
                  isUnderline = "true" pdfFontName = "Courier-Oblique"/>
            </textElement>
            
            <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "0" y = "300" width = "150" height = "40"/>
         
         <textElement>
            <font fontName = "Monospaced" size = "12" isBold = "true"
               isStrikeThrough = "true" pdfFontName = "Courier-Bold"/>
         </textElement>
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "300" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "400" width = "150" height = "40"/>
            
            <textElement>
               <font fontName = "Monospaced" size = "12" isBold = "true"
                  isStrikeThrough = "true" pdfFontName = "Courier-Bold"/>
            </textElement>
				
            <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "0" y = "350" width = "150" height = "40" 
            forecolor = "#FF0000"/>
         
         <textElement>
            <font size = "14"/>
         </textElement>
			
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "350" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "450" width = "150" height = "40"
               forecolor = "red"/>
            
            <textElement><font size = "14"/></textElement>
            <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "0" y = "400" width = "150" height = "40" mode = "Opaque"
            forecolor = "#00FF00" backcolor = "#FFFF00"/>
         
         <textElement>
            <font fontName = "Serif" size = "12" isBold = "true" 
               pdfFontName = "Times-Bold"/>
         </textElement>
			
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "400" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "500" width = "150" height = "40"
               forecolor = "green" backcolor = "#FFFF00" mode = "Opaque"/>
            
            <textElement>
               <font fontName = "Serif" size = "12" isBold = "true"
                  pdfFontName = "Times-Bold"/>
            </textElement>
				
            <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement x = "0" y = "450" width = "150" height = "40" mode = "Opaque"
            forecolor = "#0000FF" backcolor = "#FFDD99"/>
         
         <textElement textAlignment = "Center" verticalAlignment = "Middle">
            <font fontName = "SansSerif" size = "12" isBold = "false"
            isItalic = "true" pdfFontName = "Sans.Slanted" isPdfEmbedded = "true"/>
         </textElement>
			
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "450" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "550" width = "150" height = "90"
               forecolor = "blue" backcolor = "#FFDD99" mode = "Opaque"/>
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font fontName = "SansSerif" size = "12" isBold = "false"
                  pdfFontName = "Sans.Slanted" isPdfEmbedded = "true"/>
            </textElement>
				
            <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      </staticText>
      
      <staticText>
         <reportElement mode = "Opaque" x = "0" y = "500" width = "150" height = "40"
            forecolor = "#FF0000" backcolor = "#99DDFF"/>
         
         <textElement textAlignment = "Right" verticalAlignment = "Bottom">
            <font fontName = "SansSerif" size = "12" isBold = "true"
               pdfFontName = "DejaVu Sans Bold" isPdfEmbedded = "true"/>
         </textElement>
			
         <text><![CDATA[Welcome to TutorialsPoint!]]></text>
      </staticText>
      
      <staticText>
         <reportElement x = "160" y = "500" width = "390" height = "40"/>
         <textElement/>
         
         <text>
            <![CDATA[<staticText>
            <reportElement x = "0" y = "650" width = "150" height = "90"    forecolor = "red"
               backcolor = "#99DDFF" mode = "Opaque"/>
            
            <textElement textAlignment = "Right" verticalAlignment = "Bottom">
               <font fontName = "SansSerif" size = "12" isBold = "true"
                  pdfFontName = "DejaVu Sans Bold" isPdfEmbedded = "true"/>
            </textElement>
				
            <text>Welcome to TutorialsPoint!</text></staticText>]]>
         </text>
      
      </staticText>
   
   </band>
</title>

</jasperReport>
Java-код для заполнения и генерации отчета приведен ниже. Давайте сохраним этот файл JasperFontsReportFill.java в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint.

package com.tutorialspoint;

import net.sf.jasperreports.engine.JREmptyDataSource;
import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;

public class JasperFontsReportFill {
   public static void main(String[] args) {
      String sourceFileName = "C://tools/jasperreports-5.0.1/test/" + 
         "jasper_report_template.jasper";

      try {
         JasperFillManager.fillReportToFile(sourceFileName, null,
            new JREmptyDataSource());
      } catch (JRException e) {
         // TODO Auto-generated catch block
         e.printStackTrace();
      }

   }
}
Здесь мы используем экземпляр JREmptyDataSource при заполнении отчетов, чтобы имитировать источник данных с одной записью в нем, но со всеми полями, являющимися нулевыми .

## Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview the report 
      stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
		
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperFontsReportFill (viewFullReport является целью по умолчанию) как —

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperFontsReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defaulting to build.
   [javac] Compiling 5 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperFontsReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 45 minutes 3 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —

Пример шрифтов Jasper Report

Здесь мы видим, что текст «Welcome to TutorialsPoint» отображается в разных форматах шрифтов.

Поддержка Юникода
В JasperReports для работы с текстами требуются специальные инструменты для обработки как символьных представлений, так и свойств форматирования текста. Любой текст можно рассматривать как последовательность символов с определенной структурой представления. Внешний вид текста состоит как из макета (и абзаца), так и из настроек шрифта. Но хотя в большинстве случаев текстовая разметка остается неизменной, настройки шрифта могут измениться при запуске отчета в разных локалях.

Мы знаем, что разные языки нуждаются в разных наборах символов для представления определенных символов. Поэтому работа с текстами означает работу со шрифтами. Однако подробное обсуждение того, как использовать шрифты в JasperReports, доступно в главе « Шрифты отчета» .

Одной из основных особенностей, касающихся текстового содержания в данном отчете, является возможность его интернационализации. Это означает, что мы можем запустить отчет в разных локализованных средах, используя разные языки и другие настройки локализации, без каких-либо жестко запрограммированных изменений. Кодировка символов является важной функцией, когда отчет предназначен для интернационализации.

Кодировка символов
Персонаж — это наименьшая единица письма, передающая значимую информацию. Это абстрактное понятие, персонаж не имеет визуального облика. «Прописная латинская буква A» отличается от «строчной латинской буквы a» и от «заглавной кириллицы A» и «заглавной греческой альфы».

Визуальное представление персонажа называется глифом . Определенный набор глифов называется шрифтом . «Прописные латинские буквы A», «Прописные кириллицы A» и «Прописные буквы греческого алфавита» могут иметь одинаковые глифы, но это разные символы. В то же время глифы для «заглавной латинской буквы A» могут выглядеть очень по-разному в Times New Roman, Gill Sans и Poetica канцелярском курсиве, но они по-прежнему представляют один и тот же символ.

Набор доступных символов называется репертуаром символов . Местоположение (индекс) данного символа в репертуаре называется его позицией кода или кодовой точкой. Метод численного представления кодовой точки в данном репертуаре называется кодировкой символов .

Кодировки обычно выражаются в октетах. Октет — это группа из восьми двоичных цифр, т. Е. Восьми единиц и нулей. Октет может выражать числовой диапазон от 0 до 255 или от 0x00 до 0xFF, чтобы использовать шестнадцатеричное представление.

Unicode
Юникод — это репертуар персонажей, который содержит большинство символов, используемых на языках мира. Он может вместить миллионы символов, и уже содержит сотни тысяч. Юникод делится на «плоскости» по 64К символов. В большинстве случаев используется только первый план, известный как базовый многоязычный план, или BMP.

UTF-8 является рекомендуемой кодировкой. Он использует переменное количество октетов для представления различных символов.

В файле JRXML атрибут кодировки указывается в заголовке. Он используется во время составления отчета для декодирования содержимого XML. Например, если отчет содержит только французские слова и такие символы, как ç, é, â, то достаточно кодировки ISO-8859-1 (aka Latin-1) —

<?xml version = "1.0" encoding = "ISO-8859-1"?>
Как видно выше, в идеале мы можем выбрать кодировку, подходящую для минимального набора символов, который может правильно представлять все символы в документе. Но в случае мультиязычных документов (т. Е. Документов, содержащих слова, написанные на нескольких языках), следует выбирать кодировку, адаптированную к минимальному набору символов, способную правильно представлять все символы в документе, даже если они принадлежат разным языкам. Одной из кодировок символов, способных обрабатывать многоязычные документы, является UTF-8 , используемый JasperReports в качестве значения кодировки по умолчанию.

Тексты обычно хранятся в файлах комплекта ресурсов, а не в документе во время интернационализации. Таким образом, бывают случаи, когда сам JRXML выглядит полностью ASCII-совместимым, но сгенерированные отчеты во время выполнения содержат тексты, которые невозможно прочитать с помощью ASCII. В результате для определенного типа форматов экспорта документов (таких как CSV, HTML, XHTML, XML и текст) необходимо знать кодировку для сгенерированного документа. Различные языки поддерживаются разными кодировками символов. Поэтому каждый раз нам нужно запускать отчет в локализованной среде. Далее, мы должны знать, какая кодировка символов наиболее подходит для сгенерированного языка документа. В этом случае свойство кодирования, определенное в самом файле JRXML, может быть более бесполезным.

Для решения такого рода проблем мы можем использовать свойство клиента экспорта, известное как net.sf.jasperreports.export.character.encoding . Это пользовательское свойство экспорта по умолчанию — UTF-8 и присутствует в JasperReports.

Это значение по умолчанию устанавливается в файле default.jasperreports.properties . Для более конкретных параметров во время экспорта также доступен параметр экспорта CHARACTER_ENCODING.

пример
Чтобы продемонстрировать использование поддержки юникода в Jasperreports, давайте напишем новый шаблон отчета (jasper_report_template.jrxml). Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test . Здесь мы будем отображать текст на разных языках, используя символы Unicode (\ uXXXX). Любой символ, закодированный с помощью UTF-8, может быть представлен только с использованием его четырехзначного шестнадцатеричного кода. Например, греческая буква Γ может быть записана как \ u0393. Когда встречаются такие обозначения, механизм вызывает соответствующее представление символов в наборе символов, и будет распечатан только этот конкретный символ. Содержимое JRXML приведено ниже:

<?xml version = "1.0" encoding = "UTF-8"?>

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth = "555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20">

   <parameter name = "GreekText" class = "java.lang.String" isForPrompting = "false">
      <defaultValueExpression><![CDATA["\u0394\u03B5\u03BD "+
         "\u03BA\u03B1\u03C4\u03B1\u03BB\u03B1\u03B2\u03B1\u03AF"+
         "\u03BD\u03C9 \u0395\u03BB\u03BB\u03B7\u03BD\u03B9\u03BA\u03AC"]]>
      </defaultValueExpression>
   </parameter>
   
   <parameter name = "CyrillicText" class = "java.lang.String" isForPrompting = "false">
      <defaultValueExpression><![CDATA["\u042F \u043D\u0435 "+
         "\u043C\u043E\u0433\u0443 \u043F\u043E\u043D\u044F\u0442\u044C "+
         "\u0433\u0440\u0435\u0447\u0435\u0441\u043A\u0438\u0439"]]>
      </defaultValueExpression>
   </parameter>

   <parameter name = "ArabicText" class = "java.lang.String" isForPrompting = "false">
      <defaultValueExpression><![CDATA["\u0627\u0646\u0646\u0649 \u0644\u0627 "+
         "\u0627\u0641\u0647\u0645 \u0627\u0644\u0644\u063A\u0629 "+
         "\u0627\u0644\u0639\u0631\u0628\u064A\u0629"]]>
      </defaultValueExpression>
   </parameter>
   
   <parameter name = "HebrewText" class = "java.lang.String" isForPrompting = "false">
      <defaultValueExpression><![CDATA["\u05D0\u05E0\u05D9 \u05DC\u05D0 "+
         "\u05DE\u05D1\u05D9\u05DF \u05E2\u05D1\u05E8\u05D9\u05EA"]]>
      </defaultValueExpression>
   </parameter>
   
   <title>
      <band height = "782">
         
         <textField>
            <reportElement x = "0" y = "50" width = "200" height = "60"/>
            
            <textElement>
               <font fontName = "DejaVu Sans" size = "14"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{GreekText} + "\n" + $P{CyrillicText}]]>
            </textFieldExpression>
         </textField>
         
         <staticText>
            <reportElement x = "210" y = "50" width = "340" height = "60"/>
            <textElement/>
            
            <text>
               <![CDATA["GreekText and CyrillicText"]]>
            </text>
         </staticText>
         
         <textField>
            <reportElement x = "0" y = "120" width = "200" height = "60"/>
            
            <textElement>
               <font fontName = "DejaVu Sans" size = "14" isBold = "true"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{GreekText} + "\n" + $P{CyrillicText}]]>
            </textFieldExpression>
				
         </textField>
         
         <staticText>
            <reportElement x = "210" y = "120" width = "340" height = "60"/>
            <textElement/>
            <text><![CDATA["GreekText and CyrillicText"]]></text>
         </staticText>
         
         <textField>
            <reportElement x = "0" y = "190" width = "200" height = "60"/>
            
            <textElement>
               <font fontName = "DejaVu Sans" size = "14" isItalic = "true" 
                  isUnderline = "true"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{GreekText} + "\n" + $P{CyrillicText}]]>
            </textFieldExpression>
				
         </textField>
         
         <staticText>
            <reportElement x = "210" y = "190" width = "340" height = "60"/>
            <textElement/>
            <text><![CDATA["GreekText and CyrillicText"]]></text>
         </staticText>
         
         <textField>
            <reportElement x = "0" y = "260" width = "200" height = "60"/>
            
            <textElement>
               <font fontName = "DejaVu Sans" size = "14" isBold = "true" 
                  isItalic = "true" isUnderline = "true"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{GreekText} + "\n" + $P{CyrillicText}]]>
            </textFieldExpression>
				
         </textField>
         
         <staticText>
            <reportElement x = "210" y = "260" width = "340" height = "60"/>
            <textElement/>
            <text><![CDATA["GreekText and CyrillicText"]]></text>
         </staticText>

         <textField>
            <reportElement x = "0" y = "330" width = "200" height = "60"/>
            
            <textElement textAlignment = "Right">
               <font fontName="DejaVu Sans" size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{ArabicText}]]>
            </textFieldExpression>
				
         </textField>
         
         <textField>
            <reportElement x = "210" y = "330" width = "340" height = "60"/>
            
            <textElement textAlignment = "Right">
               <font fontName = "DejaVu Sans" size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{HebrewText}]]>
            </textFieldExpression>
				
         </textField>
      
      </band>
   </title>
	
</jasperReport>
В приведенном выше файле мы видим наличие кодировки UTF-8. Также локализованные фрагменты текста Unicode хранятся в параметрах документа.

Код Java для заполнения и генерации отчета, как показано ниже. Давайте сохраним этот файл JasperUnicodeReportFill.java в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint.

package com.tutorialspoint;

import net.sf.jasperreports.engine.JREmptyDataSource;
import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;

public class JasperUnicodeReportFill {
   public static void main(String[] args) {
      String sourceFileName ="C://tools/jasperreports-5.0.1/test/" + 
         "jasper_report_template.jasper";

      try {
         JasperFillManager.fillReportToFile(sourceFileName, null, 
            new JREmptyDataSource());
      } catch (JRException e) {
         // TODO Auto-generated catch block
         e.printStackTrace();
      }

   }
}
Здесь мы используем экземпляр JREmptyDataSource при заполнении отчетов для имитации источника данных с одной записью в нем, но со всеми полями в этой единственной записи, равными NULL .

Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml выбирается из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview the report 
      stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
		
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>

   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperUnicodeReportFill (viewFullReport является целью по умолчанию) следующим образом:

C:\tools\jasperreports-5.0.1\test>ant  -Dmain-class=com.tutorialspoint.JasperUnicodeReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defaulting t
   [javac] Compiling 1 source file to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperUnicodeReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 4 minutes 1 second
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —

Пример Jasper Report Unicode

Здесь мы видим, что текст отображается на разных языках. Также мы видим, что языки сгруппированы на одной странице и также смешаны в один и тот же текстовый элемент.

Стили отчетов
JasperReports имеет функцию <style>, которая помогает контролировать свойства текста в шаблоне отчета. Этот элемент представляет собой набор настроек стиля, объявленных на уровне отчета. Свойства, такие как цвет переднего плана, цвет фона, шрифт полужирный, курсив или обычный, размер шрифта, граница для шрифта и многие другие атрибуты контролируются элементом <style>. Стили могут расширять другие стили, а также добавлять или переопределять свойства родительского стиля.

Свойства стиля
Элемент <style> имеет много атрибутов. Некоторые из наиболее часто используемых перечислены в таблице ниже —

S.NO	Атрибут и описание
1	
название

Является обязательным. Он должен быть уникальным, поскольку он ссылается на соответствующий стиль отчета по всему отчету.

2	
IsDefault

Указывает, является ли этот стиль стилем документа по умолчанию.

3	
стиль

Ссылка на родительский стиль.

4	
Режим

Определяет прозрачность элемента. Возможные значения: Opaque и Transparent .

5	
ForeColor

Цвет переднего плана объекта.

6	
BackColor

Цвет фона объекта.

7	
заполнить

Определяет шаблон заливки, используемый для заливки объекта. На данный момент единственное допустимое значение — Solid .

6	
радиус

Определяет радиус угловой дуги прямоугольника.

7	
scaleImage

Определяет масштаб только для изображений. Возможные значения: Clip, FillFrame, RetainShape, RealHeight и RealSize .

8	
hAlign

Определяет горизонтальное выравнивание. Возможные значения: Левый, Центр, Правый и Обоснованный .

9	
VALIGN

Определяет вертикальное выравнивание. Возможные значения: Top, Middle и Bottom .

10	
вращение

Определяет поворот элемента. Возможные значения: None, Left, Right и UpsideDown .

11	
межстрочный интервал

Определяет межстрочный интервал между строками текста. Возможные значения: Single, 1_1_2, Double .

12	
наценка

Определяет стиль разметки для стилизованных текстов.

13	
Fontname

Определяет имя шрифта.

14	
размер шрифта

Определяет размер шрифта.

15	
isBold

Указывает, является ли стиль шрифта жирным.

16	
isItalic

Указывает, является ли стиль шрифта курсивом.

17	
isUnderline

Указывает, подчеркнут ли стиль шрифта.

18	
isStrikeThrough

Указывает, зачеркнут ли стиль шрифта.

19	
pdfFontName

Указывает имя связанного шрифта PDF.

20	
pdfEncoding

Определяет кодировку символов для формата вывода PDF.

22	
isPdfEmbedded

Указывает, встроен ли шрифт PDF.

23	
шаблон

Определяет шаблон формата для форматированных текстов.

24	
isBlankWhenNull

Указывает, должна ли отображаться пустая строка (пробел), если выражение имеет значение null.

название

Является обязательным. Он должен быть уникальным, поскольку он ссылается на соответствующий стиль отчета по всему отчету.

IsDefault

Указывает, является ли этот стиль стилем документа по умолчанию.

стиль

Ссылка на родительский стиль.

Режим

Определяет прозрачность элемента. Возможные значения: Opaque и Transparent .

ForeColor

Цвет переднего плана объекта.

BackColor

Цвет фона объекта.

заполнить

Определяет шаблон заливки, используемый для заливки объекта. На данный момент единственное допустимое значение — Solid .

радиус

Определяет радиус угловой дуги прямоугольника.

scaleImage

Определяет масштаб только для изображений. Возможные значения: Clip, FillFrame, RetainShape, RealHeight и RealSize .

hAlign

Определяет горизонтальное выравнивание. Возможные значения: Левый, Центр, Правый и Обоснованный .

VALIGN

Определяет вертикальное выравнивание. Возможные значения: Top, Middle и Bottom .

вращение

Определяет поворот элемента. Возможные значения: None, Left, Right и UpsideDown .

межстрочный интервал

Определяет межстрочный интервал между строками текста. Возможные значения: Single, 1_1_2, Double .

наценка

Определяет стиль разметки для стилизованных текстов.

Fontname

Определяет имя шрифта.

размер шрифта

Определяет размер шрифта.

isBold

Указывает, является ли стиль шрифта жирным.

isItalic

Указывает, является ли стиль шрифта курсивом.

isUnderline

Указывает, подчеркнут ли стиль шрифта.

isStrikeThrough

Указывает, зачеркнут ли стиль шрифта.

pdfFontName

Указывает имя связанного шрифта PDF.

pdfEncoding

Определяет кодировку символов для формата вывода PDF.

isPdfEmbedded

Указывает, встроен ли шрифт PDF.

шаблон

Определяет шаблон формата для форматированных текстов.

isBlankWhenNull

Указывает, должна ли отображаться пустая строка (пробел), если выражение имеет значение null.

Условные стили
В некоторых ситуациях стиль следует применять только при соблюдении определенных условий (например, для чередования смежных цветов строк в разделе сведений отчета). Это может быть достигнуто с помощью условных стилей.

У условного стиля есть два элемента —

выражение логического условия
стиль
Стиль используется, только если условие оценивается как истинное .

Применение стилей к элементам отчета
Любой тип элемента отчета может ссылаться на определение стиля отчета, используя атрибут style. Следовательно, все свойства стиля, объявленные определением стиля, которые применимы к текущему элементу, будут унаследованы. Чтобы переопределить унаследованные значения, можно использовать свойства стиля, указанные на уровне элемента отчета.

Шаблоны стиля
Мы можем сделать набор отчетов с общим видом, определив стиль в общем месте. На этот шаблон общего стиля могут ссылаться шаблоны отчетов. Шаблон стиля — это файл XML, который содержит одно или несколько определений стиля. Файлы шаблонов стилей, используемые соглашением, имеют расширение * .jrtx , но это не обязательно.

Шаблон стиля содержит следующие элементы —

<jasperTemplate> — это корневой элемент файла шаблона стиля.

<шаблон> — этот элемент используется для включения ссылок на другие файлы шаблона. Содержимое этого элемента интерпретируется как местоположение указанного файла шаблона.

<style> — этот элемент идентичен элементу с тем же именем из шаблонов дизайна отчетов (файлы JRXML), за исключением того, что стиль в шаблоне стиля не может содержать условные стили. Это ограничение вызвано тем фактом, что условные стили включают выражения отчета, а выражения могут интерпретироваться только в контексте одного определения отчета.

<jasperTemplate> — это корневой элемент файла шаблона стиля.

<шаблон> — этот элемент используется для включения ссылок на другие файлы шаблона. Содержимое этого элемента интерпретируется как местоположение указанного файла шаблона.

<style> — этот элемент идентичен элементу с тем же именем из шаблонов дизайна отчетов (файлы JRXML), за исключением того, что стиль в шаблоне стиля не может содержать условные стили. Это ограничение вызвано тем фактом, что условные стили включают выражения отчета, а выражения могут интерпретироваться только в контексте одного определения отчета.

Ссылки на шаблоны стилей включены в отчеты JRXML как элементы <template>. Шаблоны стилей загружаются во время заполнения отчета, а ссылки на имена стилей разрешаются после загрузки всех шаблонов. При загрузке шаблонов стилей и преобразовании имен стилей в стили создается дерево / график шаблонов стилей, верхняя часть которого представляет собой набор стилей, определенных в отчете. В этом дереве ссылки на имена стилей разрешаются до последнего стиля, который соответствует имени при прохождении в глубину.

пример
Давайте попробуем условные стили и шаблоны стилей. Давайте добавим элемент < style > alternateStyle к нашему существующему шаблону отчета (глава « Проекты отчетов» ). В зависимости от условия цвет шрифта меняется на синий для четного счета. Мы также включили шаблон стиля «styles.jrtx» . Пересмотренный шаблон отчета (jasper_report_template.jrxml) выглядит следующим образом. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test —

<?xml version = "1.0"?>
<!DOCTYPE jasperReport PUBLIC
   "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" pageWidth = "595"
   pageHeight = "842" columnWidth = "515"
   leftMargin = "40" rightMargin = "40" topMargin = "50" bottomMargin = "50">
	
   <template>"styles.jrtx"</template>
   
   <style name = "alternateStyle" fontName = "Arial" forecolor = "red">
      <conditionalStyle>
         <conditionExpression>
            <![CDATA[new Boolean($V{countNumber}.intValue() % 2 == 0)]]>
         </conditionExpression>
			
         <style forecolor = "blue" isBold = "true"/>
      </conditionalStyle>
   </style>
   
   <parameter name = "ReportTitle" class = "java.lang.String"/>
   <parameter name = "Author" class = "java.lang.String"/>

   <queryString>
      <![CDATA[]]>
   </queryString>

   <field name = "country" class = "java.lang.String">
      <fieldDescription><![CDATA[country]]></fieldDescription>
   </field>

   <field name = "name" class = "java.lang.String">
      <fieldDescription><![CDATA[name]]></fieldDescription>
   </field>

   <variable name = "countNumber" class = "java.lang.Integer" calculation = "Count">
      <variableExpression><![CDATA[Boolean.TRUE]]></variableExpression>
   </variable>

   <title>
      <band height = "70">
         
         <line>
            <reportElement x = "0" y = "0" width = "515" height = "1"/>
         </line>
         
         <textField isBlankWhenNull = "true" bookmarkLevel = "1">
            <reportElement x = "0" y = "10" width = "515" height = "30"/>
				
            <textElement textAlignment = "Center">
               <font size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{ReportTitle}]]>
            </textFieldExpression>
            
            <anchorNameExpression><![CDATA["Title"]]></anchorNameExpression>
         </textField>

         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "40" width = "515" height = "20"/>
            
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{Author}]]>
            </textFieldExpression>
				
         </textField>
      
      </band>
   </title>

   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" 
               width = "535" height = "15" backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
				
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
				
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
				
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
				
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>

   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" 
               width = "535" height = "14" backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
            
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
				
         </staticText>
         
         <textField>
            <reportElement style = "alternateStyle" x = "414" y = "0" 
               width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" 
               style = "Strong"/>
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>

</jasperReport>
Содержимое шаблона стиля styles.jrtx выглядит следующим образом. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test.

<?xml version = "1.0"?>

<!DOCTYPE jasperTemplate PUBLIC "-//JasperReports//DTD Template//EN"
  "http://jasperreports.sourceforge.net/dtds/jaspertemplate.dtd">

<jasperTemplate>
   <style name = "Strong" isBold = "true" pdfFontName = "Helvetica-Bold" 
      backcolor = "lightGray forecolor = "green"/>
</jasperTemplate>
Java-коды для заполнения отчетов остаются без изменений. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = 
         "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource = new 
         JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      /**
       * Passing ReportTitle and Author as parameters
       */
      parameters.put("ReportTitle", "List of Contacts");
      parameters.put("Author", "Prepared By Manisha");

      try {
         JasperFillManager.fillReportToFile(
         sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java указано ниже —

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml взят из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview the 
      report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
		
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
		
   </target>

</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) как —

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28: warning:
   'includeantruntime' was not set, defaulting to build.sysclasspath=last;
   set to false for repeatable builds
   [javac] Compiling 3 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See
   http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —

Пример стиля отчета Jasper

Здесь мы видим, что цвет шрифта меняется на синий для четного количества (в стране столбца). В имени столбца цвет шрифта меняется на зеленый (на этот стиль ссылаются из шаблона стиля).

Скрипты отчетов
Мы видели в наших предыдущих главах, данные, отображаемые в отчете, обычно выбираются из параметров отчета и полей отчета. Эти данные могут быть обработаны с использованием переменных отчета и их выражений. Существуют ситуации, когда сложная функциональность не может быть легко достигнута с помощью выражений или переменных отчета. Примерами этого могут быть сложные манипуляции со строками, построение карт или списки объектов в памяти или манипуляции датами с использованием сторонних API Java. Для таких ситуаций JasperReports предоставляет нам простой и мощный способ сделать это с помощью Scriptlets .

Скриплеты — это последовательности кода Java, которые выполняются каждый раз, когда происходит событие отчета. На значения переменных отчета можно воздействовать через скриптлеты.

Декларация сценария
Мы можем объявить скриптлет двумя способами:

Использование элемента < scriptlet >. Этот элемент имеет атрибут name и class class . Атрибут class должен указывать имя класса, который расширяет класс JRAbstractScriptlet . Класс должен быть доступен в пути к классам во время заполнения отчета и должен иметь пустой конструктор, чтобы механизм мог создать его экземпляр на лету.

Использование атрибута scriptletClass элемента < jasperReport > в шаблоне отчета (JRXML). Устанавливая этот атрибут с полностью определенным именем скриптлета (включая полное имя пакета), мы указываем, что хотим использовать скриптлет. Экземпляр скриптлета, созданный с этим атрибутом, действует как первый скриптлет в списке скриплетов и имеет предопределенное имя REPORT.

Использование элемента < scriptlet >. Этот элемент имеет атрибут name и class class . Атрибут class должен указывать имя класса, который расширяет класс JRAbstractScriptlet . Класс должен быть доступен в пути к классам во время заполнения отчета и должен иметь пустой конструктор, чтобы механизм мог создать его экземпляр на лету.

Использование атрибута scriptletClass элемента < jasperReport > в шаблоне отчета (JRXML). Устанавливая этот атрибут с полностью определенным именем скриптлета (включая полное имя пакета), мы указываем, что хотим использовать скриптлет. Экземпляр скриптлета, созданный с этим атрибутом, действует как первый скриптлет в списке скриплетов и имеет предопределенное имя REPORT.

Класс сценариев
Скриплет — это Java-класс, который должен расширять любой из следующих классов:

net.sf.jasperreports.engine.JRAbstractScriptlet — этот класс содержит ряд абстрактных методов, которые должны быть переопределены в каждой реализации. Эти методы автоматически вызываются JasperReports в соответствующий момент. Разработчик должен реализовать все абстрактные методы.

net.sf.jasperreports.engine.JRDefaultScriptlet — этот класс содержит пустые реализации по умолчанию для каждого метода в JRAbstractScriptlet. От разработчика требуется только реализовать те методы, которые ему нужны для его / ее проекта.

net.sf.jasperreports.engine.JRAbstractScriptlet — этот класс содержит ряд абстрактных методов, которые должны быть переопределены в каждой реализации. Эти методы автоматически вызываются JasperReports в соответствующий момент. Разработчик должен реализовать все абстрактные методы.

net.sf.jasperreports.engine.JRDefaultScriptlet — этот класс содержит пустые реализации по умолчанию для каждого метода в JRAbstractScriptlet. От разработчика требуется только реализовать те методы, которые ему нужны для его / ее проекта.

В следующей таблице перечислены методы в вышеприведенном классе. Эти методы будут вызываться механизмом отчетов в соответствующее время, на этапе заполнения отчета.

S.NO	Метод и описание
1	
public void beforeReportInit ()

Вызывается до инициализации отчета.

2	
public void afterReportInit ()

Вызывается после инициализации отчета.

3	
public void beforePageInit ()

Вызывается перед инициализацией каждой страницы.

4	
public void afterPageInit ()

Вызывается после инициализации каждой страницы.

5	
public void beforeColumnInit ()

Вызывается перед инициализацией каждого столбца.

6	
public void afterColumnInit ()

Вызывается после инициализации каждого столбца.

7	
public void beforeGroupInit (String groupName)

Вызывается до инициализации группы, указанной в параметре.

8	
public void afterGroupInit (String groupName)

Вызывается после инициализации группы, указанной в параметре.

9	
public void beforeDetailEval ()

Вызывается перед каждой записью в подробном разделе отчета.

10	
public void afterDetailEval ()

Вызывается после каждой записи в подробном разделе отчета.

public void beforeReportInit ()

Вызывается до инициализации отчета.

public void afterReportInit ()

Вызывается после инициализации отчета.

public void beforePageInit ()

Вызывается перед инициализацией каждой страницы.

public void afterPageInit ()

Вызывается после инициализации каждой страницы.

public void beforeColumnInit ()

Вызывается перед инициализацией каждого столбца.

public void afterColumnInit ()

Вызывается после инициализации каждого столбца.

public void beforeGroupInit (String groupName)

Вызывается до инициализации группы, указанной в параметре.

public void afterGroupInit (String groupName)

Вызывается после инициализации группы, указанной в параметре.

public void beforeDetailEval ()

Вызывается перед каждой записью в подробном разделе отчета.

public void afterDetailEval ()

Вызывается после каждой записи в подробном разделе отчета.

В отчете может быть указано любое количество скриптлетов. Если скриптлет не указан для отчета, механизм все равно создает один экземпляр JRDefaultScriptlet и регистрирует его с помощью встроенного параметра REPORT_SCRIPTLET.

Мы можем добавить любые дополнительные методы, которые нам нужны, к нашим скриптлетам. Отчеты могут вызывать эти методы с помощью встроенного параметра REPORT_SCRIPTLET.

Глобальные сценарии
Мы можем связать скриптлеты с отчетами по-другому, то есть объявить скриптлеты глобально. Это заставляет скриптлеты применяться ко всем отчетам, заполняемым в данном развертывании JasperReports. Это легко сделать благодаря тому, что скриптлеты могут быть добавлены в JasperReports в качестве расширений. Точка расширения сценария представлена интерфейсом net.sf.jasperreports.engine.scriptlets.ScriptletFactory . JasperReports загрузит все фабрики скриплетов, доступные через расширения во время выполнения. Затем он запросит у каждого из них список экземпляров скриптлетов, которые они хотят применить к текущему отчету, который выполняется. При запросе списка экземпляров сценариев механизм предоставляет некоторую контекстную информацию, которую фабрика может использовать, чтобы решить, какие сценарии действительно применяются к текущему отчету.

Отчет губернаторов
Регуляторы — это всего лишь расширение глобальных скриплетов, которые позволяют нам решать проблему, связанную с тем, что механизм отчетов входит в бесконечный цикл во время выполнения при создании отчетов. Неверные шаблоны отчетов не могут быть обнаружены во время разработки, поскольку в большинстве случаев условия для ввода бесконечных циклов зависят от фактических данных, которые вводятся в двигатель во время выполнения. Органы управления отчетами помогают в принятии решения о том, вошел ли определенный отчет в бесконечный цикл, и они могут его остановить. Это предотвращает исчерпание ресурсов для машины, на которой выполняется отчет.

JasperReports имеет два простых регулятора отчетов, которые будут останавливать выполнение отчета на основе указанного максимального числа страниц или указанного интервала времени ожидания. Они —

net.sf.jasperreports.governors.MaxPagesGovernor — это глобальный скриптлет, который ищет два свойства конфигурации, чтобы определить, применяется он или нет к отчету, который выполняется в данный момент. Свойства конфигурации:

net.sf.jasperreports.governor.max.pages.enabled = [правда | ложь]

net.sf.jasperreports.governor.max.pages = [целое число]

net.sf.jasperreports.governors.TimeoutGovernor — это также глобальный скриптлет, который ищет следующие два свойства конфигурации, чтобы определить, применяется он или нет.

Свойства конфигурации:

net.sf.jasperreports.governor.timeout.enabled = [правда | ложь]

net.sf.jasperreports.governor.timeout = [] миллисекунд

net.sf.jasperreports.governors.MaxPagesGovernor — это глобальный скриптлет, который ищет два свойства конфигурации, чтобы определить, применяется он или нет к отчету, который выполняется в данный момент. Свойства конфигурации:

net.sf.jasperreports.governor.max.pages.enabled = [правда | ложь]

net.sf.jasperreports.governor.max.pages = [целое число]

net.sf.jasperreports.governors.TimeoutGovernor — это также глобальный скриптлет, который ищет следующие два свойства конфигурации, чтобы определить, применяется он или нет.

Свойства конфигурации:

net.sf.jasperreports.governor.timeout.enabled = [правда | ложь]

net.sf.jasperreports.governor.timeout = [] миллисекунд

Свойства обоих регуляторов можно задать глобально, в файле jasperreports.properties или на уровне отчета, в качестве пользовательских свойств отчета. Это полезно, потому что разные отчеты могут иметь различный расчетный размер или ограничения по времени, а также потому, что вы можете захотеть включить регуляторы для всех отчетов, в то время как некоторые отключить его, или наоборот.

пример
Давайте напишем класс скриптлета ( MyScriptlet ). Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ MyScriptlet.java выглядит следующим образом:

package com.tutorialspoint;

import net.sf.jasperreports.engine.JRDefaultScriptlet;
import net.sf.jasperreports.engine.JRScriptletException;


public class MyScriptlet extends JRDefaultScriptlet {

   public void afterReportInit() throws JRScriptletException{
      System.out.println("call afterReportInit()");
      // this.setVariableValue("AllCountries", sbuffer.toString());
      this.setVariableValue("someVar", new String("This variable value 
         was modified by the scriptlet."));
   }

   public String hello() throws JRScriptletException {
      return "Hello! I'm the report's scriptlet object.";
   }

}
Подробности вышеупомянутого класса скриптлета следующие:

В методе afterReportInit мы устанавливаем значение для переменной «someVar» this.setVariableValue («someVar», new String («Это значение переменной было изменено сценарием.»)).

В конце класса был определен дополнительный метод с именем ‘hello’ . Это пример метода, который может быть добавлен в Scriptlet, который на самом деле возвращает значение, а не устанавливает переменную.

В методе afterReportInit мы устанавливаем значение для переменной «someVar» this.setVariableValue («someVar», new String («Это значение переменной было изменено сценарием.»)).

В конце класса был определен дополнительный метод с именем ‘hello’ . Это пример метода, который может быть добавлен в Scriptlet, который на самом деле возвращает значение, а не устанавливает переменную.

Далее мы добавим ссылку на класс скриптлета в наш существующий шаблон отчета (глава « Конструкции отчета» ). Пересмотренный шаблон отчета (jasper_report_template.jrxml) выглядит следующим образом. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test —

<?xml version = "1.0"?>
<!DOCTYPE jasperReport PUBLIC
   "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" pageWidth = "595"
   pageHeight = "842" columnWidth = "515"
   leftMargin = "40" rightMargin = "40" topMargin = "50" bottomMargin = "50"
   scriptletClass = "com.tutorialspoint.MyScriptlet">
	
   <style name = "alternateStyle" fontName = "Arial" forecolor = "red">
      
      <conditionalStyle>
         <conditionExpression>
            <![CDATA[new Boolean($V{countNumber}.intValue() % 2 == 0)]]>
         </conditionExpression>
			
         <style forecolor = "blue" isBold = "true"/>
      </conditionalStyle>
   </style>
   
   <parameter name = "ReportTitle" class = "java.lang.String"/>
   <parameter name = "Author" class = "java.lang.String"/>

   <queryString>
      <![CDATA[]]>
   </queryString>

   <field name = "country" class = "java.lang.String">
      <fieldDescription>
         <![CDATA[country]]>
      </fieldDescription>
   </field>

   <field name = "name" class = "java.lang.String">
      <fieldDescription>
         <![CDATA[name]]>
      </fieldDescription>
   </field>

   <variable name = "countNumber" class = "java.lang.Integer" 
      calculation = "Count">
      <variableExpression><
         ![CDATA[Boolean.TRUE]]>
      </variableExpression>
   </variable>

   <variable name = "someVar" class = "java.lang.String">
      <initialValueExpression>
        <![CDATA["This is the initial variable value."]]>
      </initialValueExpression>
   </variable>

   <title>
      <band height = "100">
         
         <line>
            <reportElement x = "0" y = "0" width = "515" height = "1"/>
         </line>
         
         <textField isBlankWhenNull = "true" bookmarkLevel = "1">
            <reportElement x = "0" y = "10" width = "515" height = "30"/>
            
            <textElement textAlignment = "Center">
              <font size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
              <![CDATA[$P{ReportTitle}]]>
            </textFieldExpression>
				
            <anchorNameExpression>
               <![CDATA["Title"]]>
            </anchorNameExpression>
         </textField>
        
         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "40" width = "515" height = "20"/>
            
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{Author}]]>
            </textFieldExpression>
         </textField>
         
         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "50" width = "515" 
               height = "30" forecolor = "#993300"/>
             
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$V{someVar}]]>
            </textFieldExpression>
				
         </textField>

      </band>
   </title>

   <columnHeader>
      <band height = "23">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "3" 
               width = "535" height = "15"
               backcolor = "#70A9A9" />
            
            <box>
               <bottomPen lineWidth = "1.0" lineColor = "#CCCCCC" />
            </box>
				
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
				
         </staticText>
         
         <staticText>
            <reportElement x = "414" y = "3" width = "121" height = "15" />
                
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
            
            <text><![CDATA[Country]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "3" width = "136" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font isBold = "true" />
            </textElement>
				
            <text><![CDATA[Name]]></text>
         </staticText>
      
      </band>
   </columnHeader>

   <detail>
      <band height = "16">
         
         <staticText>
            <reportElement mode = "Opaque" x = "0" y = "0" 
               width = "535"	height = "14"
               backcolor = "#E5ECF9" />
            
            <box>
               <bottomPen lineWidth = "0.25" lineColor = "#CCCCCC" />
            </box>
				
            <textElement />
				
            <text>
               <![CDATA[]]>
            </text>
         </staticText>
         
         <textField>
            <reportElement style = "alternateStyle" x="414" y = "0" 
               width = "121" height = "15" />
            
            <textElement textAlignment = "Center" verticalAlignment = "Middle">
               <font size = "9" />
            </textElement>
            
				
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "0" y = "0" width = "136" height = "15" />
            <textElement textAlignment = "Center" verticalAlignment = "Middle" />
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
   
   <summary>
      <band height = "45">
            
         <textField isStretchWithOverflow = "true">
            <reportElement x = "0" y = "10" width = "515" height = "15" />
            <textElement textAlignment = "Center"/>
               
            <textFieldExpression class = "java.lang.String">
               <![CDATA["There are " + String.valueOf($V{REPORT_COUNT}) +
                  " records on this report."]]>
            </textFieldExpression>
         </textField>
         
         <textField isStretchWithOverflow = "true">
            <reportElement positionType = "Float" x = "0" y = "30" width = "515"
               height = "15" forecolor = "# 993300" />
               
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
               
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{REPORT_SCRIPTLET}.hello()]]>
            </textFieldExpression>
            
         </textField>
         
      </band>
   </summary>
	
</jasperReport>
Детали пересмотренного шаблона отчета приведены ниже —

Мы ссылались на класс MyScriptlet в атрибуте scriptletClass элемента <jasperReport>.

Скриплеты могут только получать доступ, но не изменять поля и параметры отчета. Однако скриптлеты могут изменять значения переменных отчета. Это может быть достигнуто путем вызова метода setVariableValue (). Этот метод определен в классе JRAbstractScriptlet, который всегда является родительским классом любого скриптлета. Здесь мы определили переменную someVar , которая будет изменена MyScriptlet, чтобы иметь значение Это значение было изменено скриптлетом .

Приведенный выше шаблон отчета имеет вызов метода в группе Summary, который иллюстрирует, как писать новые методы (в скриптлетах) и использовать их в шаблоне отчета. ( $ P {REPORT_SCRIPTLET} .hello () )

Мы ссылались на класс MyScriptlet в атрибуте scriptletClass элемента <jasperReport>.

Скриплеты могут только получать доступ, но не изменять поля и параметры отчета. Однако скриптлеты могут изменять значения переменных отчета. Это может быть достигнуто путем вызова метода setVariableValue (). Этот метод определен в классе JRAbstractScriptlet, который всегда является родительским классом любого скриптлета. Здесь мы определили переменную someVar , которая будет изменена MyScriptlet, чтобы иметь значение Это значение было изменено скриптлетом .

Приведенный выше шаблон отчета имеет вызов метода в группе Summary, который иллюстрирует, как писать новые методы (в скриптлетах) и использовать их в шаблоне отчета. ( $ P {REPORT_SCRIPTLET} .hello () )

Java-коды для заполнения отчетов остаются без изменений. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = 
         "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource = new 
         JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      /**
       * Passing ReportTitle and Author as parameters
       */
      parameters.put("ReportTitle", "List of Contacts");
      parameters.put("Author", "Prepared By Manisha");

      try {
         JasperFillManager.fillReportToFile(
         sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java указано ниже —

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml взят из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview 
      the report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>

</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) как —

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defaulting to bu
   [javac] Compiling 4 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.
   [java] call afterReportInit()
   [java] call afterReportInit()

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 18 minutes 49 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —

Пример Jasper Report Scriplet

Здесь мы видим два сообщения из класса MyScriptlet —

В разделе заголовка — это значение переменной было изменено скриптлетом
Внизу — Привет! Я объект сценария отчета.
Создать подотчеты
Подотчеты являются одной из приятных особенностей JasperReports. Эта функция позволяет включать отчет в другой отчет, то есть один отчет может быть вложенным отчетом другого. Подотчеты помогают нам упростить дизайн отчетов, поскольку мы можем создавать множество простых отчетов и инкапсулировать их в основной отчет. Подотчеты составляются и заполняются как обычные отчеты. Любой шаблон отчета может быть использован в качестве вложенного отчета, когда включен в другой шаблон отчета, без каких-либо изменений внутри (шаблона отчета).

Вложенные отчеты похожи на обычные шаблоны отчетов. На самом деле это объекты net.sf.jasperreports.engine.JasperReport , которые получаются после компиляции объекта net.sf.jasperreports.engine.design.JasperDesign .

Элемент <subreport>
Элемент <subreport> используется при добавлении подотчетов в основные отчеты. Вот список подэлементов в элементе <subreport> JRXML.

<ReportElement>

<parametersMapExpression> — используется для передачи карты, содержащей параметры отчета, в подотчет. Карта обычно получается из параметра в основном отчете или с помощью встроенного параметра REPORTS_PARAMETERS_MAP для передачи параметров родительского отчета во вложенный отчет. Это выражение всегда должно возвращать объект java.util.Map, ключами которого являются имена параметров.

<subreportParameter> — этот элемент используется для передачи параметров в подотчет. У него есть имя атрибута, которое является обязательным.

<connectionExpression> — используется для передачи java.sql.Connection в подотчет. Он используется только тогда, когда шаблону подотчета требуется соединение с базой данных на этапе заполнения отчета.

<dataSourceExpression> — используется для передачи источника данных в подотчет. Этот источник данных обычно получают из параметра в главном отчете или с помощью встроенного параметра REPORT_DATA_SOURCE для передачи источника данных родительского отчета в подотчет.

Элементы ( connectionExpression и dataSourceExpression ) не могут присутствовать одновременно в объявлении элемента <subreport>. Это связано с тем, что мы не можем предоставить источник данных и соединение с вложенным отчетом. Мы должны определиться с одним из них и придерживаться его.

<returnValue> — используется для присвоения значения одной из переменных подотчета одной из переменных основного отчета. Этот подэлемент имеет следующие атрибуты:

subreportVariable — Этот атрибут указывает имя переменной подотчета, значение которой должно быть возвращено.

toVariable — этот атрибут задает имя родительской переменной отчета, значение которой нужно скопировать / увеличить со значением из подотчета.

Вычисление — Этот атрибут может принимать значения: Ничего, Подсчет, DistinctCount, Сумма, Среднее, Самое низкое, Самое высокое, Стандартное отклонение, Дисперсия. Значение по умолчанию для расчета атрибута — «Ничего».

incrementerFactoryClass — этот атрибут указывает класс фабрики для создания экземпляра инкремента.

<subreportExpression> — указывает, где найти шаблон скомпилированного отчета для вложенного отчета. Этот элемент имеет атрибут класса . Атрибут класса может принимать любое из следующих значений: java.lang.String, java.io.File, java.net.URL, java.io.InputStream, net.sf.jasperreports.engine.JasperReport. Значением по умолчанию является java.lang.String .

isUsingCache — это атрибут элемента <subreport>. Это логическое значение, при значении true механизм создания отчетов будет пытаться распознать ранее загруженные объекты шаблона подотчета, используя их указанный источник. Эта функция кэширования доступна только для элементов подотчета, в которых выражения, возвращающие объекты java.lang.String в качестве источника шаблона подотчета, представляют имена файлов, URL-адреса или ресурсы пути к классам.

<ReportElement>

<parametersMapExpression> — используется для передачи карты, содержащей параметры отчета, в подотчет. Карта обычно получается из параметра в основном отчете или с помощью встроенного параметра REPORTS_PARAMETERS_MAP для передачи параметров родительского отчета во вложенный отчет. Это выражение всегда должно возвращать объект java.util.Map, ключами которого являются имена параметров.

<subreportParameter> — этот элемент используется для передачи параметров в подотчет. У него есть имя атрибута, которое является обязательным.

<connectionExpression> — используется для передачи java.sql.Connection в подотчет. Он используется только тогда, когда шаблону подотчета требуется соединение с базой данных на этапе заполнения отчета.

<dataSourceExpression> — используется для передачи источника данных в подотчет. Этот источник данных обычно получают из параметра в главном отчете или с помощью встроенного параметра REPORT_DATA_SOURCE для передачи источника данных родительского отчета в подотчет.

Элементы ( connectionExpression и dataSourceExpression ) не могут присутствовать одновременно в объявлении элемента <subreport>. Это связано с тем, что мы не можем предоставить источник данных и соединение с вложенным отчетом. Мы должны определиться с одним из них и придерживаться его.

<returnValue> — используется для присвоения значения одной из переменных подотчета одной из переменных основного отчета. Этот подэлемент имеет следующие атрибуты:

subreportVariable — Этот атрибут указывает имя переменной подотчета, значение которой должно быть возвращено.

toVariable — этот атрибут задает имя родительской переменной отчета, значение которой нужно скопировать / увеличить со значением из подотчета.

Вычисление — Этот атрибут может принимать значения: Ничего, Подсчет, DistinctCount, Сумма, Среднее, Самое низкое, Самое высокое, Стандартное отклонение, Дисперсия. Значение по умолчанию для расчета атрибута — «Ничего».

incrementerFactoryClass — этот атрибут указывает класс фабрики для создания экземпляра инкремента.

<subreportExpression> — указывает, где найти шаблон скомпилированного отчета для вложенного отчета. Этот элемент имеет атрибут класса . Атрибут класса может принимать любое из следующих значений: java.lang.String, java.io.File, java.net.URL, java.io.InputStream, net.sf.jasperreports.engine.JasperReport. Значением по умолчанию является java.lang.String .

isUsingCache — это атрибут элемента <subreport>. Это логическое значение, при значении true механизм создания отчетов будет пытаться распознать ранее загруженные объекты шаблона подотчета, используя их указанный источник. Эта функция кэширования доступна только для элементов подотчета, в которых выражения, возвращающие объекты java.lang.String в качестве источника шаблона подотчета, представляют имена файлов, URL-адреса или ресурсы пути к классам.

пример
Давайте рассмотрим простой пример, демонстрирующий создание вложенных отчетов с использованием JRDataSource. Давайте сначала напишем два новых шаблона отчета, один из которых будет подчиненным, а другой — основным отчетом. Содержимое шаблона подотчета (address_report_template.jrxml) приведено ниже. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test.

<?xml version = "1.0" encoding = "UTF-8"?>
<jasperReport
   xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "address_report_template" pageWidth = "175" pageHeight = "842" 
   columnWidth = "175" leftMargin = "0" rightMargin = "0" 
   topMargin = "0" bottomMargin = "0">

   <field name = "city" class = "java.lang.String"/>
   <field name = "street" class = "java.lang.String"/>
   
   <background>
      <band splitType = "Stretch"/>
   </background>
   
   <title>
      <band height = "20" splitType = "Stretch">
         
         <staticText>
            <reportElement x = "0" y = "0" width = "100" height = "20"/>
            
            <textElement>
               <font size = "14" isBold = "true"/>
            </textElement>
				
            <text><![CDATA[Addresses]]></text>
         </staticText>
      
      </band>
   </title>
   
   <pageHeader>
      <band height = "12" splitType = "Stretch"/>
   </pageHeader>
   
   <columnHeader>
      <band height = "12" splitType = "Stretch"/>
   </columnHeader>
   
   <detail>
      <band height = "27" splitType = "Stretch">
         
         <textField>
            <reportElement x = "0" y = "0" width = "120" height = "20"/>
            
            <textElement>
               <font size = "12" isBold = "true"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{city}+" Address:"]]>
            </textFieldExpression>
         </textField>
         
         <textField isStretchWithOverflow = "true">
            <reportElement x = "120" y = "0" width = "435" height = "20"/>
            
            <textElement>
               <font size = "12"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{street}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </detail>
   
   <columnFooter>
      <band height = "8" splitType = "Stretch"/>
   </columnFooter>
  
   <pageFooter>
      <band height = "11" splitType = "Stretch"/>
   </pageFooter>
   
   <summary>
      <band height = "9" splitType = "Stretch"/>
   </summary>

</jasperReport>
Поскольку мы используем источник данных, нам нужно написать соответствующий файл POJO SubReportBean.java, как показано ниже. Сохраните его в каталог C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint —

package com.tutorialspoint;

public class SubReportBean {
   private String city;
   private String street;

   public String getCity() {
      return city;
   }

   public void setCity(String city) {
      this.city = city;
   }

   public String getStreet() {
      return street;
   }

   public void setStreet(String street) {
      this.street = street;
   }
}
Здесь мы объявили два поля ‘city’ и ‘street’ и определили соответствующие методы getter и setter.

Теперь давайте обновим наш существующий файл DataBean . Мы добавим новое поле subReportBeanList , которое является java.util.List. Это поле будет содержать список объектов SubReportBean. Содержимое файла DataBean приведено ниже. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint.

package com.tutorialspoint;

import java.util.List;

public class DataBean {
   private String name;
   private String country;
   private List<SubReportBean> subReportBeanList;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }

   public List<SubReportBean> getSubReportBeanList() {
      return subReportBeanList;
   }

   public void setSubReportBeanList(List<SubReportBean> subReportBeanList) {
      this.subReportBeanList = subReportBeanList;
   }
}
Давайте теперь обновим файл C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java . Содержимое этого файла как —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {

      // Create sub report data
      SubReportBean subBean1 = new SubReportBean();
      subBean1.setCity("Mumbai");
      subBean1.setStreet("M.G.Road");
      SubReportBean subBean2 = new SubReportBean();
      subBean2.setCity("New York");
      subBean2.setStreet("Park Street");
      SubReportBean subBean3 = new SubReportBean();
      subBean3.setCity("San Fransisco");
      subBean3.setStreet("King Street");

      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      // Create master report data
      dataBeanList.add(produce("Manisha", "India",
         Arrays.asList(subBean1)));
      dataBeanList.add(produce("Dennis Ritchie", "USA",
         Arrays.asList(subBean2)));
      dataBeanList.add(produce("V.Anand", "India",
         Arrays.asList(subBean1)));
      dataBeanList.add(produce("Shrinath", "California",
         Arrays.asList(subBean3)));

      return dataBeanList;
   }

   /*
    * This method returns a DataBean object,
    * with name, country and sub report
    * bean data set in it.
    */
   private DataBean produce(String name, String country,
      List<SubReportBean> subBean) {
      DataBean dataBean = new DataBean();

      dataBean.setName(name);
      dataBean.setCountry(country);
      dataBean.setSubReportBeanList(subBean);

      return dataBean;
   }
}
В методе yield () в приведенном выше файле мы устанавливаем список SubReportBean.

## Теперь давайте напишем новый шаблон основного отчета (jasper_report_template.jrxml). 
Сохраните этот файл в каталоге C: \ tools \ jasperreports-5.0.1 \ test . Содержимое этого файла:

<?xml version = "1.0" encoding = "UTF-8"?>
<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth ="555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20">

   <parameter name = "SUBREPORT_DIR" class = "java.lang.String" isForPrompting = "false">
      <defaultValueExpression>
         <![CDATA["C:\\tools\\jasperreports-5.0.1\\test\\"]]>
      </defaultValueExpression>
   </parameter>
   
   <field name = "country" class = "java.lang.String"/>
   <field name = "name" class = "java.lang.String"/>
   <field name = "subReportBeanList" class = "java.util.List"/>
   
   <background>
      <band splitType = "Stretch"/>
   </background>
   
   <title>
      <band height = "35" splitType = "Stretch">
         
         <staticText>
            <reportElement x = "0" y = "0" width = "204" height = "34"/>
            
            <textElement>
               <font size = "26" isBold = "true"/>
            </textElement>
				
            <text><![CDATA[Contact Report]]></text>
         </staticText>
      
      </band>
   </title>
   
   <pageHeader>
      <band height = "17" splitType = "Stretch"/>
   </pageHeader>
   
   <columnHeader>
      <band height = "21" splitType = "Stretch"/>
   </columnHeader>
   
   <detail>
      <band height = "112" splitType = "Stretch">
            
         <staticText>
            <reportElement x = "0" y = "0" width = "100" height = "20"/>
            
            <textElement>
               <font size = "12" isBold = "true"/>
            </textElement>
				
            <text><![CDATA[Name:]]></text>
         </staticText>
         
         <staticText>
            <reportElement x = "0" y = "20" width = "100" height = "20"/>
            
            <textElement>
               <font size = "12" isBold = "true"/>
            </textElement>
				
            <text><![CDATA[Country:]]></text>
         </staticText>
         
         <textField>
            <reportElement x = "104" y = "0" width = "277" height = "20"/>
            
            <textElement>
               <font size = "12"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{name}]]>
            </textFieldExpression>
         </textField>
         
         <textField>
            <reportElement x = "104" y = "20" width = "277" height = "20"/>
            
            <textElement>
               <font size = "12"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$F{country}]]>
            </textFieldExpression>
         </textField>
         
         <subreport>
            <reportElement positionType = "Float" x = "335" y = "25" width = "175"
               height = "20" isRemoveLineWhenBlank = "true" backcolor = "#99ccff"/>

            <dataSourceExpression>
               new net.sf.jasperreports.engine.data.JRBeanCollectionDataSource
                  ($F{subReportBeanList})
            </dataSourceExpression>
            
            <subreportExpression class = "java.lang.String">
               <![CDATA[$P{SUBREPORT_DIR} + "address_report_template.jasper"]]>
            </subreportExpression>
         </subreport>
         
         <line>
            <reportElement x = "0" y = "50" width = "550" height = "1"/>
         </line>
      
      </band>
   </detail>
   
   <columnFooter>
      <band height = "19" splitType = "Stretch"/>
   </columnFooter>
   
   <pageFooter>
      <band height = "18" splitType = "Stretch"/>
   </pageFooter>
   
   <summary>
      <band height = "14" splitType = "Stretch"/>
   </summary>

</jasperReport>
В приведенном выше шаблоне мы определили новый параметр «SUBREPORT_DIR», который определяет путь к подотчету. Мы определили поле subReportBeanList типа java.util.List, которое соответствует свойству в файле DataBean. Элемент <subreport> имеет вложенный элемент <dataSourceExpression>. Мы поместили список subReportBeanList в экземпляр JRBeanCollectionDataSource. В подэлементе <subreportExpression /> мы дали имя подотчета (AddressReport.jasper).

Теперь давайте напишем новый класс CreateReport для компиляции и выполнения нашего шаблона отчета. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ CreateReport.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperCompileManager;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.JasperReport;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class CreateReport {

   public static void main(String[] args) {
      String masterReportFileName = "C://tools/jasperreports-5.0.1/test"
         + "/jasper_report_template.jrxml";
      String subReportFileName = "C://tools/jasperreports-5.0.1/test"
         + "/AddressReport.jrxml";
      String destFileName = "C://tools/jasperreports-5.0.1/test"
         + "/jasper_report_template.JRprint";
			
      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();
      JRBeanCollectionDataSource beanColDataSource = new 
         JRBeanCollectionDataSource(dataList);

      try {
         /* Compile the master and sub report */
         JasperReport jasperMasterReport = JasperCompileManager
            .compileReport(masterReportFileName);
         JasperReport jasperSubReport = JasperCompileManager
            .compileReport(subReportFileName);

         Map<String, Object> parameters = new HashMap<String, Object>();
         parameters.put("subreportParameter", jasperSubReport);
         JasperFillManager.fillReportToFile(jasperMasterReport, 
            destFileName, parameters, beanColDataSource);

      } catch (JRException e) {

         e.printStackTrace();
      }
      System.out.println("Done filling!!! ...");
   }
}
Здесь мы видим, что мы компилируем шаблоны основного и вложенного отчета и передаем файл основного отчета (.jasper) для заполнения отчета.

Генерация отчетов
Теперь все наши файлы готовы, давайте скомпилируем и выполним их, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml взят из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview the 
      report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
		
   </target>

</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.CreateReport (viewFullReport — цель по умолчанию) следующим образом:

Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28: 
      warning: 'includeantruntime' was not set, defaulting to
   [javac] Compiling 7 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig 
      for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\
      jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.CreateReport
   [java] Compiling Report Design ...
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [java] log4j:WARN Please initialize the log4j system properly.
   [java] Done filling!!! ...

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 72 minutes 13 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —

Jasper SubReport Пример

Здесь мы видим, что отображаются атрибуты Имя, Страна и Адрес.

#Создание диаграмм
Ранее людям приходилось полагаться на скриптлеты для сбора данных диаграммы и визуализации диаграммы с использованием элемента изображения в шаблоне отчета. JasperReports упрощает задачу, поскольку в него встроена поддержка диаграмм с использованием нового компонента диаграммы.

Используя новый компонент диаграммы, пользователь должен применять только визуальные параметры и определять выражения, которые помогут построить набор данных диаграммы. JasperReports использует JFreeChart в качестве базовой библиотеки диаграмм. При настройке нового компонента диаграммы участвуют следующие три компонента:

Общий компонент диаграммы.

Набор данных диаграммы (который группирует настройки, связанные с данными диаграммы).

График диаграммы (который группирует визуальные настройки, связанные с отображением элементов диаграммы).

Общий компонент диаграммы.

Набор данных диаграммы (который группирует настройки, связанные с данными диаграммы).

График диаграммы (который группирует визуальные настройки, связанные с отображением элементов диаграммы).

JasperReports в настоящее время поддерживает следующие типы диаграмм: круговая диаграмма, круговая диаграмма 3D, линейка, линейчатая 3D, линейка XY, линейчатая диаграмма с накоплением, линейчатая трехмерная диаграмма, линия, линейная ось XY, площадь, область XY, многоуровневая область, разброс, пузырь, временные ряды, высокая -Низкое-открытое-закрытое, подсвечник, несколько осей, метр, термометр и гантт.

## Свойства диаграммы
Диаграммы являются обычными элементами отчета, поэтому некоторые свойства их разделяют со всеми остальными элементами отчета. Существует элемент JRXML с именем < chart >, используемый для создания всех типов диаграмм. Этот элемент группирует специальные специфичные для диаграммы настройки, которые применяются ко всем типам диаграмм.

Подэлементы диаграммы
Подэлементами элемента <chart> являются —

<reportElement> — это отображаемые объекты, такие как статические тексты, текстовые поля, изображения, линии и прямоугольники, которые вы помещаете в разделы шаблона отчета.

<Box> — этот элемент используется для окружения диаграмм границей, настраиваемой с каждой стороны.

<chartTitle> — этот элемент используется для размещения заголовка диаграммы. Атрибут position определяет положение заголовка диаграммы в отчете. Этот элемент имеет атрибуты — Position (значения могут быть Top , Bottom , Left , Right . Значение по умолчанию — Top ), color . <chartTitle> имеет шрифт и titleExpression в качестве подэлементов.

<chartSubtitle> — этот элемент используется для размещения субтитров диаграммы. Этот элемент имеет атрибут — цвет . <chartSubtitle> содержит шрифт и выражение subtitleExpression в качестве подэлементов.

<chartLegend> — элемент может управлять связанными со шрифтом свойствами, а также цветом текста и цветом фона легенды диаграммы, используя этот элемент. Этот элемент имеет атрибуты — textColor и backgroundColor .

<anchorNameExpression> — этот элемент создает цель для привязки.

<hyperlinkReferenceExpression> — этот элемент содержит выражение отчета, указывающее имя внешнего ресурса (обычно URL).

<hyperlinkAnchorExpression> — гиперссылка указывает на привязку во внешнем ресурсе.

<hyperlinkPageExpression> — гиперссылка указывает на страницу в текущем отчете.

<hyperlinkTooltipExpression> — этот элемент управляет всплывающей подсказкой гиперссылки. Тип выражения должен быть java.lang.String .

<hyperlinkParameter> — этот элемент, если он присутствует, генерирует окончательную гиперссылку в зависимости от значений параметра.

<reportElement> — это отображаемые объекты, такие как статические тексты, текстовые поля, изображения, линии и прямоугольники, которые вы помещаете в разделы шаблона отчета.

<Box> — этот элемент используется для окружения диаграмм границей, настраиваемой с каждой стороны.

<chartTitle> — этот элемент используется для размещения заголовка диаграммы. Атрибут position определяет положение заголовка диаграммы в отчете. Этот элемент имеет атрибуты — Position (значения могут быть Top , Bottom , Left , Right . Значение по умолчанию — Top ), color . <chartTitle> имеет шрифт и titleExpression в качестве подэлементов.

<chartSubtitle> — этот элемент используется для размещения субтитров диаграммы. Этот элемент имеет атрибут — цвет . <chartSubtitle> содержит шрифт и выражение subtitleExpression в качестве подэлементов.

<chartLegend> — элемент может управлять связанными со шрифтом свойствами, а также цветом текста и цветом фона легенды диаграммы, используя этот элемент. Этот элемент имеет атрибуты — textColor и backgroundColor .

<anchorNameExpression> — этот элемент создает цель для привязки.

<hyperlinkReferenceExpression> — этот элемент содержит выражение отчета, указывающее имя внешнего ресурса (обычно URL).

<hyperlinkAnchorExpression> — гиперссылка указывает на привязку во внешнем ресурсе.

<hyperlinkPageExpression> — гиперссылка указывает на страницу в текущем отчете.

<hyperlinkTooltipExpression> — этот элемент управляет всплывающей подсказкой гиперссылки. Тип выражения должен быть java.lang.String .

<hyperlinkParameter> — этот элемент, если он присутствует, генерирует окончательную гиперссылку в зависимости от значений параметра.



## Атрибуты диаграммы
Атрибуты в элементе <chart>, доступные для всех типов диаграмм:

isShowLegend — этот атрибут используется для определения того, будет ли отображаться легенда диаграммы в отчете. Значения могут быть истинными или ложными . По умолчанию установлено значение true .

valuationTime — Определяет, когда выражение диаграммы будет оценено. Значения могут быть сейчас , отчет , страница , столбец , группа , группа . Значение по умолчанию сейчас .

valuationGroup — этот атрибут определяет имя группы, которая будет использоваться для оценки выражений диаграммы. Значение этого атрибута должно соответствовать названию группы, которое мы хотели бы использовать в качестве группы оценки диаграммы.

hyperlinkType — этот атрибут может содержать любое текстовое значение. Значением по умолчанию является None . Это означает, что ни текстовые поля, ни изображения не представляют гиперссылки, даже если присутствуют специальные выражения гиперссылки.

hyperlinkTarget — этот атрибут помогает настроить поведение указанной ссылки при ее нажатии в средстве просмотра. Значения могут быть Self или Blank . Значением по умолчанию является Self .

bookmarkLevel — этот атрибут, если задано положительное целое число, создает закладки в отчетах, экспортируемых в PDF. Значение по умолчанию 0 .

customizerClass — это имя класса (необязательно), которое можно использовать для настройки диаграммы. Значением этого элемента должна быть строка, содержащая имя класса настройщика.

isShowLegend — этот атрибут используется для определения того, будет ли отображаться легенда диаграммы в отчете. Значения могут быть истинными или ложными . По умолчанию установлено значение true .

valuationTime — Определяет, когда выражение диаграммы будет оценено. Значения могут быть сейчас , отчет , страница , столбец , группа , группа . Значение по умолчанию сейчас .

valuationGroup — этот атрибут определяет имя группы, которая будет использоваться для оценки выражений диаграммы. Значение этого атрибута должно соответствовать названию группы, которое мы хотели бы использовать в качестве группы оценки диаграммы.

hyperlinkType — этот атрибут может содержать любое текстовое значение. Значением по умолчанию является None . Это означает, что ни текстовые поля, ни изображения не представляют гиперссылки, даже если присутствуют специальные выражения гиперссылки.

hyperlinkTarget — этот атрибут помогает настроить поведение указанной ссылки при ее нажатии в средстве просмотра. Значения могут быть Self или Blank . Значением по умолчанию является Self .

bookmarkLevel — этот атрибут, если задано положительное целое число, создает закладки в отчетах, экспортируемых в PDF. Значение по умолчанию 0 .

customizerClass — это имя класса (необязательно), которое можно использовать для настройки диаграммы. Значением этого элемента должна быть строка, содержащая имя класса настройщика.

## Настройка диаграммы
Как упоминалось выше, JasperReports использует JFreeChart в качестве базовой библиотеки диаграмм. JFreeChart содержит функции, которые напрямую не поддерживаются JasperReports. Мы можем воспользоваться этими функциями, предоставив класс настройщика через атрибут customizerClass в элементе <chart>. Класс настройщика — это ничто иное, как реализация интерфейса net.sf.jasperreports.engine.JRChartCustomizer . Самый простой способ реализовать этот интерфейс — расширить класс net.sf.jasperreports.engine.JRAbstractChartCustomizer и, таким образом, получить доступ к параметрам, полям и переменным для более гибкой настройки диаграммы на основе данных отчета.

Наборы диаграмм
Одним из общих свойств для всех типов диаграмм является элемент < dataset >. Наборы данных диаграммы помогают отображать данные отчета и получать данные диаграммы во время выполнения. Каждый тип диаграммы содержит различные подэлементы для определения выражений диаграммы. Эти выражения определяют данные, используемые для создания диаграммы. Все эти подэлементы содержат элемент <dataset>, который определяет, когда выражения диаграммы вычисляются и сбрасываются.

В JasperReports доступно несколько типов наборов данных диаграмм, поскольку каждый тип диаграмм работает с определенными наборами данных: круговая диаграмма, категория, XY, временной ряд, период времени, XYZ и High-Low. Каждый из этих типов наборов данных реализует интерфейс net.sf.jasperreports.engine.JRChartDataset, который определяет наборы данных диаграммы. Все наборы данных диаграммы инициализируются и увеличиваются одинаково; однако они отличаются только типом данных или сериями данных, которые они отображают.



# Свойства набора данных
## Атрибуты элемента <dataset> —

атрибут	Описание	Ценности
resetType	Этот атрибут определяет, когда значение выражения диаграммы должно быть сброшено.	Нет, Отчет, Страница, Колонка, Группа. Значением по умолчанию является Отчет .
resetGroup	Этот атрибут определяет имя группы, в которой значение выражения диаграммы сбрасывается.	Значение этого атрибута должно совпадать с именем любой группы, объявленной в шаблоне отчета JRXML.
incrementType	Этот атрибут определяет, когда следует пересчитать значение выражения диаграммы.	Нет, Отчет, Страница, Колонка, Группа. Значением по умолчанию является «Нет» .
incrementGroup	Этот атрибут определяет имя группы, в которой выражение диаграммы пересчитывается.	Значение этого атрибута должно совпадать с именем группы, объявленной в шаблоне отчета JRXML.
В следующей таблице приведены подэлементы элемента <dataset> —

Подэлемент	Описание
<IncrementWhenExpression>	Способ увеличения набора данных диаграммы может быть настроен путем фильтрации нежелательных данных с помощью этого подэлемента.
<DatasetRun>	Он содержит информацию, необходимую для создания экземпляра поднабора отчетов.
Типы наборов данных
Конкретные типы наборов данных описаны ниже —

Набор данных пирога
Круговой набор данных характеризуется следующими выражениями —

<keyExpression> — представляет категории, которые будут составлять срезы на круговой диаграмме. Это выражение может возвращать любой объект java.lang.Comparable.

<valueExpression> — создает значения, которые соответствуют каждой категории / ключу в наборе данных. Значения всегда являются объектами java.lang.Number.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого среза на круговой диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для круговой диаграммы.

<sectionHyperlink> — устанавливает гиперссылки, связанные с круговыми секциями.

<keyExpression> — представляет категории, которые будут составлять срезы на круговой диаграмме. Это выражение может возвращать любой объект java.lang.Comparable.

<valueExpression> — создает значения, которые соответствуют каждой категории / ключу в наборе данных. Значения всегда являются объектами java.lang.Number.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого среза на круговой диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для круговой диаграммы.

<sectionHyperlink> — устанавливает гиперссылки, связанные с круговыми секциями.

Набор данных категории
Набор данных категории характеризуется элементом <categorySeries>, который содержит —

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<categoryExpression> — возвращает имя категории для каждого значения в серии, указанной в выражении серии. Категории являются java.lang. Сопоставимые объекты.

<valueExpression> — создает значения, которые соответствуют каждой категории в наборе данных. Значения всегда являются объектами java.lang.Number.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<categoryExpression> — возвращает имя категории для каждого значения в серии, указанной в выражении серии. Категории являются java.lang. Сопоставимые объекты.

<valueExpression> — создает значения, которые соответствуют каждой категории в наборе данных. Значения всегда являются объектами java.lang.Number.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

Набор данных XY
Набор данных XY характеризуется элементом <xySeries>, который содержит —

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<xValueExpression> — возвращает значение java.lang.Number, представляющее значение X из пары (x, y), которая будет добавлена ​​в текущий ряд данных.

<yValueExpression> — возвращает значение java.lang.Number, представляющее значение Y из пары (x, y), которая будет добавлена ​​в текущий ряд данных.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<xValueExpression> — возвращает значение java.lang.Number, представляющее значение X из пары (x, y), которая будет добавлена ​​в текущий ряд данных.

<yValueExpression> — возвращает значение java.lang.Number, представляющее значение Y из пары (x, y), которая будет добавлена ​​в текущий ряд данных.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

Набор данных XYZ
Набор данных XYZ характеризуется элементом <xyzSeries>, который содержит —

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<xValueExpression> — возвращает значение java.lang.Number, представляющее значение X из элемента (x, y, z), который будет добавлен в текущий ряд данных.

<yValueExpression> — возвращает значение java.lang.Number, представляющее значение Y из элемента (x, y, z), который будет добавлен в текущий ряд данных.

<zValueExpression> — возвращает значение java.lang.Number, представляющее значение Z из элемента (x, y, z), который будет добавлен в текущий ряд данных.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<xValueExpression> — возвращает значение java.lang.Number, представляющее значение X из элемента (x, y, z), который будет добавлен в текущий ряд данных.

<yValueExpression> — возвращает значение java.lang.Number, представляющее значение Y из элемента (x, y, z), который будет добавлен в текущий ряд данных.

<zValueExpression> — возвращает значение java.lang.Number, представляющее значение Z из элемента (x, y, z), который будет добавлен в текущий ряд данных.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

Набор данных временного ряда
Набор данных временного ряда характеризуется атрибутом timePeriod и элементом <timeSeries>. Атрибут timePeriod указывает тип ряда данных в наборе данных. Временные ряды могут содержать числовые значения, связанные с днями, месяцами, годами или другими предварительно определенными периодами времени. Возможные значения: год, квартал, месяц, неделя, день — это значение по умолчанию, час, минута, секунда, миллисекунда.

Элемент <timeSeries> содержит —

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<timePeriodExpression> — возвращает значение java.util.Date, из которого механизм извлекает соответствующий период времени в зависимости от значения, установленного для атрибута timePeriod, упомянутого выше.

<valueExpression> — возвращает значение java.lang.Number, которое связывается с соответствующим значением периода времени при увеличении текущей серии набора данных.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<timePeriodExpression> — возвращает значение java.util.Date, из которого механизм извлекает соответствующий период времени в зависимости от значения, установленного для атрибута timePeriod, упомянутого выше.

<valueExpression> — возвращает значение java.lang.Number, которое связывается с соответствующим значением периода времени при увеличении текущей серии набора данных.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

Набор данных периода времени
Набор данных периода времени характеризуется элементом <timePeriodSeries>, который содержит —

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<startDateExpression> — указывает начало интервала даты, с которым будет связано числовое значение при его добавлении в ряд периода времени.

<endDateExpression> — указывает конец интервала даты, с которым будет связано числовое значение при его добавлении в ряд периода времени.

<valueExpression> — возвращает значение java.lang.Number, связанное с текущим интервалом дат, указанным в выражениях даты начала и окончания.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

<seriesExpression> — указывает название серии. Это выражение может возвращать любой объект java.lang.Comparable.

<startDateExpression> — указывает начало интервала даты, с которым будет связано числовое значение при его добавлении в ряд периода времени.

<endDateExpression> — указывает конец интервала даты, с которым будет связано числовое значение при его добавлении в ряд периода времени.

<valueExpression> — возвращает значение java.lang.Number, связанное с текущим интервалом дат, указанным в выражениях даты начала и окончания.

<labelExpression> — если это выражение отсутствует, на диаграмме будут отображаться метки по умолчанию для каждого элемента на диаграмме. Используйте это выражение, которое возвращает значения java.lang.String, чтобы настроить метки элементов для диаграммы.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

Высокий низкий набор данных
Высокий низкий набор данных характеризуется следующими выражениями —

<seriesExpression> — в настоящее время поддерживается только одна серия на графике High-Low или Candlestick. Однако этот отдельный ряд должен быть идентифицирован значением java.lang.Comparable, возвращаемым этим выражением, и его также следует использовать в качестве имени ряда в легенде диаграммы.

<dateExpression> — возвращает дату, к которой относится текущий элемент (максимум, минимум, открытие, закрытие, объем).

<highExpression> — возвращает значение java.lang.Number, которое будет частью элемента данных, добавляемого в серию при увеличении набора данных.

<lowExpression> — возвращает значение java.lang.Number, которое будет частью элемента данных, добавляемого в серию при увеличении набора данных.

<openExpression> — возвращает значение java.lang.Number, которое будет частью элемента данных, добавляемого в серию при увеличении набора данных.

<closeExpression> — возвращает значение java.lang.Number, которое будет частью элемента данных, добавляемого в серию при увеличении набора данных.

<volumeExpression> — числовое выражение, которое возвращает значение тома, используемое для текущего элемента данных. Используется только для свечных графиков.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

<seriesExpression> — в настоящее время поддерживается только одна серия на графике High-Low или Candlestick. Однако этот отдельный ряд должен быть идентифицирован значением java.lang.Comparable, возвращаемым этим выражением, и его также следует использовать в качестве имени ряда в легенде диаграммы.

<dateExpression> — возвращает дату, к которой относится текущий элемент (максимум, минимум, открытие, закрытие, объем).

<highExpression> — возвращает значение java.lang.Number, которое будет частью элемента данных, добавляемого в серию при увеличении набора данных.

<lowExpression> — возвращает значение java.lang.Number, которое будет частью элемента данных, добавляемого в серию при увеличении набора данных.

<openExpression> — возвращает значение java.lang.Number, которое будет частью элемента данных, добавляемого в серию при увеличении набора данных.

<closeExpression> — возвращает значение java.lang.Number, которое будет частью элемента данных, добавляемого в серию при увеличении набора данных.

<volumeExpression> — числовое выражение, которое возвращает значение тома, используемое для текущего элемента данных. Используется только для свечных графиков.

<itemHyperlink> — устанавливает гиперссылки, связанные с элементами диаграммы.

Набор данных значения
Это специальная реализация набора данных диаграмм, которая содержит одно значение и используется для визуализации диаграмм «Метр» и «Термометр». Значение собирается с использованием выражения <valueExpression>.

Графики
Другим распространенным элементом JRXML для всех типов диаграмм является элемент < plot >. Это позволяет нам определить некоторые характеристики диаграммы, такие как ориентация и цвет фона. Графики различаются в зависимости от типа диаграммы.

Атрибут Участка
В приведенной ниже таблице обобщены атрибуты элемента <plot> —

атрибут	Описание	Ценности
BackColor	Этот атрибут определяет цвет фона диаграммы.	Любое шестизначное шестнадцатеричное значение является допустимым значением для этого атрибута. Шестнадцатеричное значение должно предшествовать #.
ориентация	Этот атрибут определяет ориентацию диаграммы.	Горизонтальный, вертикальный Значение по умолчанию «Вертикальный»
backgroundAlpha	Этот атрибут определяет прозрачность цвета фона диаграммы.	Допустимые значения для этого атрибута включают любое десятичное число от 0 до 1 включительно. Чем выше число, тем менее прозрачным будет фон. Значением по умолчанию является «1».
foregroundAlpha	Этот атрибут определяет прозрачность цветов переднего плана диаграммы.	Допустимые значения для этого атрибута включают любое десятичное число от 0 до 1 включительно. Чем выше число, тем менее прозрачным будет фон. Значением по умолчанию является «1».
labelRotation	Этот атрибут позволяет вращать текстовые метки на оси X, чтобы вращать по часовой стрелке или против часовой стрелки. Этот атрибут применяется только к диаграммам, для которых ось x не является числовой или не отображает даты.	Значением по умолчанию является «0,0».
Элемент <plot> имеет подэлемент <seriesColor>, атрибутами которого являются: seriesOrder и color . Этот элемент настраивает цвета для серии и их положение в последовательности цветов.

Специальные настройки для графиков
piePlot — не имеет особых настроек

pie3DPlot — Содержит атрибут deepFactor , числовое значение в диапазоне от 0 до 1, которое представляет глубину круговой диаграммы в процентах от высоты области графика.

barPlot — можно отображать или скрывать метки, метки или метки элементов, а также предоставляет настройки для обеих осей.

bar3DPlot — обеспечивает те же настройки, что и barPlot, и генерирует 3D-эффект с использованием атрибутов xOffset и yOffset.

linePlot — можно показать или скрыть линии, соединяющие точки элемента, можно показать или скрыть фигуры, связанные с точками элемента, и предоставляет настройки для обеих осей.

scatterPlot — Подобно linePlot, он может отображать или скрывать линии, соединяющие точки элемента, может отображать или скрывать фигуры, связанные с точками элемента, и предоставляет настройки для обеих осей.

areaPlot — предоставляет настройки для обеих осей.

bubblePlot — можно установить размеры пузырьков, задав атрибут scaleType и предоставив настройки для обеих осей.

timeSeriesPlot — можно показать или скрыть линии, соединяющие точки элемента, можно показать или скрыть фигуры, связанные с точками элемента, и предоставляет параметры настройки для обеих осей.

highLowPlot — можно показать или скрыть открытые отметки, можно показать или скрыть закрывающие отметки и предоставляет настройки для обеих осей.

CandlePlot — можно показать или скрыть громкость, и предоставляет настройки для обеих осей.

meterPlot — содержит специальные настройки для формы циферблата, угла шкалы, единиц измерения, интервала тиков, цвета циферблата, цвета иглы, цвета тика, шрифта отображения цвета, шаблона цвета и формата, диапазона данных и интервалов измерителя.

thermometerPlot — содержит специальные настройки для местоположения значения, цвета ртути, отображения / скрытия линий значений, шрифта отображения значения, шаблона цвета и формата, диапазона данных, низкого диапазона, среднего диапазона и верхнего диапазона.

multiAxisChart — содержит специальные настройки для оси, включенной в график.

piePlot — не имеет особых настроек

pie3DPlot — Содержит атрибут deepFactor , числовое значение в диапазоне от 0 до 1, которое представляет глубину круговой диаграммы в процентах от высоты области графика.

barPlot — можно отображать или скрывать метки, метки или метки элементов, а также предоставляет настройки для обеих осей.

bar3DPlot — обеспечивает те же настройки, что и barPlot, и генерирует 3D-эффект с использованием атрибутов xOffset и yOffset.

linePlot — можно показать или скрыть линии, соединяющие точки элемента, можно показать или скрыть фигуры, связанные с точками элемента, и предоставляет настройки для обеих осей.

scatterPlot — Подобно linePlot, он может отображать или скрывать линии, соединяющие точки элемента, может отображать или скрывать фигуры, связанные с точками элемента, и предоставляет настройки для обеих осей.

areaPlot — предоставляет настройки для обеих осей.

bubblePlot — можно установить размеры пузырьков, задав атрибут scaleType и предоставив настройки для обеих осей.

timeSeriesPlot — можно показать или скрыть линии, соединяющие точки элемента, можно показать или скрыть фигуры, связанные с точками элемента, и предоставляет параметры настройки для обеих осей.

highLowPlot — можно показать или скрыть открытые отметки, можно показать или скрыть закрывающие отметки и предоставляет настройки для обеих осей.

CandlePlot — можно показать или скрыть громкость, и предоставляет настройки для обеих осей.

meterPlot — содержит специальные настройки для формы циферблата, угла шкалы, единиц измерения, интервала тиков, цвета циферблата, цвета иглы, цвета тика, шрифта отображения цвета, шаблона цвета и формата, диапазона данных и интервалов измерителя.

thermometerPlot — содержит специальные настройки для местоположения значения, цвета ртути, отображения / скрытия линий значений, шрифта отображения значения, шаблона цвета и формата, диапазона данных, низкого диапазона, среднего диапазона и верхнего диапазона.

multiAxisChart — содержит специальные настройки для оси, включенной в график.

Типы графиков
JasperReports предлагает встроенную поддержку для нескольких типов диаграмм. Они перечислены ниже:

pieChart — комбинация набора данных Pie и графика Pie.

pie3DChart — Группирует набор данных Pie и 3D-график Pie.

barChart — базовая комбинация набора данных категории и гистограммы.

bar3DChart — обертывает набор данных категории и трехмерный график Bar.

xyBarChart — поддерживает наборы данных периода времени, наборы данных временного ряда и наборы данных XY, а также использует гистограмму для визуализации оси и элементов.

stackedBarChart — использует данные из набора данных категории и отображает их содержимое с использованием гистограммы.

stackedBar3DChart — использует данные из набора данных «Категория» и отображает их содержимое, используя трехмерный график Bar.

lineChart — группирует набор данных категории и линейный график.

xyLineChart — группирует набор данных XY и линейный график.

areaChart — элементы из набора данных категории отображаются с использованием графика площади.

stackedAreaChart — элементы из набора данных категории отображаются с использованием графика площади.

xyAreaChart — использует данные из набора данных XY и отображает их на графике площади.

scatterChart — оборачивает набор данных XY в график рассеяния.

bubbleChart — объединяет набор данных XYZ с графиком Bubble.

timeSeriesChart — группирует набор данных временного ряда и график временного ряда.

highLowChart — комбинация набора данных High-Low и графика High-Low.

CandlestickChart — использует данные из набора данных High-Low, но со специальным графиком Candlestick.

meterChart — отображает одно значение из набора данных Value на циферблате, используя параметры рендеринга из графика Meter.

thermometerChart — отображает одно значение в наборе данных Value с использованием параметров рендеринга из графика термометра.

multiAxisChart — содержит несколько осей диапазона, все из которых имеют общую ось домена.

pieChart — комбинация набора данных Pie и графика Pie.

pie3DChart — Группирует набор данных Pie и 3D-график Pie.

barChart — базовая комбинация набора данных категории и гистограммы.

bar3DChart — обертывает набор данных категории и трехмерный график Bar.

xyBarChart — поддерживает наборы данных периода времени, наборы данных временного ряда и наборы данных XY, а также использует гистограмму для визуализации оси и элементов.

stackedBarChart — использует данные из набора данных категории и отображает их содержимое с использованием гистограммы.

stackedBar3DChart — использует данные из набора данных «Категория» и отображает их содержимое, используя трехмерный график Bar.

lineChart — группирует набор данных категории и линейный график.

xyLineChart — группирует набор данных XY и линейный график.

areaChart — элементы из набора данных категории отображаются с использованием графика площади.

stackedAreaChart — элементы из набора данных категории отображаются с использованием графика площади.

xyAreaChart — использует данные из набора данных XY и отображает их на графике площади.

scatterChart — оборачивает набор данных XY в график рассеяния.

bubbleChart — объединяет набор данных XYZ с графиком Bubble.

timeSeriesChart — группирует набор данных временного ряда и график временного ряда.

highLowChart — комбинация набора данных High-Low и графика High-Low.

CandlestickChart — использует данные из набора данных High-Low, но со специальным графиком Candlestick.

meterChart — отображает одно значение из набора данных Value на циферблате, используя параметры рендеринга из графика Meter.

thermometerChart — отображает одно значение в наборе данных Value с использованием параметров рендеринга из графика термометра.

multiAxisChart — содержит несколько осей диапазона, все из которых имеют общую ось домена.

пример
Чтобы продемонстрировать графики, напишем новый шаблон отчета (jasper_report_template.jrxml). Здесь мы добавим элемент <barChart> в раздел <pageHeader> и раздел < pieChart > в <summary>. Мы будем отображать в диаграммах оценки, полученные для каждого предмета. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test . Содержимое файла приведено ниже.

<?xml version = "1.0" encoding = "UTF-8"?>

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" pageWidth = "595" pageHeight = "860"
   columnWidth = "515" leftMargin = "40" rightMargin = "40"
   topMargin = "50" bottomMargin = "50">

   <field name = "subjectName" class = "java.lang.String"/>
   <field name = "marks" class = "java.lang.Integer"/>
   
   <variable name = "countNumber" class = "java.lang.Integer" calculation = "Count">
      <variableExpression>
         <![CDATA[Boolean.TRUE]]>
      </variableExpression>
   </variable>
   
   <background>
      <band splitType = "Stretch"/>
   </background>
   
   <title>
      <band height = "79" splitType = "Stretch"/>
   </title>
   
   <pageHeader>
      <band height = "200">
    
         <barChart>
            <chart evaluationTime = "Report">
               <reportElement x = "0" y = "0" width = "555" height = "200"/>
            
               <chartTitle>
                  <titleExpression>
                     <![CDATA["My First JR Bar Chart"]]>
                  </titleExpression>
               </chartTitle>
            </chart>
      
            <categoryDataset>
               <dataset incrementType = "None"/>
            
               <categorySeries>
                  <seriesExpression>
                     <![CDATA[$F{subjectName}]]>
                  </seriesExpression>
            
                  <categoryExpression>
                     <![CDATA[$F{subjectName}]]>
                  </categoryExpression>
            
                  <valueExpression>
                     <![CDATA[$F{marks}]]>
                  </valueExpression>

               </categorySeries>
            </categoryDataset>
      
            <barPlot isShowTickMarks = "false">
               <plot/>
            </barPlot>
         </barChart>
      
      </band>
   </pageHeader>
   
   <columnHeader>
      <band height = "20" splitType = "Stretch"/>
   </columnHeader>
   
   <detail>
      <band height = "20" splitType = "Stretch"/>
   </detail>
   
   <columnFooter>
      <band height = "20" splitType = "Stretch"/>
   </columnFooter>
   
   <pageFooter>
      <band height = "20" splitType = "Stretch"/>
   </pageFooter>
   
   <summary>
      <band height = "400" splitType = "Stretch">
      
         <pieChart>
            <chart evaluationTime = "Report">
               <reportElement x = "135" y = "0" width = "270" height = "300"/>
            
               <chartTitle>
                  <titleExpression>
                     <![CDATA["My First JR Pie Chart"]]>
                  </titleExpression>
               </chartTitle>
            </chart>
         
            <pieDataset>
               <dataset incrementType = "None"/>
               
               <keyExpression>
                  <![CDATA[$F{subjectName}]]>
               </keyExpression>
            
               <valueExpression>
                  <![CDATA[$F{marks}]]>
               </valueExpression>
            </pieDataset>
            
            <piePlot>
               <plot/>
               <itemLabel/>
            </piePlot>
         </pieChart>
      
      </band>
   </summary>
	
</jasperReport>
Детали вышеупомянутого файла как даны ниже —

Элементом JRXML, используемым для создания гистограммы, является </ barChart> в <pageHeader>. Он содержит подэлемент </ chart>, который содержит подэлемент <reportElement>, определяющий размеры и положение диаграммы.

Элемент <dataset> в линейчатой ​​диаграмме должен быть заключен между элементами <categoryDataset> и </ categoryDataset> JRXML.

<categoryDataset> должен содержать элемент <categorySeries>. Этот элемент определяет, какой элемент данных будут представлять столбцы (в данном примере имена субъектов).

<categoryDataset> также должен содержать элемент, который определяет, как данные будут разделены на категории для сравнения. Здесь данные разделены именами субъектов.

Элемент <valueExpression> определяет, какое выражение используется для определения значения каждого столбца на графике. Здесь мы используем «знаки».

Для круговой диаграммы мы использовали элемент <pieChart> в разделе <summary>. Он содержит подэлемент </ chart>.

Подэлемент содержит выражение отчета, указывающее, что использовать в качестве ключа на диаграмме. Здесь мы использовали subjectName.

Подэлемент содержит выражение, используемое для вычисления значения для ключа. Здесь мы использовали знаки.

Элементом JRXML, используемым для создания гистограммы, является </ barChart> в <pageHeader>. Он содержит подэлемент </ chart>, который содержит подэлемент <reportElement>, определяющий размеры и положение диаграммы.

Элемент <dataset> в линейчатой ​​диаграмме должен быть заключен между элементами <categoryDataset> и </ categoryDataset> JRXML.

<categoryDataset> должен содержать элемент <categorySeries>. Этот элемент определяет, какой элемент данных будут представлять столбцы (в данном примере имена субъектов).

<categoryDataset> также должен содержать элемент, который определяет, как данные будут разделены на категории для сравнения. Здесь данные разделены именами субъектов.

Элемент <valueExpression> определяет, какое выражение используется для определения значения каждого столбца на графике. Здесь мы используем «знаки».

Для круговой диаграммы мы использовали элемент <pieChart> в разделе <summary>. Он содержит подэлемент </ chart>.

Подэлемент содержит выражение отчета, указывающее, что использовать в качестве ключа на диаграмме. Здесь мы использовали subjectName.

Подэлемент содержит выражение, используемое для вычисления значения для ключа. Здесь мы использовали знаки.

Java-коды для заполнения отчетов остаются без изменений. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = 
         "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource = new 
         JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();

      try {
         JasperFillManager.fillReportToFile( sourceFileName,
            parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Поскольку мы будем отображать оценки, полученные по каждому предмету, POJO необходимо изменить. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java приведено ниже —

package com.tutorialspoint;

public class DataBean {
   private String subjectName;
   private Integer marks;

   public String getSubjectName() {
      return subjectName;
   }

   public void setSubjectName(String subjectName) {
      this.subjectName = subjectName;
   }

   public Integer getMarks() {
      return marks;
   }

   public void setMarks(Integer marks) {
      this.marks = marks;
   }

}
Даже содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java необходимо обновить, как указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("English", 58));
      dataBeanList.add(produce("SocialStudies", 68));
      dataBeanList.add(produce("Maths", 38));
      dataBeanList.add(produce("Hindi", 88));
      dataBeanList.add(produce("Scince", 78));
      
      return dataBeanList;
   }

   /*
    * This method returns a DataBean object, with subjectName ,
    * and marks set in it.
    */
   private DataBean produce(String subjectName, Integer marks) {
      DataBean dataBean = new DataBean();

      dataBean.setSubjectName(subjectName);
      dataBean.setMarks(marks);

      return dataBean;
   }
}
Генерация отчетов
Далее, давайте скомпилируем и выполним вышеуказанные файлы, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml взят из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview the 
      report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
		
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
			
         <classpath refid = "classpath" />
      </jrc>
   </target>

</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) следующим образом:

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defaulting to bu
   [javac] Compiling 3 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig 
      for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 19 minutes 45 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как на экране ниже —

Пример диаграммы Джаспера

Пример круговой диаграммы Джаспера

Здесь мы видим, что гистограмма создается в верхнем колонтитуле, а круговая диаграмма — в разделах сводки.

JasperReports — Кросс-таблицы
Кросс-таблицы (кросс-табулирования) — это отчеты, содержащие таблицы, в которых данные располагаются по строкам и столбцам в табличной форме. Объект кросс-таблицы используется для вставки отчета кросс-таблицы в основной отчет. Кросс-таблицы могут использоваться с любым уровнем данных (номинальным, порядковым, интервальным или относительным) и обычно отображать обобщенные данные, содержащиеся в переменных отчета, в форме динамической таблицы. Переменные используются для отображения агрегированных данных, таких как суммы, числа, средние значения.

Crosstab Properties
Элемент JRXML <crosstab> используется для вставки кросс-таблицы в отчет.

атрибут
Ниже приведен список атрибутов элемента < crosstab > —

isRepeatColumnHeaders — указывает, следует ли перепечатывать заголовки столбцов после разрыва страницы. Значением по умолчанию является true .

isRepeatRowHeaders — указывает, следует ли перепечатывать заголовки строк после разрыва столбца кросс-таблицы. Значением по умолчанию является true .

columnBreakOffset — Когда происходит разрыв столбца, указывает количество вертикального пространства, измеренное в пикселях, перед тем, как последующий фрагмент кросс-таблицы будет размещен ниже предыдущего на той же странице. Значение по умолчанию 10.

runDirection — указывает, должны ли данные кросс- таблицы заполняться слева направо (LTR) или справа налево (RTL). Значением по умолчанию является LTR.

ignoreWidth — указывает, будет ли кросс- таблица расширяться за пределы начального предела ширины кросс- таблицы , и не будет ли разрывов столбцов. В противном случае он остановит рендеринг столбцов в пределах ширины кросс-таблицы и продолжит работу с оставшимися столбцами только после того, как все строки начнут рендеринг. Значением по умолчанию является false .

isRepeatColumnHeaders — указывает, следует ли перепечатывать заголовки столбцов после разрыва страницы. Значением по умолчанию является true .

isRepeatRowHeaders — указывает, следует ли перепечатывать заголовки строк после разрыва столбца кросс-таблицы. Значением по умолчанию является true .

columnBreakOffset — Когда происходит разрыв столбца, указывает количество вертикального пространства, измеренное в пикселях, перед тем, как последующий фрагмент кросс-таблицы будет размещен ниже предыдущего на той же странице. Значение по умолчанию 10.

runDirection — указывает, должны ли данные кросс- таблицы заполняться слева направо (LTR) или справа налево (RTL). Значением по умолчанию является LTR.

ignoreWidth — указывает, будет ли кросс- таблица расширяться за пределы начального предела ширины кросс- таблицы , и не будет ли разрывов столбцов. В противном случае он остановит рендеринг столбцов в пределах ширины кросс-таблицы и продолжит работу с оставшимися столбцами только после того, как все строки начнут рендеринг. Значением по умолчанию является false .

Подэлементы
Элемент <crosstab> имеет следующие подэлементы —

<reportElement> — этот элемент определяет положение, ширину и высоту кросс-таблицы внутри ее вложения. Атрибуты для этого элемента включают все стандартные атрибуты <reportElement>.

<crosstabParameter> — этот элемент используется для доступа к переменным и параметрам отчета из кросс-таблицы. Атрибуты для этого элемента включают —

name — определяет имя параметра

класс — указывает класс параметров.

<parametersMapExpression> — Этот элемент используется для передачи переменной отчета или параметра, содержащего экземпляр java.util.Map , в качестве набора параметров для кросс-таблицы. Этот элемент не содержит атрибутов.

<crosstabDataset> — этот элемент определяет набор данных, который будет использоваться для заполнения кросс-таблицы (подробное объяснение см. в следующем разделе). Атрибуты для этого элемента включают —

isDataPreSorted — указывает, предварительно ли отсортированы данные в наборе данных. Значением по умолчанию является false .

<crosstabHeaderCell> — этот элемент определяет содержимое области, найденной в верхнем левом углу кросс-таблицы, где встречаются заголовки столбцов и строки. Размер этой ячейки вычисляется автоматически на основе определенной ширины и высоты строки и столбца.

<rowGroup> — этот элемент определяет группу, используемую для разделения данных на строки. Атрибуты для этого элемента включают —

name — определяет имя группы строк.

ширина — это определяет ширину группы строк.

headerPosition — определяет позицию содержимого заголовка (Top, Middle, Bottom, Stretch).

totalPosition — определяет позицию всего столбца (Start, End, None).

Этот элемент содержит следующие подэлементы —

<Ковш>

<crosstabRowHeader>

<crosstabTotalRowHeader>

<columnGroup> — этот элемент определяет группу, используемую для разделения данных на столбцы. Атрибуты для этого элемента включают —

name — определяет имя группы столбцов.

высота — определяет высоту заголовка группы столбцов.

headerPosition — определяет позицию содержимого заголовка ( Right, Left, Center, Stretch ).

totalPosition — определяет позицию всего столбца ( Start, End, None ).

Этот элемент содержит следующие подэлементы —

<Ковш>

<crosstabColumnHeader>

<crosstabTotalColumnHeader>

<measure> — этот элемент определяет вычисление, которое будет выполняться по строкам и столбцам. Атрибуты для этого элемента включают —

имя — это определяет имя меры.

класс — указывает класс меры.

вычисление — указывает, какое вычисление должно выполняться между значениями ячейки кросс-таблицы. Его значения могут быть любыми из следующих: Ничего, Счетчик, DistinctCount, Сумма, Среднее, Минимальное, Максимальное, Стандартное отклонение, Дисперсия и Первое . Значением по умолчанию является Ничто .

<crosstabCell> — этот элемент определяет способ размещения данных в ячейках без заголовка. Атрибуты для этого элемента включают —

columnTotalGroup — указывает группу, используемую для расчета общего количества столбцов.

высота — это определяет высоту ячейки.

rowTotalGroup — указывает группу, используемую для вычисления итоговой суммы строки.

ширина — это определяет ширину ячейки.

<whenNoDataCell> — этот элемент определяет, что отображать в пустой ячейке кросс-таблицы. Этот элемент не содержит атрибутов.

<reportElement> — этот элемент определяет положение, ширину и высоту кросс-таблицы внутри ее вложения. Атрибуты для этого элемента включают все стандартные атрибуты <reportElement>.

<crosstabParameter> — этот элемент используется для доступа к переменным и параметрам отчета из кросс-таблицы. Атрибуты для этого элемента включают —

name — определяет имя параметра

класс — указывает класс параметров.

<parametersMapExpression> — Этот элемент используется для передачи переменной отчета или параметра, содержащего экземпляр java.util.Map , в качестве набора параметров для кросс-таблицы. Этот элемент не содержит атрибутов.

<crosstabDataset> — этот элемент определяет набор данных, который будет использоваться для заполнения кросс-таблицы (подробное объяснение см. в следующем разделе). Атрибуты для этого элемента включают —

isDataPreSorted — указывает, предварительно ли отсортированы данные в наборе данных. Значением по умолчанию является false .

<crosstabHeaderCell> — этот элемент определяет содержимое области, найденной в верхнем левом углу кросс-таблицы, где встречаются заголовки столбцов и строки. Размер этой ячейки вычисляется автоматически на основе определенной ширины и высоты строки и столбца.

<rowGroup> — этот элемент определяет группу, используемую для разделения данных на строки. Атрибуты для этого элемента включают —

name — определяет имя группы строк.

ширина — это определяет ширину группы строк.

headerPosition — определяет позицию содержимого заголовка (Top, Middle, Bottom, Stretch).

totalPosition — определяет позицию всего столбца (Start, End, None).

Этот элемент содержит следующие подэлементы —

<Ковш>

<crosstabRowHeader>

<crosstabTotalRowHeader>

<columnGroup> — этот элемент определяет группу, используемую для разделения данных на столбцы. Атрибуты для этого элемента включают —

name — определяет имя группы столбцов.

высота — определяет высоту заголовка группы столбцов.

headerPosition — определяет позицию содержимого заголовка ( Right, Left, Center, Stretch ).

totalPosition — определяет позицию всего столбца ( Start, End, None ).

Этот элемент содержит следующие подэлементы —

<Ковш>

<crosstabColumnHeader>

<crosstabTotalColumnHeader>

<measure> — этот элемент определяет вычисление, которое будет выполняться по строкам и столбцам. Атрибуты для этого элемента включают —

имя — это определяет имя меры.

класс — указывает класс меры.

вычисление — указывает, какое вычисление должно выполняться между значениями ячейки кросс-таблицы. Его значения могут быть любыми из следующих: Ничего, Счетчик, DistinctCount, Сумма, Среднее, Минимальное, Максимальное, Стандартное отклонение, Дисперсия и Первое . Значением по умолчанию является Ничто .

<crosstabCell> — этот элемент определяет способ размещения данных в ячейках без заголовка. Атрибуты для этого элемента включают —

columnTotalGroup — указывает группу, используемую для расчета общего количества столбцов.

высота — это определяет высоту ячейки.

rowTotalGroup — указывает группу, используемую для вычисления итоговой суммы строки.

ширина — это определяет ширину ячейки.

<whenNoDataCell> — этот элемент определяет, что отображать в пустой ячейке кросс-таблицы. Этот элемент не содержит атрибутов.

Группировка данных в кросс-таблице
Механизм расчета кросс-таблицы агрегирует данные, просматривая связанные записи набора данных. Чтобы собрать данные, сначала нужно сгруппировать их. В кросс-таблице строки и столбцы основаны на определенных элементах группы, называемых сегментами . Определение корзины должно содержать —

bucketExpression — выражение, которое будет оценено для получения элементов группы данных.

comptorExpression — Необходим в том случае, если естественное упорядочение значений не является лучшим выбором.

orderByExpression — указывает значение, используемое для сортировки данных.

bucketExpression — выражение, которое будет оценено для получения элементов группы данных.

comptorExpression — Необходим в том случае, если естественное упорядочение значений не является лучшим выбором.

orderByExpression — указывает значение, используемое для сортировки данных.

Группы строк и столбцов (определенные выше) в кросс-таблице полагаются на сегменты .

Встроенные переменные кросс-таблицы
Ниже приведен список текущих значений меры и итогов разных уровней, соответствующих ячейке, можно получить через переменные, названные в соответствии со следующей схемой:

Текущее значение вычисления меры сохраняется в переменной, имя которой совпадает с именем меры.

<Measure> _ <Column Group> _ALL — Это дает итоговое значение для всех записей в группе столбцов из той же строки.

<Measure> _ <Row Group> _ALL — это итоговое значение для всех записей в группе строк из одного столбца.

<Measure> _ <Row Group> _ <Column Group> _ALL — Это дает объединенную сумму, соответствующую всем записям в группах строк и столбцов.

Текущее значение вычисления меры сохраняется в переменной, имя которой совпадает с именем меры.

<Measure> _ <Column Group> _ALL — Это дает итоговое значение для всех записей в группе столбцов из той же строки.

<Measure> _ <Row Group> _ALL — это итоговое значение для всех записей в группе строк из одного столбца.

<Measure> _ <Row Group> _ <Column Group> _ALL — Это дает объединенную сумму, соответствующую всем записям в группах строк и столбцов.

пример
Чтобы продемонстрировать кросс-таблицы, напишем новый шаблон отчета (jasper_report_template.jrxml). Здесь мы добавим кросс-таблицу в сводный раздел. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test . Содержимое файла приведено ниже.

<?xml version = "1.0" encoding = "UTF-8"?>

<!DOCTYPE jasperReport PUBLIC "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">
	
<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth = "555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20">

   <parameter name = "ReportTitle" class = "java.lang.String"/>
   <parameter name = "Author" class = "java.lang.String"/>
   
   <field name = "name" class = "java.lang.String"/>
   <field name = "country" class = "java.lang.String"/>
   
   <title>
      <band height = "70">
         
         <line>
            <reportElement x = "0" y = "0" width = "515" height = "1"/>
         </line>
         
         <textField isBlankWhenNull = "true" bookmarkLevel = "1">
            <reportElement x = "0" y = "10" width = "515" height = "30"/>
            
            <textElement textAlignment = "Center">
               <font size = "22"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{ReportTitle}]]>
            </textFieldExpression>
            
            <anchorNameExpression>
               <![CDATA["Title"]]>
            </anchorNameExpression>
         </textField>
         
         <textField isBlankWhenNull = "true">
            <reportElement  x = "0" y = "40" width = "515" height = "20"/>
            
            <textElement textAlignment = "Center">
               <font size = "10"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{Author}]]>
            </textFieldExpression>
         </textField>
      
      </band>
   </title>
   
   <summary>
      <band height = "60">
      
      <crosstab>
         <reportElement width = "782" y = "0" x = "0" height = "60"/>
          
         <rowGroup name = "nameGroup" width = "100">
         
            <bucket>
               <bucketExpression class = "java.lang.String">
                  <![CDATA[$F{name}]]>
               </bucketExpression>
            </bucket>
            
            <crosstabRowHeader>
            
               <cellContents>
                  <box border = "Thin" borderColor = "black"/>
                  
                  <textField>
                     <reportElement width = "100" y = "0" x = "0" height = "20"/>
                     <textElement textAlignment = "Right" 
                        verticalAlignment = "Middle"/>
                     
                     <textFieldExpression>
                        <![CDATA[$V{nameGroup}]]>
                     </textFieldExpression>
                  </textField>
            
               </cellContents>
         
            </crosstabRowHeader>

         </rowGroup>
         
         <columnGroup name = "countryGroup" height = "20">
            <bucket>
               
               <bucketExpression class = "java.lang.String">
                  $F{country}
               </bucketExpression>
            </bucket>
            
            <crosstabColumnHeader>
               <cellContents>
                  <box border = "Thin" borderColor = "black"/>
                  <textField isStretchWithOverflow = "true">
                     <reportElement width = "60" y = "0" x = "0" height = "20"/>
                     <textElement verticalAlignment = "Bottom"/>
                     <textFieldExpression>
                        <![CDATA[$V{countryGroup}]]>
                     </textFieldExpression>
                  </textField>
               </cellContents>
            </crosstabColumnHeader>

         </columnGroup>
         
         <measure name = "tailNumCount" class = "java.lang.Integer"  
            calculation = "Count">
            <measureExpression>$F{country}</measureExpression>
         </measure>
         
         <crosstabCell height = "20" width = "60">
            <cellContents backcolor = "#FFFFFF">
               <box borderColor = "black" border = "Thin"/>
               <textField>
                  <reportElement x = "5" y = "0" width = "55" height = "20"/>
                  <textElement textAlignment = "Left" 
                     verticalAlignment = "Bottom"/>
                  <textFieldExpression class = "java.lang.Integer">
                      $V{tailNumCount}
                  </textFieldExpression>
               </textField>
            </cellContents>
         </crosstabCell>
      
      </crosstab>
      
      </band>
   </summary>
	
</jasperReport>
Детали вышеупомянутого файла следующие:

Кросс-таблица определяется элементом <crosstab>.

Элемент <rowGroup> определяет группу для разделения данных на строки. Здесь каждая строка будет отображать данные для другого имени.

Элементы <bucket> и <bucketExpression> определяют, какое выражение отчета использовать в качестве разделителя группы для <rowGroup>. Здесь мы использовали поле имени в качестве разделителя, чтобы разделить строки по имени.

Элемент <crosstabRowHeader> определяет выражение, которое будет использоваться в качестве заголовка строки. Он содержит единственный подэлемент, а именно <cellContents>, который действует как внутренняя полоса внутри кросс-таблицы. Вместо определения имени переменной для текстового поля внутри <crosstabRowHeader>, мы присвоили имя <rowGroup> (через его атрибут name), поэтому оно создает неявную переменную. Элемент <crosstabRowHeader> определяет содержимое ячейки заголовка для всей строки. Он принимает один элемент <cellContents> как единственный подэлемент.

Элемент <columnGroup> и его подэлементы аналогичны элементу <rowGroup>, за исключением того, что он влияет на столбцы, а не на строки.

Элемент <measure> определяет вычисление для строк и столбцов. Атрибут вычисления имеет значение Count .

Элемент <crosstabCell> определяет способ размещения данных в ячейках без заголовка. Этот элемент также содержит единственный элемент <crosstabCell> в качестве единственного подэлемента.

Кросс-таблица определяется элементом <crosstab>.

Элемент <rowGroup> определяет группу для разделения данных на строки. Здесь каждая строка будет отображать данные для другого имени.

Элементы <bucket> и <bucketExpression> определяют, какое выражение отчета использовать в качестве разделителя группы для <rowGroup>. Здесь мы использовали поле имени в качестве разделителя, чтобы разделить строки по имени.

Элемент <crosstabRowHeader> определяет выражение, которое будет использоваться в качестве заголовка строки. Он содержит единственный подэлемент, а именно <cellContents>, который действует как внутренняя полоса внутри кросс-таблицы. Вместо определения имени переменной для текстового поля внутри <crosstabRowHeader>, мы присвоили имя <rowGroup> (через его атрибут name), поэтому оно создает неявную переменную. Элемент <crosstabRowHeader> определяет содержимое ячейки заголовка для всей строки. Он принимает один элемент <cellContents> как единственный подэлемент.

Элемент <columnGroup> и его подэлементы аналогичны элементу <rowGroup>, за исключением того, что он влияет на столбцы, а не на строки.

Элемент <measure> определяет вычисление для строк и столбцов. Атрибут вычисления имеет значение Count .

Элемент <crosstabCell> определяет способ размещения данных в ячейках без заголовка. Этот элемент также содержит единственный элемент <crosstabCell> в качестве единственного подэлемента.

Java-коды для заполнения отчетов остаются без изменений. Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ JasperReportFill.java указано ниже —

package com.tutorialspoint;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JasperFillManager;
import net.sf.jasperreports.engine.data.JRBeanCollectionDataSource;

public class JasperReportFill {
   @SuppressWarnings("unchecked")
   public static void main(String[] args) {
      String sourceFileName = 
         "C://tools/jasperreports-5.0.1/test/jasper_report_template.jasper";

      DataBeanList DataBeanList = new DataBeanList();
      ArrayList<DataBean> dataList = DataBeanList.getDataBeanList();

      JRBeanCollectionDataSource beanColDataSource =
      new JRBeanCollectionDataSource(dataList);

      Map parameters = new HashMap();
      /**
       * Passing ReportTitle and Author as parameters
       */
      parameters.put("ReportTitle", "List of Contacts");
      parameters.put("Author", "Prepared By Manisha");

      try {
         JasperFillManager.fillReportToFile(
         sourceFileName, parameters, beanColDataSource);
      } catch (JRException e) {
         e.printStackTrace();
      }
   }
}
Содержимое файла POJO C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBean.java :

package com.tutorialspoint;

public class DataBean {
   private String name;
   private String country;

   public String getName() {
      return name;
   }

   public void setName(String name) {
      this.name = name;
   }

   public String getCountry() {
      return country;
   }

   public void setCountry(String country) {
      this.country = country;
   }
}
Содержимое файла C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint \ DataBeanList.java выглядит следующим образом:

package com.tutorialspoint;

import java.util.ArrayList;

public class DataBeanList {
   public ArrayList<DataBean> getDataBeanList() {
      ArrayList<DataBean> dataBeanList = new ArrayList<DataBean>();

      dataBeanList.add(produce("Manisha", "India"));
      dataBeanList.add(produce("Dennis Ritchie", "USA"));
      dataBeanList.add(produce("V.Anand", "India"));
      dataBeanList.add(produce("Shrinath", "California"));

      return dataBeanList;
   }

   /**
    * This method returns a DataBean object,
    * with name and country set in it.
    */
   private DataBean produce(String name, String country) {
      DataBean dataBean = new DataBean();
      dataBean.setName(name);
      dataBean.setCountry(country);
      
      return dataBean;
   }
}
Генерация отчетов
Далее, давайте скомпилируем и выполним вышеуказанные файлы, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml взят из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>
<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview the 
      report stored in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid = "classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
		
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFill (viewFullReport является целью по умолчанию) следующим образом:

C:\tools\jasperreports-5.0.1\test>ant -Dmain-class=com.tutorialspoint.JasperReportFill
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defaulting to
   [javac] Compiling 3 source files to C:\tools\jasperreports-5.0.1\test\classes

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig 
      for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFill
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger (
   net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 20 minutes 53 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —

Пример кросс-таблицы отчета Jasper

Здесь мы видим, что каждая страна и название сведены в таблицу.

JasperReports — Интернационализация
Иногда нам нужны отчеты на разных языках. Написание одного и того же отчета для каждого языка подразумевает много лишней работы. Только фрагменты текста, отличающиеся от языка к языку, должны быть написаны отдельно и загружены в текстовые элементы во время выполнения, в зависимости от настроек локали. Это цель интернационализации отчета. Интернационализированные отчеты, однажды написанные, могут работать везде.

На следующих этапах мы перечислили, как создавать отчеты на разных языках, а также некоторые другие функции интернационализации отчетов.

Свяжите пакет ресурсов java.util.ResourceBundle с шаблоном отчета. Есть два способа связать объект java.util.ResourceBundle с шаблоном отчета.

Во время разработки путем установки атрибута resourceBundle объекта шаблона отчета в качестве базового имени целевого пакета ресурсов.

Динамическая / динамическая ассоциация может быть создана путем предоставления объекта java.util.ResourceBundle в качестве значения параметра REPORT_RESOURCE_BUNDLE во время заполнения отчета.

Если отчет необходимо создать в локали, отличной от текущей, встроенный параметр REPORT_LOCALE можно использовать для указания локали среды выполнения при заполнении отчета.

Чтобы упростить интернационализацию отчета, в выражениях отчета доступен специальный синтаксис $ R {} для ссылки на ресурсы java.lang.String, размещенные внутри объекта java.util.ResourceBundle, связанного с отчетом. Синтаксис символа $ R {} извлекает ресурс, зависящий от локали, из пакета ресурсов на основе ключа, который должен быть заключен в квадратные скобки —

Свяжите пакет ресурсов java.util.ResourceBundle с шаблоном отчета. Есть два способа связать объект java.util.ResourceBundle с шаблоном отчета.

Во время разработки путем установки атрибута resourceBundle объекта шаблона отчета в качестве базового имени целевого пакета ресурсов.

Динамическая / динамическая ассоциация может быть создана путем предоставления объекта java.util.ResourceBundle в качестве значения параметра REPORT_RESOURCE_BUNDLE во время заполнения отчета.

Если отчет необходимо создать в локали, отличной от текущей, встроенный параметр REPORT_LOCALE можно использовать для указания локали среды выполнения при заполнении отчета.

Чтобы упростить интернационализацию отчета, в выражениях отчета доступен специальный синтаксис $ R {} для ссылки на ресурсы java.lang.String, размещенные внутри объекта java.util.ResourceBundle, связанного с отчетом. Синтаксис символа $ R {} извлекает ресурс, зависящий от локали, из пакета ресурсов на основе ключа, который должен быть заключен в квадратные скобки —

<textFieldExpression>
   $R{report.title}
</textFieldExpression>
В приведенном выше текстовом поле отображается заголовок отчета путем извлечения значения String из комплекта ресурсов, связанного с шаблоном отчета, на основе локали, используемой во время выполнения, и ключа report.title .

Форматирование сообщений на разных языках в зависимости от локали отчета, в отчетах есть встроенный метод net.sf.jasperreports.engine.fill.JRCalculator . Этот метод предлагает функциональность, аналогичную классу java.text.MessageFormat . Этот метод, msg (), имеет три удобные подписи, которые позволяют вам использовать до трех параметров сообщения в сообщениях.

Встроенный метод str () (эквивалент синтаксиса $ R {} внутри выражений отчета), который предоставляет доступ к содержимому пакета ресурсов на основе языкового стандарта отчета.

Для форматирования даты и времени встроенный параметр REPORT_TIME_ZONE можно использовать для обеспечения правильного преобразования времени.

В сгенерированном выводе библиотека хранит информацию о направлении выполнения текста, так что документы, сгенерированные на языках с написанием справа налево (таких как арабский и иврит), могут быть правильно отображены.

Если приложение использует встроенный просмотрщик Swing для отображения сгенерированных отчетов, его необходимо интернационализировать, адаптируя кнопку «Подсказки» или другие отображаемые тексты. Это очень легко сделать, поскольку средство просмотра использует предопределенный пакет ресурсов для извлечения информации о конкретной локали. Базовое имя для этого пакета ресурсов — net.sf.jasperreports.view.viewer.

Форматирование сообщений на разных языках в зависимости от локали отчета, в отчетах есть встроенный метод net.sf.jasperreports.engine.fill.JRCalculator . Этот метод предлагает функциональность, аналогичную классу java.text.MessageFormat . Этот метод, msg (), имеет три удобные подписи, которые позволяют вам использовать до трех параметров сообщения в сообщениях.

Встроенный метод str () (эквивалент синтаксиса $ R {} внутри выражений отчета), который предоставляет доступ к содержимому пакета ресурсов на основе языкового стандарта отчета.

Для форматирования даты и времени встроенный параметр REPORT_TIME_ZONE можно использовать для обеспечения правильного преобразования времени.

В сгенерированном выводе библиотека хранит информацию о направлении выполнения текста, так что документы, сгенерированные на языках с написанием справа налево (таких как арабский и иврит), могут быть правильно отображены.

Если приложение использует встроенный просмотрщик Swing для отображения сгенерированных отчетов, его необходимо интернационализировать, адаптируя кнопку «Подсказки» или другие отображаемые тексты. Это очень легко сделать, поскольку средство просмотра использует предопределенный пакет ресурсов для извлечения информации о конкретной локали. Базовое имя для этого пакета ресурсов — net.sf.jasperreports.view.viewer.

пример
Чтобы продемонстрировать интернационализацию, давайте напишем новый шаблон отчета (jasper_report_template.jrxml). Содержимое JRXML приведено ниже. Сохраните его в каталоге C: \ tools \ jasperreports-5.0.1 \ test.

<?xml version = "1.0" encoding = "UTF-8"?>

<!DOCTYPE jasperReport PUBLIC "//JasperReports//DTD Report Design//EN"
   "http://jasperreports.sourceforge.net/dtds/jasperreport.dtd">

<jasperReport xmlns = "http://jasperreports.sourceforge.net/jasperreports"
   xmlns:xsi = "http://www.w3.org/2001/XMLSchema-instance"
   xsi:schemaLocation = "http://jasperreports.sourceforge.net/jasperreports
   http://jasperreports.sourceforge.net/xsd/jasperreport.xsd"
   name = "jasper_report_template" language = "groovy" pageWidth = "595"
   pageHeight = "842" columnWidth = "555" leftMargin = "20" rightMargin = "20"
   topMargin = "20" bottomMargin = "20" resourceBundle = "localizationdemo">
   
   <title>
      <band height = "552">
         
         <textField>
            <reportElement positionType = "Float" x = "150" y = "20" 
               width = "400" height = "50"/>
            
            <textElement>
               <font size = "24"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$P{REPORT_LOCALE}.getDisplayName ($P{REPORT_LOCALE})]]>
            </textFieldExpression>
         </textField>

         <textField isStretchWithOverflow = "true" isBlankWhenNull = "true">
            <reportElement positionType = "Float" x = "20" y = "125" 
               width = "530" height = "20"/>
            
            <textElement textAlignment = "Justified">
               <font size = "14"/>
            </textElement>
            
            <textFieldExpression class = "java.lang.String">
               <![CDATA[$R{localization.text1}]]>
            </textFieldExpression>
         
         </textField>
      
      </band>
   </title>

</jasperReport>
В приведенном выше файле атрибут resourceBundle элемента <jasperReport> сообщает JasperReports, где получить локализованные строки для использования в отчете. Нам нужно создать файл свойств с корневым именем, соответствующим значению атрибута. Этот файл должен существовать в любом месте CLASSPATH при заполнении отчета. В этом примере файл свойств localizationdemo.properties сохраняется в каталоге C: \ tools \ jasperreports-5.0.1 \ test . Содержимое этого файла выглядит следующим образом —

localization.text1 = This is English text.
Чтобы использовать другую локаль, имя файла должно быть localizationdemo [locale] .properties. Здесь мы напишем файл для испанской локали. Сохраните этот файл как — C: \ tools \ jasperreports-5.0.1 \ test \ localizationdemo_es.properties . Содержимое этого файла:

localization.text1 = Este texto es en Español.
Синтаксис для получения значения для свойств resourceBundle: $ R {key}.

Чтобы JasperReports знал, какую локаль мы хотим использовать, нам нужно присвоить значение встроенному параметру. Имя этого параметра определяется как константа REPORT_LOCALE, а эта константа определяется в классе net.sf.jasperreports.engine.JRParameter . Значение константы должно быть экземпляром java.util.Locale . Эта логика включена в код Java для заполнения и генерации отчета. Давайте сохраним этот файл JasperReportFillI18.java в каталоге C: \ tools \ jasperreports-5.0.1 \ test \ src \ com \ tutorialspoint. Содержимое файла выглядит следующим образом:

package com.tutorialspoint;

import java.util.HashMap;
import java.util.Locale;

import net.sf.jasperreports.engine.JREmptyDataSource;
import net.sf.jasperreports.engine.JRException;
import net.sf.jasperreports.engine.JRParameter;
import net.sf.jasperreports.engine.JasperFillManager;

public class JasperReportFillI18 {

   public static void main(String[] args) {
      String sourceFileName = "C://tools/jasperreports-5.0.1/test/"
         + "jasper_report_template.jasper";
      HashMap parameterMap = new HashMap();
      if (args.length > 0) {
         parameterMap.put(JRParameter.REPORT_LOCALE, new Locale(args[0]));
      }
      try {
         JasperFillManager.fillReportToFile(sourceFileName, null, 
            new JREmptyDataSource());
      } catch (JRException e) {
         // TODO Auto-generated catch block
         e.printStackTrace();
      }

   }
}
Генерация отчетов
Мы скомпилируем и выполним вышеуказанный файл, используя наш обычный процесс сборки ANT. Содержимое файла build.xml (сохраненного в каталоге C: \ tools \ jasperreports-5.0.1 \ test) приведено ниже.

Файл импорта — baseBuild.xml взят из главы « Настройка среды» и должен быть расположен в том же каталоге, что и build.xml.

<?xml version = "1.0" encoding = "UTF-8"?>

<project name = "JasperReportTest" default = "viewFillReport" basedir = ".">
   <import file = "baseBuild.xml" />
   
   <target name = "viewFillReport" depends = "compile,compilereportdesing,run"
      description = "Launches the report viewer to preview the report stored 
      in the .JRprint file.">
      
      <java classname = "net.sf.jasperreports.view.JasperViewer" fork = "true">
         <arg value = "-F${file.name}.JRprint" />
         <classpath refid = "classpath" />
      </java>
   </target>
   
   <target name = "compilereportdesing" description = "Compiles the JXML file and
      produces the .jasper file.">
      
      <taskdef name = "jrc" classname = "net.sf.jasperreports.ant.JRAntCompileTask">
         <classpath refid="classpath" />
      </taskdef>
      
      <jrc destdir = ".">
         <src>
            <fileset dir = ".">
               <include name = "*.jrxml" />
            </fileset>
         </src>
         <classpath refid = "classpath" />
      </jrc>
   
   </target>
	
</project>
Далее, давайте откроем окно командной строки и перейдем в каталог, где находится build.xml. Наконец, выполните команду ant -Dmain-class = com.tutorialspoint.JasperReportFillI18 (viewFullReport является целью по умолчанию) следующим образом:

C:\tools\jasperreports-5.0.1\test>ant  -Dmain-class=com.tutorialspoint.JasperReportFillI18
Buildfile: C:\tools\jasperreports-5.0.1\test\build.xml

clean-sample:
   [delete] Deleting directory C:\tools\jasperreports-5.0.1\test\classes
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jasper
   [delete] Deleting: C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrprint

compile:
   [mkdir] Created dir: C:\tools\jasperreports-5.0.1\test\classes
   [javac] C:\tools\jasperreports-5.0.1\test\baseBuild.xml:28:
   warning: 'includeantruntime' was not set, defaulting to
   [javac] Compiling 1 source file to C:\tools\jasperreports-5.0.1\test\classes
   [javac] Note: C:\tools\jasperreports-5.0.1\test\src\com\tutorialspoint\
      JasperReportFillI18.java
   uses unchecked or u
   [javac] Note: Recompile with -Xlint:unchecked for details.

compilereportdesing:
   [jrc] Compiling 1 report design files.
   [jrc] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.engine.xml.JRXmlDigesterFactory).
   [jrc] log4j:WARN Please initialize the log4j system properly.
   [jrc] log4j:WARN See http://logging.apache.org/log4j/1.2/faq.html#noconfig 
      for more info.
   [jrc] File : C:\tools\jasperreports-5.0.1\test\jasper_report_template.jrxml ... OK.

run:
   [echo] Runnin class : com.tutorialspoint.JasperReportFillI18
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

viewFillReport:
   [java] log4j:WARN No appenders could be found for logger
   (net.sf.jasperreports.extensions.ExtensionsEnvironment).
   [java] log4j:WARN Please initialize the log4j system properly.

BUILD SUCCESSFUL
Total time: 3 minutes 28 seconds
В результате вышеупомянутой компиляции открывается окно JasperViewer, как показано на приведенном ниже экране —


