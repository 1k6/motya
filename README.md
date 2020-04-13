<h1 align="center">Motya</h1>
<p align="center">
    Открытая и бесплатная утилита для генерации демотиваторов.
    <br /><br />
    <img alt="Made with Python" src="https://img.shields.io/badge/Made%20with-Python-%23FFD242?logo=python&logoColor=white">
    <img alt="Repo size" src="https://img.shields.io/github/repo-size/mishailovic/motya">
    <img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg">
</p>

   Motya - генератор демотиваторов на python. Все что вам нужно это установить модуль pillow из pip и наслаждаться его работой. Берет рандомную картинку из папки "images" и прилепляет на нее рандомный текст из файла "phrases.txt" (Если в папке и в файле только одна картинка и один текст, то будет использовать только их. Сохраняет готовое изображение в файл result.png, если таковой уже есть - то перезаписывает. Наслаждайтесь.

![crinny](result.png)


## 🚀 Установка

1. Установите Python версии не ниже 3.7. Сделать это можно так:

    <h3>Для Windows</h3>

    Скачайте установщик с [официального сайта](https://www.python.org/downloads/) и запустите его. Убедитесь, что при установке отметили галочку ![Add Python to PATH](https://user-images.githubusercontent.com/42045258/69171091-557d2780-0b0c-11ea-8adf-7f819357f041.png)

    <h3>Для Android</h3>

    Установите приложение [Termux](https://play.google.com/store/apps/details?id=com.termux), запустите его и введите следующие команды поочерёдно:
     ```sh
     pkg install python
     ```

2. Введите следующую команду ([куда?](http://comp-profi.com/kak-vyzvat-komandnuyu-stroku-ili-konsol-windows/)):

```sh
git clone https://github.com/mishailovic/motya.git
cd motya
pip3 intsall pillow
```

## 🚩 Запуск

Всё просто! Введите команду `python3 motya.py` или `python motya.py` и ваш демотиватор готов!
 
