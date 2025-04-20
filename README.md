# Конспектик по Abelton 11 Live

По курсу от [отечественного битмейкера](https://www.youtube.com/watch?v=cdcgVkYV0k4&t=3191s)

## Советы

Полезно изучить системные выпадающие меню

<img src="./images/menu.png" />

<details>
  <summary>Особенно <code>View</code></summary>
  <img src="./images/view.png" width="400px"/>
</details>

Нажимаем на пункт меню и смотрим что меняется в интерфейсе

## [DAW (digital audio workstation)](https://www.youtube.com/watch?v=cdcgVkYV0k4&t=3191s)

**Источники** звука отправляют сигналы в **плагины**, которые как-то обрабатывают звук и отправляют в **микшер**, который объединяет все обработанные звуки в итоговый

## [Интерфейс, плэйлист, браузер](https://youtu.be/cdcgVkYV0k4?si=cMZCAJBRxUy0doN7&t=664)

Посмотрим что мы видим перед собой при первом запуске Abelton, разберём зачем тут столько всего

<details>
  <summary>Картинка</summary>
  <img src="./images/interface.png"/>
</details>

## [MIDI дорожки](https://youtu.be/cdcgVkYV0k4?si=ovXWhRoDmKv3r-Yf&t=1912)

- Создаём `MIDI` дорожки
- Назначаем на них инструменты
- Редактируем `piano roll`

### [Из audio в MIDI](https://youtu.be/cdcgVkYV0k4?si=PKfoA7ujtLyquWEN&t=2352)

1. Назначаем инструмент на `MIDI` дорожку
2. Перетаскиваем на дорожку звуковой файл
3. Извлекаем из него мелодию или гармонию на `piano roll`

## [Эффекты](https://youtu.be/cdcgVkYV0k4?si=B-Hy4Ipm9H8UPT8O&t=2989)

Перетаскиваем эффект в секцию эффектов дорожки

## [Микшер](https://youtu.be/cdcgVkYV0k4?si=AAApZ2UJl63TXLJ0&t=3182)

Принимает звук из разных дорожек и смешивает в одну дорожку

- `Mute/Solo` для дорожек
  - `Cmd+Solo`
- Панарамирование
- Настройки `Master`-дорожки

## [Return-каналы](https://youtu.be/cdcgVkYV0k4?si=juT5TGC2g6J5qin2&t=4158)

Почему-то в видео называются `Send`-каналами

Это такие каналы на которые послается звук, приходящий в микшер, этот звук там тоже как-то обрабатывается и то, что получилось отправляется `master` канал, и там это всё сливается в один звук. Могут быть в режиме `pre-fader` (звук отправляется в `return`-канал до применения настроек микшера) и `post-fader` (звук отправляется в `return`-канал после применения настроек микшера)

Нужно при сведении звука



