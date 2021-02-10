# **Счетчики JoCoCo:**

### *BRANCH* 
Считает процент выполнения кода в ветках if/else/switch; Выбрала этот счетчик, т.к. метод в задании сделан с использованием for, if. Счетчик вычисляет количество веток определенное этими операторами и определяет количество выполненных и пропущенных. Поскольку одна ветка может включать в себя несколько инструкций байт-кода результат анализа каждой строки подсвечивается в зависимости от количества инструкций покрытых тестом:
- Красный: Не выполнено ни одной инструкции ветки;
- Желтый: Выполнено часть инструкций ветки;
- Зеленый: Выполнены все инструкции ветки; 
  Доступен даже при отсутствии отладочной информации;
  
### *INSTRUCTIONS* 
Считает количество инструкций в байт-коде, которые были исполнены.
Покрытие описывается как процент выполненных и пропущенных инструкций кода. Независит от форматирования файла исходного кода. Доступен даже при отсутствии отладочной информации;

### *LINE* 
Проверяет исполненный код по полям, т.е., если хотя бы одна инструкция была исполнена, то код строки исполнен.
Результат анализа каждой строки подсвечивается в зависимости от количества инструкций покрытых тестом:
- Красный: Не выполнено ни одной инструкции;
- Желтый: Выполнено часть инструкций;
- Зеленый: Выполнены все инструкции;
  Для работы необходимо компилировать файл с включением отладочной информации;

### *COMPLEXITY*
Считает необходимое количество тест-кейсов, чтобы покрыть все возможные пути в коде.