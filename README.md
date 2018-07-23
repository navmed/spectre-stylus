# spectre-stylus
A stylus port of the Spectre CSS - https://picturepan2.github.io/spectre/index.html

To use this with Vue, use the following code

````
<style lang="stylus">
@import 'assets/spectre-0.5.3.stylus/_variables.styl'
@import 'assets/spectre-0.5.3.stylus/*'
@import 'assets/spectre-0.5.3.stylus/icons/_icons-core.styl'
@import 'assets/spectre-0.5.3.stylus/icons/*'
@import 'assets/spectre-0.5.3.stylus/mixins/*'
@import 'assets/spectre-0.5.3.stylus/utilities/*'
</style>
````

Import them in this order to avoid missing variables. 
