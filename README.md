- Название: bvi_vue
- Назначение: модуль предназначен для преобразования страницы в формат, доступный для восприятия людей с проблемами по зрению.
- Использование разработчиком:
    для размещения, импортируйте в свою страницу при помощи
    import BVI from 'bvi_vue';

    Далее, установите в любую точку сайта тег
    <BVI />

    Показателем того, что все работает, будет появление огромного черного глаза на весь экран. 

- Параметры и стили:
    Имеет 2 входных параметра:
    = height - задает высоту глаза, что позволяет изменять его размер
    = color - задает цвет глаза, поддерживает стандартные цвета CSS и в формате RGB (#rrggbb)
 
    Не имеет стандартных стилей. 

- Принцип работы:
    Модуль импортирует библиотеки Button visually impaired, соответственно, поддерживает внутренние возможности bvi, в том числе управление контентом классами:
    = bvi-hide - при включении версии для людей с ограничениями элемент с этим классом будет скрыт от показа.
    = bvi-show - при включении версии для людей с ограничениями элемент с этим классом будет показан.
    = bvi-no-styles - при включении версии элемент с этим классом отключит все css стили. 
