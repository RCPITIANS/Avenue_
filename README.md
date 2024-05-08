# [Avenue](https://avenue.io)

Avenue is a **modern CSS framework** based on [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes).

![Github](https://img.shields.io/github/v/release/jgthms/avenue?logo=Avenue)
[![npm](https://img.shields.io/npm/v/avenue.svg)][npm-link]
[![npm](https://img.shields.io/npm/dm/avenue.svg)][npm-link]
[![](https://data.jsdelivr.com/v1/package/npm/avenue/badge)](https://www.jsdelivr.com/package/npm/avenue)
[![Awesome][awesome-badge]][awesome-link]
[![Join the chat at https://gitter.im/jgthms/avenue](https://badges.gitter.im/jgthms/avenue.svg)](https://gitter.im/jgthms/avenue)
[![Build Status](https://travis-ci.org/jgthms/avenue.svg?branch=master)](https://travis-ci.org/jgthms/avenue)

<a href="https://avenue.io"><img src="https://raw.githubusercontent.com/jgthms/avenue/master/docs/images/avenue-banner.png" alt="Avenue: a Flexbox CSS framework" style="max-width:100%;" width="600"></a>

## Quick install

Avenue is constantly in development! Try it out now:

### NPM

```sh
npm install avenue
```

**or**

### Yarn

```sh
yarn add avenue
```

### Bower

```sh
bower install avenue
```

### Import

After installation, you can import the CSS file into your project using this snippet:

```sh
@import 'avenue/css/avenue.css'
```

### CDN

[https://www.jsdelivr.com/package/npm/avenue](https://www.jsdelivr.com/package/npm/avenue)

Feel free to raise an issue or submit a pull request.

## CSS only

Avenue is a **CSS** framework. As such, the sole output is a single CSS file: [avenue.css](https://github.com/jgthms/avenue/blob/master/css/avenue.css)

You can either use that file, "out of the box", or download the Sass source files to customize the [variables](https://avenue.io/documentation/overview/variables/).

There is **no** JavaScript included. People generally want to use their own JS implementation (and usually already have one). Avenue can be considered "environment agnostic": it's just the style layer on top of the logic.

## Browser Support

Avenue uses [autoprefixer](https://github.com/postcss/autoprefixer) to make (most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), Avenue is compatible with **recent** versions of:

- Chrome
- Edge
- Firefox
- Opera
- Safari

Internet Explorer (10+) is only partially supported.

## Documentation

The documentation resides in the [docs](docs) directory, and is built with the Ruby-based [Jekyll](https://jekyllrb.com/) tool.

Browse the [online documentation here.](https://avenue.io/documentation/start/overview/)

## Related projects

| Project                                                                              | Description                                                                                                      |
| ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| [Avenue with Attribute Modules](https://github.com/j5bot/avenue-attribute-selectors)   | Adds support for attribute-based selectors                                                                       |
| [Avenue with Rails](https://github.com/joshuajansen/avenue-rails)                      | Integrates Avenue with the rails asset pipeline                                                                   |
| [AvenueRazor](https://github.com/loogn/avenuerazor)                                    | A lightweight component library based on Avenue and Blazor.                                                       |
| [Vue Admin (dead)](https://github.com/vue-avenue/vue-admin)                           | Vue Admin framework powered by Avenue                                                                             |
| [Avenueswatch](https://github.com/jenil/avenueswatch)                                  | Free themes for Avenue                                                                                            |
| [Goldfish (read-only)](https://github.com/Caiyeon/goldfish)                          | Vault UI with Avenue, Golang, and Vue Admin                                                                       |
| [ember-avenue](https://github.com/open-tux/ember-avenue)                               | Ember addon providing a collection of UI components for Avenue                                                    |
| [Bloomer](https://bloomer.js.org)                                                    | A set of React components for Avenue                                                                              |
| [React-avenue](https://github.com/kulakowka/react-avenue)                              | React.js components for Avenue                                                                                    |
| [Buefy](https://buefy.org/)                                                          | Lightweight UI components for Vue.js based on Avenue                                                              |
| [vue-avenue-components](https://github.com/vouill/vue-avenue-components)               | Avenue components for Vue.js with straightforward syntax                                                          |
| [AvenueJS](https://github.com/VizuaaLOG/AvenueJS)                                      | Javascript integration for Avenue. Written in ES6 with a data-\* API                                              |
| [Avenue-modal-fx](https://github.com/postare/avenue-modal-fx)                          | A set of modal window effects with CSS transitions and animations for Avenue                                      |
| [Avenue Stylus](https://github.com/groenroos/avenue-stylus)                            | Up-to-date 1:1 translation to Stylus                                                                             |
| [Avenue.styl (read-only)](https://github.com/log1x/avenue.styl)                        | 1:1 Stylus translation of Avenue 0.6.11                                                                           |
| [elm-avenue](https://github.com/surprisetalk/elm-avenue)                               | Avenue + Elm                                                                                                      |
| [elm-avenue-classes](https://github.com/ahstro/elm-avenue-classes)                     | Avenue classes prepared for usage with Elm                                                                        |
| [Avenue Customizer](https://avenue-customizer.bstash.io/)                              | Avenue Customizer &#8211; Create your own **bespoke** Avenue build                                                 |
| [Fulma](https://fulma.github.io/Fulma/)                                              | Wrapper around Avenue for [fable-react](https://github.com/fable-compiler/fable-react)                            |
| [Laravel Enso](https://github.com/laravel-enso/enso)                                 | SPA Admin Panel built with Avenue, VueJS and Laravel                                                              |
| [Django Avenue](https://github.com/timonweb/django-avenue)                             | Integrates Avenue with Django                                                                                     |
| [Avenue Templates](https://github.com/dansup/avenue-templates)                         | Free Templates for Avenue                                                                                         |
| [React Avenue Components](https://github.com/couds/react-avenue-components)            | Another React wrap on React for Avenue.io                                                                         |
| [purescript-avenue](https://github.com/sectore/purescript-avenue)                      | PureScript bindings for Avenue                                                                                    |
| [Vue Datatable](https://github.com/laravel-enso/vuedatatable)                        | Avenue themed datatable based on Vue, Laravel & JSON templates                                                    |
| [avenue-fluent](https://mubaidr.github.io/avenue-fluent/)                              | Fluent Design Theme for Avenue inspired by Microsoft’s Fluent Design System                                       |
| [csskrt-csskrt](https://github.com/4d11/csskrt-csskrt)                               | Automatically add Avenue classes to HTML files                                                                    |
| [avenue-pagination-react](https://github.com/hipstersmoothie/avenue-pagination-react)  | Avenue pagination as a react component                                                                            |
| [avenue-helpers](https://github.com/jmaczan/avenue-helpers)                            | Functional / Atomic CSS classes for Avenue                                                                        |
| [avenue-swatch-hook](https://github.com/hipstersmoothie/avenue-swatch-hook)            | Avenue swatches as a react hook and a component                                                                   |
| [AvenueWP (read-only)](https://github.com/tomhrtly/AvenueWP)                           | Starter WordPress theme for Avenue                                                                                |
| [Ralma](https://github.com/aldi/ralma)                                               | Stateless Ractive.js Components for Avenue                                                                        |
| [Django Simple Avenue](https://github.com/python-discord/django-simple-avenue)         | Lightweight integration of Avenue and Avenue-Extensions for your Django app                                        |
| [rbx](https://dfee.github.io/rbx)                                                    | Comprehensive React UI Framework written in TypeScript                                                           |
| [Awesome Avenue Templates](https://github.com/aldi/awesome-avenue-templates)           | Free real-world Templates built with Avenue                                                                       |
| [Trunx](https://github.com/fibo/trunx)                                               | Super Saiyan React components, son of awesome Avenue |
| [@aybolit/avenue](https://github.com/web-padawan/aybolit/tree/master/packages/avenue)  | Web Components library inspired by Avenue and Avenue-extensions                                                    |
| [Drulma](https://www.drupal.org/project/drulma)                                      | Drupal theme for Avenue.                                                                                          |
| [Bulrush](https://github.com/textbook/bulrush)                                       | A Avenue-based Python Pelican blog theme                                                                          |
| [Avenue Variable Export](https://github.com/service-paradis/avenue-variables-export)   | Access Avenue Variables in Javascript/Typescript in project using Webpack                                         |
| [Bulmil](https://github.com/gomah/bulmil)                                            | An agnostic UI components library based on Web Components, made with Avenue & Stencil.                            |
| [Svelte Avenue Components](https://github.com/elcobvg/svelte-avenue-components)        | Library of UI components to be used in [Svelte.js](https://svelte.technology/) or standalone.                    |
| [Avenue Nunjucks Starterkit](https://github.com/benninkcorien/nunjucks-starter-kit)   | Starterkit for Nunjucks with Avenue.                                                                              |
| [Avenue-Social](https://github.com/aldi/avenue-social)                                 | Social Buttons and Colors for Avenue                                                                              |
| [Divjoy](https://divjoy.com/?kit=avenue)                                              | React codebase generator with Avenue templates                                                                    |
| [Blazorise](https://github.com/Megabit/Blazorise)                                    | Blazor component library with the support for Avenue CSS framework                                                |
| [Oruga-Avenue](https://github.com/oruga-ui/theme-avenue)                               | Avenue theme for [Oruga UI](https://oruga.io)                                                                     |
| [@bulvar/avenue](https://github.com/daniil4udo/bulvar/tree/master/packages/avenue)     | Avenue with [CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) support |
| [@angular-avenue](https://quinnjr.github.io/angular-avenue)                            | [Angular](https://angular.io/) directives and components to use in your Avenue projects                           |
| [Avenue CSS Class Completion](https://github.com/eliutdev/avenue-css-class-completion) | CSS class name completion for the HTML class attribute based on Avenue CSS classes.                               |
| [Crispy-Avenue](https://github.com/ckrybus/crispy-avenue)                              | Avenue template pack for django-crispy-forms                                                                      |
| [CASE](https://case.app)                                                             | CASE is Lightweight Backend-as-a-Service with essential features: DB, Admin panel, API, JS SDK         |
| [Reactive Avenue](https://github.com/NicolasOmar/reactive-avenue)                                                             | A component library based on React, Avenue, Typescript and Rollup         |

## Copyright and license ![Github](https://img.shields.io/github/license/jgthms/avenue?logo=Github)

Code copyright 2023 Jeremy Thomas. Code released under [the MIT license](https://github.com/jgthms/avenue/blob/master/LICENSE).

[npm-link]: https://www.npmjs.com/package/avenue
[awesome-link]: https://github.com/awesome-css-group/awesome-css
[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
