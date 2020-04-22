# SASS
Sass convenience tools.


## @functions

`transition-props($props...)`

`spacing($space)`

`strip-unit($number)`

`get-asset-url($asset, $path: $default-path)`

`str-replace($string, $search, $replace: "")`

`escape-svg($string)`


## @mixins

`render-map($map)`

`render-map-by-breakpoints-up($map)`

`position($pos: null, $top: null, $right: null, $bottom: null, $left: null) `

`flex($flex-direction: null, $justify-content: null, $align-items: null, $flex-wrap: null)`

`word-break($v: break-word)`

`u-spacing($size, $last: false)`

`visibility($toggle)`

`font-variant($color: null, $font-family: null, $font-weight: null) `

`padding($size, $axis: null)`

`margin($size, $axis: null)`


### Road-map (todo-list)

1. Split features (@mixins and @functions) into individual files.
2. Add @error and @warning logs to each feature.
3. Add tests to each feature.
4. Add detailed usage and dependency description to each feature.
5. Create a minified version.
6. Create dist version (as node package).
7. Add more features.
