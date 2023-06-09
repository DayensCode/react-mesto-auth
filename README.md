# Frontend-проект: "Место"

## Описание проекта

Интерактивная страница, куда можно добавлять фотографии, удалять их и ставить лайки. В сравнении с [предыдущей](https://github.com/DayensCode/mesto-react) работой в данном проекте добавлен функционал регистрации и авторизации пользователей на сайте в своем личном кабинете.

![image](https://user-images.githubusercontent.com/92729800/204303554-fd708625-c724-46f9-9045-261b69f63b27.png)

### Ссылка на макет

https://www.figma.com/file/5H3gsn5lIGPwzBPby9jAOo/Sprint-14-RU?node-id=0%3A1

### Ссылка на проект

https://dayenscode.github.io/react-mesto-auth/

## Используемые языки

[HTML](https://ru.wikipedia.org/wiki/HTML)
[CSS](https://ru.wikipedia.org/wiki/CSS)
[JS](https://ru.wikipedia.org/wiki/JavaScript)
[React](https://ru.wikipedia.org/wiki/React)

## Установка и запуск приложения в локальном репозитории

- _git clone https://github.com/DayensCode/react-mesto-auth.git_ - клонировать репозиторий (с использованием HTTPS) на свое устройство
- _npm install --save react-router-dom_ - установить зависимости
- _npm start_ - запустить приложение в режиме разработчика (в браузере ввести ссылку http://localhost:3000/react-mesto-auth/sign-in, если приложение не открылось там автоматически)
- При использовании приложения для входа в личный кабинет пользователю требуется зарегистрироваться _https://dayenscode.github.io/react-mesto-auth/sign-up_ и пройти авторизацию _https://dayenscode.github.io/react-mesto-auth/sign-in_
- При авторизации в локальном хранилище сохраняется токен пользователя, который при закрытии вкладки с приложением и возвращении позволяет оставаться авторизованным на сайте. Он удаляется после нажатия на кнопку выхода из личного кабинета

## Процесс создания

Была осуществлена верстка дополнительных компонентов (стартовых окон с формами регистрации и авторизации пользователей) и элементов (отображаемый логин-почта, кнопка выхода из личного кабинета), был написан соответсвующий функционал.

## Функционал

- Регистрация и авторизация пользователей
- Редактирование данных пользователя
- Обновление автара
- Добавление новой карточки
- Добавление и снятие лайка (есть счетчик лайков)
- Модальное окно успешной/неудачной регистрации на сайте
- Модальное окно с увеличенной фотографией карточки

## Планы по улучшению

- Адаптация новых компонентов
- Добавление модального окна подтверждения удаления карточки
- Открытие и закрытие модальных окон по оверлэю и клавише "Escape"
- Добавление спиннеров загрузки
- Валидация форм
- Окно предварительной загрузки страницы
- Страница 404
- Оптимизация приложения для людей с ограниченными возможностями (label для инпутов форм)
- Добавление функции сабмита форм нажатием на клавишу "Enter"
