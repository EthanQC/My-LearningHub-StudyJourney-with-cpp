# algorithm
`<algorithm>`头文件提供了一些标准算法，可直接使用，但推荐加上`std::`

## sort算法
`sort()`是一个被包含在cpp的`<algorithm>`标准库中的排序算法，默认的排序顺序是升序，需要放入迭代器才能使用。

对于不能随机访问的数据结构来说，sort算法是不能使用的，此时应使用该种容器自带的排序算法。