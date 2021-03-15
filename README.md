# light-or-dark

A micro package for returning whether a hex or rgb color is light or dark.

Based on https://awik.io/determine-color-bright-dark-using-javascript/.

## Usage

```js
import lightOrDark, { isLight, isDark } from 'light-or-dark'

lightOrDark('#000000') // "dark"
isLight('rgba(255, 255, 255)') // true
isDark('#ffffff') // false
```
