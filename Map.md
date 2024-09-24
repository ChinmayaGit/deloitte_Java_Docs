# Map
```
Map<Character, Integer> result = countChars(arr);
```
Pass map:
```
public static Map<Character, Integer> countChars(char[] arr){}

Map<Character, Integer> result = countChars(arr);
```
# Hash Map:

```
Map<Character, Integer> charCountMap = new HashMap<>();
```
Pass hash map:
```
public static Map<String, String> getStudents(HashMap<String, Integer> students)

 Map<String, String> medalResults = getStudents(studentMarks);
 ```
 ```
public static <K, V extends Comparable<V>> List<V> getValues(HashMap<K, V> map) {}

List<Integer> sortedValues = getValues(map);
```
### Check the char in Map
```
charCountMap.containsKey(c)
```
### Add in Map (by: key(c) value(1))
```
charCountMap.put(c, 1);
```
### Get all Values
```
result.entrySet()
```
### Get key and its value
```
entry.getKey() + ": " + entry.getValue()
```