Ops engineer first interview questions.

`Credits to Southbridge.io. Thnx for some questions, guys, I've tried to customize this. If you don't like the level of customization - please tell @ vadim.isakanov@gmail.com`

1. Расскажите, чем отличаются команды: "run.sh" ". run.sh" "/run.sh" "./run.sh" .

2. Клиент жалуется на проблемы в работе БД MySQL - простые запросы выполняются медленно. Опишите подробно ваши действия. 

3. На сервере закончилось свободное место, навые файлы не создаются, но df -h показывает, что места достаточно. Ваши следующие действия? 

4. Внезапно и очень быстро на сервере начинает заканчиваться свободное место. Что вы будете делать для диагностики проблемы?

4. Что такое pip?

5. Приведите пример конфига для nginx с использованием map для редиректа всех посетителей с user-agent 'Android', 'android', 'iOS', 'ios' с aaa.test.com на m.aaa.test.com

6. У вас есть nginx c настроенными vhosts для доменов aaa.test.com и bbb.test.com. При этом в настройках каждого nginx vhost указано конкретное имя через директиву server_name.
В качестве бекэнда - apache на 127.0.0.1:8080.

В DNS прописано

`*.test.com   IN   A  ip.add.re.ss`

Что  откроется при переходе на
-    https://aaa.test.com
-    http://aaa.test.com
-    https://bbb.test.com
-    http://bbb.test.com
-    https://ccc.test.com
-    http://ccc.test.com
