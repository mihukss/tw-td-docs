# **Процесс создания документации**

В данном документе мы формируем требования к процессу документирования в разработке.

## Спецификация
Перед тем как начать разработку, необходимо сформулировать требования к будущему продукту.
Ответственный за продукт (это может быть тимлид, проджект или продукт вместе с техническим писателем) составляет документ,
который должен содержать следующую информацию:

- **что мы делаем** (улучшаем работу почтовых рассылок);
- **какие задачи бизнеса продукт должен решить** (повысить процент доставки писем и увеличить доход от рассылки);
- **пользовательская история** — что делает пользователь с продуктом. Может быть оформлена в виде диаграммы (см. пример тут) или описания того, как можно убедиться, что продукт работает, как было задумано (definition of done).

После этого документ передаётся разработчикам.

Если в процессе разработки функциональные требования изменились, то документ должен быть обновлен. 

## Функциональная документация

Разработчик пишет код с комментариями внутри. Из комментариев другой разработчик (или он сам через год) должен понять,
зачем добавлена данная функция, что она делает, какие возможны ограничения и так далее. 

Вместе с ревью кода происходит ревью комментариев. В дальнейшем по комментариям автоматически формируется документация для
разработчиков.

После окончания разработки составляется краткий документ, который содержит:

- ссылку на репозиторий с кодом продукта;
- ссылку на требования;
- краткое описание функциональности;
- описание, с какими системами/сервисами взаимодействует продукт;
- описание API (если было использовано или создано).

Данный документ может наполняться поэтапно, если разработка занимает несколько спринтов. 

## Итоговое ревью

После окончания разработки и выпуска продукта необходимо провести ревью документации. Во время ревью проверяется:

- соответствие спецификации итоговому продукту;
- наличие необходимых комментариев в коде продукта;
- полноту и достаточность функциональной документации.