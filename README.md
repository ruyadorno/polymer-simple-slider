# &lt;simple-slider&gt;

[![NPM version](https://badge.fury.io/js/polymer-simple-slider.svg)](https://npmjs.org/package/polymer-simple-slider) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/ruyadorno/polymer-simple-slider)

A Polymer element providing a [simple slider](http://ruyadorno.github.io/SimpleSlider) functionality.

> Maintained by [Ruy Adorno](https://github.com/ruyadorno).


## Demo

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="simple-slider.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<simple-slider style="width:400px; height:400px">
    <img src="http://placekitten.com/g/400/400"/>
    <img src="https://unsplash.it/400/400/?random=0"/>
    <img src="https://unsplash.it/400/400/?random=1"/>
    <img src="https://unsplash.it/400/400/?random=2"/>
</simple-slider>
```

 > [Check more examples](http://ruyadorno.github.io/polymer-simple-slider).


## Usage

1. Install using Bower (also available on npm)

    ```sh
    bower install --save polymer-simple-slider
    ```

2. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponents.js/webcomponents.js"></script>
    ```

3. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/polymer-simple-slider/simple-slider.html">
    ```

4. Start using it!

    ```html
    <simple-slider style="width:500px; height:500px">
        <img src="foo/bar1.png"/>
        <img src="foo/bar2.png"/>
        <img src="foo/bar3.png"/>
    </simple-slider>
    ```


## Options

version: 1.0.1

Attribute              | Options                   | Default             | Description
---                    | ---                       | ---                 | ---
`no-auto-play`         | Boolean                   | `false`             | If this attr is present, do not auto play slides
`transitionProperty`   | `left`, `right`, `opacity`| `left`              | Determines the css property to be animated
`transitionDuration`   | *Number*                  | `0.5`               | Value setting the duration of animation transition
`transitionDelay`      | *Number*                  | `3`                 | Value determining the wait between each animation when you use **autoPlay:true**
`startValue`           | *Number*                  | `-elem.width`       | Initial value of slide elements when starting a transition animation
`visibleValue`         | *Number*                  | `0`                 | The value a slide element should have when it is displayed
`endValue`             | *Number*                  | `elem.width`        | The value a slide will move to during a transition animation


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## History

For detailed changelog, check [Releases](https://github.com/ruyadorno/polymer-simple-slider/releases).


## More info
This project is a simple polymer element implementation of [SimpleSlider](http://ruyadorno.github.io/SimpleSlider/). Please visit its page for more information.

## License

[MIT License](http://opensource.org/licenses/MIT)

