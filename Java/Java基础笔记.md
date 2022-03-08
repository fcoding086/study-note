# JAVA基础笔记

## 容器
### Iterator迭代器
- 用于遍历List、Set和Map，通过List、Set、Map的实现类的方法，将这些类的对象转化为Iterator对象，然后处理。
- 常用方法 hasNext();next();
- Map实现类使用entry()方法先转换为Set类，再进行遍历

### Collections工具类
- 排序：shuffle(); reverse(); sort();
- 查找：binarySearch();

### JavaBean
- 空的构造方法
- set();get();
- set&get快捷键
