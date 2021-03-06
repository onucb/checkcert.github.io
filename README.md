Введение в определение сертификата iOS
Этот исходный код может помочь пользователям быстро обнаружить и понять, правильно ли работает сертификат IOS, который они используют, и был ли статус сертификата отозван разработчиком или заблокирован Apple. Пользователям удобно быстро найти статус сертификата и предоставить соответствующую информацию о времени истечения срока действия или времени отзыва.


## 1. Функции следующие:
1. Поддержка онлайн-обнаружения сертификата ios
2. Поддержка последней версии протокола сертификата G3.
3. Поддержка обнаружения сертификата пакета IPA
4. Улучшить точность сертификата испытаний
5. Поддерживайте несколько состояний сертификата и выделяйте их
6. Поддержка отображения времени подписания сертификата
7. Отображение типа сертификата: внутренний или специальный.


## 2. Как использовать:
1. Сначала создайте веб-сервер
2. Получите исходный код обнаружения сертификата
3. Настройте файл веб-конфигурации

пример:  
Вот пример сервера nginx:

server {  
  listen 80;  
  server_name www.example.com;  
  root /opt/p12certcheck;  

  location / {  
	index  index.html index.htm index.php;  
    }  
}   

инструкция:
server_name Это поле доменное имя заполняется в соответствии с вашей реальной ситуацией.
root Укажите здесь корневой путь к исходному коду веб-сайта.  

Ссылка доступа:
http://www.example.com;  

## 3. Отображение эффекта:
![](https://github.com/Forever18/p12certcheck/blob/main/static/pack/checkcert/images/p12.png)  
![](https://github.com/Forever18/p12certcheck/blob/main/static/pack/checkcert/images/ipa.png)  

