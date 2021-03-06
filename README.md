# Ganimate.css: Animate.css for GWT styling

[![License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat)](https://opensource.org/licenses/MIT)

Easiest way to add amazing animations to your GWT application!

## Introduction from [Animate.css](https://daneden.github.io/animate.css/) library:

`animate.css` is a bunch of cool, fun, and cross-browser animations for you to use in your projects. Great for emphasis, home pages, sliders, and general just-add-water-awesomeness.

## Installation (default: production version)

* download **[release page](https://github.com/wlsc/ganimate.css/releases)**, place it into your project's lib folder and include it to a project

* include into your **\<module_name\>.gwt.xml** file:

```xml
  <inherits name='de.wlsc.gwt.theme.ganimate.css.Ganimate' />
  ```

* and just use it like this:

```java
  <g:Label styleName="animated bounceInRight" />
  ```

## Installation (unminified version)

* download jar from the **[release page](https://github.com/wlsc/ganimate.css/releases)**, place it into your project's lib folder and include it to a project

* include into your **\<module_name\>.gwt.xml** file:
 
```xml
  <inherits name='de.wlsc.gwt.theme.ganimate.css.GanimateDebug' />
  ```

* and just use it like this:

```java
  <g:Label styleName="animated bounceInRight" />
  ```

## Animations

| Class Name        |                    |                     |                      |
| ----------------- | ------------------ | ------------------- | -------------------- |
| `bounce`          | `flash`            | `pulse`             | `rubberBand`         |
| `shake`           | `headShake`        | `swing`             | `tada`               |
| `wobble`          | `jello`            | `bounceIn`          | `bounceInDown`       |
| `bounceInLeft`    | `bounceInRight`    | `bounceInUp`        | `bounceOut`          |
| `bounceOutDown`   | `bounceOutLeft`    | `bounceOutRight`    | `bounceOutUp`        |
| `fadeIn`          | `fadeInDown`       | `fadeInDownBig`     | `fadeInLeft`         |
| `fadeInLeftBig`   | `fadeInRight`      | `fadeInRightBig`    | `fadeInUp`           |
| `fadeInUpBig`     | `fadeOut`          | `fadeOutDown`       | `fadeOutDownBig`     |
| `fadeOutLeft`     | `fadeOutLeftBig`   | `fadeOutRight`      | `fadeOutRightBig`    |
| `fadeOutUp`       | `fadeOutUpBig`     | `flipInX`           | `flipInY`            |
| `flipOutX`        | `flipOutY`         | `lightSpeedIn`      | `lightSpeedOut`      |
| `rotateIn`        | `rotateInDownLeft` | `rotateInDownRight` | `rotateInUpLeft`     |
| `rotateInUpRight` | `rotateOut`        | `rotateOutDownLeft` | `rotateOutDownRight` |
| `rotateOutUpLeft` | `rotateOutUpRight` | `hinge`             | `jackInTheBox`       |
| `rollIn`          | `rollOut`          | `zoomIn`            | `zoomInDown`         |
| `zoomInLeft`      | `zoomInRight`      | `zoomInUp`          | `zoomOut`            |
| `zoomOutDown`     | `zoomOutLeft`      | `zoomOutRight`      | `zoomOutUp`          |
| `slideInDown`     | `slideInLeft`      | `slideInRight`      | `slideInUp`          |
| `slideOutDown`    | `slideOutLeft`     | `slideOutRight`     | `slideOutUp`         |
| `heartBeat`       |

## License

Ganimate.css is licensed under the MIT license.
