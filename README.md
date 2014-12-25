UEditor是由百度web前端研发部开发所见即所得富文本web编辑器
===================================
UEditor是由百度web前端研发部开发所见即所得富文本web编辑器，具有轻量，可定制，注重用户体验等特点，开源基于MIT协议，允许自由使用和修改代码。

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist wdteam/yii2-ueditor "*"
```

or add

```
"wdteam/yii2-ueditor": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \wdteam\ueditor\WdUeditor::widget(); ?>```