Щоб запустити проект, необхідно виконати наступні команди:

1. Завантажити проект з репозиторію
2. Встановити залежності
3. Запустити проект командою uvicorn main:app --reload
4. Перейти за посиланням http:///127.0.0.1:8000/docs#/default/get_paraphrase_paraphrase_get
5. Ввести в поле tree фразу для перефразування 
6. Ввести в поле Limit кількість бажаних перефразованих фраз
7. Пiсля виконання даних дiй, вiдповiдь буде виведена в форматi JSON, та також створений локально файл
пiд назвою output.json, де будуть збережені перефразовані фразb
