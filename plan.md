# Анализ и планирование работ по долгосрочным задачам

Простые, типовые задачи обычно не требуют серъёзной аналитики и планирования. Их легче всего вести в трекере. Главное, что требуется по таким задачам — вовремя оповещать заказчиков, когда работы будут выполнены.

Когда идёт работа по долгосрочным, сложным и непонятным техническим задачам, в которой задействованы инженеры из разных команд, требуется дополнительная координация всех участников, разграничение этапов и зон ответственности. Для этого можно создать, например, общедоступную страничку в Confluence ("на вики"), добавить к ней всех участников, проанализировать задачу и представить этапы работ в таблице.

Конечно же, отдельные технические задачи нужно по-прежнему вести в командном трекере, но свести вместе всех заинтересованных в решении большой задачи и окинуть взглядом весь процесс проще всего на общей страничке и в табличном виде.

## Шаблон плана работ

Ниже представлен возможный вид странички с планом работ по долгосрочной задаче. Выделенный <в скобках> текст нужно заменить на свои значения.

### Общие сведения

Здесь собираем требования и пожелания от продуктовой команды <название команды> по задаче <краткое описание задачи>. Проведём аналитику и составим план работ.

- Задача: <ссылка на задачу в трекере, если есть>
- Заказчики (контакты от команды): <ссылки на людей из продуктовой команды, кого можно спрашивать по задаче>
- Исполнители (контакты от DevOps): <кто исполнители или ответственные со стороны DevOps-инженеров>

### Краткая суть задачи

<В свободной форме, со слов заказчика описываем требования, пожелания или ТЗ. Что они хотят получить в конце?>

### Анализ требований

| N | Требование по задаче                                     | Что есть для решения задачи                                                             |
|---|----------------------------------------------------------|-----------------------------------------------------------------------------------------|
| 1 | <одна конкретная фича, которая требуется заказчикам>     | <Какие инструменты уже есть для решения, а что потребуется разработать/доработать?>     |
| 2 | <вторая фича>                                            | <Какие инструменты уже есть для решения, а что потребуется разработать/доработать?>     |
| 3 | <третья фича>                                            | <Какие инструменты уже есть для решения, а что потребуется разработать/доработать?>     |
| 4 | ...                                                      | ...                                                                                     |
| 5 | ...                                                      | ...                                                                                     |

### План работ

| N | Этапы работ                       | Планируемые объемы работ | Фактические объёмы   | Планируемый ввод в эксплуатацию | Статус      | Ответственный за реализацию от DevOps | Координатор со стороны заказчика          | Ограничения или возможные проблемы. Комментарии                              |
|---|-----------------------------------|--------------------------|----------------------|---------------------------------|-------------|---------------------------------------|-------------------------------------------|------------------------------------------------------------------------------|
| 1 | Анализ требований                 | <трудочасы по плану>     | <трудочасы по факту> | <дата или месяц сдачи этапа>    | <Решено>    | <исполнители от DevOps>               | <Кто будет проверять и принимать работу?> | ...                                                                          |
| 3 | <отдельный логический этап работ> | <трудочасы по плану>     | <трудочасы по факту> | <дата или месяц сдачи этапа>    | <Не готово> | <исполнители от DevOps>               | <Кто будет проверять и принимать работу?> | <Возникшие проблемы или ограничения для реализации этапа. Любые комментарии> |
| 2 | <отдельный логический этап работ> | <трудочасы по плану>     | <трудочасы по факту> | <дата или месяц сдачи этапа>    | <В работе>  | <исполнители от DevOps>               | <Кто будет проверять и принимать работу?> | <Возникшие проблемы или ограничения для реализации этапа. Любые комментарии> |
| 4 | <отдельный логический этап работ> | <трудочасы по плану>     | <трудочасы по факту> | <дата или месяц сдачи этапа>    | <Решено>    | <исполнители от DevOps>               | <Кто будет проверять и принимать работу?> | ...                                                                          |
| 5 | <отдельный логический этап работ> | <трудочасы по плану>     | <трудочасы по факту> | <дата или месяц сдачи этапа>    | <Решено>    | <исполнители от DevOps>               | <Кто будет проверять и принимать работу?> | ...                                                                          |
| 6 | ...                               | ...                      | ...                  | ...                             | ...         | ...                                   | ...                                       | ...                                                                          |
| 7 | ...                               | ...                      | ...                  | ...                             | ...         | ...                                   | ...                                       | ...                                                                          |
| 8 | ...                               | ...                      | ...                  | ...                             | ...         | ...                                   | ...                                       | ...                                                                          |
| 9 | ...                               | ...                      | ...                  | ...                             | ...         | ...                                   | ...                                       | ...                                                                          |
