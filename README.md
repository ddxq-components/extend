extend
==========

extend用一个或多个其他对象来扩展一个对象，返回被扩展的对象，用法同jQuery.extend。

----------

## 使用说明

### extend([deep,] target, obj1 [, objN])

* deep:如果第一个参数设置为true，则jQuery返回一个深层次的副本，递归地复制找到的任何对象。否则的话，副本会与原对象共享结构。 未定义的属性将不会被复制，然而从对象的原型继承的属性将会被复制。
* target:待修改对象。
* object1:待合并到第一个对象的对象。
* objectN:待合并到第一个对象的对象。
