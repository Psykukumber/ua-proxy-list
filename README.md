# Список сайтов, заблокированных в Украине (для [SwithyOmega](https://github.com/FelisCatus/SwitchyOmega))
[![GitHub license](https://img.shields.io/badge/license-Unlicense-blue.svg)](https://raw.githubusercontent.com/Psykukumber/ua-proxy-list/master/LICENSE) [![Twitter feedback](https://img.shields.io/badge/feedback-twitter-blue.svg)](https://twitter.com/psykukumber) [![Telegram feedback](https://img.shields.io/badge/feedback-telegram-blue.svg)](https://t.me/psykukumber)

Данный список предназначен для использования в програмной связке Chromium/Firefox + [SwithyOmega](https://github.com/FelisCatus/SwitchyOmega) + [Shadowsocks](https://shadowsocks.org). С его помощью проксируется трафик только к заблокированным сайтам, в то время, как ко всем остальным - идет напрямую.

## Использование

1. Установите SwithyOmega ([Chrome](https://chrome.google.com/webstore/detail/padekgcemlokbadohgkifijomclgjgif), [Firefox](https://addons.mozilla.org/en-US/firefox/addon/switchyomega/)) и пропишите в него адрес вашего SOCKS5-прокси
2. Откройте настройки SwitchyOmega > Profiles > auto proxy
3. Нажмите кнопку "Add a rule list". В разделе "Switch Rules" найдите графу "Rule list rules" и выберите ваш профиль прокси.
4. В поле "Rule List URL" вставьте ссылку:
```
https://raw.githubusercontent.com/Psykukumber/ua-proxy-list/master/sites.sorl
```
затем нажмите "Apply changes"

5. Переключите активный профиль на "auto switch"

_Примечание: настоятельно рекомендуется изменить DNS-сервера в настройках вашего интернет-подключения на следующие:_

* _[1.1.1.1](https://1.1.1.1) от CloudFlare_
* _[8.8.8.8](https://8.8.8.8) или [8.8.4.4](https://8.8.4.4) от Google_
* _[OpenNIC](https://www.opennic.org/)_

## Что делать, если в списке не хватает какого-то сайта?

Вы можете открыть новый тикет в багтрекере или направить мне пулл реквест и я постара.сь добавить новый сайт в список как можно скорее. Если же вы не хотите ждать, то можете добавить сайт самостоятельно в настройках расширения.

## У меня есть вопрос...

Напишите мне в [Твиттер](https://twitter.com/psykukumber) или [Телеграм](https://t.me/psykukumber)

## Отказ от ответственности

ФАЙЛЫ В ЭТОМ РЕПОЗИТОРИИ РАСПРОСТРАНЯЕТСЯ В ФОРМАТЕ "КАК ЕСТЬ". ИСПОЛЬЗУЯ ДАННЫЕ СПИСКИ, ИНСТРУКЦИИ ИЛИ ИХ ЧАСТИ ВЫ СОГЛАШАЕТЕСЬ С ТЕМ, ЧТО ОСОЗНАЕТЕ ВСЕ ВОЗМОЖНЫЕ ПОСЛЕДСТВИЯ И ИСПОЛЬЗУЕТЕ ИХ НА СОБСТВЕННЫЙ СТРАХ И РИСК. АВТОР НЕ НЕСЕТ ОТВЕТСТВЕННОСТИ ЗА ПОТЕРЮ ДАННЫХ, ВЗЛОМЫ УЧЕТНЫХ ЗАПИСЕЙ, ВЫХОД ОБОРУДОВАНИЯ ИЗ СТРОЯ, ПРОБЛЕМЫ С ПРАВООХРАНИТЕЛЬНЫМИ ОРГАНАМИ И СПЕЦСЛУЖБАМИ, ТЕРРОРИСТИЧЕСКТЕ АКТЫ, ВОЙНЫ, ЗЕМЛЕТРЯСЕНИЯ, НАВОДНЕНИЯ, ЦУНАМИ, РЕВОЛЮЦИИ, МАССОВОЕ ВЫМИРАНИЕ РЫБЫ, СМЕРТЬ ВАШЕЙ СОБАКИ, ВТОРЖЕНИЕ ИНОПЛАНЕТЯН, ОСКОРБЛЕНИЯ В ТВИТТЕРЕ, ИЗБРАНИЕ ПРЕЗИДЕНТОМ ИДИОТА, ПРЕЖДЕВРЕМЕННОЕ НАЧАЛО СУДНОГО ДНЯ, КОЛЛАПС СОЛНЦА В ЧЕРНУЮ ДЫРУ, ТЕПЛОВУЮ СМЕРТЬ ВСЕЛЕННОЙ А ТАКЖЕ ПОЛНУЮ НЕСПОСОБНОСТЬ ПРОЧИТАТЬ И ОСОЗНАТЬ НАЗНАЧЕНИЕ, СМЫСЛ И СУТЬ ДАННОЙ ИНСТРУКЦИИ И ЛЮБЫЕ ДРУГИЕ ВОЗМОЖНЫЕ ПОСЛЕДСТВИЯ.
