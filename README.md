
After pushing all six items, the Array has these values length: 6, capacity: 12, ptr: 3. The capacity was increased twice - first to 3 and then to 12 once the capacity of 3 was met. The Memory allocation increase also meant moving to a new ptr that can accomadate the new capacity.

After running pop three times, the Array has these values length: 3, capacity: 12, ptr: 3. The capactiy and ptr were upped to accomodate the array at it's largest but the memory is not released when the array shrinks in size.
The array returns NaN instead of the string value. The resize method increase the capacity and reassigns the ptr of the existing values when the array is pushed beyond the current memory allocation.

O(n)

O(n)

O(n)

O(n^2)

O(n^2)

O(n^2)

O(n^3)

O(n^2)
