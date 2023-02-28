## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
##
В начале запускается магазин без игрушек, можно выбрать ручное добавление игрушек п.м.1, либо автоматически п.м.5, ответив на 1 вопрос.
По остальным пунктам меню пояснения не требуются

## Коды ошибок
Итоговый код ошибки формируется из суммы кодов ошибок при проверке каждого поля отдельно:
    Пустое имя игрушки - код ошибки 1
    Некорректное количество - код ошибки 2
    Некорректный шанс - код ошибки 4
    Некорректные границы - код ошибки 8
Результирующий код при вводе всех полей некорректно будет 15, если первые 2 ошибки то 3, если вторая и третья ошибки - 6.
Что позволяет однозначно идентифицировать, что именно было некорректно введено.