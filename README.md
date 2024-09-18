# lesson19

## Попов Георгий Андреевич

# задачи 

1. Сложные высказывания:

- А ∧ В: «В Африке водятся жирафы, и в Мурманске идёт снег».
- А ∨ В: «В Африке водятся жирафы или в Мурманске идёт снег».
- ¬А: «В Африке не водятся жирафы».
- ¬B: «В Мурманске не идёт снег».
- А → В: «Если в Африке водятся жирафы, то в Мурманске идёт снег».
- A ↔ B: «В Африке водятся жирафы тогда и только тогда, когда в Мурманске идёт снег».

2. Отрицание высказывания:

«Винни-Пух не любит мёд или дверь в дом не открыта».

3. Что такое таблица истинности?

Таблица истинности — это таблица, отображающая все возможные значения логических переменных и результат работы логических операций над ними. Она показывает, при каких условиях логическое выражение истинно (истина) или ложно (ложь).

![image](https://github.com/user-attachments/assets/5fe41ca7-971c-453a-829f-aa8583a0c167)

Таблица истинности для операции «НЕ» содержит только две строки, поскольку она зависит только от одного логического значения (истина или ложь). Операции, использующие две переменные (например, «И» и «ИЛИ»), имеют 4 строки, поскольку каждая переменная может принимать два значения (0 или 1), что дает 2^2 = 4 комбинации. 

С количеством переменных:
- Для 3 переменных: 2^3 = 8 строк.
- Для 4 переменных: 2^4 = 16 строк.
- Для 5 переменных: 2^5 = 32 строки.

5. Порядок значений переменных в таблице истинности:
Обычно значения переменных записываются в порядке от старших к младшим, например: A, B, C и т.д. Это нужно для системности и единообразия, чтобы было легко сравнивать результаты и проводить анализ.

6. Когда истинно высказывание A И B? A ИЛИ B?
- A И B истинно, только если обе переменные A и B истинны.
- A ИЛИ B истинно, если хотя бы одна из переменных A или B истинна.

7. Электрические схемы для операций «И» и «ИЛИ»:
- Операция «И» может быть иллюстрирована схемой с параллельным подключением, где электрическое устройство работает только в случае, если оба входа активны.
- Операция «ИЛИ» иллюстрируется схемой с последовательным подключением, где устройство работает, если хотя бы один из входов активен.

8. Знаки для операций:
- «НЕ» обозначается символом ¬ или ~.
- «И» обозначается символом ∧.
- «ИЛИ» обозначается символом ∨.

9. Почему операции «И» и «ИЛИ» называются логическим умножением и сложением?
- Операция «И» называется логическим умножением, потому что она требует, чтобы все входы были истинными (похожим образом, как результаты умножения).
- Операция «ИЛИ» называется логическим сложением, так как истина достигается, если хотя бы один из входов истинный (похожим на сложение чисел).

10. Различие арифметического и логического сложения:
Арифметическое сложение работает с числами, а логическое сложение (например, операция «ИЛИ») работает с логическими значениями и ведет себя иначе: в логике 1 + 1 = 1, а в арифметике 1 + 1 = 2.

11. Сколько можно определить различных логических функций:
- С двумя переменными: 2^(2^2) = 16 различных функций.
- С тремя переменными: 2^(2^3) = 256 различных функций.

12. Исключающее ИЛИ против ИЛИ:
Операция «исключающее ИЛИ» (XOR) истинна, когда одно из высказываний истинно, но не оба, в то время как операция «ИЛИ» истинна, когда щито одно или оба высказывания истинны.

13. Исключающее ИЛИ как сложение по модулю 2:
Поскольку в операции «исключающее ИЛИ» истинность зависит от количества истинных входов, оно может быть представлено как простое вычисление по модулю 2.

14. Выражение A В с базовыми операциями:
A В можно записать как ¬(¬A И ¬B) с использованием операций «НЕ» и «И».

15. Доказательство логического равенства:
Логическое равенство можно доказать с помощью таблиц истинности (показав, что оба выражения дают одинаковый результат) или с помощью логических тождеств и преобразований.

16. Свойства исключающего ИЛИ:
Исключающее ИЛИ обладает свойствами коммутативности, ассоциативности и является тем элементом, что дает выходное значение 1, когда на входе нечетное количество единиц.

17. Обратимая операция:
Обратимая операция — это операция, для которой существует обратная операция. Например, «НЕ» и (в некоторых случаях) «исключающее ИЛИ» являются обратимыми.

18. Своиства исключающего ИЛИ для шифрования:
Операция «исключающее ИЛИ» обладает свойством, что повторное применение одного и того же оператора к тому же значению восстанавливает оригинал, что делает её полезной для простых методов шифрования.

19. «Если A, то B»:
В обычной речи это подразумевает причинно-следственную связь, тогда как в математической логике это представляет собой условное высказывание, которое истинно во всех случаях, кроме когда A истина, а B ложна.

20. Логическая формула «Если утюг горячий, то лоб холодный»:
U → L (где U — «утюг горячий», L — «лоб холодный»).

21. Формула «Неверно, что если утюг горячий, то лоб холодный»:
¬(U → L). 

Невозможно сразу сказать, каким является утюг и каким — лоб; мы можем сказать только, что хотя бы одно из высказываний неверно.

22. Импликация через «НЕ» и «ИЛИ»:
Импликацию можно выразить так: A → B ≡ ¬A ∨ B. Доказательство основано на таблице истинности.

23. Эквивалентность через «НЕ», «И» и «ИЛИ»:
Эквивалентность можно выразить как: A ↔ B ≡ (A → B) ∧ (B → A) ≡ (¬A ∨ B) ∧ (¬B ∨ A). 

24. Штрих Шеффера и стрелка Пирса:
Эти операции представляют интерес, так как они могут служить для определения всех остальных логических операций. Штрих Шеффера (NAND) и стрелка Пирса (NOR) являются универсальными логическими операциями.

25. Тождества для штриха Шеффера:
Обратите внимание, что НО операцией «A | B» через штрих Шеффера можно выразить: A | B = ¬(A NAND B). Аналогичные преобразования можно выполнить и для стрелки Пирса.

26. Формализация:
Формализация — это процесс перевода проблем или утверждений в формальный (математически точный) язык для последующего анализа или решения.

### ![image](https://github.com/user-attachments/assets/420c912a-37f0-4dd0-b53e-8d9b730becea)



