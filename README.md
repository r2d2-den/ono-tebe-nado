

# "Оно тебе надо — аукцион вещей, в которые никто не верил"
<div style="display: flex; gap: 10px; background-color:rgb(46, 46, 46); padding: 10px; border-radius: 8px; font-family: 'Comic Sans MS', sans-serif; margin-top: 20px;">
  <div style="background-color:rgb(235, 72, 43); color: white; padding: 5px 10px; border-radius: 4px; font-weight: bold; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3); transition: transform 0.3s ease; box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);">
    HTML
  </div>
  <div style="background-color:rgb(57, 84, 235); color: white; padding: 5px 10px; border-radius: 4px; font-weight: bold; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3); transition: transform 0.3s ease; box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);">
    CSS
  </div>
</div>

## Описание проекта
Проект представляет собой аукцион, на котором представлены лоты, в которые никто не верил, но которые в конечном итоге стали культовыми. На сайте можно посмотреть различные лоты, узнать о проекте и сделать ставку на интересующий товар.

### Основные компоненты:
- **Главная страница** с навигацией и логотипом.
- **Лоты** с различными категориями товаров (например, фильмы, книги, картины).
- **О проекте**, где описывается концепция аукциона.
- **Контакты и информация** в подвале страницы.

## Структура HTML

1. **`<header>`** — верхняя часть страницы:
   - Содержит навигацию с ссылками на главную, лоты и страницу о проекте.
   - Логотип и контактная информация (номер телефона, email, адрес).

2. **`<main>`** — основная часть:
   - **Секция "Cover"**: фон с титульным текстом и кнопкой для участия в аукционе.
   - **Секция "Lots"**: отображает список лотов с карточками товаров (например, фильмы, книги, картины).
   - **Секция "About"**: информация о проекте, его концепции и философии.

3. **`<footer>`** — подвал:
   - Контактная информация.
   - Навигация с ссылками на страницы.
   - Социальные иконки для перехода в социальные сети.

## Стили CSS

1. **Общие стили**:
   - Используется flexbox и grid для создания гибких и отзывчивых макетов.


### Структура классов CSS

- **`.container`**: ограничивает ширину контента, выравнивая его по центру.
- **`.header`**: включает в себя навигацию, логотип и контактные данные.
- **`.cover`**: фон с текстом и кнопкой для участия в аукционе.
- **`.lots`**: блок для отображения лотов, карточки товаров.
- **`.about`**: информация о проекте с логотипом и описанием.

