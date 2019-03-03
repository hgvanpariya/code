# Convert ArrayList to Array in Java


```java
List<String> myList = new LinkedList<>();
myList.add("myname1");
myList.add("myname2");
myList.add("myname3");
myList.add("myname4");


String[] myArr = new String[myList.size()];
myArr = myList.toArray(myArr);

for(String s : myArr)
  System.out.println(s);
```
