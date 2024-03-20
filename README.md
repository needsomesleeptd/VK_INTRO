# VK_INTRO
Приложенные файлы:
* Features -- код генерации признаков, генерирует файлы test_features.csv, train_features.csv.
* ChoosingModel -- код анализа разлтичных моделей и отбора признаков, также там подбираются гиперпараметры и мотивация выбора модели(модели учаться, используя файлы test_features.csv, train_features.csv).
* OnlyTrain -- код исключительно обучения модели на test_features.csv, train_features.csv(это сгенерированные признаки, а не отобранные).
выбора модели(модели учаться, используя файлы test_features.csv, train_features.csv).
* PredictOnly -- код исключительно предсказания (с помощью сохраненной модели model.joblib), получает на вход именно отобранные признаки (получаются после скрипта OnlyTrain, и имеют префикс predict (Напр. predict_features_test.csv))

OnlyTrain, также генерирует submission.csv отбирая признаки и обучаясь на всех данных.