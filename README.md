##This polymer element is just an adaptation of this jQuery plugin: [Unicorn.js](https://github.com/paulirish/Unicorn-js)

##[Demo](http://demo.paulvarache.ninja/unicorn-puke)

Thanks to the all mighty web components, lighten up your websites and webapps with unicorn-puke !  
A simple
```html
<unicorn-puke>My awesome text</unicorn-puke>
```
will change your life.  
You can personalize your puke with some attributes:
<ol>
    <li>Saturation
        <ul>
            <li>changes the intensity of colours</li>
            <li>accepts integer values between 1 and 100</li>
            <li>defaults to 100</li>
        </ul>
    </li>
    <li>Light
        <ul>
            <li>reflects the colours' brightness</li>
            <li>accepts integer values between 1 and 100</li>
            <li>defaults to 50, as values of 100 will produce solid white text</li>
        </ul>
    </li>
    <li>Speed (ms)
        <ul>
            <li>the length of one cycle</li>
            <li>accepts integer values representing ms (1s = 1000ms)</li>
            <li>defaults to 10</li>
        </ul>
    </li>
    <li>ltr
        <ul>
            <li>specifies the direction of "<strong>bow-flow</strong>," standing for `left to right`</li>
            <li>accepts binary value of true or false</li>
            <li>defaults to false, so <strong>bow-flow</strong> is right to left</li>
        </ul>
    </li>
</ol>

[2]: https://raw2.github.com/toddpress/Unicorn-js/master/unicorn.js
