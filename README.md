# Домашнее задание к занятию "`Система мониторинга Zabbix. Часть 2`" - `Дёмин Максим`


### Задание 1

Что нужно сделать:
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон
Создайте Item который будет собирать информацию об загрузке CPU в процентах
Создайте Item который будет собирать информацию об загрузке RAM в процентах
Требования к результату
￼ Прикрепите в файл README.md скриншот страницы шаблона с названием «Задание 1»

### Решение:
<img width="1919" height="1079" alt="Screenshot_20260109_204135" src="https://github.com/user-attachments/assets/3838c55b-62c0-4a96-9466-a4768144eb87" />
<img width="1919" height="1079" alt="Screenshot_20260109_212225" src="https://github.com/user-attachments/assets/4b9ca72a-659d-4066-9496-d8135acace2a" />
<img width="1919" height="1079" alt="Screenshot_20260109_214007" src="https://github.com/user-attachments/assets/07528fc9-1a51-48fd-bc0c-0c6f44d7ae7c" />
<img width="1919" height="1079" alt="Screenshot_20260109_205837" src="https://github.com/user-attachments/assets/4e14eead-23fd-41f7-9d98-6fc168322c85" />

### Задание 2-3

Что нужно сделать:

Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server
Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов
Добавьте Zabbix Agentов в раздел Configuration > Hosts вашего Zabbix Servera
Прикрепите за каждым хостом шаблон Linux by Zabbix Agent
Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов
Требования к результату
￼ Результат данного задания сдавайте вместе с заданием 3

Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон
Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent
Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона
Требования к результату
￼ Прикрепите в файл README.md скриншот страницы хостов, где будут видны привязки шаблонов с названиями «Задание 2-3». Хосты должны иметь зелёный статус подключения

### Решение:
<img width="1919" height="1079" alt="Screenshot_20260109_212204" src="https://github.com/user-attachments/assets/8c1464c7-9f5b-4017-8642-0a5c4074ddf0" />
<img width="1919" height="1079" alt="Screenshot_20260109_214549" src="https://github.com/user-attachments/assets/1904aefd-abd5-4c57-a097-c36a69e88f91" />
<img width="1919" height="1079" alt="Screenshot_20260109_214606" src="https://github.com/user-attachments/assets/c58faf9c-942c-4af9-afc1-a7188e07da12" />
<img width="1919" height="1079" alt="Screenshot_20260109_210504" src="https://github.com/user-attachments/assets/e74e818f-d70c-4b3d-89eb-133c5c1c434a" />
<img width="1919" height="1079" alt="Screenshot_20260109_210525" src="https://github.com/user-attachments/assets/86e5b2ac-3f5b-4235-9e0d-7aa97195362b" />


### Задание 1

Что нужно сделать:
Создайте свой кастомный дашборд.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
В разделе Dashboards создайте новый дашборд
Разместите на нём несколько графиков на ваше усмотрение.
Требования к результату
￼ Прикрепите в файл README.md скриншот дашборда с названием «Задание 4»

### Решение:
<img width="1919" height="1079" alt="Screenshot_20260109_214741" src="https://github.com/user-attachments/assets/2bd7bd64-90cd-43f6-9e2d-01f955704451" />

