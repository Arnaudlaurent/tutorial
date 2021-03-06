> Этот подраздел основан на руководстве Geek Girls Carrots (https://github.com/ggcarrots/django-carrots)

Django написан на Python. Нам нужен Python, чтобы сделать что-нибудь в Django. Давай начнем с его установки! Мы хотим, чтобы ты установила Python 3.4, поэтому, если у тебя уже есть более ранняя версия, то её придется обновить.

### Windows

Ты можешь загрузить Python для Windows с официального веб-сайта: https://www.python.org/downloads/release/python-343/. После загрузки ***.msi** файла, ты должна запустить его (двойной щелчок) и следовать инструкциям. Важно помнить путь (каталог), куда ты установила Python. Это понадобится позже!

Обрати внимание на второй экран мастера установки, который называется "Customize" (Настройка): тебе нужно пролистать его вниз и выбрать опцию "Add python.exe to the Path" (Добавить python.exe к системной переменной Path), как на рисунке:

![Не забудьте добавить Python в системную переменную Path](../python_installation/images/add_python_to_windows_path.png)

### Linux

Вполне вероятно, что у тебя уже установлен Python. Чтобы проверить это (а также версию языка), открой консоль и введи следующую команду:

    $ python3 --version
    Python 3.4.3
    

Если Python не установлен, или ты хочешь использовать другую версию языка, то можешь установить его следующим образом:

#### Debian или Ubuntu

Введи эту команду в консоль:

    $ sudo apt-get install python3.4
    

#### Fedora (версии вплоть до 21)

Используй следующую команду в консоли:

    $ sudo yum install python3.4
    

#### Fedora (версии 22 и выше)

Используй следующую команду в консоли:

    $ sudo dnf install python3.4
    

#### openSUSE

Используй следующую команду в консоли:

    $ sudo zypper install python3


### OS X

Тебе нужно перейти по ссылке https://www.python.org/downloads/release/python-343/ и скачать дистрибутив Python:

  * Скачай файл *Mac OS X 64-bit/32-bit installer*,
  * Сделай двойной щелчок на *python-3.4.3-macosx10.6.pkg* для запуска установщика.

Убедись, что установка прошла успешно, открыв приложение *Терминал* и запустив команду `python3`:

    $ python3 --version
    Python 3.4.3
    

* * *

Если у тебя остались какие-либо сомнения, или что-то пошло не так и ты понятия не имеешь что делать дальше - спроси своего тренера! Иногда дела идут не совсем гладко, поэтому лучше попросить помощи у кого-то с большим опытом.
