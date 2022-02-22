# 🗓План чтения Библии за год

[![PDFs Made with LaTeX](https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white)](https://www.latex-project.org)
[![Automated by GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Web Site Made with Jekyll](https://img.shields.io/badge/jekyll-3.9.0-blue.svg)](https://jekyllrb.com)
[![Powered by Liquid Templates](https://img.shields.io/badge/liquid-4.0.3-blue.svg)](https://shopify.github.io/liquid/)
[![Powered by SASS CSS pre-processor](https://img.shields.io/badge/sass-3.7.4-blue.svg)](https://sass-lang.com)

В предлагаемом плане Ветхий и Новый заветы читаются параллельно.

[Cкачать в виде модуля для приложения `MyBible`][00].

Для установки модуля сначала скачайте его, затем переместите или скопируйте его (а именно файл `NovChurch.plan.SQLite3`) из папки `Downloads` в папку `MyBible`, в которой находится уже установленное приложение `MyBible`, чтобы увидеть эту папку сначала вам придётся выбрать устройство хранения данных, по умолчанию это внутренняя память гаджета, а не `SDCARD`. После этого план будет доступен внутри приложения `MyBible`.

Ссылки для скачивания файлов для печати (в формате PDF):

- [Шрифтом среднего размера на двух страницах][01]
- [Крупным шрифтом на шести страницах][02]
- [Мелким шрифтом в виде книжечки][03]

[Интерактивная версия][04] со ссылками на сайт `bible.by`, но нужно завести аккаунт на `github.com` и форкнуть план себе, тогда чекбоксами можно будет отмечать прочитанное.

Видео-инструкция как сложить книжечку для тех кто использует молодёжный вариант:

[![Видео-инструкция](https://i.ytimg.com/vi/IAb31rIeGZo/hqdefault.jpg)](https://www.youtube.com/watch?v=IAb31rIeGZo)

Маленький, но возможно весьма полезный совет печатающим молодёжный вариант: При печати выставляйте масштаб печати вручную. По умолчанию принтер даже уменьшает масштаб, чтобы ничего не вылезло за края, так у меня по умолчанию принтер назначает масштаб `93%`, что делает шрифт мелким до нечитаемости. Я же выставляю масштаб `108%`, ну минимум `105%` у вас наверное получится чтобы ничего за края не вылезло и тогда шрифт ощутимо крупнее получается, на радость глазам. 

## Под капотом

Благодаря [обработчику событий][05] файлы `.pdf` пересобираются при изменениях в файлах `.tex`.

[00]: ./download/NOVCHURCH-p.plan.SQLite3
[01]: ./download/commonplan.pdf
[02]: ./download/eldersplan.pdf
[03]: ./download/youthplan.pdf
[04]: https://gist.github.com/a1ip/ace8fca44da7bd67cbf3100a645a2046
[05]: .github/workflows/latex2pdf.yml
