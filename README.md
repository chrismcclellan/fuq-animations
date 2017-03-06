#Fuq Animations
A Sass animations library riddled with mixins.

## Using Mixins

```scss
.your-element {
   @include animations-slide-in-up;
   @include animations-speed(300ms);
}
```

```scss
// Configurations
// Will output both selector types ('camelize', 'slugify')
// Pass one or two items in a list or false
$animations-format: (
    'camelize',
    'slugify'
) !default;

// Animation speeds
$animations-speed:            1000ms !default;
$animations-speed-hinge:      2000ms !default;
$animations-speed-flip-out-x:  750ms !default;
$animations-speed-flip-out-y:  750ms !default;
$animations-speed-bounce-in:   750ms !default;
$animations-speed-bounce-out:  750ms !default;

// These will be comiled into css unless a new config exists
// Ideally you create a `$animations-config` that only includes what you want built
// Mixins will still be available!
$animations-configs: (
    extras,
    bounce,
    bounce-in,
    bounce-in-up,
    bounce-in-right,
    bounce-in-down,
    bounce-in-left,
    bounce-out,
    bounce-out-up,
    bounce-out-right,
    bounce-out-down,
    bounce-out-left,
    fade,
    fade-in-up,
    fade-in-up-big,
    fade-in-right,
    fade-in-right-big,
    fade-in-down,
    fade-in-down-big,
    fade-in-left,
    fade-in-left-big,
    fade-out,
    fade-out-up,
    fade-out-up-big,
    fade-out-right,
    fade-out-right-big,
    fade-out-down,
    fade-out-down-big,
    fade-out-left,
    fade-out-left-big,
    flip,
    flip-in-x,
    flip-in-y,
    flip-out-x,
    flip-out-y,
    flash,
    hinge, 
    light-speed-in,
    light-speed-out,
    pulse, 
    roll-in,
    roll-out, 
    shake, 
    swing, 
    tada,  
    wiggle,
    wobble,
    rotate-in,
    rotate-in-down-left,
    rotate-in-down-right,
    rotate-in-up-left,
    rotate-in-up-right,
    rotate-out,
    rotate-out-down-left,
    rotate-out-down-right,
    rotate-out-up-left,
    rotate-out-up-right,
    slide-in-up,
    slide-in-right,
    slide-in-down,
    slide-in-left,
    slide-out-up,
    slide-out-right,
    slide-out-down,
    slide-out-left
) !default;
```

## Roadmap

- [ ] Config lookup in project root

- [ ] Dryer mixins

- [ ] Grunt task

- [ ] NPM

## License
Fuq Animations & Animate.css is licensed under the MIT license. (http://opensource.org/licenses/MIT)

