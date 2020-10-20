# Module_2
Эксплораторный анализ данных.

→ **Основные цели и задачи проекта:**

Цель проекта

Целью данного проекта является исследование взаимосвязи между условиями жизни, уровнем благополучия учащихся в возрасте от 15 до 22 лет и их академическими успехами по математике. Анализ проводится с целью заблаговременного выявления учашихся, находящихся в потенциальной группе риска.

Задача проекта

Глобальной задачей данного исследования является использование методов машинного обучения для построения модели, которая бы предсказывала результаты государственного экзамена по математике. Однако основной задачей данного проекта стоит именно проведение эксплораторного анализа данных с целью выявить наиболее релевантные переменные, которые будут включены в будущую модель.

→ **Краткая информация о данных:**

Анализируемый датасет содержит 29 потенциальных предикторов для предсказания финального количества баллов, набранного учеником по математике (score). Всего датасет содержит 395 наблюдений, однако среди некоторых переменных присутствует небольшое количество пропущенных значений.

→ **Этапы работы над проектом:**

Для каждой переменной был проведен анализ пропущенных значений, проверка на наличае выбросов для количественных переменных, а также анализ уникальных значений для категориальных переменных. В процессе анализа были рассмотрены все переменные и их взаимосвязь с зависимой переменной - количеством баллов по математике. 

→ **Ответы на вопросы саморефлексии:**

**Какой частью своей работы вы остались особенно довольны?**

Мне удалось закрепить на практике довольно простые, но очень полезные приемы работы с данными: разные способы создания датафреймов, написание простых функций, получение дескриптивных статистик.

**Что не получилось сделать так, как хотелось? Над чем ещё стоит поработать?**

Совершенно не получилась часть с визуализацией данных: у меня была абсолютно четкая идея того, какой график я хочу получить (я всегда рисую шаблон графика на бумаге, прежде чем реализовывать его на практике), однако знаний по библиотекам визуализации совсем не хватило. В данном проекте имело огромный смысл визуализировать взаимоотношение каждого предиктора и балла по математике (преобразовав независиму переменную для случаев работы с категориальными предикторами). Проблемы возникли на этапе работы с таблицей со сгруппированными данными: переменная группировки отображалась в таблице как индекс, и сама таблице не являлась датафреймом, с которым можно легко работать. Задавала эти вопросы в Slack, но исчерпывающего ответа, к сожалению, не получила. В общем и целом - была бы очень благодарна за дополнительный модуль по визуализации и работе с таблицами, это очень важно!

**Что интересного и полезного вы узнали в этом модуле?**

Некоторые особенности работы с разными типами данных.

**Что является вашим главным результатом при прохождении этого проекта?**

Думаю, главным результатом является способность сосредоточиться и сделать довольно большой объем работы. Мне была очень интересна тема проекта, однако отсутствие твердых знаний по визуализации немного огорчало.

**Какие навыки вы уже можете применить в текущей деятельности?**

Составление отчета по эксплораторному анализу любых данных, описание результатов с точки зрения статистики.

**Планируете ли вы дополнительно изучать материалы по теме проекта?**

Определенно да - по визуализации данных!


**Комментарий для ментора:**
Основная мысль сформулирована в разделе "что не получилось в проекте".
