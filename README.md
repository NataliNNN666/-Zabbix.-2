# задание 1

Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.   
Процесс выполнения Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.  
 В веб\-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон Создайте Item который будет собирать информацию об загрузке CPU в процентах   
Создайте Item который будет собирать информацию об загрузке RAM в процентах



<img width="1920" height="1020" alt="Снимок экрана 2026-03-16 120508" src="https://github.com/user-attachments/assets/1e8feafd-48e2-4f65-9d98-e3b0c451db03" />



<img width="1920" height="1020" alt="Снимок экрана 2026-03-16 115846" src="https://github.com/user-attachments/assets/146eac85-8b60-493e-a937-e01ceea8d360" />


<img width="1920" height="1020" alt="Снимок экрана 2026-03-16 115744" src="https://github.com/user-attachments/assets/436d57e5-7bc8-4a4d-95c6-ae4926ce9103" />



<img width="1920" height="1020" alt="Снимок экрана 2026-03-16 115644" src="https://github.com/user-attachments/assets/1f9a01df-a126-4e5e-9da5-bf51bceb6fc1" />


<img width="1920" height="1020" alt="Снимок экрана 2026-03-16 115810" src="https://github.com/user-attachments/assets/e97459c5-df29-4391-a0f1-3bbf201866f8" />

<img width="1920" height="1020" alt="Снимок экрана 2026-03-20 142831" src="https://github.com/user-attachments/assets/da084aa1-78c7-4018-b39d-2fd0d909e668" />


<img width="1920" height="1020" alt="Снимок экрана 2026-03-20 143142" src="https://github.com/user-attachments/assets/3d828057-f135-44b8-a0a6-c20dfcd04295" />



<img width="1920" height="1020" alt="Снимок экрана 2026-03-20 143823" src="https://github.com/user-attachments/assets/308ea1bf-7c91-4bc5-ab2f-4ab7289acd1a" />



# задание 2,3

Добавьте в Zabbix два хоста и задайте им имена \<фамилия и инициалы-1\> и \<фамилия и инициалы-2\>. Например: ivanovii-1 и ivanovii-2.  
  Процесс выполнения:  
 Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.  
 Установите Zabbix Agent на 2 виртмашины, одной из них может быть ваш Zabbix Server Добавьте Zabbix Server в список разрешенных серверов ваших Zabbix Agentов Добавьте Zabbix Agentов в раздел Configuration \> Hosts вашего Zabbix Servera Прикрепите за каждым хостом шаблон Linux by Zabbix Agent Проверьте что в разделе Latest Data начали появляться данные с добавленных агентов

 
Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон
Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent
Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона

<img width="1920" height="1020" alt="Снимок экрана 2026-03-16 125103" src="https://github.com/user-attachments/assets/435ee5dc-f7b8-45bf-9c73-7cd9dac024dc" />




<img width="1920" height="1020" alt="Снимок экрана 2026-03-20 150011" src="https://github.com/user-attachments/assets/9d26006a-37de-4134-bf28-ca917276c614" />


# задание 4

Создайте свой кастомный дашборд.    
Процесс выполнения Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.  
 В разделе Dashboards создайте новый дашборд Разместите на нём несколько графиков на ваше усмотрение.





<img width="1282" height="893" alt="Снимок экрана 2026-03-20 154035" src="https://github.com/user-attachments/assets/3729c7bf-9228-41c2-b27b-864a3b859340" />


# задание 5

Создайте карту и расположите на ней два своих хоста.   
 Процесс выполнения Настройте между хостами линк. Привяжите к линку триггер, связанный с agent.ping одного из хостов, и установите индикатором сработавшего триггера красную пунктирную линию. Выключите хост, чей триггер добавлен в линк. Дождитесь срабатывания триггера.


<img width="1920" height="1020" alt="Снимок экрана 2026-03-16 143743" src="https://github.com/user-attachments/assets/e89fcc1e-eef2-4998-a439-978a64c10b34" />


<img width="1920" height="1020" alt="Снимок экрана 2026-03-16 144308" src="https://github.com/user-attachments/assets/62d180a8-4fff-44c5-99b1-f8c64fc71551" />


