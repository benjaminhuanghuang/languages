### C++
```


```
### C
```

```

### Go
```
```
### Java
Check map.containsKey
```
  Map<Character, Integer> map = new HashMap<>();
  for (int i = 0; i < str.length(); i++) {
      char c = str..charAt(i)
      if (map.containsKey(c)) {
          map.put(c, map.get(c) + 1);
      } else {
          map.put(c, 1);
      }
  }
```
Or use getOrDefault（JDK 8）
```
  Map<Integer, Integer> map = new HashMap<>();
  for (int num : nums) {
      map.put(num, map.getOrDefault(num, 0) + 1);
  }
```

### C#
```  

```
### Python
Create dict from words
```

```


### JavaScript
```
```
### TypeScript
```
  const expectedCounts = new Map(Object.entries({ one: 1, of: 1, each: 1 }))
```