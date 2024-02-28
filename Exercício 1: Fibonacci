def fibonacci(n):
    fib_sequence = [0, 1]
    for i in range(2, n):
        fib_sequence.append(fib_sequence[i-1] + fib_sequence[i-2])
    return fib_sequence

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

def insertion_sort(arr):
    for i in range(1, len(arr)):
        key = arr[i]
        j = i - 1
        while j >= 0 and arr[j] > key:
            arr[j + 1] = arr[j]
            j -= 1
        arr[j + 1] = key
    return arr

# Exemplo de uso
if __name__ == "__main__":
    # Fibonacci
    n = 10
    print(f"Sequência de Fibonacci com {n} termos:")
    print(fibonacci(n))

    # Fatorial
    num = 5
    print(f"Fatorial de {num}: {factorial(num)}")

    # Ordenação por Inserção
    arr = [12, 11, 13, 5, 6]
    print(f"Array original: {arr}")
    sorted_arr = insertion_sort(arr.copy())
    print(f"Array ordenado: {sorted_arr}")
