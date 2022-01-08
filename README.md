# Shiki Enhanced Theme
Для личного использования, в целом.
Увеличенный размер шрифта, закруглённые углы, мелкие фиксы кривых ручек morr'a. Также переделанный Профиль и Списки просмотренного.

Код в полнейшем беспорядке, да и к тому же не редактировался с ~2017. Я предупредил.

## Установка
1. Скопируйте код из блока ниже
2. На [Шикимори](shikimori.one) перейдите в Настройки > Внешний вид сайта > Стили сайта
3. Вставте код в поле CSS
4. (Необязательно) Замените ссылки на фоновые изображения

```css
/**
** Фоны для Светлой темы
** Используются по умолчанию
**/
:root {
  --site-bg: url("https://i.vgy.me/LRi1Vl.png"); /* Фон сайта 1920x1080 */
  --profile-head-bg: url("https://i.vgy.me/BCgcCC.jpg"); /* Фон обложки профиля 1200x250 */
  --user-id: 42277; /* Ваш ID на Шикимори */
}

/**
** Фоны для Тёмной темы
** Используются при выборе Тёмной темы оформления в ОС
** Поддерживаются в ОС: Windows 10 1809+, macOS 10.14+, Android 10+
** Поддерживаются в браузерах: Chrome 76+, Firefox 67+, Opera 62+
** Полный список (внизу страницы):
** https://developer.mozilla.org/ru/docs/Web/CSS/@media/prefers-color-scheme
**/
@media (prefers-color-scheme: dark) {
  :root {
  	--site-bg: url("https://i.vgy.me/QtJnyX.jpg"); /* Фон сайта 1920x1080 */
  	--profile-head-bg: url("https://i.vgy.me/Ukcgch.jpg"); /* Фон обложки профиля 1200x250 */
	}
}

/** Импорт файлов стиля с GitHub **/
@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/colors.css");
@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/fonts.css");
@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/main.css");
@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/menu.css");
@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/profile.css");
@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/profile-history.css");
@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/profile-graphs.css");
@import url("https://raw.githubusercontent.com/Trixlight/shiki/main/style/profile-lists.css");
```
## Credits
Тёмный фон: [https://www.pixiv.net/en/artworks/62824816](https://www.pixiv.net/en/artworks/62824816)   
Тёмный фон шапки профиля: ???   
Светлый фон: [https://www.pixiv.net/en/artworks/64444012](https://www.pixiv.net/en/artworks/64444012)  
Светлый фон шапки профиля: [https://www.pixiv.net/en/artworks/82906571](https://www.pixiv.net/en/artworks/82906571)
