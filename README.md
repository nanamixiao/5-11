# 5-11

## part I
o(n^2)

## part II
O(n)

## part III
``` cpp

using namespace std;

void reverse(int arr[], int size) {
    for (int i = 0, j = size - 1; i < j; ++i, --j) {

        int tmp = arr[i];
        arr[i] = arr[j];
        arr[j] = tmp;
    }
}


```

## part VI


Version #1	O(N)	O(N)
Version #2	O(N)	O(1)
Version #3	O(N)	O(N)


