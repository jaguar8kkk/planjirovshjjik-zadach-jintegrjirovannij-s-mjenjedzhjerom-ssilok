# integracija-algoritmizatora-celej-i-menedzhera-ssylok

#предложение Создать нестандартный файловый менеджер с нестандартными интерфейсом, реализованным, как пошаговый алгоритм (изображение имеется), где папки - это шаги алгоритма, и нестандартной логикой добавления файлов.

Предлагаю все файлы и папки хранить в папках по датам их добавления, а в шагах алгоритма хранить только ярлыки на эти файлы и папки. Пользователь создаёт ссылку на файл, и сам файл автоматически создаётся в общей директории. Также, при создании ярлыков, предлагать пользователю указать "срок годности" ярлыка - параметр отвечающий за то, во скольких шагах после данного отзеркалится ярлык.

Для начала, этого достаточно. Потом можно будет реализовать удобную систему поиска ветвей алгоритма, но эта задача уже сложнее.