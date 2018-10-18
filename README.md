# Drupal8-API

Druapal8 was released in November 2015, and it improves and integrates a lot of modules inside its core. Drupal 8 also adds a lot of functionality from the beginning like a WYSIWYG editor for the texts or the most used tools like Views or the traductions' module.

In the other hand, the theme implemetation changes a lot. Drupal8 uses __TWIG__, a template engine written in PHP, unlike Drupal 7 that used a simple PHP syntax.  

### Links ###

__Drupal8 Offical Website__: https://www.drupal.org/8

__TWIG Website__: https://twig.symfony.com/

## Repository's content ##

Inside this repository you'll find a basic custom theme, written using Drupal8's API.

```bash
├── css
│   │
│   ├── fontawesome-all.min.css
│   ├── jquery-ui.css
│   ├── style.css
│
├── images
├── js
│   ├── custom.js
│   ├── jquery.ui.js
│
├── templates
│   |
│   ├── html.html.twig
│   ├── node.html.twig
│   ├── page.html.twig
│
├── vendor
│   |
│   ├── foundation
│   │     ├── css
│   │     │   ├── app.css
│   │     │   ├── foundation.css
│   │     │   ├── foundation.min.css
│   │     ├── js
│   │         ├── vendor
│   │         │    ├── jquery.js
│   │         │    ├── what-input.js
│   │         ├── app.css
│   │         ├── foundation.js
│   │         ├── foundation.min.js
│   │
│   ├── swiper
│        ├── dist
│            ├── css
│            │    ├── swiper.css
│            │    ├── swiper.min.js
│            ├── js
│                ├── swiper.esm.bundle.js
│                ├── swiper.esm.js
│                ├── swiper.js
│                ├── swiper.min.js
│                ├── swiper.min.js.map
│
├── Drupal8API.info.yml
├── Drupal8API.libraries.yml
├── theme_settings.php
├── Drupal8API.theme
└── README.md
```