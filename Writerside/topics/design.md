# Переход с дизайна на верстку

## Формы

<deflist collapsible="true">
    <def title="Есть форма для заявки" collapsible="true" default-state="collapsed">
        Должно быть отправленное состояние или благодарность
    </def>
    <def title="Есть поле с файлом" collapsible="true" default-state="collapsed">
        Должно быть состояние приложенного файла
    </def>
    <def title="Есть поле логина" collapsible="true" default-state="collapsed">
        <warning>
            <p>
                Если поле принимает email и телефон, а так-же имеет маску, то такое невозможно реализовать.
                Для маски поля должны быть отдельно для мыла и отдельно для телефона.
            </p>
        </warning>
    </def>
</deflist>

## Поиск

<deflist collapsible="true">
    <def title="Есть быстрый поиск" collapsible="true" default-state="collapsed">
        <p>Должно быть состояние:</p>
        <list type="decimal">
            <li>Когда ничего не найдено</li>
            <li>Без введенного значения</li>
            <li>Результата поиска</li>
            <li>Загрузки результата</li>
        </list>
    </def>
    <def title="Есть страница поиска" collapsible="true" default-state="collapsed">
        <p>Должно быть состояние:</p>
        <list type="decimal">
            <li>Когда ничего не найдено</li>
            <li>Результата поиска</li>
        </list>
    </def>
</deflist>

## Элементы

<deflist collapsible="true">
    <def title="Есть видео" collapsible="true" default-state="collapsed">
        <p>Описать должен ли быть кастомный плеер, стандартный браузерный или ютуб</p>
        <warning>
            <p>Если видео с ютуба и дизайн хочет при запуске открывать сразу в полном экране, то такое нельзя реализовать</p>
        </warning>
    </def>
    <def title="Есть селектор" collapsible="true" default-state="collapsed">
        <p>Должно быть состояние</p>
        <list>
            <li>Открытого селектора</li>
            <li>Выбранного варианта</li>
        </list>
    </def>
    <def title="Есть многоуровневое меню" collapsible="true" default-state="collapsed">
        Если нет мобильного макета, то он должен быть отрисован для меню
    </def>
</deflist>
<tip>
    <p>
        Вероятно в дизайне не отрисованы состояния наведения на кнопки и элементы. 
        Это необязательно, но будьте готовы, что верстальщик не будет этого делать, если не отрисовать
    </p>
</tip>

