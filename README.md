# Boiled Page hero singleton

Hero SCSS singleton for Boiled Page frontend framework. It is intended to create a hero with a title, a headline, and some buttons.

## Install

Place `_hero.scss` file to `/assets/css/singletons` directory, and add its path to singleton block in `assets/css/app.scss` file. You will also need to add button component to make buttons working properly.

- Button component: <https://www.github.com/abelbrencsan/boiled-page-button-component>

## Usage

### Classes

Class name | Description | Example
---------- | ----------- | -------
`hero` | Applies hero. | `<div class="hero"></div>`
`hero-button-list` | Applies a list of buttons inside hero. Use grid component fr alignments | `<ul class="hero-button-list grid"></ul>`

### Examples

#### Example 1

The following example shows a hero with a title, a headline, and two buttons.

```html
<div class="hero">
  <div class="container">
    <h1>Lorem ipsum dolor amet</h1>
    <p>Nulla tempus lacus eget sodales venenatis metus</p>
    <ul class="hero-button-list grid grid--gutter grid--gutter--half grid--center grid--uniform">
      <li class="grid-col grid-col--xsmall--full">
        <a href="#" class="button button--fit" role="button">Button 1</a>
      </li>
      <li class="grid-col grid-col--xsmall--full">
        <a href="#" class="button button--fit" role="button">Button 2</a>
      </li>
    </ul>
  </div>
</div>
```
