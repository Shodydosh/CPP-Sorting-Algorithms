# Method 1: Standard (Accepted) 
Time: O(n * lgn)

```CPP
void stlSort(vector<int>& nums) {
	sort(nums.begin(), nums.end());
}
```
# Method 2: Stable (Accepted) 
Time: O(n * lgn)

```CPP
void stableStlSort(vector<int>& nums) {
	stable_sort(nums.begin(), nums.end());
}
```

##
Created by [Shodydosh](https://github.com/Shodydosh) :innocent:
Last Edited on: 11/17/2022
