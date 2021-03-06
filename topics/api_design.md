Чаще всего под "апишкой" мы подразумеваем серверные обработчики для
 http-запросов. Тем не менее, расшифровка API - Application Programming
 Interface - не содержит в себе ни слова про веб
 или какое-то еще окружение.

По большому счету, вы пишете API почти каждый день, даже когда
 занимаетесь сугубо внутренними задачами. Любой код, который будет
 использоваться другим разработчиком в другом компоненте, можно считать
 API - даже если другой разработчик это вы же, только завтра, а другой
 компонент лежит в соседнем файле того же репозитория.

В целом, принципы хорошего API не зависят от окружения, для которого
 вы его пишете - будь это протокол HTTP, консольная команда или набор
 функций и методов на вашем языке программирования. Окружение влияет
 только на то, как эти принципы оптимально для него реализуются.

Ссылки ниже посвящены как общим для всех сред принципам дизайна
 API, так и более конкретным примерам, в основном из веба.

- [Три принципа](https://nordicapis.com/the-three-principles-of-excellent-api-design/),
  важных для дизайна абсолютно любого API.
- [Статья про API-first design](https://www.torocloud.com/blog/how-to-implement-an-API-first-design-methodology).
  Чем-то похоже на top-down разработку, про которую рассказывал
  Илья на митапе.
- [Презентация о дизайне хорошего API в коде](http://fwdinnovations.net/whitepaper/APIDesign.pdf).
  Хоть примеры и написаны на Java, в целом эти подходы распространимы
  на любой язык.
- [Пример очень плохого веб-API](https://blog.usejournal.com/how-not-to-design-restful-apis-fb4892d9057a),
  по которому становится понятно, как сделать плохой API в
  любой другой среде.
- Дискуссионная статья:
  [когда в вебе лучше применять REST-образный дизайн](https://nordicapis.com/is-rest-still-a-good-api-design-style-to-use/),
  а когда стоит искать альтернативы.
- Пример хорошего веб-API, основанного на RPC -
  [Slack](https://api.slack.com/web). Особенно хорошо здесь
  устроен нейминг.
