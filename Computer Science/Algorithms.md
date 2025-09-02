## 1 Sliding Window

```cpp
int l = 0, r = 0;
while (r < vec.size()) {
    window_property.add(vec[r]);

    while (window_property condition) {
	    window_property.remove(vec[l]);
	    l++;
	 }
	
	 ans += r - l + 1;
    r++;
}
```

```cpp
int l = 0;
for (int r = 0; r < vec.size(); r++) {
    window_property.add(vec[r]);
    
    while (l <= r && window_property condition) {
        window_property.remove(vec[l]) ;
        l++;
    }
    ans += r - l + 1;
}
```
