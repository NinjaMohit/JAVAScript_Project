<h1>This Project involve visualization of  Bubble sort, Merge sort, and Quicksort algorithms using HTML, CSS, and JavaScript</h1>

<h3>1. Visualization </h3>
<p>Visualization Update Function (div_update):
  
This function is responsible for updating the style (height and background-color) of a sorting element (cont) with a specified height and color.
It uses setTimeout to introduce a delay based on the delay_time variable, ensuring a smooth visualization.
  
Button Enablement (enable_buttons):
This function is used to enable buttons and input fields after a certain delay (c_delay). The delay is updated as elements are visualized.
</p>
<img src="https://github.com/NinjaMohit/JAVAScript_Project/blob/main/SortingVisualization_Algo/images/img1.png?raw=true">
<img src="https://github.com/NinjaMohit/JAVAScript_Project/blob/main/SortingVisualization_Algo/images/img2.png?raw=true">
<br>

<h3>2. Bubble sort</h3>
<p>
Time and Space Complexity Display:
The function Bubble begins by setting and displaying the time and space complexities for the Bubble Sort algorithm. These complexities are expressed in terms of Big O notation.

Visualization Loop:
The outer loop runs for array_size - 1 iterations, representing each pass of the Bubble Sort algorithm.
During the inner loop, the div_update function is called to update the visual representation of the array elements.</p>
<img src="https://github.com/NinjaMohit/JAVAScript_Project/blob/main/SortingVisualization_Algo/images/img3.png?raw=true">
<br>

<h3>3. Merge sort</h3>
<p>ime and Space Complexity Display:
The function Merge begins by setting and displaying the time and space complexities for the Merge Sort algorithm. These complexities are expressed in terms of Big O notation.

Visualization Loop:
The merge_partition function is called with the range of indices (0 to array_size - 1) to initiate the merge sort process.
The merge_partition function recursively divides the array into two halves until each subarray has a single element.
The merge_sort function is responsible for merging two sorted halves back together while updating the visualization.</p>
<img src="https://github.com/NinjaMohit/JAVAScript_Project/blob/main/SortingVisualization_Algo/images/img6.png">
<br>


<h3>3.Quick sort</h3>
<p>Time and Space Complexity Display:
The function Quick begins by setting and displaying the time and space complexities for the Quick Sort algorithm. These complexities are expressed in terms of Big O notation.
Visualization Loop:

The quick_sort function is called with the entire array range (0 to array_size - 1) to initiate the quick sort process.The quick_sort function recursively partitions the array and sorts its partitions.

Partitioning Process:
The quick_partition function is responsible for partitioning the array and determining the pivot element.
The pivot element is selected as the first element of the partition.
<img src="https://github.com/NinjaMohit/JAVAScript_Project/blob/main/SortingVisualization_Algo/images/img7.png">
<done>

