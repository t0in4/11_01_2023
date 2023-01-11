# Слова и предложения

Предположим, если текст содержит предложения, которые в среднем имеют более 10 слов в каждом предложении, то этот текст трудно читать. А если в каждом предложении меньше 10 слов, то этот текст легко читать. 

Ввод содержит одну линию текста. 

Вывод "HARD", если текст трудно читать, и "EASY" если текст легко читать.

Например, первый пример содержит два предложения с 6 и 10 словами (число также считаются как слова), поэтому слов в среднем, в каждом предложении меньше чем 10.

Во втором примере, также два предложения, но с 6 и 16 словами, поэтому слов в среднем 11 и это более 10 слов.

Если среднее равно 10, то текст всё ещё рассматриваем как легкий в чтении.

Примеры:

1
ввод: 
### This text is simple to read! It has on average less than 10 words per sentence.
вывод:
###  EASY

2
ввод:
###  This text is hard to read. It contains a lot of sentences as well as a lot of words in each sentence
вывод:
### HARD
