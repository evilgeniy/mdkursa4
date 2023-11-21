053504 Sergeev Eugen
## 🔻**Cocktail data base**

**Functions:**
* User log in\log out
* User signup
* Viewing the best cocktails according to the editors
* Search for cocktails
* View cocktail recipes


## 🔻**Wareframe:**

![Image alt](https://github.com/evilgeniy/mdkursa4/blob/main/Wireframe.png)

```
def check_argument_count(func):
    def wrapper(*args, **kwargs):
        total_arguments = len(args) + len(kwargs)
        if total_arguments > 10:
            print("Много значений")
        else:
            return func(*args, **kwargs)
    return wrapper

@check_argument_count
def my_function(*args, **kwargs):
    return sum(args)

# Примеры вызова функции с разным количеством аргументов
print(my_function(1, 2, 3, 4, 5))  # Выведет результат: 15
print(my_function(1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11))  # Выведет "Много значений"
```

