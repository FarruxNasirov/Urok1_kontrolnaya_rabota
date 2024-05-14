Код программы:
```python
def less_than_equal_three(input_array):
    
    filtered_array = []
    
    for item in input_array:
        if len(item) <= 3:
            filtered_array.append(item)
    
    return filtered_array


original_array = ["Hello", "2", "world", ":)", "no", "yes", "abc", "a", "xyz", "12345"]
result = less_than_equal_three(original_array)

print("Изначальный массив:", original_array)
print("Отфильтрованный массив:", result)
```

Результат вывода в терминал:

> ![image answer in terminal](photo_2024-05-08_22-54-06.jpg)

