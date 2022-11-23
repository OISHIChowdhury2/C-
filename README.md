# Searching
<h3>Properties of Linear Search</h3>
It is important to note that the linear search algorithm does not need to use a sorted list.Also, the algorithm can be customised for use</b>
in different scenarios like searching for an array of objects by key. 
<br/>
<b>Time Complexity of Linear Search</b>
  
The best-case time complexity is achieved if the element searched is the first element in the list.Now,the search would complete with a single comparison. Hence, </b>
the best-case time complexity would be O(1).<br />

The worst-case time complexity occurs if the element searched is the last element or is not present in the list.In this case, the search has to compare all elements </b>
in the array. We say that the input data has length n,which means the overall time complexity is O(n) due to the n comparisons made.<br />

In the example above, I used the linearSearch function on an array with eight elements.In the worst case, when the search value is not in the list or is at the end</b>
of the list, the function would have to make eight comparisons.Because our array is so small, there is no need to optimise using a different algorithm. However,</b>
beyond a certain point,it is no longer efficient to use a linear search algorithm, and that's when using a binary search algorithm would be better.<br />

The average time complexity of linear search is also O(n).<br />


<h2>Binary Search</h2>
We start with a sorted array as required to perform a binary search. Note that sorting the array is expensive, but once it's done, the array can be efficiently</b> searched many times.</b>
Now, the high and low pointers will be set to the first and last elements respectively. The mid pointer is set to the index given by (low - high) / 2.</b>
Since searchValue > mid, we need to search the right side of the array. So we set the low pointer to be just after mid, and mid is reset to be between the low and </b>
high pointers.</b>
Again, the target value is towards the right of the array. Once again, we adjust the low and high pointers. Now the low and mid pointers are the same.Now,the</b> searchValue is found at mid, which means we have reached the end of our search!</b>


<b>Time Complexity</b>
One of the main reasons why we use binary search for finding elements in an array would be its time complexity. In a best-case scenario, the time complexity for </b>
Binary Search is O(1). This happens when the element in the middle of the array matches the search element.</b>

At worst, the time complexity for searching an element using binary search is O(log n)—much less than O(n) for large values of n. To get an idea of how much </b></b>
slower growing log(n) is than n, here is a table of typical values of log(n).</b>

git init <br />
git add README.md <br />
git commit -m "first commit" <br />
git branch -M main <br />
git remote add origin  <br />
git push -u origin main <br />

