# CSS-препроцессорами (Less,Sass, Stylus)
![Logo](https://github.com/coder-areaweb/LESS_SASCC_Stylus/blob/main/Prepros.png)

### Описание курса:

В данном курсе рассмотриваю препроцессоры CSS (LESS,(SAAS/SCSS),STYLUS), а также пробую различные GUI-приложения для удобства использования и ускорения веб-верстки.

Препроцессоры дают:
- возможность записать код короче
- в проектах редко используют чистый CSS
- сильно расширяют возможности обычного CSS
- упрощают работу с однотипным кодом
- логичная и понятная структура
- проще вносить изменения и поддерживать код в актуальном состоянии
- есть возможность оптимизировать скорость загрузки стилей.

По окончанию курса научился :
- записывать код короче
- вносить правки в существующий стиль
- форматировать чистый CSS с помощью:
- CLI (ручной сборки)
- GUI App(визуального компилятора)
- Подключать JS-преобразователь к HTML, например less.js
- Пользоваться Online Services (онлайн сервис)

### Используемые ресурсы и инструменты:
- [VS Codium (Редактор кода)](https://vscodium.com/)
- [Compass.app](http://compass.kkbox.com/)
- [Scout](https://scout-app.io/)
- [Crunch2](http://getcrunch.co/)
- [Prepros](https://prepros.io/)
- [Fire.app](https://fireapp.kkbox.com/)
### Онлайн инструменты:
- [LESS Compiler](https://beautifytools.com/less-compiler.php)
- [Online LESS Compiler WinLESS](http://winless.org/online-less-compiler)
- [SassMeister](https://www.sassmeister.com/)
- [Saas Playground](https://sass-lang.com/playground/)
- [SASS/SCSS Playground](https://playcode.io/scss)


### Полезные ссылки:
#### Справочная информация:
- [CSS PRE processors](https://csspre.com/compare/)
- [Less](https://lesscss.org/)
- [Sass/SCSS](https://sass-scss.ru/)
- [Stylus](https://stylus-lang.com/)
- [Stylus cheatsheet](https://devhints.io/stylus)
- [Stylable](https://stylable.io/)
- [PostCSS](https://postcss.org/)


---

### Список уроков Flexbox:
#0 thecharity  
#1 Переменные variables  
#2 Вложеность стилей(nesting)  
#3 Миксины(mixins)  
#4 Расширение классов(extends)  
#5 Функции цветиа (color-functions)  
#6 Импорт(imports)  
#7.1 Условные операторы (ifelse)  
#7.2 Цикл(loops) (for/each/while)  

## Authors

- [MakeWeb.me](https://www.youtube.com/watch?v=31gAMHPoc48)
- [MakeWeb.me](https://www.youtube.com/watch?v=mQwVTORvxco)
- [BrainsCloud](https://www.youtube.com/watch?v=YkPT0Wb8ikU)


---

## Инсталяция и компиляция

Для ручной сборки в терминале: Linux Debian from apt or apt-get

## Инсталяция SAAS:

```bash
  sudo apt install sassc
```
## Сборка/компиляция:
```bash
sass source/stylesheets/index.scss build/stylesheets/index.css
```

## Инсталяция LESS:

```bash
  sudo apt install less
```
## Сборка/компиляция:
```bash
lessc [option option=parameter ...] <source> [destination]
lessc -x styles.less styles.css
```

## Инсталяция STYLUS:

```bash
  sudo apt install node-stylus
```
## Сборка/компиляция:
```bash
stylus -w styl/*.styl -o css/styles.css
```
