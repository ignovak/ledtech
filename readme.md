### Ссылка на текущую версию

https://73e0043c6478c1ef82b73a36ee0709259c2576bd-www.googledrive.com/host/0B8HDxP_G74KGT0Y1VjFIWS1Hek0/

### Installation

```
gem install middleman
cd path_to_project
middleman server
```

See https://github.com/middleman/middleman

### TODO
* Допилить SEO (title, description, мета-теги для социальных сетей)
* Допилить pixel perfect
* Добавить favicon
* Для production потребуются дополнительные frontend-работы:
  * Подставить правильные урлы для ссылок
  * Поправить поведение для контролов по ховеру
  * Подставить данные на витрине
  * Оживить карусель
  * Добавить поделяшки (vk, fb, twitter)
* Оптимизировать картинки, они слишком тяжёлые (попробовать поменять png -> jpg, ну и, может, упростить сами картинки)
* Потестить разные браузеры (в ie могут быть проблемы)
* Макет, по-моему, можно улучшить, но тут уже нужен дизайнер
  * Логотип перевести в svg
  * Поддержать планшеты/смартфоны
    * Проверить текущую вёрстку на разных разрешениях
    * Продумать адаптивность для попапов
  * Все переходы по ссылкам в навигационном меню будут вести на эту же страницу
    * Как по мне, макет это не учитывает, а сделан скорее для общего случая, когда ссылки ведут на разные страницы сайта
    * Если всё же здесь всё оставить как есть, вопрос: как должны вести себя элементы меню при переходах?

* "Главная" – странное название
* Не забыть про вычитку
* Уточнить размер изображений в каталоге: они должны помещаться в область либо же уметь сжиматься
* Уточнить поля для формы
* Нет формы для отправки отзыва
* Куда ведут ссылки для заказа?
* В отзывах где взять аватар?
* Ссылки на поделяшки?
* Добавить обработку ошибок
* Закрывать попап по esc
