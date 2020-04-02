**КРАТКОЕ ОПИСАНИЕ**

01.04.2020 - 01.04.2020 было проведено ручное тестирование приложения Precision.

На тестирование затрачено: 00:05:00

***В результате тестирования выявлены следующие дефекты:***

При сложении regularBonus и specialBonus теряется процент баллов

Ссылка на описание дефекта:

https://github.com/xeniaplotnikova/Precision/issues/1

**ОПИСАНИЕ ПРОЦЕСА ТЕСТИРОВАНИЯ**

***В процессе тестирования использовались следующие артефакты:***

    Входные данные
    Готовый код с инициализированными типами данных:
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);

    IntelliJ IDEA - интегрированная среда разработки ПО

***В качестве тестовых данных использовались данные, приведенные в готовом коде:***

    double regularBonus = 0.3;
    double specialBonus = 0.6;

Источник: https://github.com/netology-code/javaqa-homeworks/tree/master/programming

***Тестирование производилось в следующем окружении:***

Windows 10 Pro, версия 1903; Firefox 73.0.1 (32-битный), последняя версия, IntelliJ IDEA 2019.3.4 GitBush, Git version 2.26.0
