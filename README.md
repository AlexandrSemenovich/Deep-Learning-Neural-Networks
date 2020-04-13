# Deep-Learning-Neural-Networks
# Описание модели
Данная модель представляет собой Свёрточную нейронную сеть, суть которой заключается в применении операции свёртки к исходному изображению. Сверточные сети отличаются очень высокой способностью к распознаванию паттернов на изображениях, поэтому их чаще всего применяют в работах с доменами, связанными с обработкой изображений.

Сверточные нейронные сети работают на основе фильтров, которые занимаются распознаванием определенных характеристик изображения (например, прямых линий). Фильтр — это коллекция ядер; иногда в фильтре используется одно ядро. Ядро — это обычная матрица чисел, называемых весами, которые “обучаются” (подстраиваются, если вам так удобнее) с целью поиска на изображениях определенных характеристик. Фильтр перемещается вдоль изображения и определяет, присутствует ли некоторая искомая характеристика в конкретной его части. Для получения ответа такого рода совершается операция свертки, которая является суммой произведений элементов фильтра и матрицы входных сигналов. С помощью операции свёртки мы получаем фичи, которые свёрточная сеть использует при обучении. Размер ядра сверточной нейронной сети определяет количество фич, которые будут объединены для получения новых фич на выходе.

# Параметры модели
Данная нейронная сеть была обучена на 50 эпопах с размером батча 4. Слоев свертки у нее 2( первый слой свертки имеет 3 входа и 6 выходов, а второй слой свертки имеет 6 входов и 16 выходов). Темп обучения данной нейросети 0.001 и коэффициент 0.9 
# Результаты 
1) Точность с тестовыми данными 

![Image alt](https://github.com/{AlexandrSemenovich}/{Deep-Learning-Neural-Networks}/raw/{master}/{https://github.com/AlexandrSemenovich/Deep-Learning-Neural-Networks/blob/master/%D0%93%D1%80%D0%B0%D1%84%D0%B8%D0%BA%D0%B8/%D0%90%D0%BA%D0%BA%D1%83%D1%80%D0%B0%D1%82%D0%BD%D0%BE%D1%81%D1%82%D1%8C%20%D1%82%D0%B5%D1%81%D1%82%20%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5.png}/image.png)

2) Точность с тренировочными данными 



3) Потери с тестовыми данными



4)Потери с тренировочными данными
