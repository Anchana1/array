# array
----------------------python----------------------------------
def findremainder(arr, len, n):
    product = 1
    for i in range(len):
        product = product * arr[i]
    return product % n
arr = [100, 10, 5, 2, 35, 11]
len = len(arr)
n = 11
print(findremainder(arr, len, n))

output:9
