def findsm(arr):
    smallest = arr[0]
    smallest_index = 0
    for i in range(1,len(arr)):
        if arr[i] < smallest :
            smallest = arr[i]
            smallest_index = i
    return smallest_index  

# Example 

arr = [213,3453,2,2213,65321,234,342,4,6,8,23,4454,2]   

print(findsm(arr))

# output (return index) --   2
