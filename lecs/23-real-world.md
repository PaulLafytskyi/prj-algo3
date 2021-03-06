# Алгоритмы в практических задачах

> Что такое хорошая алгоритмическая подготовка?

  Да, хорошая алгоритмическая подготовка важна для программиста. И нет, хорошая — это вовсе не заучивание алгоритмов из списка «Самых Важных Алгоритмов, Которые Должен Знать Каждый». На мой взгляд хорошая алгоритмическая подготовка должна стремиться дать программисту следующие три умения.

  Во-первых, это умение решать непонятные задачи. В нечетких формулировках жизненных задач видеть возможные строгие трактовки. По строгим трактовкам накидывать варианты решения. Всесторонне анализировать разные варианты и выбирать самый подходящий.

  Очевидно, для этого недостаточно просто знать алгоритмы. Нужно уметь “видеть их”, распознавать возможности их применения.

  Во-вторых, алгоритмическая подготовка должна прививать привычку анализировать эффективность каждого вашего решения. Не пропускать в критических местах квадратичные или экспоненциальные алгоритмы, и не закладывать в архитектуру программы идеи, которые потом невозможно будет реализовать достаточно эффективно.

  В-третьих, алгоритмическая подготовка должна помогать умело пользоваться готовыми инструментами. Базы данных — это сплошные структуры данных и алгоритмы. Причем на концептуальном уровне довольно простые и понятные — деревья поиска, хэштаблицы, SS-Table, …

  Например, зная, что индекс в БД — это просто дерево поиска, несложно понять, какие запросы могут быть выполнены быстро, а какие обречены на full-scan. Зная, как на каких алгоритмах работает полнотекстовый поиск в Lucene, можно предсказать, какие запросы к Elastic будут давать релевантные ответы, а какие — нет, и даже как это можно доработать.

  Если подводить итог:

  - Кроме самих алгоритмов — учитесь их распознавать в задачах реального мира.
  - Прививайте себе привычку анализировать эффективность кода, который вы пишите.
  - Изучайте алгоритмы под капотом у инструментов, которыми вы пользуетесь — это пригодится при их эксплуатации.

-- Павел Егоров, <https://tproger.ru/experts/7/>

## Литература

- https://stackoverflow.com/questions/9625246/what-are-the-underlying-data-structures-used-for-redis
- https://github.com/rodricios/autocomplete
- http://blog.scalyr.com/2014/05/searching-20-gbsec-systems-engineering-before-algorithms/
