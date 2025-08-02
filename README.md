# kotlin-utils


## Example: Ascending Order Function

This function prints a list of integers in ascending order:

```kotlin
fun ascending(list: List<Int>) {
    val forOrderedList = list
    val sort = forOrderedList.sorted()
    println("Ascending order: $sort")
}
```

### Usage

```kotlin
val nums = listOf(5, 3, 8, 1)
ascending(nums) // Output: Ascending order: [1, 3, 5, 8]
```
