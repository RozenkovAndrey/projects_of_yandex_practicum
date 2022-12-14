# Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок.


# Статус проекта: Завершен

# Описание проекта:

В проекте были определены характеристики, влияющие на выдачу банком кредита его клиентам.


# Использованные библиотеки:
pandas, matplotlib, seaborn


# Использованные данные:
/datasets/data.csv - входные данные от банка — статистика о платёжеспособности клиентов;

# Основные выводы:

При группировке клиентов по количеству детей можно сделать вывод, что наиболее надежными по возврату кредита клиентами являеются люди без детей.
Процент не возврата кредита по этой категории составляет 7,54%. Наименее надежная: родители 4х детей процент невозврата - 9.76%.
Для оценки категории родителей с 5-ю детьми необходимо больше данных.

Наиболее надежной категорией среди клиентов по семейному статусу являются вдовы/вдовцы с процентом задержки по кредиту 6.62%.
Наименее надежные - женатые/замужние. Их процент задержек по кредиту составляет 9.76%.

Наиболее надежной категорией среди клиентов по уровню дохода являются клиенты с уровенм дохода D - процент задолженности 6,02%. 
Наименее надежные - с категорией C. Их процент задолженности составляет 8.5%.

Наиболее надежной категорией среди клиентов по целям для кредита являются те, 
кто берет кредит на операции с недвижимостью - процент задолженности в этой группе -7.26%. Наименее надежные - категория с операциями с автомобилем.
Их процент задолженности составляет 9.35%.
