
# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Харьков Ярослав Русланович
- РИ222702
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
Задание 1. Написать программу Hello World на Python с запуском в Jupiter Notebook.
Задание 2. Написать программу Hello World на C# с запуском на Unity. 
Задание 3. Оформить отчет в виде документации на github (markdown-разметка).

## Цель работы
Установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.
Ход работы:

- Установить инструмент Anaconda и написать необходимую программу с запуском в Jupiter Notebook.

```py

print("Hello World!")

```
![изображение](https://github.com/Quvir/DA-in-GameDev-lab1/blob/main/jupyterhelloworld.png)

## Задание 2
### Написать программу Hello World на C# с запуском на Unity. 

- Устанавливаем Unity и Visual Studio Code.
- Создаём скрипт с необходимым кодом.

```py

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class HelloWorld : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        Debug.Log("Hello world");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
![изображение](https://github.com/Quvir/DA-in-GameDev-lab1/blob/main/unityhelloworld.png)

## Задание 3
### Оформить отчет в виде документации на github (markdown-разметка).

- Копируем макет.
- Пишем этот отчёт.

## Выводы

В ходе данной работы было успешно установленно всё необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
