# Algorithms

## Searches

### Linear Search 

Definition: Linear search (also as known as sequential search) is the process of finding a value by searching through every element till we find the value that we want.

![Linear-Search](https://user-images.githubusercontent.com/42160652/71761075-d57d0800-2e94-11ea-88b9-98264291afa3.png)
###### It goes through each element till we found the target.

**Linear Search Implementation in Java**
```java
public int linearSearch(int a[], int target){

//returns the index of the target 
for(int x=0; x<a.length; x++){
if(a[x] == target)
      return x;
 }
 
 //returns -1 if the element is not found
 return -1;
}
```

**Time Complexity:** The time complexity of this prorgram is O(n) because it will take a very short time to find the first
element but then finding the next element will take longer and so on. The time it takes to find each element will increase linearly which is why the time complexity is O(n).

__Best Case, Average Case, and Worst Case__ 

**Best Case:** You found the first element                           
      
     Big O Notation: O(1)

**Average Case:** You found the middle element
     
     Big O Notation: O(n) even though it is O(n/2) but remember we will drop the constant which is 1/2

**Worst Case:** You found the last element or element is not found
     
     Big O Notation: O(n)
   
###### Note: n is the length of the line
      
### Binary Search 

Definition: Binary search (also as known as half-interval search) is used to find a specific value within an array.

![Binary Search](https://www.geeksforgeeks.org/wp-content/uploads/Binary-Search.png)

__BEST CASE, WORST CASE, AND AVERAGE CASE__

**Best Case:** O(1)

**Worst Case:** O(log n)

**Examples:**


