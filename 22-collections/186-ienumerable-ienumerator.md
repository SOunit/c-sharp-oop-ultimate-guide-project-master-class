# IEnumerable

- represents group of elements

  - array
  - collection
  - string = group of characters

- IEnumerable

  - ICollection
    - IList
      - List
    - IDictionary
      - Dictionary
      - SortedList
    - HashSet
  - Stack
  - Queue

- good for flexibility
  ```
  // can replace with Que, Stack, etc.
  IEnumerable messages = new List<string>(){"test1","test2","test3",}
  ```

# IEnumerator
