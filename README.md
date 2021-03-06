# Какие пункты из уроков есть

* Intro to HTML, HEAD, BODY, and HEADER
* HTML: Lists, Paragraphs, and Text Styling
* HTML: Displaying Data With Tables
* HTML: Images & Forms
* What is CSS?
* How to use Inline, Internal and External CSS
* CSS: Element, ID & Class Selectors
* CSS: Colors
* CSS: Backgrounds & Borders


# Задание 1

Рано или поздно ты станешь руководителем своего стартапа. И он будет настолько большим, что тебе потребуется своя команда.
Давай представим, как могла бы выглядеть внутренняя HR система в этом стартапе?

* Во вкладке браузера заголовок для твоей страницы это "HR система"
* Есть список кандидатов в виде таблице - в первом столбце ФИО, а во втором - результат хайринга ("пройдено", "запланировано", "принят оффер")
* Для каждого кандидата есть отдельная карточка. На ней должны быть ФИО, краткое описание, и фотография. Попробуй использовать абзацы и списки, а так же выдели жирным ключевую информацию. Добавь картинку (фотки можно взять из [специального сервиса, где их генерирует нейросеть](https://thispersondoesnotexist.com/))


# Задание 2

Давай немного улучшим эту систему и сделаем её более приятной для глаз

* Попробуй использовать якоря, чтобы нажать на имя в таблице и быстро попасть на карточку сотрудника
* Для карточек сотрудников добавь какой-нибудь ненавязчивый фоновый цвет, сделай скругление границ и добавь рамку. Используй css-классы для этого и отедльный файл со стилями
* Попробуй сделать картинку маленькой и круглой
* Сделай рамки у таблицы через id-селектор (граница должна быть одинарная)

# Задание 3

Нам 100% понадобится заводить новых кандидатов!

* В конце страницы сделай небольшую форму с полями name (текст), description (абзац) и кнопка submit.
* Форма не должна ничего сохранять, но можно в ней заводить данные
* Постарайся, чтобы все элементы формы были друго под другом


# Финал

На последок нужно провести небольшой рефакторинг, как и кода, так и приложения. Пройдись этому чеклисту

* Все элементы имеют отступы, ничто ни с чем не слипается
* Все стили вынесены в css-файлы (нет инлайн стилей)
* У таблицы одинарная рамка
* и т.д. в таком духе