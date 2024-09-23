# String Split (StringTokenizer):

break a string

*it can break a string not a word*

```
System.out.println("Enter a line of integers separated by spaces:");

		String input = scanner.nextLine();

		StringTokenizer token = new StringTokenizer(input);
```


# String Rreverse (StringBuffer)

```
 StringBuffer sb = new StringBuffer("Hello");
        System.out.println("String buffer = " + sb);

        sbf.reverse();
        System.out.println("reverse :" + sb);
```
*or*

# String (StringBuilder)

```
StringBuilder result = new StringBuilder();
```
# String (.append())

This method in Java helps "merge" or concatenate multiple pieces of data

```
StringBuilder sb = new StringBuilder("Hello");
```
```
sb.append(" ");
sb.append("World");
sb.append("!");
System.out.println(sb.toString());
```

Insert at the front (index 0)
```
sb.insert(0, "Hello ");
System.out.println("After inserting at the front: " + sb);   
```
Insert in the middle (index 6, after "Hello ")
```
sb.insert(6, "Beautiful ");
zSystem.out.println("After inserting in the middle: " + sb);
```