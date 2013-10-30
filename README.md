#jquery-s2t

A simple jQuery plugin to convert between Simplified Chinese and Traditional Chinese.

## Usage

`s2t` means Convert Simplified Chinese to Traditional Chinese.

`t2s` means Convert Traditional Chinese to Simplified Chinese.

First You should import `jQuery1.6+` and `jquery.s2t.js`:

``` html
<script type='text/javascript' src="jquery.min.js"></script>
<script type='text/javascript' src="jquery.s2t.js"></script>
```

Enjoy:

``` javascript
// Convert string
var result = $.s2t('我是程序员！');
var result = $.t2s('我是程序員！');

// Convert HTML Elements
$('.content-wap').s2t();
$('.content-wap').t2s();
```

## Examples

西窗烛 http://www.xichuangzhu.com
