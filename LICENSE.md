n = int(input("Введите количество чисел Фибоначчи: "))
a, b = 0, 1
fibonacci_series = [a, b]
for i in range(2, n):
    c = a + b
    fibonacci_series.append(c)
    a, b = b, c
print("Числа Фибоначчи:", fibonacci_series)
