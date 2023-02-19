# Домашнее задание к занятию «Testability, автотесты, введение в ООП: объекты и методы»

##  Инструкция к выполнению домашнего задания

Перед тем как отправить своё решение на проверку преподавателю, сверьтесь с чеклистом.

<details>
  <summary> 1. В решении выполнены все требования задания</summary>

Убедитесь, что все требования задания выполнены. Для этого перед отправкой внимательно прочтите весь текст условия задания и соотнесите сказанное в нём с вашим решением. Навык самопроверки работы перед ревью пригодится вам как при обучении, так и на работе.

  ---

</details>

<details>
  <summary> 2. Проект и репозиторий настроены правильно</summary>

Репозиторий должен быть папкой вашего idea-проекта. Обратите внимание, что репозиторием не должна быть папка, в которой лежит папка проекта, он сам должен быть папкой проекта. В нём должны быть соответствующие файлы и папки — `src` и другие.

Не забудьте создать .gitignore-файл в корне проекта и добавить туда в игнорирование автогенерируемую папку `out` и папку настроек идеи `.idea`.
  
---
</details>

<details>
   <summary> 3. Что делать, если возникли сложности :new: </summary>

Это здорово. Если их преодолевать правильно, то можно получить большую образовательную пользу для себя. Периодическое возникновение вопросов, недопонимание пройденного материала — нормальная и неотъемлемая часть обучения. А мы здесь, чтобы помочь вам пройти этот путь.

### Что делать, если непонятна теория
1. Если подобный вопрос разбирался на лекции, посмотрите ещё раз раздел с этой темой в видеозаписи.
1. Если вопрос не решился, попробуйте поискать ответ самостоятельно в интернете, этот навык пригодится вам в работе.
1. Если самостоятельно разобраться не удалось, задайте вопрос в общем чате, мы обязательно поможем.

### Что делать, если непонятно условие задания
1. Прежде чем задать вопрос по условию задачи, перечитайте его ещё раз и убедитесь, что в тексте условия нет прямого ответа на этот вопрос. Умение работать с текстом — важный навык работы с информацией.
1. Если ответа на свой вопрос в тексте условия не увидели, задайте его в общем чате, мы раскроем детали условия.

### Что делать, если не получается задача
Если ваша проблема — это **ошибка компиляции** — подчёркивает красным, не даёт запустить программу, сборки проекта, CI и прочие подобные ошибки, то:
1. Найдите и прочитайте текст ошибки, который вам подсвечивает идея или логи. «Подчёркивает красным» — это не описание ошибки.
1. Попробуйте понять текст ошибки, при необходимости воспользуйтесь переводчиком. Не страшно, если вы переведёте неточно, тут главное — сам процесс: со временем и с нашей помощью вы будете это делать лучше и лучше, но, пропуская этот этап, вы не сможете научиться это делать.
1. Если не получилось понять ошибку по её тексту, попробуйте её загуглить и изучить подобную ошибку у других людей. Попробуйте примерить решения их проблем на свой код. Соотнесите найденные описания ошибки с пройденной теорией.
1. Если всё равно ваши трудности не разрешились, напишите в общий чат, обязательно указав:
    1. название задачи и ссылку на условие;
    1. ссылку на вашу работу;
    1. текст и скриншот, не фотографию, ошибки;
    1. ваши размышления и описание шагов, которые вы совершили для решения.

Если ваша проблема — это **ошибка исполнения**, программа умирает уже после запуска, или она **отрабатывает неправильно**, из-за чего ваши тесты не проходят, то:
1. Воспользуйтесь отладчиком для пошагового анализа работы вашей программы. Так вы или убедитесь в неправильности придуманного вами алгоритма, или найдёте конкретное место, где ожидаемое поведение программы разошлось с фактическим.
1. Если проблему найти не получилось, напишите в общий чат, обязательно указав:
    1. название задачи и ссылку на условие;
    1. ссылку на вашу работу;
    1. конкретное и подробное описание проблемы или затруднения при решении задачи. «Помогите, что-то не так» — это не описание;
    1. подробное описание вашего анализа программы с помощью отладчика вместе со скринами;
    1. ваши размышления и описание шагов, которые вы совершили для решения.
  ---

</details>


<details open>
  <summary>4. Отформатирован код :new: </summary>

Кроме правил, нарушение которых приводит к ошибкам компиляции, есть ещё и [правила форматирования кода](https://google.github.io/styleguide/javaguide.html), соблюдение которых обязательно при написании программ.

С большинством проблем может справиться автоформатирование в идее. Для этого выберите `Code -> Reformat code` в меню или используйте горячие сочетания клавиш. В меню будет показано актуальное сочетание для вашей операционной системы. Так, идея поправит неправильные отступы, пробелы и некоторые другие ошибки. Следите, чтобы у `if-else`, `for`, `while` всегда были `{}`.

Проблемы с именованием сущностей нужно решать самим. Так, все ячейки, кроме `final`-констант, и методы должны писаться [камелкейсом](https://ru.wikipedia.org/wiki/CamelCase) с **маленькой** буквы, а классы и интерфейсы — камелкейсом с **большой** буквы.

Мы вам настоятельно советуем всегда держать код в отформатированном виде во время разработки, со временем глаз привыкнет, и вы почувствуете, насколько это облегчает поиск ошибок в коде и его анализ. В любом случае перед отправкой кода на проверку его обязательно нужно отформатировать, иначе он может быть отправлен на доработку без более глубокой проверки на этой итерации.
</details>

## Задание 1. Мили — модернизация (обязательное к выполнению)

Вы уже научились создавать классы и методы. Поэтому вам необходимо модернизировать [приложение для расчёта миль](./PRIMITIVES.md). Теперь сама логика расчёта будет находиться в специально выделенном классе сервиса, а в Main мы будем лишь создавать объект этого сервиса и вызывать его метод, передавая аргументами все необходимые данные для расчёта. Получив от вызова метода рассчитанный результат, мы выведем его на экран.

#### Этапы выполнения
1. Создайте класс `BonusMilesService` (`File -> New -> Java Class`, вводите название и нажимаете `Enter`).
1. Определите в нём метод `calculate`, который:
    1. принимает на вход один параметр: `cost` типа `int`;
    1. анализируя значение переданного параметра, возвращает рассчитанное количество миль (тип — `int`).

Разместите следующий код в классе `Main`:

```java
public class Main {
    public static void main(String[] args) {
        BonusMilesService service = new BonusMilesService();
        int price = 10_000;
        int miles = service.calculate(price);
        System.out.println(miles);
    }
}
```

Убедитесь, что выводимое в консоль значение соответствует результатам предыдущей версии приложения.

#### Результат
На проверку отправьте ссылку на ваш публичный репозиторий GitHub с решением.

## Задание 2*. Индекс массы тела (необязательная задача)

Вы решили написать сервис, который рассчитывает индекс массы тела (body mass index).

#### Этапы выполнения
1. Самостоятельно собрать информацию о том, какие входные данные нужны для расчёта, вы же умеете гуглить 😉
1. Создать класс `BmiService` с методом `calculate`. Помните, что вы считаете индекс, а не выдаёте диагноз.
1. Продемонстрировать в `Main` по аналогии с первой задачей:
    1. создание объекта,
    1. вызов метода `calculate`,
    1. печать в консоль результата,

#### Результат
На проверку отправьте ссылку на ваш публичный репозиторий GitHub с решением.

## Задание 3*. Кредитный калькулятор (необязательная задача повышенной сложности)

Вам поручили написать кредитный калькулятор, который считает как на сайте. Но формулы, естественно, не дали.

Вам нужно провести небольшой анализ и написать свой `CreditPaymentService`, который умеет рассчитывать ежемесячный платёж (см. аннуитетный платёж).

Параметры, их количество, типы, а также формулу вам необходимо определить исходя из скриншотов ниже.

Обратите внимание: на тех же данных ваш сервис должен считать так же.

Чтобы это продемонстрировать, в `Main` создайте объект и три раза вызовите его метод `calculate`. Результаты каждого вызова выводите в консоль.

Скриншоты для решения задачи. Важно: это не реальный сервис.

![image](https://user-images.githubusercontent.com/53707586/145564347-174ef746-013e-4793-bda1-79d81ac18e65.png)
![image](https://user-images.githubusercontent.com/53707586/145564368-0c1aaa9c-563b-4177-9ad6-a9f9adef8f92.png)
![image](https://user-images.githubusercontent.com/53707586/145564380-5140f2ab-312c-46c1-b423-1e5c209617b5.png)

#### Результат
На проверку отправьте ссылку на ваш публичный репозиторий GitHub с решением.

Каждое задание выполняйте в отдельном репозитории.