# Дальніміри TeraRanger

TeraRanger надає ряд легких сенсорів вимірювання відстані на основі інфрачервоної технології часу польоту (ToF). Вони зазвичай швидші і мають більший діапазон, ніж ехолокатори, і менші та легші, ніж системи на основі лазера.

PX4 підтримує:

- [TeraRanger Evo 60м](https://www.terabee.com/shop/lidar-tof-range-finders/teraranger-evo-60m/) (0.5 – 60 м)
- [TeraRanger Evo 600Гц](https://www.terabee.com/shop/lidar-tof-range-finders/teraranger-evo-600hz/) (0.75 - 8 м)

::: info PX4 також підтримує _TeraRanger One_ (необхідний адаптер I2C). Ця функція припинена.
:::

## Де купити

- TBD

## Схема розташування виводів

## Підключення

Усі сенсори TeraRanger повинні бути підключені через шину I2C.

## Конфігурація програмного забезпечення

Датчики увімкнені за допомогою параметра [SENS_EN_TRANGER](../advanced_config/parameter_reference.md#SENS_EN_TRANGER) (ви можете встановити тип датчика або те, що PX4 повинен автоматично визначити тип).

:::note
Якщо використовується автоматичне виявлення для датчиків Evo, мінімальні та максимальні значення діапазону встановлюються ​​на найнижчі та найвищі можливі показники у сім'ї Evo (наразі 0,5 - 60 м).
Для використання правильних максимальних/мінімальних значень слід встановити відповідну модель датчика Evo в параметрі (замість автоматичного визначення).
:::

:::tip
Драйвер для цього дальномера зазвичай присутній у вбудованому програмному забезпеченні. Якщо відсутній, вам також потрібно додати драйвер (`distance_sensor/teraranger`) до конфігурації плати.
:::

## Додаткова інформація

- [Довідник модулів: Датчик відстані (Драйвер): teraranger](../modules/modules_driver_distance_sensor.md#teraranger)