# React
Тестовое задание (frontend)

Тестовое задание состоит из обязательных и дополнительных пунктов.
Задача: Реализовать SPA по добавлению пользователя в таблицу благотворительного забега на
дистанции 5, 3 и 10 км.
Условия
Одностраничное приложение без горизонтальной и вертикальной прокруток.
Корректная работа в IE 10 и выше.
Разрешение: 1920 х 1080px.
Допустимо использование популярных фреймворков.
Что должно быть реализовано:
1 Форма, с полями «Заявки на участие в забеге»:
  a)ФИО участника забега (текстовое поле)
  b)Дата рождения (календарь с выбором даты)
  c)Email (c валидацией на корректность)
  d)Телефон (с маской ввода)
  e)Дистанция - Выпадающий список (3 км, 5 км, 10 км)
  f)Сумма взноса, руб. (произвольное число)
  g)Кнопка «Отправить заявку» (активна, когда все поля заполнены), после нажатия – все поля формы очищаются, и пользователь добавляется     в таблицу, расположенную под формой.
2 Таблица, должна обновляться при добавлении нового пользователя без перезагрузки страницы.
3 Изначальные данные для таблицы, представлены в файле: users.json
4В таблице должна иметь возможность фильтрации данных по:
  - дате регистрации (по умолчанию),
  - по сумме взноса
  - по дистанции забега
Дополнительно:
  1 Предусмотреть пагинацию, если пользователей больше N – для переключения на след.
  пред. страницы.
  2 Корректная (читабельная, без горизонтального скролла) адаптация под 1280х800px
  3 Использования store (Vuex, Redux)
Результат работы
  Передать либо как url для клонирования из какого-либо Git-репозитория, либо архивом.
