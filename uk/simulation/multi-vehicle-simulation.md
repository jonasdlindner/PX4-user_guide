# Симуляція кількох рухомих засобів

PX4 підтримує симуляцію кількох рухомих засобів використовуючи наступні симулятори:

- [Симулятор Gazebo](../sim_gazebo_gz/multi_vehicle_simulation.md) (з та без ROS)
- [Симулятор Gazebo Classic](../sim_gazebo_classic/multi_vehicle_simulation.md) (з та без ROS)
- [Симулятор FlightGear](../sim_flightgear/multi_vehicle.md)
- [Симулятор JMAVSim](../sim_jmavsim/multi_vehicle.md)

Вибір симулятора залежить від рухомого засобу що моделюється, наскільки "якісна" потрібна симуляція (і для яких функцій), і скільки засобів потрібно симулювати одночасно.

- FlightGear це найбільш точний симулятор і в результаті найбільш ресурсомісткий. Він може бути використаний, якщо вам потрібна гарна симуляція, але не надто багато засобів за раз. Також його можна використати, якщо потрібно симулювати різні типи рухомих засобів одночасно.
- [Gazebo](../sim_gazebo_gz/README.md) менш точний і менш потужний та підтримує багато функцій, які не доступні для FlightGear. Він може симулювати набагато більше засобів за раз, ніж FlightGear, та дозволяє симулювати різні їх типи водночас. Він може використовуватись тільки на Ubuntu 20.04 і новіше. Зверніть увагу, що це наступник [Gazebo Classic](../sim_gazebo_classic/README.md) (дивіться нижче).
- [Gazebo Classic](../sim_gazebo_classic/README.md) менш точний і менш потужний та підтримує багато функцій та засобів, які не доступні для FlightGear. Він може симулювати набагато більше засобів за раз, ніж FlightGear, та дозволяє симулювати різні їх типи водночас.
- JMAVSim - це дуже легкий симулятор, який підтримує лише квадрокоптери. Рекомендується у випадку, якщо вам необхідно підтримувати багато квадрокоптерів та симуляція може бути приблизна.