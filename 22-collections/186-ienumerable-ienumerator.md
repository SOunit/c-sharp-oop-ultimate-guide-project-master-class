# IEnumerable

- represents group of elements

  - array
  - collection
  - string = group of characters

- `IEnumerable` Hierarchy

  - ICollection
    - IList
      - List
    - IDictionary
      - Dictionary
      - SortedList
    - HashSet
  - Stack
  - Queue

- has `getEnumerator`

- good for flexibility
  ```
  // can replace with Que, Stack, etc.
  IEnumerable messages = new List<string>(){"test1","test2","test3",}
  ```

# IEnumerator

- to read through `IEnumerable`

- forEach
  - `current`
  - `MoveNext`
  - `Reset`
