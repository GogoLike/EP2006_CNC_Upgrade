View this project on [CADLAB.io](https://cadlab.io/project/25653). 

## EP2006_CNC_Upgrade Project

# Стиль работы.

Назначение веток:

main ------- релиз

testing ---- проверки

dev -------- разработка


Под каждую задачу/фичу/идею создается отдельная ветка от dev, включающая в название краткое описание задачи/фичи/идеи.

Для работы над отдельным фрагментом схемы в свободной зоне создается вспомогательный лист, в котором и производится работа над задачей/фичей/идеей.

По итогу подхода к работе или для сохранения промежуточных этапов производятся commit'ы, содержащие информацию о проделанной работе (* изменение, - удаление, + добавление).

После завершения работы над задачей/фичей/идеей создается pull-request на слияние с dev.

После всех объединений делается слияние dev -> testing.

После тестирования и проверок делается слияние testing -> main.

Игорь тестирует
Константин ознакомился
