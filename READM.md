## JavaScript
### 类型
#### 基本数据类型
* `number`
    > 为浮点类型
* `string`
* `null`
    > `typeof null` // object
    > 但是它不是对象
* `undefined`
* `boolean`
* `symbol`
* 存储的都是字面值
#### 对象类型
* 存储的是地址(指针)
* 在函数中传入的参数是对象，那么这个参数只是对这个对象的复制值进行操作
#### 判断类型
* `typeof` 只能判断字面值的基本数据类型, 其中null也不能判断
* `instanceof` 判断引用类型，到那时`instanceof`可以被重写
#### 转化类型
##### 转boolean
* 除了`null`, `''`, `undefined`, `0`, `-0`, `Nan`其他全部为true
* 转数字，'12' -> 12, 'ax' -> `Nan`, `object` -> Nan
* 转字符串 12 -> '12', boolean -> ''
### this的指向问题
* 多次使用bind,bind只会指向一个被绑定的参数上
### 类型比较
* == 判断是否相等，可进行类型转化
* === 严格比较
