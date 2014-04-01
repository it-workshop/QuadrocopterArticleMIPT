Исходник tex для статьи по коптеру для МФТИ
===========================================

Проект использует cmake и [cmakeuselatex](http://www.cmake.org/Wiki/CMakeUserUseLATEX)

Как собрать:

    mkdir /tmp/paper
    cd /tmp/paper
    cmake /path/to/your/cloned/repository
    make
    
В папке /tmp/paper появится файл paper.pdf, собранный из проекта.
