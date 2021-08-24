def get_missing_number(arr):
    size = len(arr)
    missing = 1

    for i in range(0,size):
        missing ^= arr[i]
        missing ^= i+2

    return missing

A = [1, 2, 3, 4, 6]
miss = get_missing_number(A)
print(miss)
