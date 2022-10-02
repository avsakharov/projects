# Примеры выполненных проектов

В этом репозитории находятся некоторые из выполненных мной проектов в области машинного обучения, аналитики и теории управления. Связаться со мной можно по электронной почте: sakharov.av@phystech.edu

## Краткое описание проектов

Данные проекты были выполнены во время в рамках учебной работы на платформе Яндекс.Практикуме.

| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
| [Оценка коэффициента восстановление золота из руды](gold_recovery_rate) | Создание прототипа модели машинного обучения для компании, разрабатывающей решения для увеличения эффективности работы промышленных предприятий. Модель предсказывает коэффициент восстановления золота из золотосодержащей руды на основе данных, содержащих параметры добычи и очистки. Качество работы модели определялось по метрике sMAPE. | *pandas*, *numpy*, *sklearn*, *plotly* |
| [Определение выходной температуры стали](steel_temp_modeling) | Металлургический комбинат поставил задачу уменьшить потребление электроэнергии на этапе обработки стали. Необходимо построить модель, которая предскажет температуру стали на выходе из ковша. Модель должна определять температуру стали на выходе из ковша с заданной точностью по метрике MAE. | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn*, *xgboost*, *catboost* |
| [Определение токсичности комментариев](nlp_toxic_comments) | Обучение модели, которая будет классифицировать комментарии на позитивные и негативные (токсичные). Исходные данные представлены в виде набора комментариев с разметкой о токсичности правок. В качестве функционала качества берется F1-мера. Для выполнения задачи проводилась лемматизация и векторизация слов процедурой TF-IDF. | *pandas*, *numpy*, *re*, *nltk*, *sklearn*, *xgboost*, *catboost* |
| [Анализ распределения астероидов в Солнечной системе](astorb) | Исследование распределения астероидов по различным параметрам орбиты по базе данных Лоуэловской обсерватории. Особое внимание уделялось кентаврам и койперовским объектам, среди которых искались астероиды с полярной орбитой. | *pandas*, *matplotlib*, *seaborn* |
| [Разработка алгоритма управления движением автомобиля по заданной траектории]() | Разработка математической модели автомобиля, а также системы автоматического управления автомобилем с целью проезда по заданной на плоскости траектории методом NMPC (nonlinear model predictive control). | *numpy*, *casadi*, *scipy*, *matplotlib* |
