Название проекта: Название проекта: выявление определяющих успешность игры закономерностей.

Описание исследования: Доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. Нужно отработать принцип работы с данными.

Цель исследования: Выявить потенциально популярный продукт и спланировать рекламные кампании.

Суть исследования. Нужно выявить определяющие успешность игры закономерности. Которые позволят сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. Нужно отработать принцип работы с данными. Неважно, прогнозируются ли продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.

Задачи исследования:
1.Открыть файл с данными и изучить общую информацию
2. Подготовить данные
3. Провести исследовательский анализ данных
4. Составить портрет пользователя каждого региона
5. Проверить гипотезы
6. Написать общий вывод

Нулевая и альтернативная гипотезы сформулированы исходя из задачи, где требуется проверить равенство средних значений отзывов 2 платформ и 2 жанров.
Выбран метод ttest_ind, т.к. он подходит для для проверки гипотезы о равенстве среднего двух генеральных совокупностей по взятым из них выборкам. Средние пользовательские рейтинги платформы Xbox One = Средние пользовательские рейтинги платформы PC.
Средние пользовательские рейтинги жанров Action ≠ средние пользовательские рейтинги жанров Sports.

Вывод:

Сначала был изучен датасет, его значения и параметры, затем построена гистограмма.
Исходя из первичного изучения данных, можно сделать вывод, что столбцы с оценками пользователей и критиков, а также с рейтингом имеют много пропусков. При изучении гистограмм сделан вывод, что самыми популярными платформами являются PS2 и PS3. Больше всего игр выпущено в 2010 году. Самым популярным жанром за все годы является Action. Самая популярная оценка критиков - 70. Самая популярная оценка пользователей в диапазоне 7.7 - 8.3. В категории E - больше всего игр.
Удалены строки с пропусками в столбцах с именем, годом выпуска и жанром. Обработаны значения tbd в столбце user_score. Данные в столбцах приведены к нужному виды. Найдены и удалены дубликаты. Добавлен столбец с суммарными продажами.
В ходе исследовательского анализа данных выявлены года, в которые выпущено больше всего игр - 2008, 2009. Лидирующей платформой по рпродажам за всё время является PS2. Построены графики распределения продаж по годам для самых популярных платформ. Выбран актуальный период для анализа: 2015-2016 года. Построен график распределения продаж по годам для платформам за актуальный период. Выделены лидирующие по продажам платформы - PS4 И XOne. Построен «Ящик с усами» по глобальным продажам игр в разбивке по платформам. На платформе PS4 слабая отрицательная корреляция по оценкам пользователей и слабая положительная корреляция по оценкам критиков. Большая часть оценок являются положительными. На платформе XOne значения очень похожи на PS4 имеется слабая отрицательная корреляция по оценкам пользователей и слабая положительная корреляция по оценкам критиков. 3DS имеет слабую положительную корреляцию по оценкам пользователей и слабую положительную корреляцию по оценкам критиков. Построены графики общего распределения игр по жанрам. Основная масса выпущенных игр в жанре Shooter.
Составлен портрет пользователя для каждого региона:
В северной Америке преобладают PS4 и XOne имея по более 50 млн продаж. Затем с долей менее 10 млн продаж 3DS, WiiU, X360.
В северной Америке самым популярным является жанр Shooter с почти 50 млн. продаж, Затем с 35 млн. Action, чуть менее 30 млн. Sports, с 20 млн. Role-Playing и 5 млн. у Misc.
Категория M занимает лидирующую позицию и более 40 млн. продаж в Северной Америке, немногим менее 40 млн. продаж у игр без категории. Категория E получила менее 30 млн. продаж, T в районе 25 млн, у E10+ немногим менее 20 млн. продаж.
В Европе лидирующую позицию занимает PS4 с продажами более 80 млн. Меньшая доля у XOne 30 млн. Затем с долей менее 10 млн продаж PC, 3DS, PS3.
В Европе самыми популярными явлются жанры Shooter с +-40 млн. продаж, Action с чуть менее 35 млн. и Sports с продажами немногим менее 30 млн. Role-playing занимает менее 20 млн., Racing менее 10 млн. продаж.
Категория M занимает лидирующую позицию и более 40 млн. продаж в Европе, немногим менее 40 млн. продаж у игр без категории и категории E, T в районе 20 млн, у E10+ немногим более 10 млн. продаж.
В Японии лидирующую позицию занимает 3DS. Затем с долей около 10 млн. идут PS4 и PSV. По 5 млн продаж у PS3 и WiiU.
В Японии самыми популярными явлются жанры Action с более 20 млн. продаж и Role-playing с долей менее 25 млн. Shooter, Misc и Adventure занимают по менее 5 млн. продаж.
В японии более 30 млн. проданных игр - без категории. Немного менее 10 млн. продаж у категории T. Менее 5 млн. у E, M и E10+.
В японии много проданных игр без рейтинга ESRB, это связано с тем, что возрастные рейтинги в Японии выдаются компанией CERO. На европейских проектах PEGI. Это объясняет наличие пустых значений в Европе и Северной Америке.
Были проанализированы игры, в актуальном периоде. Следует проводить рекламные компании на PS4 и XOne, в Северной Америке и Европе, в жанре Shooter, Action, с рейтингом от ESRB - M. Причиной следует объём продаж на этих платформах и регионах, популярность жанров и кол-во продаж игр с рейтингом M.
