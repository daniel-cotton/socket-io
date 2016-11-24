# \<socket-io\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/daniel-cotton/socket-io)


Polymer 1.0 element for socket.io apis.

Demo/Docs available @ https://daniel-cotton.github.io/socket-io/

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="socket.io.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<socket-io id="socket" endpoint="https://socket-io-tester.herokuapp.com/" events="[[events]]"></socket-io>
```



# To use the element

Firstly - install via Bower.

    bower install --save daniel-cotton/socket-io
    
Then import into your Polymer project

```html
<link rel="import" href="../bower_components/socket-io/socket-io.html">
```


# To Build

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Running Tests

```
$ polymer test
```

This component can be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
