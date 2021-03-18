# Игра "Виселица" (hangman)
Игра написана в качестве учебной программы  на языке Ruby ver.2.7.0
## Описание
Программа загадывает слово и показывает такое количество подчёркиваний, сколько букв в слове.

Игрок начинает угадывать буквы, чтобы отгадать слово. Если буква есть в слове, то буква выводится 
на своём месте в слове (если таких букв несколько — то выводятся все), а если буквы нет — то программа рисует 
один элемент виселицы с человечком (верёвка, голова, шея, туловище, 2 руки, ноги — всего 7 элементов-попыток).

Если игрок не успел угадать слово раньше, чем виселица нарисована полностью, то он считается «повешенным».
Если слово отгадано — то игрок победил.

В игре буква `Ё` учитывается как `Е`, буква `Й` как `И`

## Настройка игры
Для добавления, либо изменения загадываемых игрой слов, необходимо оредактировать **/data/words.txt** файл.

## Запуск игры
#### Для запуска необходимо:
1. склонировать репозиторий
2. в терминале зайти в папку с программой
3. выполнить комманды: 
```
  bundle install
```
```
  bundle exec ruby main.rb
```

### Приятной Игры!
