#tradition.js

Convert between Traditional and Simplified Chinese.

## Usage
    // convert string
    var result = s2t('我是程序员！');
    var result = t2s('我是程序员！');

    // convert contents of a HTML Node
    var wap = document.getElementById('content-wap');
    s2t(wap);
    t2s(wap);

    // convert contents of a HTML NodeList
    var paras = document.getElementsByTagName('p');
    s2t(wap);
    t2s(wap);
