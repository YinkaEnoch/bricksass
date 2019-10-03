# BrickSass
### A simple SASS/SCSS placeholder library for creating seamless CSS rules. The library approach makes it easier for SASS/SCSS developers to write rules with minimal effort and in less line(s). The library is written using mixins, placeholders and variables so as to make it extendable and easy-to-use for developers without introducing unnecessary rules and bloats into their projects.
--------------------------------------
## Example Usage
To use the library in your project, download the library into your project directory and import the `_index.scss` file into your project's main sass/scss file.

>Inside your main.scss file include: `@import 'path/to/bricksass/index'`

## Using the placeholder rules in your CSS rules
Brick.SASS rules can be used by extending them from within your CSS rules. The placeholder rules should be declared at the top of your style so as to minimize conflict with your defined rules.
```
.container{
  @extend %w-100,%h-100;
}
```
```
.header{
  @extend %is-uppercase, %text-center, %size-3, %font-bold;
}
```
--------------------------------------
## Author
  * [Yinka Enoch Adedokun](https://yinkaenoch.github.io)
--------------------------------------
## License
This library is released under the [MIT License](https://www.opensource.org/licenses/MIT)
