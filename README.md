# Как добавить библиотеку kotlinx.serialization.json в intellijIDEA

Изначально можно столкнуться с такой проблемой:
![Проблема](src/pic1.png)
Чтобы ее решить вот пошаговый гайд:
## Шаг 1
![Шаг 1](src/pic2.png)
Нажать на file и открыть project structure
## Шаг 2
![Шаг 2](src/pic3.png)
Перейти на вкладку Modules
## Шаг 3
![Шаг 3](src/pic4.png)
Далее на вкладку Dependencies
## Шаг 4
![Шаг 4](src/pic5.png)
Нажать на "+"
## Шаг 5
![Шаг 5](src/pic6.png)

Далее Library
## Шаг 6
![Шаг 6](src/pic7.png)

Затем New Library
## Шаг 7
![Шаг 7](src/pic8.png)

Затем From Maven
## Шаг 8
![Шаг 8](src/pic9.png)
Затем ввести в поле следующий текст: org.jetbrains.kotlinx:kotlinx-serialization-json-jvm:1.6.2
## Шаг 9
![Шаг 9](src/pic10.png)

Нажать "OK"
## Шаг 10
![Шаг 10](src/pic11.png)
На вкладке Level выбрать Global Library, чтобы библиотеку было проще добавлять в другие проекты
## Шаг 11
![Шаг 11](src/pic12.png)
Поставить галочку в чекбоксе напротив новой добавленной зависимости
## Шаг 12
![Шаг 12](src/pic13.png)

Нажать Apply, Затем OK
## Шаг 13
![Шаг 13](src/pic14.png)
Радоваться!
