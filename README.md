Цели проекта

Обучение программированию на Java: Игра "Угадай слово" служит практическим примером для изучения основ программирования на языке Java, включая работу с массивами, строками и вводом/выводом данных.

Развитие логического мышления: Игра помогает развивать логическое мышление и навыки решения проблем, так как игроку нужно анализировать свои догадки и делать выводы на основе полученной информации.

Создание интерактивного приложения: Проект демонстрирует, как создать простое интерактивное приложение, которое взаимодействует с пользователем.
Описание функциональности

Инициализация игры: Программа выбирает слово, которое нужно угадать, и инициализирует массив для хранения угаданных букв.

Игровой процесс:

Пользователь видит текущее состояние слова (например, "_ _ _ a _") и количество оставшихся попыток.

Пользователь вводит букву, и программа проверяет, есть ли эта буква в загаданном слове.

Если буква угадана, она отображается в текущем состоянии слова. Если нет, количество попыток уменьшается.

Проверка результатов: Игра продолжается до тех пор, пока пользователь не угадает слово или не исчерпает все попытки. В конце игры программа выводит сообщение о результате.

Обработка ввода: Программа обрабатывает ввод пользователя, проверяя, является ли введенный символ буквой и не был ли он уже угадан.
Условия эксплуатации

Требования к системе: Для запуска программы требуется установленная Java Development Kit (JDK) версии 8 или выше.

Запуск программы: Пользователь должен скопировать код в файл с именем GuessTheWordGame.java, скомпилировать его с помощью команды javac GuessTheWordGame.java и запустить с помощью команды java GuessTheWordGame.

Ввод данных: Игра требует ввода букв с клавиатуры. Пользователь должен вводить только одну букву за раз.

Ограничения: Игра не учитывает регистр букв (например, 'A' и 'a' считаются одинаковыми), и не проверяет, вводил ли пользователь уже угаданную букву.
