# Bucket Sort

Bucket sort is a comparison sort algorithm that operates on elements by dividing them into different buckets and then sorting these buckets individually. Each bucket is sorted individually using a separate sorting algorithm or by applying the bucket sort algorithm recursively. Bucket sort is mainly useful when the input is uniformly distributed over a range.

Assume one has the following problem in front of them:

One has been given a large array of floating point integers lying uniformly between the lower and upper bound. This array now needs to be sorted. A simple way to solve this problem would be to use another sorting algorithm such as Merge sort, Heap Sort or Quick Sort. However, these algorithms guarantee a best case time complexity of O(NlogN). However, using bucket sort, the above task can be completed in O(N) time.

```
pip install allalgorithms
```

## Usage

```py
from allalgorithms.sorting import bucket_sort

arr = [77, 2, 10, -2, 1, 7]

print(bucket_sort(arr))
# -> [-2, 1, 2, 7, 10, 77]
```

## API

### bucket_sort(array)

> Returns a sorted array

##### Params:

- `array`: Unsorted Array
