# Warning: this project as been deprecated

If you're on Ember 2.x we recommend using
[emberx-range-input](https://github.com/thefrontside/emberx-range-input),
otherwise you can continue to use this addon.

# emberx-slider

[![npm version](https://badge.fury.io/js/emberx-slider.svg)](http://badge.fury.io/js/emberx-slider)
[![Ember Observer Score](http://emberobserver.com/badges/emberx-slider.svg)](http://emberobserver.com/addons/emberx-slider)
[![Build Status](https://travis-ci.org/thefrontside/emberx-slider.svg)](https://travis-ci.org/thefrontside/emberx-slider)

A Slider component based on the native html5 range input.

The component itself takes on a number value between two bounds, that
proceeds in discrete step values. So, for example, to indicate a
percentage of saturation in an image, where the smallest change in
saturation is 1%, you might specify your slider control like:

```handlebars
{{x-slider min=0 max=100 step=1 value=saturationPercentage}}
```

The `value` property is fully reactive, and is ideal for real-time
visualizations.

### Default Values

While `min`, `max`, and `step` can take on any numeric values, the
default use-case is optimized for representing percentages stepped by
1%. There fore the proceeding example could have been written simply
as:

```handlebars
{{x-slider value=saturationPercenage}}
```

## EmberX

emberx-select is part of the "missing components of ember" collectively
known as emberx:

* [emberx-select](https://github.com/thefrontside/emberx-select)
* [emberx-slider](https://github.com/thefrontside/emberx-slider)
* [emberx-file-input](https://github.com/thefrontside/emberx-file-input)

## Installation

ember install emberx-slider

## Running Tests

* `ember test`
* `ember test --server`


## Code of Conduct
Please note that this project is released with a Contributor Code of
Conduct. By participating in this project you agree to abide by its
terms, which can be found in the `CODE_OF_CONDUCT.md` file in this
repository.
