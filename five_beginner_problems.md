1. **Merging Two Lists**:
```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]
list1.extend(list2)
print(list1)  # Output: [1, 2, 3, 4, 5, 6]
```

2. **Check for Empty List**:
```python
def check_empty(my_list):
    if len(my_list) == 0:
        return True
    return False

my_list = []
result = check_empty(my_list)
print(result)  # Output: True
```

3. **Square Each Element**:
```python
numbers = [1, 2, 3, 4, 5]
squared_list = []
for num in numbers:
    squared_list.append(num ** 2)
    
print(squared_list)  # Output: [1, 4, 9, 16, 25]
```

4. **Concatenate Elements**:
```python
words = ["Hello ", "world", "!"]
new_word = ''
for word in words:
    new_word += word
print(new_word)  # Output: Hello world!
```

5. **Find Even Numbers**:
```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]
evens = [num for num in numbers if num % 2 == 0]
print(evens)  # Output: [2, 4, 6, 8]
```

You've done a great job tackling these problems! If you have any more questions or need further assistance, just let me know. Happy coding! 😊
