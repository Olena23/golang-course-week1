# Високосный год

Проверьте год и сообщите, является ли он високосным.

Трудность здесь в том, что високосный год в григорианском календаре приходится:

```Текст
на каждый год, который нацело делится на 4
   кроме каждого года, который нацело делится на 100
     если только год не будет нацело делиться на 400
```

Например, 1997 год - это не високосный год, а 1996 високосный год. 1900 - нет, а 2000 да.
Вот сслыка с хорошим объяснением почему так [this youtube video][video].

[video]: https://www.youtube.com/watch?v=WWAUJjVgp08

## Запуск тестов
Чтобы запустить тесты  просто выполние комманду `go test` в папке с упражнением или открыв файл с тестами в редакторе (VS Code) и нажав кнопку ***Run Tests / Запустить тесты***

## Source

JavaRanch Cattle Drive, exercise 3 [http://www.javaranch.com/leap.jsp](http://www.javaranch.com/leap.jsp)
