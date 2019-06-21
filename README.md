# angled-cointainer
An SCSS mixin for creating angled containers with fallbacks for browsers that do not support clip-path property

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation
Download and add to your projects scss structure.

## Usage
Include in a class and then add the class to you container

```scss
.angle-example {
	@include angle-container($angle-top: 3, $angle-bottom: 3, $angle-position-y: 'both', $angle-position-x: 'right');
}
```

