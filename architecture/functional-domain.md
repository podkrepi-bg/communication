---
description: Техническа документация на Подкрепи.бг
---

# Функционален домейн

При избора на архитектурните решения е добре да се има предвид контекстът (домейнът), в който работим - какви са Ограниченията, Изискванията и Вдъхновенията за Проекта Подкрепи.БГ.

## Ограничения

### Бюджет

Започваме с парите - Проектът няма бюджет. Организацията е НПО на доброволен принципи и се издържа от дарения към НПО-то, които, по условие, са непредвидими. Не събираме % от дарителските кампании, т.е. повече ползватели не гарантира повече пари за издръжка на сървъри и платени услуги. В този смисъл, търсим хостинг решение, за което:

1. Да не плащаме на месечна база (или ако плащаме, то да е минимална сума)
2. Плащанията да не зависят от използваното място, памет или процесорно време
3. Да имаме достъп до данните, дори и при неплатени сметки

### Непрекъсваемост и възстановяемост на услугата

Като следствие от бюджета, Организацията няма служители на пълно работно време. В същото време, основните кампании са за дарения от спешно естество (медицински операции), сумите са големи и не можем да си позволим те да са недостъпни, с което да се застраши човешки живот. В този смисъл, търсим решение, което:

1. Да скалира автоматично и без прекъсване при натоварване, при отпадане на сървър, препълване на диск
2. Да има активна защита от автоматизирани атаки
3. Да пази бекъп на физически отделна система

### Прозрачност на операциите

Платформата Подкрепи.бг се основава на Прозрачност. Дарителите ни се доверяват, защото осигуряваме прозрачност, чрез отворен код, отворени данни/ трансакции, отворени решения. В този смисъл, трябва ни решение, което позволоява следното:

1. Всички операции и промени в данните на платформата трябва да са проследими.&#x20;
2. Финансовите трансакции трябва да дават информация откъде са дошли и как са изразходвани дарените пари
3. Никой (дори и админите) не трябва да може да променя базата ръчно или през скрипт - т.е. историята остава така, както се е случила

### Независимост

Като следствие на бюджета, нямаме назначени постоянни юристи, финансисти, медицински експерти, програмисти или админи. Ограничени сме и от таксите за странични услуги, като банки и парньори за разплащания. В този смисъл, трябва да сме независими по отношение на:

1. Независимост от знания - документираме, за да не зависим от знанието на единични хора
2. Независимост от единствен доставчик на услуга - например хостинг на сървъри. Трябва да търсим поне два доставчика за да си осигурим независимост
3. Независимост от трети страни - искаме данните да стоят в България или най-далече - в рамките на ЕС

## Функционални изисквания

1. Модул **Регистрация** и управление на права на потребители
2. Модул **Кампании** - създаване, одобряване, събиране на дарения и приключване
3. Модул **Плащания** - дарения и преводи към потребителски сметки
4. Модул **Администрация** - управление на платформата
5. Модул **Прозрачност** - рипорти, анализ на данни и аномалии
6. Модул **Комуникация** - тикетинг система за потребителски въпроси и управление на специфични казуси

## Вдъхновения

Тук са нещата, които искаме (ако е възможно) да успеем да постигнем и когато взимаме решения, опитваме да не заключим тези възможности.

### Локализация и глобализация

Платформата стартира с фокус България, но искаме да може да се използва и в други държави.&#x20;

### Сървъри и хостинг доставчици

Мечтаем за силно разпределена среда, в която всеки да може да дари не само пари, но и изчислителна мощ(computing power). В този смисъл, търсим мулти-хостинг хибридно решение, с което да ползваме няколко български хостинг доставчици или сървъри от частни компании и дори -  лични компютри.&#x20;

### Да покажем, че е възможно!

Реализирането на такъв проект е изключително трудно не само технически, но и като легално, финансово и експертно знание - виж Ограничения. Искаме да проправим пътеката и да оставим "рецепта", която да може да се ползва и за реализация на други неправителствени публични проекти.
