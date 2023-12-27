Пользовательская документация
Инструкции по использованию
1. Начало смены
Прежде чем начать продажи, удостоверьтесь, что смена открыта. Если смена не открыта, система автоматически начнет новую смену.
2. Основное меню
Основное меню предоставляет следующие опции:
1.	Совершить продажу: Добавить продукты в корзину и завершить продажу.
2.	Сформировать отчет по продажам: Посмотреть отчет о продажах за все время.
3.	Сформировать ежедневный отчет: Получить отчет о продажах за текущий день.
4.	Сформировать еженедельный отчет: Получить отчет о продажах за последнюю неделю.
5.	Сформировать ежемесячный отчет: Получить отчет о продажах за последний месяц.
6.	Сформировать отчет за период: Ввести пользовательский период и получить отчет о продажах.
7.	Выйти в основное меню: Выйти из меню управления продажами.
3. Совершение продажи
Выберите опцию "Совершить продажу" и следуйте инструкциям:
•	Добавьте продукты в корзину.
•	Укажите количество продуктов.
•	Выберите метод оплаты: наличные или карта.
4. Формирование отчетов
Выберите соответствующую опцию отчета:
•	Сформировать отчет по продажам: Вывести общий отчет о продажах.
•	Сформировать ежедневный отчет: Получить отчет о продажах за текущий день.
•	Сформировать еженедельный отчет: Получить отчет о продажах за последнюю неделю.
•	Сформировать ежемесячный отчет: Получить отчет о продажах за последний месяц.
•	Сформировать отчет за период: Ввести пользовательский период и получить отчет о продажах.
5. Завершение смены
По завершении рабочего дня выберите опцию "Завершить смену". Система автоматически сформирует отчет о продажах за текущий день.
Описание команд и их функций
1.	make_sale(inventory_manager, cart_manager):
o	Добавляет продукты в корзину и завершает продажу.
2.	generate_sales_report():
o	Формирует общий отчет о продажах.
3.	generate_daily_report(inventory_manager):
o	Формирует отчет о продажах за текущий день.
4.	generate_weekly_report():
o	Формирует отчет о продажах за последнюю неделю.
5.	generate_monthly_report():
o	Формирует отчет о продажах за последний месяц.
6.	generate_report_by_period():
o	Позволяет пользователю ввести период и получить отчет о продажах за этот период.
7.	end_shift():
o	Завершает текущую смену и формирует отчет о продажах за день.
8.	calculate_and_display_sales_report(sales, report_name, total_sales, total_sales_cash, total_sales_card, inventory_report):
o	Вычисляет и отображает общий отчет о продажах.
9.	save_daily_report_to_file(report_filename, total_sales, total_sales_cash, total_sales_card, inventory_report):
o	Сохраняет ежедневный отчет в файл.
10.	generate_report_by_dates(start_date, end_date, save_to_file=True):
•	Генерирует отчет о продажах за заданный период и сохраняет в файл, если указано.
11.	generate_report_by_period(period_type):
•	Генерирует отчет о продажах в зависимости от выбранного типа периода (daily, weekly, monthly).
12.	generate_report_by_dates(start_date, end_date, save_to_file=True):
•	Генерирует отчет о продажах за заданный период и сохраняет в файл, если указано.