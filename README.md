# gist

TvvT gists

## base.css

reset文件

Note：如要全局定义文字大小，请用`body{font-size:1.2em;}`，这里如果用rem，android设备chrome里继承不了，此bug一直未修复。其他地方请用rem单位

## common.less

常用less简写调用，建议放到less文件开头调用`@import 'common.less';`

Note：使用时，每个都加括号，避免和其他类名冲突。例如`.clearfix();`