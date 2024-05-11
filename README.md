// Итоговая контрольная работа по основному блоку
// Урок 1. Контрольная работа
// Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе Разработчик. Мы должны убедится, что базовое знакомство с IT прошло успешно.

// Задача алгоритмически не самая сложная, однако для полноценного выполнения проверочной работы необходимо:

// Задача:
// Написать программу, которая из имеющегося массива строк формирует новый массив из строк,
// длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры,
// либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями,
// лучше обойтись исключительно массивами.

// Примеры:

// [“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
// [“1234”, “1567”, “-2”, “computer science”] → [“-2”]
// [“Russia”, “Denmark”, “Kazan”] → []


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
