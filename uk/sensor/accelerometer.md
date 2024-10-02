# Апаратне забезпечення та налаштування акселерометра

PX4 використовує дані акселерометра для оцінки швидкості.

Вам не потрібно прикріплювати акселерометр як окремий зовнішній пристрій:

- Більшість польотних контролерів, таких, як в [Pixhawk Series](/flight_controller/pixhawk_series.md), включають в себе акселерометр як частину польот контролеру [Inertial Motion (IMU)](https://en.wikipedia.org/wiki/Inertial_measurement_unit).
- Гіроскопи присутні як частина зовнішньої системи інерціальної навігації, ARHS або системи підвищеної точності глобальної навігації INS (../sensor/inertial_navigation_systems.md).

Потрібно відкалібрувати акселерометр перед першим використанням безпілотника:

- [Accelerometer Calibration](../config/accelerometer.md)