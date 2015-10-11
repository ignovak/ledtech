### Installation

```
gem install middleman
cd path_to_project
middleman server
```

See https://github.com/middleman/middleman

### TODO
* Допилить SEO (title, description, мета-теги для социальных сетей)
* Допилить сниппеты (но сначала дообсуждать дизайн)
* Допилить pixel perfect
* Для production потребуются дополнительные frontend-работы:
  * Подставить правильные урлы для ссылок
  * Поправить поведение для контролов по ховеру
  * Подставить данные на витрине
  * Оживить карусель
  * Подставить данные для отзывов
  * Реализовать добавление отзывов (лучше аяксом)
  * Добавить поделяшки (vk, fb, twitter)
* Оптимизировать картинки, они слишком тяжёлые (попробовать поменять png -> jpg, ну и, может, упростить сами картинки)
* Поддержать планшеты/смартфоны
* Потестить разные браузеры (в ie могут быть проблемы)
* Макет, по-моему, можно улучшить, но тут уже нужен дизайнер
  * Увеличить фоновую картинку для шапки (при разрешении больше 1400 выглядит некрасиво: https://yadi.sk/i/0j2ZR86yjduV5)
  * Все переходы по ссылкам в навигационном меню будут вести на эту же страницу
    * Как по мне, макет это не учитывает, а сделан скорее для общего случая, когда ссылки ведут на разные страницы сайта
    * Если всё же здесь всё оставить как есть, вопрос: как должны вести себя элементы меню при переходах?
  * Правда ли нужно столько КАПСЛОКА?
  * Цвета, фон, контролы etc
