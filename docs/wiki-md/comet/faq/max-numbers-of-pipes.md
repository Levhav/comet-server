
# Вопрос от пользователя

Мне нужно сделать на сайте рассылку уведомления о новом комментарии к новости. Новостей, понятное дело, много. Для этой цели нужно создавать отдельные каналы, название которых соответствует формату "news__comments" ?

 Например, "news_1001_commets", "news_1002_comments", ..., "news_1003_comments" ?
 Или есть иной подход?

# Ответ

Да думаю по каналу на новость нормально. пока в канале нет подписчиков канал не отнимает ресурсы сервера так что каналов можно делать сколько угодно. 

В тоже время если все новости отправлять через один канал будет много народу кто будет получать сообщения о новостях которые они не просматривают и вот это будет создавать нагрузку от которой не будет пользы, и чем больше подписчиков в канале тем больше нагрузка при любых действиях с каналом. так что лучше иметь сто каналов и в каждом по 2 подписчика чем один канал и 200 подписчиков.

# Другие вопросы от пользователей

  * [Могут ли влиять одни пользователи сервиса на других пользователей?](/docs/wiki-md/comet/faq/isolation-of-users.md)  
  * [Может ли кто то посторонний получать сообщение из каналов](/docs/wiki-md/comet/faq/access-to-channels-for-outsiders.md)
  * [Надо ли экономить количество каналов?](/docs/wiki-md/comet/faq/max-numbers-of-pipes.md)
  * [Как отправить сообщение в произвольный канал и как его потом получить на другой странице?](/docs/wiki-md/comet/faq/send-message-to-pipe.md)
  * [Как реализовать механизм отслеживания вхождения пользователей на сайт. То есть список посетителей обновляющийся на "лету"?](/docs/wiki-md/comet/faq/realtime-users-list.md) 