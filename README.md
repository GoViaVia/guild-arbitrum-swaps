# guild-arbitrum-swaps

Скрипт покупает все монеты, которые нужно купить в guild arbitrum чтобы получить роль. Каждый контракт вызывается отдельно, здесь вас не спалить. Количество монет покупается минимально необходимое. Суммарно с комиссиями выходит ~ 0.5 - 0.7$ в ETH. Поставил time out в 3 секунды между транзакциями, иначе вылетает.

1. Регистрируемся на https://arbiscan.io/login и создаем api key : https://arbiscan.io/myapikey
2. Копируем свой api key и вставляем в переменную API_KEY в файле main.py
3. Вставляем в файл private_keys.txt свои ptivate key от кошельков. Кол-во >= 1. Каждый приватник с новой строки.
