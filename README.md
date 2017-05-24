# b8
b8 compiler from MMCS SFedU


Credits:
1. Aliev M.
1. ~~Avakyan G.~~
1. ~~Bulanov D.~~
1. Ermolaev D.
1. ~~Ermolinsky A.~~
1. Fateev S.
1. Koval N.
1. Kubesh. E.
1. ~~Limarev V.~~
1. Nezhevsky N.
1. Ostapenko A.
1. Paterikin A.
1. Raskin A.
1. Rogov D.
1. ~~Silnyagin Y.~~
1. Cherkasov V.


| Team          | Dev1             | Dev2              |
| ------------- |:----------------:| :----------------:|
| RR            | Rogov D.         | Raskin A.         |
| AN            | ~~Avakyan G.~~   | Nezhevsky N.      |
| LK            | Kubesh. E.	   | Koval N.          |
| FB            | Fateev S.        | ~~Bulanov D.~~    |
| PC            | Paterikin A.     | Cherkasov V.      |
| OE            | Ostapenko A.	   | Ermolaev D.       |
| AE            | Aliev M.         | ~~Ermolinsky A.~~ |


Scientific Advisor: Mikhalkovich S.

Tasks:

RR  Rogov D.    Raskin A. 
- [x] **Парсер v2**
- [x] **Передаточная функция для реализации распространения констант**

Nezhevsky N.
- [x] Генерация трехадресного кода
- [x] Для каждого обратного ребра найти естественный цикл
- [x] Установить, все ли отступающие ребра обратные

Koval N.	Kubesh. E.
- [x] **Доступные выражения между базовыми блоками - множества e_gen(b) и e_kill(b)**
- [x] **Доступные выражения внутри ББЛ(+оптимизации)**
- [x] **Доступные выражения, итерационный алгоритм***
- [ ] Нисходящая часть алгоритма анализа на основе областей

Fateev S.
- [x] Разработка класса "область" с разновидностями "область тела" и "область цикла"
- [x] Формирование поседовательности областей R1,...,Rn в восходящем порядке

PC  Paterikin A.    Cherkasov V.
- [x] Создание CFG из базовых блоков
- [x] Поддержка goto и меток
- [x] Достигающие определения: вычисление gen_B и kill_B
- [x] Итерационный алгоритм для достигающих определений
- [x] Дерево доминаторов

Ermolaev D.
- [x]  Построить на CFG глубинное остовное дерево, перенумеровав элементы в порядке обратном посфиксному
- [x]  Переписание CFG с использованием высокоуровневой библиотеки QuickGraph
- [x]  Классификация ребер графа: наступающие, отступающие, поперечные
- [ ]  Восходящая часть алгоритма анализа на основе областей

AE  Aliev M.
- [x] Активные переменные внутри ББЛ
- [x] Живые переменные между ББЛ, множества use_B и def_B
- [x] Живые переменные - итерационный алгоритм
- [ ] Разработка класса для хранения f_r,IN[s] и f_r,OUT[B]


-------------------
- [ ] Модифицированный (ускоренный) алгоритм с правильной нумерацией базовых блоков
- [ ] 3 примера программ, дающих неправильные графы, найти отступающие ребра, не явл. обратными.
- [ ] оптимизация общего итерационного алгоритма обхода
