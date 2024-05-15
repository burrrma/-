1) Чтобы создать навык с данным функционалом - нужно создать функцию в Яндекс Облаке, выбрать язык программирования Python и создать там четыре файла: credentials.json, token.json, requirements.txt и index.py.
index.py - это основная функция, которая обеспечивает работу навыка. Туда нужно добавить текст из файла index.py.
В остальные три файла нужно также добавить содержимое соответствующих файлов из репозитория.
![image](https://github.com/burrrma/Developing-the-Alica-Voice-Assistant-Skill-for-working-with-the-HSE-Schedule-and-News/assets/114211302/a1c6ce29-8788-4cee-953c-ab595be70380)
2) Далее нужно создать навык в Яндекс Диалогах и в поле Backend выбрать Функция в Яндекс Облаке и указать созданную ранее функцию:
![image](https://github.com/burrrma/Developing-the-Alica-Voice-Assistant-Skill-for-working-with-the-HSE-Schedule-and-News/assets/114211302/4f8590e7-597a-4593-84dc-02e7fc80c994)
3) В поле Хранилище данных поставить галочку - эо нужно для сохранения данных о пользователе
![image](https://github.com/burrrma/Developing-the-Alica-Voice-Assistant-Skill-for-working-with-the-HSE-Schedule-and-News/assets/114211302/8f3e058f-4c91-4381-abcb-b6b97ea1d0dd)
4) Заполнение остальных полей в Основных Настройках не влияет на работу навыка, достаточно просто заполнить необходимые для заполнения
5) В разделе Интенты добавить интенты в соответствии с файлом intents, в ID нужно указать соответствующее ID из комментария к каждому интенту в файле,
заполнение поля Название не влияет на корректность работы навыка, в поле Грамматика нужно вставить содержимое файла intents для каждого интента:
![image](https://github.com/burrrma/Developing-the-Alica-Voice-Assistant-Skill-for-working-with-the-HSE-Schedule-and-News/assets/114211302/7e3b3a97-7fc7-4436-a450-a7acb2822553)
6) В разделе Интенты в файл Сущности нужно вставить содержимое файла entities из репозитория:
![image](https://github.com/burrrma/Developing-the-Alica-Voice-Assistant-Skill-for-working-with-the-HSE-Schedule-and-News/assets/114211302/e583c733-fb21-4cde-a244-ca73833bcd53)
7) Тестировать навык можно в разделе Тестирование
8) Для проверки навыка в голосовом режиме нужно опубликовать навык в приватном режиме
