911国精产品自偷自偷综合POPNY丨自拍论坛

    boolean removeAll(Collection<?> c)：从当前集合中移除指定集合中包含的所有元素，如果当前集合因为这个操作而发生了改变，则返回true。例如：

Collection<String> collection1 = new ArrayList<>();
collection1.add("apple");
collection1.add("banana");
collection1.add("cherry");

Collection<String> collection2 = new ArrayList<>();
collection2.add("banana");

boolean removedAll = collection1.removeAll(collection2);
System.out.println(removedAll);  // 输出 true
System.out.println(collection1);  // 输出 [apple, cherry]

typescript
运行

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    11

    查找元素：
        boolean contains(Object o)：判断集合中是否包含指定的元素，如果包含则返回true，否则返回false。比如：

Collection<String> collection = new ArrayList<>();
collection.add("apple");
boolean contains = collection.contains("apple");
System.out.println(contains);  // 输出 true

typescript
运行

    1
    2
    3
    4

    boolean containsAll(Collection<?> c)：判断当前集合是否包含指定集合中的所有元素，如果包含则返回true，否则返回
————————————————
