---
title: Home
layout: home
---

This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate







С проблемностью title/description при разворачивании на GitHub нашел пока такой выход:  
Если самая первая строка в README.md "простой текст", а не заголовок, то title/description берутся из _config.yml


# Заголовок уровня 1
Это обычная строка 1234567890  
тест синхронизации  😈
Это обычная строка 1234567890 💗

## Заголовок уровня 2 💗
Это обычная строка 1234567890  
Это обычная строка 1234567890  
хххххххххххххххххххххххххххх  
  
:blush:  
:heartpulse: 
:heartpulse:


### Заголовок уровня 3
Это обычная строка 1234567890  
Это обычная строка 1234567890
#### Заголовок уровня 4
Это обычная строка 1234567890  
Это обычная строка 1234567890
##### Заголовок уровня 5
Это обычная строка 1234567890  
Это обычная строка 1234567890


===========

## Hi there 👋

We are a group of students from [ENSEEIHT](https://www.enseeiht.fr/) (read "N7") specialized in various fields inside the Computer science department. This organization aims to regroup open source projects that we think are worth looking at, and to provide a common ground for everyone to contribute to them.

## Under construction 🚧

We're using the basic jekyll generator to generate a static site at the moment, but this is temporary. The features available might be sufficient for a basic documentation, but it clearly is impossible to build a fully featured website using this infrastructure.

## What's next? 🚀

We'll be publishing releases and news here, so stay tuned for updates.


===========



## Лаба с кодовым названием RUDN-QGIS-3D
Порядок создания **3D-модели** на *небольшой* участок местности со зданиями и внедренными 3D-моделями объектов в QGIS и Qgis2threejs


========== 001 =================================

### Порядок создания 3D-модели на небольшой  участок местности со зданиями и внедренными 3D-моделями объектов в QGIS и Qgis2threejs

#### 1) Подготовительная часть



#### Надстрочные знаки: km<sup>2</sup>. Подстрочные знаки: CO<sub>2</sub>

Here is a famous formula два доллара: $$E=mc^2$$.


Here is a famous formula один доллар: $E=mc^2$.




Создайте копию файла «Заготовка Проекта 3D.qgs», расположенного в корне папки «RUDN-QGIS-3D» с учебными материалами.

Переименуйте его, например, «**Проект 3D - Часть 2 - со зданиями.qgs**» и откройте этот проект в QGIS.

В панели Слои переместите слой «Здания - для второй части работы» на самый верх и включите его видимость.

Добавьте в проект вашу DEM (цифровую модель рельефа). Это файл с расширением **\*.tif**.

В панели Слои переместите слой с DEM в самый низ и отключите его видимость.



---------------------


| sdfdsf | fdgfdfd | ddddd   | ggggg   |
|--------|---------|---------|---------|
| 324    | 5435435 | 4435435 | 6757657 |


Это пример переноса строки (разрыв) внутри одного абзаца. Сейчас будет двойной пробел.  
Он успешно отрабатывается Writage. А вот обратный слеш, он\
Writage тоже отрабатывается. Зато он отрабатывается в GitHub.

**\*А это уже новый абзац\***

\----------------------------------------------------


Ниже `начинается многострочный` блок кода

    <!doctype html>
    <html>
        <head>
            <!-- Заголовок документа -->
        </head>
        <body>
            <!-- Тело документа -->
        </body>
    </html>

Блок кода завершился

---------------------
- - - - - - - - -

$$\phi_{n}(\kappa) = \frac{1}{4\pi^{2}\kappa^{2}}\int_{0}^{\infty}\frac{\sin(\kappa R)}{\kappa R}\frac{\partial}{\partial R}\left\lbrack R^{2}\frac{\partial D_{n}(R)}{\partial R} \right\rbrack\, dR$$


********
* * * * *

Длинный блок кода  

```html

<br> &nbsp;&nbsp; <img src="https://www.rudn.ru/u/www/images/for_smi_image/logo_rudn_eng.png" width=160>
    <p style="font-size: 16px; color: #0079c1; text-indent: 5px; margin-top: 5px;">
<b> &nbsp;&nbsp;&nbsp;&nbsp; 3D-геопортал окрестностей Махачкалы </b> </p>

```

---------------------
---------------------





