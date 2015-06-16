# Ganimate.css: Animate.css for GWT styling

Easiest way to add amazing animations to your GWT application!

## Introduction from [Animate.css](https://github.com/daneden/animate.css) library:

`animate.css` is a bunch of cool, fun, and cross-browser animations for you to use in your projects. Great for emphasis, home pages, sliders, and general just-add-water-awesomeness.

## Installation (default: production version)

* download **ganimation.css-0.6.jar**, place it into your project's lib folder and include it to a project

* include into your **\<module_name\>.gwt.xml** file:

```xml
  <inherits name='de.wlsc.gwt.theme.ganimate.css.Ganimate' />
  ```

## Installation (unminified version)

* download **ganimation.css-0.6.jar**, place it into your project's lib folder and include it to a project

* include into your **\<module_name\>.gwt.xml** file:
 
```xml
  <inherits name='de.wlsc.gwt.theme.ganimate.css.GanimateDebug' />
  ```

* and just use it like this:

```java
  <g:Label styleName="animated bounceInRight" />
  ```

## Possible list of animations 

  * `bounce`
  * `flash`
  * `pulse`
  * `rubberBand`
  * `shake`
  * `swing`
  * `tada`
  * `wobble`
  * `jello`
  * `bounceIn`
  * `bounceInDown`
  * `bounceInLeft`
  * `bounceInRight`
  * `bounceInUp`
  * `bounceOut`
  * `bounceOutDown`
  * `bounceOutLeft`
  * `bounceOutRight`
  * `bounceOutUp`
  * `fadeIn`
  * `fadeInDown`
  * `fadeInDownBig`
  * `fadeInLeft`
  * `fadeInLeftBig`
  * `fadeInRight`
  * `fadeInRightBig`
  * `fadeInUp`
  * `fadeInUpBig`
  * `fadeOut`
  * `fadeOutDown`
  * `fadeOutDownBig`
  * `fadeOutLeft`
  * `fadeOutLeftBig`
  * `fadeOutRight`
  * `fadeOutRightBig`
  * `fadeOutUp`
  * `fadeOutUpBig`
  * `flipInX`
  * `flipInY`
  * `flipOutX`
  * `flipOutY`
  * `lightSpeedIn`
  * `lightSpeedOut`
  * `rotateIn`
  * `rotateInDownLeft`
  * `rotateInDownRight`
  * `rotateInUpLeft`
  * `rotateInUpRight`
  * `rotateOut`
  * `rotateOutDownLeft`
  * `rotateOutDownRight`
  * `rotateOutUpLeft`
  * `rotateOutUpRight`
  * `hinge`
  * `rollIn`
  * `rollOut`
  * `zoomIn`
  * `zoomInDown`
  * `zoomInLeft`
  * `zoomInRight`
  * `zoomInUp`
  * `zoomOut`
  * `zoomOutDown`
  * `zoomOutLeft`
  * `zoomOutRight`
  * `zoomOutUp`
  * `slideInDown`
  * `slideInLeft`
  * `slideInRight`
  * `slideInUp`
  * `slideOutDown`
  * `slideOutLeft`
  * `slideOutRight`
  * `slideOutUp`

## License

Ganimate.css is licensed under the MIT license.
