# Newsfeed-Analysis-BI-
Исследование вовлеченности студентов учебной платформы ИТ-курсов 365datascience.com

**КОНТЕКСТ ЗАДАЧИ**
Новостная лента представляет собой раздел сайта с постоянными уведомлениями о новом контенте, новостях, достижении контрольной точки в обучении и o других видах активностей.  Этот элемент призван облегчить мониторинг прогресса в реальном времени и стимулирует вовлеченность пользователей, демонстрируя свежий контент каждый раз, когда пользователь входит на платформу. Новостная лента платформы 365datascience.com включает как посты, генерируемые автоматически, так и сообщения, созданные вручную. Автоматически сгенерированные посты уведомляют о достижении контрольной точки в обучении вроде завершения модуля, получения сертификата или перехода на следующий этап обучения. Сообщения, созданные вручную, напротив, демонстрируют мнения студентов, которыми они хотят поделиться с сообществом студентов внутри платформы.

**ЗАДАЧА** – общая цель проекта в том, чтобы определить, какие типы сообщений находят отклик у аудитории и установить потенциальные проблемы в этом разделе, наряду с выработкой предложений по усовершенствованию. Выбор визуализаций остается индивидуальным, но в качестве <ins>обязательных</ins> элементов должны присутствовать фильтры по всему диапазону дат (1 янв-31 мая 2023) и подтипам уведомлений.
Также необходимо ответить на <ins>следующие вопросы</ins>: 1. *Какой подтип постов наименее популярный, если судить по среднему количеству лайков? 2. Какой тип постов самый распространенный и самый редкий в абсолютных значениях? 3. Какой процент пользователей активно взаимодействовал с этой функцией? 4. Выскажите рекомендации по результатам построения дашборда, на что следует обратить внимание?*

Описание данных: два .csv файла отдельно и в виде книги в формате Tableau (.twbx)  с датой постов, их типом, подтипом и соответствующим количеством комментариев, лайков с 01-01-2023 по 31-05-2023.

**Столбцы**: 
Post Date – дата (д-м-гггг)
Post Subtype – подтип поста (Streak/Collection/Level/Couse Certificate/Text Post/Goal)
Post Type – общая принадлежность поста (Visual/Text Post)
Number of Comments – количество комментариев в конкретный день
Number of Likes - количество лайков в конкретный день
Number of Posts - количество постов в конкретный день

Интерактивная версия дашборда [здесь](https://public.tableau.com/app/profile/vasiliymakukha/viz/newsfeed_analysis_17396508993960/Dashboard1)

**ЗАКЛЮЧЕНИЯ И РЕКОМЕНДАЦИИ**
По итогам исследования были сформулированы выводы и даны ценные рекомендации (см. ниже).
<ins>Рекомендации</ins>: по нашим наблюдениям, сообщения типа Level доминируют в ленте новостей, превосходя все остальные подтипы. Их общее количество в два раза превышает количество постов, занявших второе место, - постов о сертификатах курсов. Несмотря на их частоту, тенденция показывает, что посты типа Level - наряду с подтипом Collection - вызывают минимальный интерес и редко побуждают пользователей ставить лайки.
Это говорит о том, что посты типа Level могут насыщать ленту новостей контентом, который пользователи не находят интересным, тем самым снижая их общее впечатление от функции. Рационально было бы пересмотреть способ создания таких постов и сократить их присутствие в ленте новостей. На первый план могут выйти более интересные посты, что потенциально повысит вовлеченность пользователей и интерес к функции - ведь на виду останутся более интересные посты, а не те, что набрали меньше лайков.
