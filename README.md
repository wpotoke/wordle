# wordle
Игра 5 Букв
Английское название данной игры «Wordle», в РФ ее можно назвать «5 Букв».



Ваша задача за 6 попыток отгадать слово из пяти букв. Игра должна подсказывать присутствие каких букв вы отгадали в слове, если правильно отгадываете еще позицию то необходимо пометить это другим цветом.



В этих примерах желтым цветом помечается угаданная позиция буквы, белым - присутствие буквы в слове.

Игра также должна проверять на корректность введенное слово, не должна принимать несуществующих слов.

Задача
Попробуйте реализовать аналог такой игры в python через консоль. Что вам понадобиться:

файл со словами, откуда вы будете случайным образом выбирать слово для игры.  В нем должны содержаться только существительные, состоящие из 5 букв. Где можно взять такой файл? Например, здесь. Правда нужно сперва исключить слова, длина которых не равна 5. Для выбора случайного слова вам понадобиться модуль random
Когда ваш файл будет готов, вы можете использовать его и для проверки существования введенных слов пользователем
 
Учитывать какие буквы из алфавита пользователь уже вводил, а какие нет
 
Разукрашивать слова при выводе в консоль. Для этого можете воспользоваться модулем colorama, вот русский гайд по использованию этого модуля
