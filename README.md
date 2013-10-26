#tradition.js

Convert between Traditional Chinese and Simplified Chinese.

## Usage

`s2t` means Convert Simplified Chinese To Traditional Chinese.

`t2s` means Convert Traditional Chinese to Simplified Chinese.

First you should import `tradition.js`:

```html
<script type='text/javascript' src="tradition.js"></script>

```

Then enjoy:


``` javascript
// Convert string
var result = s2t('我是程序员！');
var result = t2s('我是程序员！');

// Convert contents of a HTML Node
var wap = document.getElementById('content-wap');
s2t(wap);
t2s(wap);

// Convert contents of a HTML NodeList
var paras = document.getElementsByTagName('p');
s2t(paras);
t2s(paras);
```