# MemoryTraining
Мобильное приложение с шестью видами тренировок памяти и отслеживанием статистики ошибок.

Страница в 
<a href="https://www.rustore.ru/catalog/app/com.youngsophomore">
    <img src="https://img.shields.io/badge/RuStore-blue?style=plastic" height="20"/>
  </a>


<img src="https://raw.githubusercontent.com/kirillpolonskiismurf/test/master/presentation1/MemoryTraining_presentation.gif" width="290" height="600">

## Стек
- Java
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
## Возможности приложения
- Выбор одной из шести тренировок
- Настройка и сохранение параметров тренировки
- Создание и удаление пользовательских коллекций слов, фраз, вопросов к изображению
- Просмотр статистики ошибок
- Смена языка
## Реализованный функционал
- Обработка жестов-свайпов и переходы между экранами с помощью MotionLayout
- Использование SharedPreferences для хранения настроек и названий пользовательских коллекций
- Использование Internal Storage для хранения пользовательских коллекций
- Использование сторонней библиотеки [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) для построения столбчатых диаграмм, отображающих статистику ошибок
- Реализация фрагмента секундомера с помощью Handler
- Реализация кастомных адаптеров для RecyclerView
