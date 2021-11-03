**Лабораторная работа 1. Файловый tменеджер**

**Цель лабораторной работы:**

Научиться создавать сложный проект и научиться программно работать с локальными файлами и папками.

**Задания для выполнения:**

Необходимо создать примитивный файловый менеджер. Программа должна работать в определенной папке (рабочей папки менеджера) и позволять пользователю выполнять следующие простые действия в пределах рабочей папки:

1. Создание папки (с указанием имени);

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.001.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.002.png) 

2. Удаление папки по имени;

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.003.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.004.png) 

3. Перемещение между папками (в пределах рабочей папки) - заход в папку по имени, выход на уровень вверх;

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.005.png) 

4. Создание пустых файлов с указанием имени;

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.006.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.007.png) 

5. Запись текста в файл;

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.008.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.009.png) 

6. Просмотр содержимого текстового файла;

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.010.png) 

7. Удаление файлов по имени;

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.011.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.012.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.013.png) 

8. Копирование файлов из одной папки в другую;

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.014.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.015.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.016.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.017.png) 

9. Перемещение файлов;

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.018.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.019.png) 

10. Переименование файлов.

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.020.png)
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.021.png) 

**Указания к выполнению**

1. Расположение рабочей папки должно указываться в настройках файлового менеджера. Настройки должны располагаться в отдельном от основного исходного кода файле.
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.022.png) 

2. Файловый менеджер должен блокировать пользователя от выхода за пределы рабочей папки. Пользователь должен воспринимать рабочую папку как корневую и все действия файлового менеджера должны локализоваться только в пределах этой папки.

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.023.png) 

3. Программный проект должен быть оформлен как код на языке программирования Python и располагаться в определенной папке. Проект должен состоять из нескольких файлов. Расположение рабочей папки не должно быть связано с физическим расположением файлов исходного кода.
3. Файловый менеджер по умолчанию должен иметь текстовый интерфейс по аналогии с интерфейсом командной строки. Действия пользователя осуществляются вводом с клавиатуры соответствующей команды (по необходимости с параметрами).
3. Код должен быть организован в виде набора функций или классов, каждая операция файлового менеджера должна быть реализована в отдельной функции или методе класса.
3. Файловый менеджер должен быть кроссплатформенным и работать как в среде Windows, так и в UNIX системах. Необходимо протестировать работоспособность программы в разных ОС. Для кроссплатформенности рекомендуется использовать стандартную библиотеку Python для осуществления файловых операций.
3. Разработка программы должна вестись с использованием СКВ Git. Код должен публиковаться в репозитории на GitHub.
3. Перед разработкой программист должен продумать названия и структуру команд для пользователя. Команды не должны повторять команды существующих программных оболочек.

**Дополнительные задания**

1. Сделайте файловый менеджер многопользовательским. Добавьте возможность регистрации пользователей. При регистрации каждому пользователю создается своя домашняя папка, в пределах которой он может работать.

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.024.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.025.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.026.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.027.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.028.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.029.png) 


2. Придумайте и добавьте дополнительные функциональные возможности для файлового менеджера. Сделаем: Квотирование дискового пространства и отображение занятого оставшегося места.

![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.030.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.031.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.032.png) 
![](https://github.com/dvaisluk/FileManager-PY/raw/main/png/Aspose.Words.4117d108-cd13-436b-bb8e-73fc17532b8a.033.png) 

