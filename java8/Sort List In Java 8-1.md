### Find out the distinct words from the string?

```
String input = "Java Hungry Hungry Hungry Blog Alive is Awesome";		
					String[] arr = input.split(" ");
					List<String> mylist = Arrays.asList(arr);
					mylist.stream().distinct().forEach(System.out::println);
					System.out.println("@@@@@@@@@@@@@@@@@@@");	
					Set<String> mySet = 			     	mylist.stream().collect(Collectors.toSet());
									mySet.forEach(System.out::println);
```

