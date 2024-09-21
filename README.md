# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил:
- Лукоянов Владислав Александрович
- НМТ - 232202
  
Отметка о выполнении заданий:

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * |  |
| Задание 2 | * |  |
| Задание 3 | * |  |

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

## Цель работы
Установка программного обеспечения и ознакомление с ним на примере программ "Hello world!".

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.

![Скриншот 21-09-2024 160710](https://github.com/user-attachments/assets/99a372ac-78b4-4e5f-ace4-1c635eda71d0)


## Задание 2
### Написать программу Hello World на C# с запуском на Unity. 

Код скрипта "HelloWorld":

```Csharp
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class HelloWorld: MonoBehaviour
{
    public GameObject obj; 

    // Start is called before the first frame update
    void Start()
    {
        print("Hello World!");
    }

    // Update is called once per frame
    void Update()
    {
        if (Input.GetKeyUp(KeyCode.Space))

        {
            Destroy(obj);
        }
    }
}
```
При запуске программы в консоль выводится "Hello World!" и куб начинает падать на платформу:

![Скриншот 21-09-2024 161227](https://github.com/user-attachments/assets/2ed1312f-7777-4885-b281-1a8086b01b20)

![Скриншот 21-09-2024 161125](https://github.com/user-attachments/assets/5dbc93b8-7d98-4ba7-949c-814a76cf90dd)

При нажати на клавишу "пробел" объект "куб" удаляется:

![Скриншот 21-09-2024 161150](https://github.com/user-attachments/assets/935a3ec0-00ce-405f-a20d-84a3f87006b9)


## Задание 3
### Оформить отчет в виде документации на github (markdown-разметка).

Вы его читаете.

## Выводы

В процессе выполнения работы было установлено и настроенное все необходимое для прохождения курса программное обеспечение, были получены навыки по созданию отчетов в репозитории на GitHub и работы с Unity.
