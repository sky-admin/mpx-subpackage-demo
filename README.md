# mpx-subpackage-demo
> a demo about subpackage in mpx framework

subpackage可以放在任何位置，甚至是作为一个npm包单独发包，在主项目中引入。

页面跳转到subpackage里的页面时，因为构建时会加上hash，相对路径不是真实的相对路径，所以在import时候需要在最后加上?resolve可以替换为真实路径（[例子](https://github.com/sky-admin/mpx-subpackage-demo/blob/master/src/pages/index.mpx#L8)）
