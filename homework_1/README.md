Честно говоря, особо описывать по поводу решения нечего :(  
Сперва запустил бейзлайновое решение (первый сабмит) и затем поставил базовую модель на обучение на 3 эпохах (второй сабмит), но до дедлайна, как видно, все равно не успел. Немного написал об этом в комментарии на гуглформе. Прикрепляю скриншоты с обоими сабмитами.

Сабмит 1 - до дедлайна:
![score1](https://github.com/leapnprog/MADE_2019_cv/blob/master/homework_1/score1.png)

Сабмит 2 - через 2 часа после дедлайна (это скор на паблике, на прайвате - 17.28632, на всякий случай):
![score2](https://github.com/leapnprog/MADE_2019_cv/blob/master/homework_1/score2.png)

Скрипт для запуска второго сабмита:  
python hack_train.py --name "another_submit" --data "PATH_TO_DATA" --epochs 3 --gpu
