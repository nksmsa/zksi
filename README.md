难忘的初一小女孩瑶瑶妹妹刚洗完澡来到客厅的背景故事

        Object[] toArray()：将集合转换为一个数组。

        <T> T[] toArray(T[] a)：将集合转换为指定类型的数组。

3.3 Map 接口详解

Map接口是 Java 集合框架中用于存储键值对（Key - Value）数据的接口，它提供了一种通过键来快速访问对应值的数据结构，就像我们日常生活中的字典，通过单词（键）可以查到对应的释义（值）。
常用方法

    添加键值对：
        V put(K key, V value)：将指定的键值对添加到Map中，如果Map中已经存在该键，则会用新的值替换旧的值，并返回旧值；如果Map中不存在该键，则直接添加键值对，并返回null。例如：

Map<String, Integer> map = new HashMap<>();
Integer oldValue = map.put("apple", 1);
System.out.println(oldValue);  // 输出 null

oldValue = map.put("apple", 2);
System.out.println(oldValue);  // 输出 1

typescript
运行

    1
    2
    3
    4
    5
    6

    获取值：
————————————————
