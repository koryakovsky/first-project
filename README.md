commit 1
Начальная загрузка файлов

coomit 2
Изменил параметны модели
        'models': [KNeighborsClassifier()],
        'models__n_neighbors': range(2, 20),
        'preprocessor__num': [StandardScaler(), MinMaxScaler(), RobustScaler(), 'passthrough'],


на

        'models': [KNeighborsClassifier()],
        'models__n_neighbors': range 3, 18),
        'preprocessor__num': [StandardScaler(), MinMaxScaler(), RobustScaler(), 'passthrough'],



Переименование файла README

Добавление Gitignore

Добавление issue
