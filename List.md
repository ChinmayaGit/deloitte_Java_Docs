# List

```
 public static int sumOfNumbers(List<Integer> numbers){}
 ```
 ```
List<Integer> numbers = List.of(1, 2, 3, 4, 5);
int result = sumOfNumbers(numbers); 
```

Array to list
```
List<Integer> list = Arrays.stream(arr) // Create an IntStream
                                    .boxed() // Box each int to Integer
                                    .toList(); // Collect to a List<Integer>
```