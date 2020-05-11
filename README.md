# [Neumorphism UI PRO](https://demo.themesberg.com/neumorphism-ui-pro/) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fthemesberg.com%2Fproduct%2Fui-kits%2Fneumorphism-ui-pro&via=themesberg&text=Start%20developing%20neumorphic%20interfaces%20with%20Neumorphism%20UI%20PRO&hashtags=neumorphism%2Cneomorphism%2Cbootstrap)

 ![version](https://img.shields.io/badge/version-3.1.2-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/themesberg/th-neumorphism-ui-pro.svg?maxAge=2592000)](https://github.com/themesberg/th-neumorphism-ui-pro/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/themesberg/th-neumorphism-ui-pro.svg?maxAge=2592000)](https://github.com/themesberg/th-neumorphism-ui-pro/issues?q=is%3Aissue+is%3Aclosed)

<a href="https://demo.themesberg.com/neumorphism-ui-pro/">
 <img src="https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/neumorphism-ui-pro-preview.gif" alt="Neumorphism UI PRO Preview"/>
 </a>

Start developing neumorphic web applications and pages using Neumorphism UI PRO which makes use of the neumorphic design trend. It features over 1000 individual components, more than 25 sections and 13 example pages.

## Neumorphic components

All components are perfectly in compliance with the neumorphism design trend making use of the specific shadow and coloring attributes. Neumorphism UI PRO also comes with the shadow inset style add-on.

Check out [all components here](https://demo.themesberg.com/neumorphism-ui-pro/html/components/all.html).

## Example pages

Neumorphism UI PRO comes with 13 example pages including an about, pricing, contact, log in and register pages. You can use these example pages to quickly set up a working website in no time.

## Full documentation

Each component, plugin and the general workflow is well documented. Check out the [online documentation for Neumorphism UI PRO](https://themesberg.com/docs/neumorphism-ui/getting-started/quick-start/).

## Workflow

This product is built using the following widely used technologies:

- Most popular CSS Framework Bootstrap
- Productive workflow tool Gulp
- Awesome CSS preprocessor Sass

## Table of Contents

* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Demo

| Components | About | Pricing | Services |
| --- | --- | --- | --- |
| [![Components](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/github/all-components.jpg)](https://demo.themesberg.com/neumorphism-ui-pro/html/components/all.html) | [![About page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/github/about.jpg)](https://demo.themesberg.com/neumorphism-ui-pro/html/pages/about.html) | [![Pricing page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/github/pricing.jpg)](https://demo.themesberg.com/neumorphism-ui-pro/html/pages/pricing.html) | [![Services page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/github/services.jpg)](https://demo.themesberg.com/neumorphism-ui-pro/html/pages/services.html)

| Contact | Login | Register | Documentation |
| --- | --- | --- | --- |
| [![Contact page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/github/contact.jpg)](https://demo.themesberg.com/neumorphism-ui-pro/html/pages/contact.html) | [![Login page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/github/login.jpg)](https://demo.themesberg.com/neumorphism-ui-pro/html/pages/sign-in.html) | [![Register page](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/github/register.jpg)](https://demo.themesberg.com/neumorphism-ui-pro/html/pages/sign-up.html) | [![Documentation](https://themesberg.s3.us-east-2.amazonaws.com/public/products/neumorphism-ui-pro/github/docs.jpg)](https://themesberg.com/docs/neumorphism-ui/getting-started/quick-start/)

-   [Live Preview](https://demo.themesberg.com/neumorphism-ui-pro/)
-   [Details](https://themesberg.com/product/ui-kits/neumorphism-ui-pro?ref=github-neumorphism)

## Quick start

1. Download from [Themesberg](https://themesberg.com/product/ui-kits/neumorphism-ui-pro?ref=github-neumorphism)
2. Download the project's zip
3. Make sure you have Node locally installed.
4. Download Gulp Command Line Interface to be able to use gulp in your Terminal.

```
npm install gulp-cli -g
```

5. After installing Gulp, run npm install in the main `neumorphism/` folder to download all the project dependencies. You'll find them in the `node_modules/` folder.

```
npm install
```

6. Run gulp in the `neumorphism/` folder to serve the project files using BrowserSync. Running gulp will compile the theme and open `/index.html` in your main browser.

```
gulp
```

While the gulp command is running, files in the `assets/scss/`, `assets/js/` and `components/` folders will be monitored for changes. Files from the `assets/scss/` folder will generate injected CSS.

Hit `CTRL+C` to terminate the gulp command. This will stop the local server from running.

## Theme without Sass, Gulp or Npm

If you'd like to get a version of our theme without Sass, Gulp or Npm, we've got you covered. Run the following command:

```
gulp build:dev
```

This will generate a folder `html&css` which will have unminified CSS, Html and Javascript.

## Minified version

If you'd like to compile the code and get a minified version of the HTML and CSS just run the following Gulp command:

```
gulp build:dist
```

This will generate a folder `dist` which will have minified CSS, Html and Javascript.

## Documentation

The documentation for Neumorphism UI PRO is hosted on our [website](https://themesberg.com/docs/neumorphism-ui/getting-started/overview).

## File Structure

Within the download you'll find the following directories and files:

```
Neumorphism UI PRO
.
├── README.md
├── gulpfile.js
├── neumorphism-ui-pro.zip
├── package-lock.json
├── package.json
└── src
    ├── assets
    │   ├── img
    │   │   ├── blog
    │   │   ├── brand
    │   │   ├── carousel
    │   │   ├── checker_logo.png
    │   │   ├── clients
    │   │   ├── favicon
    │   │   ├── illustrations
    │   │   ├── macbook-mockup.png
    │   │   ├── megamenu-image.jpg
    │   │   ├── presentation
    │   │   ├── presentation-mockup.png
    │   │   ├── presentation-sections
    │   │   ├── sections
    │   │   ├── shop
    │   │   ├── signature.svg
    │   │   ├── team
    │   │   ├── themesberg.svg
    │   │   └── wavelogo.svg
    │   └── js
    │       └── neumorphism.js
    ├── html
    │   ├── components
    │   │   ├── accordions.html
    │   │   ├── alerts.html
    │   │   ├── all.html
    │   │   ├── badges.html
    │   │   ├── bootstrap-carousels.html
    │   │   ├── breadcrumbs.html
    │   │   ├── buttons.html
    │   │   ├── cards.html
    │   │   ├── counters.html
    │   │   ├── e-commerce.html
    │   │   ├── forms.html
    │   │   ├── icon-boxes.html
    │   │   ├── modals.html
    │   │   ├── navs.html
    │   │   ├── owl-carousels.html
    │   │   ├── pagination.html
    │   │   ├── popovers.html
    │   │   ├── progress-bars.html
    │   │   ├── steps.html
    │   │   ├── tables.html
    │   │   ├── tabs.html
    │   │   ├── timelines.html
    │   │   ├── toasts.html
    │   │   ├── tooltips.html
    │   │   ├── typography.html
    │   │   └── widgets.html
    │   ├── pages
    │   │   ├── 404.html
    │   │   ├── 500.html
    │   │   ├── about.html
    │   │   ├── blog-post.html
    │   │   ├── blog.html
    │   │   ├── coming-soon.html
    │   │   ├── contact.html
    │   │   ├── maintenance.html
    │   │   ├── pricing.html
    │   │   ├── profile.html
    │   │   ├── services.html
    │   │   ├── sign-in.html
    │   │   └── sign-up.html
    │   └── sections
    │       ├── about.html
    │       ├── blog.html
    │       ├── clients.html
    │       ├── contact.html
    │       ├── features.html
    │       ├── navbars.html
    │       ├── pricing.html
    │       ├── team.html
    │       └── testimonials.html
    ├── index.html
    ├── partials
    │   ├── _analytics.html
    │   ├── _footer.html
    │   ├── _head.html
    │   ├── _navigation.html
    │   ├── _pages-preview.html
    │   ├── _pricing.html
    │   ├── _scripts.html
    │   └── components
    │       ├── _accordions.html
    │       ├── _alerts.html
    │       ├── _badges.html
    │       ├── _bootstrap-carousels.html
    │       ├── _breadcrumbs.html
    │       ├── _buttons.html
    │       ├── _cards.html
    │       ├── _counters.html
    │       ├── _e-commerce.html
    │       ├── _forms.html
    │       ├── _icon-boxes.html
    │       ├── _modals.html
    │       ├── _navs.html
    │       ├── _owl-carousels.html
    │       ├── _pagination.html
    │       ├── _popovers.html
    │       ├── _progress-bars.html
    │       ├── _steps.html
    │       ├── _tables.html
    │       ├── _tabs.html
    │       ├── _timelines.html
    │       ├── _toasts.html
    │       ├── _tooltips.html
    │       ├── _typography.html
    │       └── _widgets.html
    └── scss
        ├── bootstrap
        │   ├── _alert.scss
        │   ├── _badge.scss
        │   ├── _breadcrumb.scss
        │   ├── _button-group.scss
        │   ├── _buttons.scss
        │   ├── _card.scss
        │   ├── _carousel.scss
        │   ├── _close.scss
        │   ├── _code.scss
        │   ├── _custom-forms.scss
        │   ├── _dropdown.scss
        │   ├── _forms.scss
        │   ├── _functions.scss
        │   ├── _grid.scss
        │   ├── _images.scss
        │   ├── _input-group.scss
        │   ├── _jumbotron.scss
        │   ├── _list-group.scss
        │   ├── _media.scss
        │   ├── _mixins.scss
        │   ├── _modal.scss
        │   ├── _nav.scss
        │   ├── _navbar.scss
        │   ├── _pagination.scss
        │   ├── _popover.scss
        │   ├── _print.scss
        │   ├── _progress.scss
        │   ├── _reboot.scss
        │   ├── _root.scss
        │   ├── _spinners.scss
        │   ├── _tables.scss
        │   ├── _toasts.scss
        │   ├── _tooltip.scss
        │   ├── _transitions.scss
        │   ├── _type.scss
        │   ├── _utilities.scss
        │   ├── _variables.scss
        │   ├── bootstrap-grid.scss
        │   ├── bootstrap-reboot.scss
        │   ├── bootstrap.scss
        │   ├── mixins
        │   ├── utilities
        │   └── vendor
        ├── neumorphism
        │   ├── _components.scss
        │   ├── _functions.scss
        │   ├── _layout.scss
        │   ├── _mixins.scss
        │   ├── _reboot.scss
        │   ├── _utilities.scss
        │   ├── _variables.scss
        │   ├── _vendor.scss
        │   ├── components
        │   ├── layout
        │   ├── mixins
        │   ├── utilities
        │   └── vendor
        └── neumorphism.scss
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

## Resources
- Demo: <https://demo.themesberg.com/neumorphism-ui-pro/>
- Download Page: <https://themesberg.com/product/ui-kits/neumorphism-ui-pro>
- Documentation: <https://themesberg.com/docs/neumorphism-ui/getting-started/quickstart>
- Themesberg EULA: <https://themesberg.com/licensing>
- Support: <https://themesberg.com/contact>
- Issues: [Github Issues Page](https://github.com/themesberg/th-neumorphism-ui-pro/issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for Neumorphism UI PRO Kit. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of Neumorphism UI PRO. Check the CHANGELOG on our [website](https://themesberg.com/product/ui-kits/neumorphism-ui-pro?ref=github-neumorphism).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://themesberg.com/contact?ref=github-neumorphism) instead of opening an issue.

## Licensing

- Copyright 2020 Themesberg (Crafty Dwarf LLC) (https://themesberg.com)
- Themesberg [EULA](https://themesberg.com/licensing)

## Useful Links

- [More themes](https://themesberg.com/themes?ref=github-neumorphism) from Themesberg
- [Free themes](https://themesberg.com/products/free-themes?ref=github-neumorphism) from Themesberg
- [Affiliate Program](https://themesberg.com/affiliate?ref=github-neumorphism)

##### Social Media

Twitter: <https://twitter.com/themesberg>

Facebook: <https://www.facebook.com/themesberg/>

Dribbble: <https://dribbble.com/themesberg>

Instagram: <https://www.instagram.com/themesberg/>
