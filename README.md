# &lt;simple-slider&gt;

A Polymer element providing a [simple slider](http://ruyadorno.github.io/SimpleSlider) functionality.

version: 0.2.0

> Maintained by [Ruy Adorno](https://github.com/ruyadorno).


## Demo

> [Check it live](http://ruyadorno.github.io/SimpleSlider).


## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/simple-slider.html">
    ```

3. Start using it!

    ```html
    <simple-slider style="width:500px; height:500px">
        <img src="foo/bar1.png"/>
        <img src="foo/bar2.png"/>
        <img src="foo/bar3.png"/>
    </simple-slider>
    ```


## Options

Attribute              | Options                   | Default             | Description
---                    | ---                       | ---                 | ---
`auto-play`            | `true`, `false`           | `true`              | Value determining if the slide transition should happen automatically
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

