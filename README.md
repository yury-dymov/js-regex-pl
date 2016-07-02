# js-regex-pl

JavaScript RegExp doesn't work with Unicode characters out of the box. This small package fixes this issue.

This is \p{L} equalent extracted from [XRegExp](https://github.com/slevithan/xregexp)

[XRegExp](https://github.com/slevithan/xregexp) is a great library but I wanted something much smaller for my needs.

# Installation
```
npm i js-regex-pl
```

# Usage

```
import pL from 'js-regex-pl';

new RegExp(`^[${pL}]+$`).test('日本語')
```
