ТЗ ИП-217 Game-of-life


1. Функциональность.

  1.1 Игра разрабатывается на языке программирования C++ с применением библиотеки “SFML-2.5.1”.
 
  1.2 Место действия этой игры — “вселенная” — это размеченная на клетки ограниченная плоскость. Каждая клетка на этой поверхности может находиться в двух состояниях: быть “живой” (заполненной) или быть “мёртвой” (пустой).
      Клетка имеет восемь соседей, окружающих её.
      Пользователь создаёт начальное состояние, а потом лишь наблюдает за её развитием. В игре можно создать процессы с полнотой по Тьюрингу, что позволяет реализовать любую машину Тьюринга.

  1.3 Распределение живых клеток в начале игры называется первым поколением. Каждое следующее поколение рассчитывается на основе предыдущего по таким правилам:
      в пустой (мёртвой) клетке, рядом с которой ровно три живые клетки, зарождается жизнь. 
      если у живой клетки есть две или три живые соседки, то эта клетка продолжает жить;
      в противном случае, если соседей меньше двух или больше трёх, клетка умирает (“от одиночества” или “от перенаселённости”).

2. Входные данные.

  2.1 Пользователь вводит начальное поколение посредством прямого нажатия на сетчатое поле через интерфейс программы.

  2.2 При запуске программы инициализируется первое поколение случайным образом, пользователь может отредактировать его или создать полностью свое поколение.

3. Интерфейс.

  3.1 Интерфейс программы - терминал операционной системы, вызываемый классом библиотеки “SFML”

  3.2 Интерфейс позволяет пользователю ставить симуляцию на паузу посредством нажатия клавиши “p”.
      Также пользовтель может изменять скорость симуляции через нажатие на стрелки на клавиатуре.
      где стрелка влево служит для замедления скорости игры, а стрелка вправо служит для ускорения игры.
