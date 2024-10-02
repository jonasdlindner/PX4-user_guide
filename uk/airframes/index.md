# Типи транспортних засобів та налаштування

PX4 підтримує численні типи транспортних засобів, включаючи різні конфігурації мультикоптерів, літаків, засобів вертикального злету та посадки(VTOL), наземних засобів, тощо.

Цей розділ пояснює, як збирати, конфігурувати та налаштовувати системи автопілотів на основі PX4 для кожного типу (багато з цих налаштувань є спільними для всіх типів).

:::info [Основні поняття > Типи дронів](../getting_started/px4_basic_concepts.md#drone-types) надають високорівневу інформацію про типи транспортних засобів і випадки використання, для яких вони найкраще підходять. :::

## Підтримувані транспортні засоби

Типи рам, які мають розробників, добре тестовані та підтримуються:

- [Багатокоптери](../frames_multicopter/index.md) (три-, чотири-, шести-, восьми- та навіть [омнікоптерні](../frames_multicopter/omnicopter.md) транспортні засоби)
- [Літаки (Фіксоване крило)](../frames_plane/index.md)
- [VTOL](../frames_vtol/index.md): [Стандартний VTOL](../frames_vtol/standardvtol.md), [VTOL з вертикальним зльотом](../frames_vtol/tailsitter.md), [VTOL з поворотними гвинтами](../frames_vtol/tiltrotor.md)

## Експериментальні транспортні засоби

Експериментальні рами - це ті типи транспортних засобів, які:

- У неї немає технічного обслуговування.
- Не регулярно тестується головною командою розробки.
- Можливо, не тестуються в CI.
- Не має необхідних характеристик для готових до виробництва засобів.
- Може не підтримувати деякі загальні конфігурації для типу транспортного засобу.

Наступні типи транспортних засобів вважаються експериментальними:

- [Дирижаблі](../frames_airship/index.md)
- [Автожири](../frames_autogyro/index.md)
- [Повітряні кулі](../frames_balloon/index.md)
- [Вертоліт](../frames_helicopter/index.md)
- [Марсохід](../frames_rover/index.md)
- [Субмарини](../frames_sub/index.md)

::: info Волонтери та контрибютори, [внесення](../contribute/index.md) нових функцій, нових конфігурацій каркасів або інших вдосконалень дуже вітається! :::

## Інші транспортні засоби

Повний набір підтримуваних типів транспортних засобів і їх конфігурації можна знайти в [Airframes](../airframes/airframe_reference.md).