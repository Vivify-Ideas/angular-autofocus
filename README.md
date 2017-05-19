# Angular Autofocus

## Description

AngularJS directive for autofocusing HTML elements. When element with the directive is added to DOM, it will automatically get the focus.

## Installation

```
npm install --save vi-angular-autofocus
```

or

```
bower install vi-angular-autofocus
```

Register the module into your main app module

```javascript
angular.module('myApp', ['vivify-ideas.angular-autofocus']);
```

## Usage

In the template, use the `vi-autofocus` directive:

### HTML

```html
<input name="name" type="text" vi-autofocus/>
```

---

LICENCE MIT