# goit-js-hw-03
* принцип роботи масивів
* базові методи масивів
* специфіка використання цикла for … of для ітерації по масиву
* можливості при роботі з функціями
* різниця між глобальною та блоковою областями видимості

		Задача 1. Генератор slug.
! Термін slug — це зрозумілий людині унікальний ідентифікатор, який використовується у веб розробці для створення читабельних URL-адрес. Це завжди рядок у нижньому регістрі, слова якого розділені тире.
  Наприклад, замість того, щоб користувач побачив в адресному рядку mysite.com/posts/1q8fh74tx, можна зробити slug із назви статті. У результаті адреса буде приємнішою для сприйняття: mysite.com/posts/arrays-for-begginers.
  
  Напиши функцію slugify(title), яка приймає заголовок статті, параметр title і повертає slug, створений із цього рядка.
  
Значенням параметра title будуть рядки, слова яких розділені лише пробілами.
	* Усі символи slug повинні бути в нижньому регістрі.
 	* Усі слова slug повинні бути розділені тире.

	Задача 2. Композиція масивів.
Напиши функцію під назвою makeArray, яка приймає три параметри: 
  * firstArray (масив), 
  * secondArray (масив),
  * maxLength (число). 
Функція повинна створювати новий масив, який містить усі елементи з firstArray, а потім усі елементи з secondArray.

Якщо кількість елементів у новому масиві перевищує maxLength, функція повинна повернути копію масиву з довжиною maxLength елементів.
В іншому випадку функція повинна повернути весь новий масив.

	Задача 3. Фільтрація масиву чисел.
Напиши функцію filterArray(numbers, value), яка приймає масив чисел (numbers) та значення (value) як параметри. 

Функція повинна повертати новий масив лише тих чисел із масиву numbers, які більші за значення value.

Усередині функції:
  * Створи порожній масив, у який будеш додавати підходящі числа.
  * Використай цикл для ітерації кожного елемента масиву numbers.
  Використовуй умовний оператор if усередині циклу для перевірки кожного елемента и додавання до свого масиву.
  Поверни свій новий масив з підходящими числами як результат.
