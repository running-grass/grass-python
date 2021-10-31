# grass-python
python的自用工具库

# FP相关

## 类型类
### Funtor
Functor为泛型的抽象类，包含一个map方法。
目前已经使内置的list类型实现了Functor

#### 相关函数
#### map
#### mapFilpped


### 其它函数
#### 函数操作
##### id
id: foall a. a -> a

##### const
const: forall a b. a -> (b -> a)

##### flip