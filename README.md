# CSS cheat sheet

CSS is much more free then HTML, everyones is different

Cascading Stylesheets, not a programing language

### Methods for adding CSS

- Inline CSS (adding CSS inside the element(very bad practice))
- Internal CSS (adding as `<style>` inside the HTML file, not so good eather)
- External CSS (make .css file and link to it(best option))

To add CSS externally to our index.html we wanna add `<link>` tag inside the header that links to our .css file

### CSS Selectors

`a { background-color: yellow; }`
where `a` is a selector, `background-color` is property and `yellow` is value

note that `a` will apply to every one of them, so in most cases we would like to use id's

There's no big difference between id's and classes, but id has to be unique, so basically just use classes

You can put class inside the div like this `<div class="box-1">`

To call it in the CSS file use '.' - `.box-1`

