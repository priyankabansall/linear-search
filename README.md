# linear-search
int main() {
     int arr[] = {3, 8, 4, 1, 9, 5, 7};
     int n = 7; // sizeof(arr) / sizeof(arr[0]);
     int target = 5;
     int result = linear_search(arr, n, target);
     if (result == -1) {
        printf("Target value not found in the array.\n");
    } else {
        printf("Target value found at index: %d\n", result);
    }
    return 0;
}
