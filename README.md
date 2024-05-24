# ... и сошлись в схватке

## ______________________________Финансовый университет

 ![IMG_3897.jpg](IMG_3897.jpg)

# ________________________________ CHAT GPT



# Кто напишет программный код эффективнее?


Правила:

Бал получает тот, чей time кода ниже

Код написанный искусственным интеллектом ->
 branch: GPT

Код студентов -> любой другой branch

дедлайн 26 мая2024

# Да начнётся битва!

## Проверка 

~~~bash
$ git checkout GPT
$ time python3 1.py

real    0m0,090s
user    0m0,045s
sys     0m0,014s

~~~
~~~bash
$ git checkout ВАША ВЕТКА
$ time python3 1.py

real    0m0,089s
user    0m0,041s
sys     0m0,011s

~~~
_________



###  задания для решения

1.  Напишите программу, которая создает нить. Родительская и вновь созданная нити должны распечатать десять строк текста.
2.  Напишите простой эхо-сервер, использующий неблокирующие сокеты и клиент к нему.
3.  Напишите простой многопоточный загрузчик URL. Список URL скрипт принимает как аргументы командной строки.
4.  Реализуйте простой HTTP-клиент. Он принимает один параметр командной строки - URL. Клиент делает запрос по указанному URL и выдает тело ответа на терминал как текст.
5.  Напишите программу, которая вычисляет число Пи при помощи ряда Эйлера. Количество потоков программы должно определяться параметром командной строки.
6.  Дана функция calculate(x, y). Напишите программу, которая создает пул из 5 процессов и распределяет в этом пуле вычисление функции на промежутке х от 0 до 1 с шагом 0,1. у равняется 2 всегда.
7.  Напишите программу, которая проверяет все числа от 0 на простоту и выводит простые числа на экран по мере нахождения. Числа должны проверяться в различных потоках (или процессах, по выбору студента) Программа должна работать до тех пор, пока ее не остановит пользователь.
8.  Напишите программу, которая обходит все файлы в директории, переданной ей как параметр и выводит на экран имена тех, чей размер задан как второй параметр. Реализовать рекурсивный обход поддиректорий.
9.  Напишите программу, которая выводит на экран список номеров открытых портов на данной машине. Использовать команду netstat.
10.  Напишите программу, которая копирует файл с удаленного хоста в текущую папку по SSH. Имя файла и адрес хоста принимать как параметры.
11.  Сценарий должен вывести (на stdout) все числа, делящиеся на 12, в диапазоне от первого параметра до последнего. Если параметры заданы некорректно, скрипт должен вывести сообщение.
12.  Сценарий должен имитировать работу лототрона -- извлекать 5 случайных неповторяющихся чисел в диапазоне 1 - 50. Сценарий должен предусматривать как вывод на stdout, так и запись чисел в файл, кроме того, вместе с числами должны выводиться дата и время генерации данного набора.
13.  Напишите сценарий, который находил бы корни "квадратного " уравнения, вида: Ax^2 + Bx + C = 0. Сценарий должен получать коэффициенты уравнения A, B и C, как аргументы командной строки, и выводить корни. Если корней нет, вывод должен быть пустым.
14.  Написать скрипт, который выведет всех потомков процесса по его PID.
15.  Напишите скрипт, который и считает кол-во измененных в течении последних 3 дней файлов из каталога, переданного как параметр и выводит на экран.
16.  Написать скрипт, который выведет информацию о топ10 процессов по потреблению оперативной памяти.
17.  Написать скрипт, который выведет все файлы в домашней директории пользователя, измененные за последнюю неделю.
18.  Напишите сценарий, который принимает как аргументы список программ и устанавливает их в текущую систему. Сделайте возможность передать список программ через текстовый файл.
19.  Напишите скрипт, выводящий сообщение в случае, если в файле /etc/hosts есть записи относящиеся к адресам отличным от 127.0.0.1.
20.  Разработать сценарий, который ведёт в файле /tmp/run.log журнал запусков. При каждом запуске сценария в конец журнала должна добавляться строка с датой и временем запуска сценария, в стандартный вывод - фраза "Hello", в stderr - количество предыдущих запусков программы. Убедиться в правильности работы программы и выводе различных сообщений в различные потоки вывода.


## Мой вывод комaнд для справки

~~~bash
root@host:/home/vladimir/fa-practics/exams/exams# git branch
  andropov
* main
root@host:/home/vladimir/fa-practics/exams/exams# git checkout andropov
Переключено на ветку «andropov»
Ваша ветка обновлена в соответствии с «origin/andropov».
root@host:/home/vladimir/fa-practics/exams/exams# time python3 1.py
This is line 1
This is line 1
This is line 2
This is line 3
This is line 4
This is line 5
This is line 6
This is line 7
This is line 8
This is line 9
This is line 10
This is line 2
This is line 3
This is line 4
This is line 5
This is line 6
This is line 7
This is line 8
This is line 9
This is line 10

real    0m0,069s
user    0m0,047s
sys     0m0,013s
root@host:/home/vladimir/fa-practics/exams/exams# time python3 3.py
Usage: python downloader.py url1 url2 url3 ...

real    0m0,400s
user    0m0,308s
sys     0m0,055s
root@host:/home/vladimir/fa-practics/exams/exams# time python3 4.py
Usage: python http_client.py <URL>

real    0m0,374s
user    0m0,310s
sys     0m0,044s
root@host:/home/vladimir/fa-practics/exams/exams# time python3 5.py
Usage: python euler_series.py <num_threads>

real    0m0,066s
user    0m0,055s
sys     0m0,008s
root@host:/home/vladimir/fa-practics/exams/exams# time python3 6.py
calculate(0.0, 2) = None
calculate(0.1, 2) = None
calculate(0.2, 2) = None
calculate(0.30000000000000004, 2) = None
calculate(0.4, 2) = None
calculate(0.5, 2) = None
calculate(0.6000000000000001, 2) = None
calculate(0.7000000000000001, 2) = None
calculate(0.8, 2) = None
calculate(0.9, 2) = None
calculate(1.0, 2) = None

real    0m0,217s
user    0m0,120s
sys     0m0,075s

root@host:/home/vladimir/fa-practics/exams/exams# time python3 11.py
Usage: python script.py <start> <end>

real    0m0,045s
user    0m0,034s
sys     0m0,008s
root@host:/home/vladimir/fa-practics/exams/exams# time python3 12.py
Сгенерированные лотерейные числа: [14, 15, 27, 47, 50]
Дата и время генерации: 2024-05-07 11:54:43.502583

real    0m0,069s
user    0m0,053s
sys     0m0,000s
root@host:/home/vladimir/fa-practics/exams/exams# time python3 13.py
Usage: python quadratic_solver.py A B C

real    0m0,052s
user    0m0,033s
sys     0m0,014s


root@host:/home/vladimir/fa-practics/exams/exams# time ./8.sh
Usage: ./8.sh <directory> <size>

real    0m0,009s
user    0m0,003s
sys     0m0,000s
root@host:/home/vladimir/fa-practics/exams/exams# time ./9.sh
./9.sh: строка 6: netstat: команда не найдена
Список открытых портов на данной машине:


real    0m0,027s
user    0m0,014s
sys     0m0,004s
root@host:/home/vladimir/fa-practics/exams/exams# time ./10.sh
Usage: ./10.sh <filename> <remote_host>

real    0m0,010s
user    0m0,003s
sys     0m0,000s
root@host:/home/vladimir/fa-practics/exams/exams# time ./14-ver2.sh
Usage: ./14-ver2.sh <PID>

real    0m0,013s
user    0m0,003s
sys     0m0,000s
root@host:/home/vladimir/fa-practics/exams/exams# time ./15.sh
Usage: ./15.sh <directory>

real    0m0,010s
user    0m0,002s
sys     0m0,001s
root@host:/home/vladimir/fa-practics/exams/exams# time ./16.sh
    PID COMMAND         %MEM
   1895 Telegram         6.6
   2755 code             4.7
   3071 chrome           4.0
   3311 code             3.6
   2686 code             3.1
   4573 synaptic         2.9
   3149 chrome           2.8
   3109 chrome           2.7
   5610 code             2.6
   2721 code             2.4


real    0m0,116s
user    0m0,023s
sys     0m0,072s
root@host:/home/vladimir/fa-practics/exams/exams# time ./17.sh
-rw------- 1 root root 7629 мая  6 11:18 /root/.bash_history
-rw-r--r-- 1 root root   35 мая  7 11:56 /root/.cache/mc/Tree
-rw-r--r-- 1 root root 3732 мая  7 11:56 /root/.config/mc/ini
-rw------- 1 root root   20 мая  7 11:52 /root/.lesshst
-rw-r--r-- 1 root root  770 мая  6 09:46 /root/.local/share/mc/filepos
-rw------- 1 root root 2772 мая  7 11:56 /root/.local/share/mc/history
-rw------- 1 root root    7 мая  7 11:44 /root/.python_history
-rw-r--r-- 1 root root  280 мая  7 11:44 /root/.synaptic/log/2024-05-07.114345.log

real    0m0,195s
user    0m0,010s
sys     0m0,067s
root@host:/home/vladimir/fa-practics/exams/exams# time ./18.sh
Не указан список программ для установки.

real    0m0,009s
user    0m0,003s
sys     0m0,001s
root@host:/home/vladimir/fa-practics/exams/exams# time ./19.sh
В файле /etc/hosts найдены записи, отличные от 127.0.0.1:
127.0.1.1       host

# The following lines are desirable for IPv6 capable hosts
::1     ip6-localhost ip6-loopback
fe00::0 ip6-localnet
ff00::0 ip6-mcastprefix
ff02::1 ip6-allnodes
ff02::2 ip6-allrouters
# Added by Docker Desktop
# To allow the same kube context to work on the host and the container:
# End of section

real    0m0,017s
user    0m0,005s
sys     0m0,002s
root@host:/home/vladimir/fa-practics/exams/exams# time ./20.sh
Hello
Number of previous runs: 1

real    0m0,019s
user    0m0,002s
sys     0m0,012s
~~~